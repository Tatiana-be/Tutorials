Конечно! Ниже — **подробная расшифровка Недели 1** из программы для **продвинутого уровня C++**, посвящённой **современному C++ (C++17 / C++20 / C++23)**. Каждый день включает:  
- **Темы дня**,  
- **Теория и примеры**,  
- **Практические задачи**,  
- **Советы и ресурсы**.

---

# 📘 **Неделя 1: Современный C++ (C++17 / C++20 / C++23)**

**Цель недели:**  
Научиться использовать современные фичи C++, которые делают код безопаснее, чище и производительнее. Вы перестанете писать "старомодный" C++ и начнёте писать код в стиле **современного C++ (Modern C++)**.

---

## 🗓️ **Расписание по дням**

---

### **День 1: `auto`, `decltype`, `if constexpr`**

#### 🔹 Темы:
- `auto` — автоматический вывод типа
- `decltype` — получение типа выражения
- `if constexpr` — компиляционное ветвление (C++17)

#### 📚 Теория:
```cpp
// auto — заменяет громоздкие объявления
auto x = 42;                    // int
auto y = std::vector<int>{1,2}; // std::vector<int>
auto it = vec.begin();          // итератор — не надо писать полный тип

// decltype — полезно в шаблонах
int a = 5;
decltype(a) b = 10;  // b — int

// if constexpr — выполняется на этапе компиляции
template <typename T>
void print_type(T value) {
    if constexpr (std::is_integral_v<T>) {
        std::cout << "Integer: " << value << "\n";
    } else if constexpr (std::is_floating_point_v<T>) {
        std::cout << "Float: " << value << "\n";
    }
}
```

#### ✅ Практика:
1. Замените все явные типы на `auto` в коде с `std::map<std::string, std::vector<int>>`.
2. Напишите функцию, возвращающую `decltype(a + b)` от двух аргументов.
3. Сделайте шаблонную функцию, которая ведёт себя по-разному для `int` и `double` с `if constexpr`.

#### 💡 Совет:
> Используйте `auto`, но не злоупотребляйте. Не пишите `auto x = func();`, если `func()` возвращает что-то неочевидное.

---

### **День 2: `std::string_view`, `std::span`**

#### 🔹 Темы:
- `std::string_view` — "взгляд" на строку без копирования (C++17)
- `std::span<T>` — безопасный "взгляд" на массив/диапазон (C++20)

#### 📚 Теория:
```cpp
#include <string_view>

void print_sv(std::string_view sv) {
    std::cout << sv << " (size: " << sv.size() << ")\n";
}

std::string s = "Hello";
print_sv(s);           // OK
print_sv("World");     // OK — не создаёт std::string
print_sv(s.substr(0,3)); // Осторожно: временный объект может "уйти"
```

```cpp
#include <span>

void print_span(std::span<int> sp) {
    for (int x : sp) std::cout << x << " ";
}

int arr[] = {1, 2, 3, 4};
print_span(arr);                    // OK
std::vector v{1,2,3};
print_span(v);                      // OK
```

#### ✅ Практика:
1. Перепишите функцию `void process(const std::string& s)` → `std::string_view`.
2. Создайте функцию `max_in_span(std::span<const int>)`, возвращающую максимум.
3. Объясните, почему `std::string_view` быстрее, чем `const std::string&`.

#### 💡 Совет:
> `std::string_view` — почти всегда лучше, чем `const std::string&` для входных параметров.

---

### **День 3: Structured Bindings**

#### 🔹 Темы:
- `auto [x, y] = pair;` — удобное извлечение из пар, кортежей, структур (C++17)

#### 📚 Теория:
```cpp
std::pair<int, std::string> p = {42, "Alice"};
auto [id, name] = p;
std::cout << id << ", " << name << "\n";

// В циклах:
std::map<std::string, int> ages = {{"Alice", 25}, {"Bob", 30}};
for (const auto& [name, age] : ages) {
    std::cout << name << " -> " << age << "\n";
}

// Для структур:
struct Point { int x, y; };
Point p2{10, 20};
auto [a, b] = p2;
```

#### ✅ Практика:
1. Перепишите цикл по `std::map` с использованием structured bindings.
2. Используйте `auto [key, value]` для обработки `std::unordered_map`.
3. Напишите функцию, возвращающую `std::tuple<int, double, std::string>` и распакуйте её.

#### 💡 Совет:
> Используйте `const auto& [k, v]`, чтобы не копировать значения при обходе контейнеров.

---

### **День 4: `std::optional`, `std::variant`, `std::any`**

#### 🔹 Темы:
- `std::optional<T>` — может содержать значение или быть пустым (C++17)
- `std::variant<T, U>` — тип-сумма (аналог `union`, но безопасный)
- `std::any` — может хранить любой тип (но медленнее)

#### 📚 Теория:
```cpp
// optional
std::optional<int> divide(int a, int b) {
    if (b == 0) return std::nullopt;
    return a / b;
}

if (auto res = divide(10, 2); res) {
    std::cout << *res << "\n";
}

// variant
std::variant<int, std::string> v = "text";
v = 42;

if (std::holds_alternative<int>(v)) {
    std::cout << std::get<int>(v) << "\n";
}

// any
std::any a = 3.14;
a = std::string("hello");
if (auto* s = std::any_cast<std::string>(&a)) {
    std::cout << *s << "\n";
}
```

#### ✅ Практика:
1. Напишите функцию `find_in_vector(std::vector<int>, int) → std::optional<size_t>`.
2. Создайте `std::variant<double, std::string, bool>` и обработайте через `std::visit`.
3. Храните в `std::vector<std::any>` разные типы и выводите их (если возможно).

#### 💡 Совет:
> `std::optional` — лучшая замена возврату `-1`, `nullptr` или булевого флага.

---

### **День 5: `std::filesystem` (C++17)**

#### 🔹 Темы:
- Работа с файлами и директориями
- Пути, проверка существования, обход директорий

#### 📚 Теория:
```cpp
#include <filesystem>
namespace fs = std::filesystem;

fs::path p = "/home/user/Documents";
if (fs::exists(p)) {
    std::cout << "Size: " << fs::file_size(p / "file.txt") << "\n";
}

// Обход директории
for (const auto& entry : fs::directory_iterator(p)) {
    if (entry.is_regular_file()) {
        std::cout << entry.path().filename() << "\n";
    }
}
```

#### ✅ Практика:
1. Напишите функцию, печатающую все `.txt` файлы в директории.
2. Подсчитайте общий размер всех файлов в папке.
3. Создайте структуру `FileInfo` с именем, размером, датой — и заполните из `fs::directory_entry`.

#### 💡 Совет:
> `std::filesystem` заменяет `dirent.h` и `stat()` из C. Кроссплатформенный и удобный.

---

### **День 6: Концепты — введение (C++20)**

#### 🔹 Темы:
- Что такое концепты?
- `template <Integral T>`
- `requires` выражения

#### 📚 Теория:
```cpp
// Простой концепт
template <typename T>
concept Integral = std::is_integral_v<T>;

template <Integral T>
T add(T a, T b) {
    return a + b;
}

// Использование
add(3, 5);     // OK
add(3.5, 2.1); // Ошибка компиляции — double не Integral
```

```cpp
// Более сложный requires
template <typename T>
concept Addable = requires(T a, T b) {
    a + b;  // выражение должно быть валидным
};

template <Addable T>
T sum(T a, T b) { return a + b; }
```

#### ✅ Практика:
1. Создайте концепт `FloatingPoint`, разрешающий `float`, `double`.
2. Напишите шаблонную функцию `max`, принимающую только `Addable` типы.
3. Сравните ошибку компиляции с `concept` и без (например, с `static_assert`).

#### 💡 Совет:
> Концепты делают шаблоны читаемыми и дают **понятные ошибки компиляции**.

---

### **День 7: Обобщение и проект**

#### 🔹 Задача недели: **"Утилита анализа файлов"**

**Цель:** Использовать все изученные фичи в одном проекте.

**Функционал:**
- Считывает директорию (через `std::filesystem`)
- Для каждого `.txt` файла:
  - Считает количество строк
  - Находит самую длинную строку
  - Возвращает `std::optional<std::string>` — первую строку, если файл не пуст
- Результат хранится в `std::vector<std::variant<FileInfo, ErrorInfo>>`
- Вывод в формате: `filename.txt: 12 lines, longest: 45 chars`

**Требования:**
- Используйте `std::string_view`, `std::optional`, `std::variant`
- Примените `structured bindings` при обходе
- Используйте `if constexpr` для обработки разных типов ошибок
- Весь код — C++17/20

#### 💡 Дополнительно:
- Сделайте функцию шаблонной с `concept ReadableFile`
- Добавьте замер времени через `std::chrono`

---

## 📚 **Ресурсы для этой недели**

- [https://en.cppreference.com](https://en.cppreference.com) — детали каждого типа
- [https://godbolt.org](https://godbolt.org) — проверка кода с разными стандартами (`-std=c++17`, `-std=c++20`)
- Книга: *«Effective Modern C++»* — Scott Meyers (главы 1–6)
- YouTube: **CppCon — "Back to the Basics! Modern C++ Basics"**

---

## ✅ **Чек-лист по итогам недели**

Вы готовы к следующей неделе, если можете:

- [ ] Объяснить, зачем нужен `std::string_view`
- [ ] Использовать `structured bindings` в циклах и деструктуризации
- [ ] Вернуть `std::optional<T>` из функции
- [ ] Обработать `std::variant` через `std::visit`
- [ ] Пройтись по директории с `std::filesystem`
- [ ] Написать простой `concept` и использовать его в шаблоне

---

Хочешь — могу:
- Прислать **готовый проект-пример** по этой неделе
- Подготовить **тест из 10 вопросов** по темам
- Дать **решения всех задач**

Просто скажи!
