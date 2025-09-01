# Придумай программу для изучения языка программирования c++

Конечно! Вот подробная **программа для изучения языка программирования C++**, рассчитанная на новичков и тех, кто хочет систематизировать свои знания. Программа рассчитана примерно на **8–12 недель** при интенсивности 4–6 часов в неделю, но может быть адаптирована под индивидуальные темпы.

---

## 📚 **Программа изучения C++ (8–12 недель)**

### ✅ **Цель:**
Научиться уверенно писать программы на C++, понимать основы языка, объектно-ориентированное программирование, работу с памятью, стандартную библиотеку (STL), и быть готовым к решению задач на собеседованиях или к участию в проектах.

---

## 🗂️ **Недельный план**

---

### **Неделя 1: Введение и основы C++**

**Темы:**
- Установка среды (IDE: Visual Studio, Code::Blocks, CLion, или компилятор g++/clang)
- Структура программы на C++ (`#include`, `main()`, `return 0`)
- Переменные, типы данных (`int`, `double`, `char`, `bool`)
- Ввод/вывод (`cin`, `cout`)
- Операторы: арифметические, логические, сравнения
- Условные операторы (`if`, `else`, `switch`)
- Циклы (`for`, `while`, `do-while`)

**Практика:**
- Написать калькулятор (сложение, вычитание и т.д.)
- Программа "Угадай число"
- Вывод таблицы умножения

---

### **Неделя 2: Функции и массивы**

**Темы:**
- Объявление и вызов функций
- Параметры и возвращаемые значения
- Область видимости переменных
- Массивы (одномерные)
- Строки (`char[]`, `std::string`)
- Поиск и сортировка в массивах

**Практика:**
- Функция для нахождения максимума в массиве
- Сортировка пузырьком
- Подсчёт гласных в строке

---

### **Неделя 3: Указатели и ссылки**

**Темы:**
- Что такое указатели (`*`, `&`)
- Арифметика указателей
- Ссылки (`&` как ссылка)
- Передача параметров по значению, по ссылке, по указателю
- Указатели на функции (базово)

**Практика:**
- Функция, меняющая значения переменных местами через указатели
- Обход массива с помощью указателей
- Простая реализация `swap`

---

### **Неделя 4: Динамическая память и строки**

**Темы:**
- `new` и `delete`
- Одномерные и двумерные динамические массивы
- Утечки памяти и как их избегать
- Работа с `std::string` (методы: `substr`, `find`, `append` и др.)
- Строковые потоки (`stringstream`)

**Практика:**
- Динамический массив с ручным управлением
- Подсчёт слов в строке
- Конкатенация строк с использованием `stringstream`

---

### **Неделя 5: Структуры и ООП — часть 1**

**Темы:**
- Структуры (`struct`)
- Объединение данных (например, `Person` с именем, возрастом)
- Классы (`class`)
- Поля и методы
- Инкапсуляция (`public`, `private`)
- Конструкторы и деструкторы

**Практика:**
- Класс `Rectangle` с методами `area()`, `perimeter()`
- Класс `Student` с полями и методами вывода
- Класс `BankAccount` с депозитом и снятием

---

### **Неделя 6: ООП — часть 2**

**Темы:**
- Наследование
- Полиморфизм (виртуальные функции, `virtual`, `override`)
- Абстрактные классы и интерфейсы
- Композиция и агрегация

**Практика:**
- Иерархия фигур: `Shape` → `Circle`, `Rectangle`
- Реализация виртуального метода `draw()`
- Создание простой игры: `Animal` → `Dog`, `Cat`

---

### **Неделя 7: STL — стандартная библиотека**

**Темы:**
- `std::vector`, `std::array`, `std::list`
- `std::map`, `std::set`, `std::unordered_map`
- Итераторы
- Алгоритмы: `sort`, `find`, `reverse`, `transform`
- Работа с файлами (`fstream`)

**Практика:**
- Хранение и сортировка списка студентов
- Подсчёт частоты слов в текстовом файле
- Чтение данных из файла и сохранение в `map`

---

### **Неделя 8: Исключения, шаблоны, и итоговый проект**

**Темы:**
- Обработка ошибок: `try`, `catch`, `throw`
- Шаблоны функций и классов
- Умные указатели (`std::unique_ptr`, `std::shared_ptr`) — кратко
- Лямбда-выражения (базово)

**Практика:**
- Шаблонная функция `max<T>()`
- Класс `SafeArray` с проверкой выхода за границы
- Итоговый проект: **Телефонная книга** или **Библиотека книг**

---

## 🎯 **Итоговый проект (на выбор):**

1. **Телефонная книга**  
   - Добавление, удаление, поиск контактов  
   - Сохранение в файл  
   - Использование классов, STL, файлового ввода-вывода

2. **Консольный калькулятор с историей**  
   - Поддержка операций +, -, *, /  
   - Хранение истории вычислений  
   - Возможность просмотра истории

3. **Простая игра: "Быки и коровы"**  
   - Генерация числа, подсчёт быков и коров  
   - Интерфейс с подсказками

---

## 📚 **Рекомендуемые ресурсы:**

- **Книги:**
  - *«Язык программирования C++. Базовый курс»* — Страуструп
  - *«C++ для начинающих»* — Лафоре
  - *«Эффективный современный C++»* — Скотт Майерс (для более продвинутых)

- **Онлайн:**
  - [learncpp.com](https://www.learncpp.com) — отличный бесплатный курс
  - [cppreference.com](https://en.cppreference.com) — справочник
  - [Codeforces](https://codeforces.com), [LeetCode](https://leetcode.com) — задачи на C++

- **Видео:**
  - Курсы на YouTube (например, от `The Cherno`, `CodeBeauty`, `freeCodeCamp`)

---

## 💡 **Советы:**

- Пишите код каждый день.
- Не копируйте — пробуйте сами.
- Отлаживайте ошибки, читайте сообщения компилятора.
- Используйте `std::` вместо `using namespace std;` (лучшая практика).
- Изучайте C++17/C++20, если возможно.

---

Если хочешь, могу составить **еженедельное расписание с ДЗ**, **тесты по темам** или **подборку задач**.


# придумай программу для продвинутого уровня

Отлично! Ниже — **программа изучения C++ для продвинутого уровня**, рассчитанная на разработчиков, уже знакомых с основами языка, ООП и STL. Цель программы — выйти на уровень **профессионального C++ разработчика**, способного работать с производительным кодом, современными стандартами (C++17/20/23), писать шаблоны, работать с многопоточностью и понимать низкоуровневые аспекты.

---

## 🚀 **Программа по C++ (уровень: продвинутый)**  
**Длительность:** 10–14 недель  
**Рекомендуемое время:** 6–8 часов в неделю  
**Цель:** Освоить современный C++, метапрограммирование, параллелизм, оптимизацию и лучшие практики разработки.

---

## 📅 **Недельный план**

---

### **Неделя 1: Современный C++ (C++17 / C++20 / C++23)**

**Темы:**
- `auto`, `decltype`, `constexpr`, `if constexpr`
- Декларации переменных: `std::string_view`, `std::span`
- Structured bindings (`auto [x, y] = point;`)
- `std::optional`, `std::variant`, `std::any`
- `std::filesystem` (C++17)
- Концепты (C++20) — введение

**Практика:**
- Переписать старый код с использованием `std::string_view`
- Использовать `std::variant` для хранения разных типов
- Написать функцию с `if constexpr` для разных типов

---

### **Неделя 2: Умные указатели и RAII**

**Темы:**
- `std::unique_ptr`, `std::shared_ptr`, `std::weak_ptr`
- Правило "0, 3, 5" (Rule of Zero/Three/Five)
- RAII (Resource Acquisition Is Initialization)
- Утечки памяти и анализ с помощью Valgrind / AddressSanitizer

**Практика:**
- Заменить `new/delete` на умные указатели
- Реализовать контейнер с автоматическим управлением памятью
- Найти и исправить утечки в "испорченном" коде

---

### **Неделя 3: Шаблоны и метапрограммирование**

**Темы:**
- Шаблонные функции и классы
- Частичная и полная специализация
- SFINAE (`std::enable_if`)
- Variadic templates
- Введение в шаблонное метапрограммирование (TMP)

**Практика:**
- Написать шаблонный `print_container()`
- Сделать `Tuple` на variadic templates
- Функция `is_arithmetic_v<T>` через SFINAE

---

### **Неделя 4: Концепты и C++20 (продвинутое)**

**Темы:**
- Синтаксис концептов: `template <Integral T>`
- Создание собственных концептов
- Улучшение ошибок компиляции с концептами
- `requires`-выражения
- Сравнение с SFINAE

**Практика:**
- Переписать шаблон с `std::enable_if` на концепты
- Создать концепт `SortableContainer`
- Написать алгоритм, работающий только с `RandomAccessIterator`

---

### **Неделя 5: Итераторы, аллокаторы и STL глубоко**

**Темы:**
- Категории итераторов (input, forward, random access и др.)
- Пользовательские итераторы
- Аллокаторы (`std::allocator`)
- Как устроены `std::vector`, `std::map`, `std::unordered_map` внутри
- Продвинутые алгоритмы: `std::transform`, `std::accumulate`, `std::partition`

**Практика:**
- Реализовать свой итератор для списка
- Написать аллокатор с подсчётом выделений
- Оптимизировать алгоритм с помощью `std::move` и `reserve`

---

### **Неделя 6: Многопоточность и параллелизм**

**Темы:**
- `std::thread`, `std::async`, `std::future`
- `std::mutex`, `std::lock_guard`, `std::unique_lock`
- `std::atomic`, `memory_order`
- `std::condition_variable`
- Пул потоков (реализация)

**Практика:**
- Параллельный подсчёт суммы массива
- Банковская система с блокировками
- Производитель-потребитель с `condition_variable`

---

### **Неделя 7: Лямбды, замыкания и функциональные подходы**

**Темы:**
- Лямбды: захват по значению/ссылке, `mutable`
- `std::function`, `std::bind`
- Лямбды в алгоритмах STL
- Generic lambdas (C++14)
- Лямбды в многопоточном контексте

**Практика:**
- Сортировка с лямбдой по нескольким полям
- Хранение лямбд в `std::vector<std::function<void()>>`
- Асинхронный обработчик событий

---

### **Неделя 8: Детали компиляции и линковки**

**Темы:**
- Процесс компиляции: препроцессор → компиляция → линковка
- Разделение на `.h` и `.cpp`
- Однократное определение (ODR)
- `inline` переменные и функции
- Статическая и динамическая линковка
- Работа с библиотеками (`.a`, `.so`, `.dll`)

**Практика:**
- Создать статическую библиотеку
- Подключить динамическую библиотеку
- Исправить ошибки линковки

---

### **Неделя 9: Производительность и оптимизация**

**Темы:**
- Профилирование (gprof, perf, Valgrind Callgrind)
- `std::move`, RVO, NRVO
- Измерение времени выполнения (`std::chrono`)
- Кэш-дружественность, layout of objects
- PIMPL-идиома
- Избегание копирования

**Практика:**
- Оптимизировать медленную сортировку
- Замерить время выполнения с `std::chrono`
- Переписать класс с PIMPL

---

### **Неделя 10–11: Проектная работа**

**Выберите один из проектов:**

#### 🔹 **1. Простой вектор с поддержкой аллокаторов и итераторов**
- Полностью совместим с STL
- Поддержка `push_back`, `emplace_back`, `reserve`, `shrink_to_fit`
- Возможность передачи пользовательского аллокатора
- Тесты через Google Test

#### 🔹 **2. HTTP-сервер на сокетах (без фреймворков)**
- Обработка GET-запросов
- Отдача статики
- Многопоточность
- Логирование

#### 🔹 **3. Интерпретатор выражений (калькулятор с переменными)**
- Парсинг выражений (например, `x = 5; y = x + 3`)
- AST (абстрактное синтаксическое дерево)
- Поддержка переменных и операций
- Возможность расширения

#### 🔹 **4. Game of Life с GUI (через SFML или ncurses)**
- Отображение сетки
- Поколения, пауза, шаг
- Сохранение/загрузка паттернов

---

### **Неделя 12: Тестирование и CI**

**Темы:**
- Google Test / Catch2
- Написание unit-тестов
- Mock-объекты (GMock)
- Непрерывная интеграция (GitHub Actions)
- Статический анализ: `clang-tidy`, `cppcheck`

**Практика:**
- Написать тесты для своего проекта
- Настроить CI для запуска тестов
- Исправить замечания `clang-tidy`

---

### **Неделя 13–14: Работа с кодом и лучшие практики**

**Темы:**
- Стиль кода (Google C++ Style Guide, LLVM)
- Документирование (Doxygen)
- RAII, noexcept, `=default`, `=delete`
- Exception safety (noexcept, RAII)
- Проектирование API
- Работа с legacy-кодом

**Практика:**
- Рефакторинг "грязного" кода
- Документирование класса через Doxygen
- Написание exception-safe функции

---

## 📚 **Рекомендуемые ресурсы (продвинутый уровень)**

- **Книги:**
  - *«Effective Modern C++»* — Скотт Майерс
  - *«C++ Concurrency in Action»* — Anthony Williams
  - *«The C++ Programming Language»* — Бьёрн Страуструп
  - *«Design Patterns»* — Гамма (GoF)
  - *«C++ Templates: The Complete Guide»* — Vandevoorde, Josuttis

- **Сайты:**
  - [cppreference.com](https://en.cppreference.com)
  - [isocpp.org](https://isocpp.org)
  - [Meeting C++](https://meetingcpp.com)

- **Видео:**
  - Выступления с конференций: **CppCon**, **C++Now**, **Meeting C++**
  - YouTube: `The Cherno`, `CppCon`, `Jason Turner (C++ Weekly)`

---

## 💡 **Советы для продвинутых:**

- Пишите код, который можно тестировать.
- Избегайте "магии" без необходимости.
- Учитесь читать ассемблер (через Compiler Explorer — godbolt.org).
- Участвуйте в open-source проектах на GitHub.
- Следите за стандартами: C++26 уже в разработке.

---

Хочешь — могу:
- Подготовить **подборку задач по каждой теме**
- Составить **чек-лист для собеседования по C++**
- Предложить **реальные open-source проекты для изучения кода**

Просто скажи!


# подготовь подборку задач по каждой теме и составь чек-лист для собеседования

Отлично! Ниже — **подробная подборка задач по каждой теме** из программы для продвинутого уровня C++ и **чек-лист для собеседования**, который поможет подготовиться к интервью на позицию C++ разработчика (middle/senior).

---

# 📚 **Подборка задач по темам (продвинутый C++)**

---

## 🔹 **Неделя 1: Современный C++ (C++17/20/23)**

**Задачи:**
1. Напишите функцию, принимающую `std::string_view`, и возвращающую количество слов.
2. Используйте `structured bindings`, чтобы распаковать `std::map<std::string, int>` в цикле.
3. Реализуйте функцию `safe_divide(a, b)`, возвращающую `std::optional<double>`.
4. Создайте `std::variant<int, std::string, std::vector<int>>` и обработайте его через `std::visit`.
5. Напишите функцию, которая читает содержимое директории с помощью `std::filesystem`.

---

## 🔹 **Неделя 2: Умные указатели и RAII**

**Задачи:**
1. Замените `new`/`delete` в классе `Matrix` на `std::unique_ptr`.
2. Реализуйте класс `Observer`, использующий `std::weak_ptr`, чтобы избежать циклических ссылок.
3. Напишите класс `ResourceManager`, который автоматически освобождает ресурс (например, файл) в деструкторе.
4. Проверьте, что ваш класс следует **Rule of Zero** — удалите копирование, если нужно.
5. Найдите и исправьте утечку памяти в коде с `shared_ptr` (циклическая ссылка).

---

## 🔹 **Неделя 3: Шаблоны и метапрограммирование**

**Задачи:**
1. Напишите шаблонную функцию `max_of(a, b, c, ...)`, принимающую произвольное число аргументов.
2. Создайте шаблонный класс `SafeArray<T, N>`, проверяющий выход за границы.
3. Сделайте `is_pointer_v<T>` с помощью SFINAE.
4. Реализуйте `apply_tuple(func, tuple)` — вызов функции с аргументами из `std::tuple`.
5. Напишите `sum_types<1, 2.5, 'c'>` — шаблон, вычисляющий сумму типов через `constexpr`.

---

## 🔹 **Неделя 4: Концепты (C++20)**

**Задачи:**
1. Создайте концепт `Arithmetic`, разрешающий только числовые типы.
2. Перепишите `template <typename T> void sort(T& container)` с `requires Sortable<T>`.
3. Напишите концепт `Iterator`, проверяющий наличие `operator*`, `operator++`, `operator!=`.
4. Сделайте шаблонную функцию, принимающую только `RandomAccessIterator`.
5. Объясните, чем концепты лучше `std::enable_if`.

---

## 🔹 **Неделя 5: Итераторы и STL глубоко**

**Задачи:**
1. Реализуйте итератор для двусвязного списка (`begin()`, `end()`).
2. Напишите аллокатор, подсчитывающий количество `allocate`/`deallocate`.
3. Оптимизируйте `std::vector<std::string>`: используйте `reserve()` и `std::move`.
4. Напишите `find_if_not` с помощью `std::not_fn`.
5. Реализуйте `zip_iterator` для одновременного обхода двух контейнеров.

---

## 🔹 **Неделя 6: Многопоточность**

**Задачи:**
1. Напишите `Thread Pool` с очередью задач.
2. Реализуйте `Thread-Safe Queue` с `std::mutex` и `std::condition_variable`.
3. Создайте `Counter` с `std::atomic<int>` и сравните с `mutex`.
4. Напишите producer-consumer с тремя потоками-производителями и двумя потребителями.
5. Объясните разницу между `memory_order_relaxed`, `acquire`, `release`.

---

## 🔹 **Неделя 7: Лямбды и функциональные подходы**

**Задачи:**
1. Отсортируйте `std::vector<std::string>` по длине с лямбдой.
2. Напишите `std::function`, который сохраняет лямбду с захватом локальной переменной.
3. Создайте `EventBus`, где обработчики — лямбды.
4. Напишите `generic lambda`, вычисляющий `a + b` для разных типов.
5. Используйте `std::bind` для фиксации первого аргумента функции.

---

## 🔹 **Неделя 8: Компиляция и линковка**

**Задачи:**
1. Создайте статическую библиотеку `libmath.a` с функцией `add()`.
2. Напишите динамическую библиотеку `.so` и подключите её через `dlopen`.
3. Исправьте ошибку ODR в проекте с двумя `.cpp`, включающими один `.h` с определением функции.
4. Объясните, зачем нужен `#pragma once` или `#ifndef`.
5. Настройте `CMakeLists.txt` для сборки проекта с тестами.

---

## 🔹 **Неделя 9: Производительность и оптимизация**

**Задачи:**
1. Замерьте время выполнения `std::vector::push_back` с `reserve()` и без.
2. Перепишите конструктор с копированием на `std::move`.
3. Реализуйте PIMPL для класса `Logger`, скрывший `std::ofstream`.
4. Найдите "bottleneck" в коде с помощью `std::chrono`.
5. Объясните, почему `std::vector<bool>` — плохая идея для производительности.

---

## 🔹 **Неделя 10–11: Проекты (задачи)**

**Для проекта "Свой вектор":**
- Поддержка `emplace_back`, `at`, `size`, `capacity`
- Пользовательский аллокатор
- Итераторы (begin/end)
- Тесты на `push_back`, `clear`, `resize`

**Для HTTP-сервера:**
- Обработка `GET /`
- Отдача `index.html`
- Многопоточность: один поток на запрос
- Логирование в файл

**Для интерпретатора:**
- Парсинг `x = 5 + 3`
- Вычисление выражений
- Поддержка переменных
- AST с `std::variant`

---

## 🔹 **Неделя 12: Тестирование и CI**

**Задачи:**
1. Напишите тесты для `SafeArray` с Google Test.
2. Добавьте `EXPECT_THROW` для проверки исключений.
3. Настройте GitHub Actions: сборка + запуск тестов.
4. Запустите `clang-tidy` и исправьте замечания.
5. Напишите mock для `Database` в тестах.

---

## 🔹 **Неделя 13–14: Лучшие практики**

**Задачи:**
1. Рефакторите класс с "загрязнённым" интерфейсом (много `public` полей).
2. Добавьте Doxygen-документацию к методам.
3. Сделайте класс `noexcept move constructible`.
4. Объясните, почему `using namespace std;` — плохо в заголовках.
5. Напишите `constexpr` функцию для вычисления факториала.

---

# ✅ **Чек-лист для собеседования по C++ (Middle/Senior)**

Проверьте, можете ли вы уверенно ответить на эти вопросы.

---

## 🧠 **1. Основы языка**
- [ ] Что такое `const`, `constexpr`, `mutable`?
- [ ] Чем отличается `struct` от `class`?
- [ ] Что такое `static` (переменная, метод, функция)?
- [ ] Как работает `virtual` и таблица виртуальных функций (vtable)?
- [ ] Что такое `override`, `final`?

---

## 🧱 **2. ООП и дизайн**
- [ ] Назовите принципы ООП.
- [ ] Что такое полиморфизм (статический/динамический)?
- [ ] Объясните разницу между наследованием и композицией.
- [ ] Что такое RAII? Приведите пример.
- [ ] Что такое Rule of Three/Five/Zero?

---

## 🔁 **3. Указатели и память**
- [ ] Чем отличается `*`, `&` в объявлениях и выражениях?
- [ ] Что такое утечка памяти? Как найти?
- [ ] Объясните разницу между `std::unique_ptr`, `shared_ptr`, `weak_ptr`.
- [ ] Что такое дangled pointer?
- [ ] Как работает `std::move`? Когда использовать?

---

## 🧩 **4. Шаблоны и метапрограммирование**
- [ ] Что такое SFINAE? Пример с `std::enable_if`.
- [ ] Чем `concepts` лучше SFINAE?
- [ ] Что такое `template specialization`?
- [ ] Как работает `variadic templates`?
- [ ] Что такое `CRTP`? Где применяется?

---

## ⚙️ **5. STL и контейнеры**
- [ ] Чем `std::vector` отличается от `std::list`?
- [ ] Как устроен `std::unordered_map`? Коллизии?
- [ ] Что такое итераторы? Категории?
- [ ] Когда использовать `std::array` vs `std::vector`?
- [ ] Что такое `std::string_view` и зачем он нужен?

---

## 🧵 **6. Многопоточность**
- [ ] Что такое `race condition`?
- [ ] Как работает `std::mutex` и `lock_guard`?
- [ ] Чем `std::async` отличается от `std::thread`?
- [ ] Что такое `deadlock`? Как избежать?
- [ ] Объясните `memory_order` в `std::atomic`.

---

## 🚀 **7. Производительность**
- [ ] Что такое RVO/NRVO?
- [ ] Когда уместно использовать `std::move`?
- [ ] Что такое PIMPL? Зачем?
- [ ] Как измерить производительность кода?
- [ ] Что такое cache-friendly код?

---

## 🛠️ **8. Практика и инструменты**
- [ ] Как настроить CMake?
- [ ] Как писать unit-тесты (Google Test)?
- [ ] Что такое CI/CD? Как настроить в GitHub?
- [ ] Как использовать `valgrind` / `AddressSanitizer`?
- [ ] Что делает `clang-tidy`?

---

## 📝 **9. Задачи на интервью**
- [ ] Реализуйте `shared_ptr` с подсчётом ссылок.
- [ ] Напишите `ThreadPool`.
- [ ] Сделайте `LRU Cache`.
- [ ] Напишите `Observer` или `Command` паттерн.
- [ ] Отладьте код с `double free` или `use after free`.

---

# 📌 Рекомендации:
- Готовьтесь писать код на доске или в редакторе без автодополнения.
- Объясняйте вслух ход мыслей.
- Учитесь читать ассемблер (https://godbolt.org).
- Практикуйте задачи с LeetCode (C++), например: `Implement Smart Pointer`, `Thread-Safe Queue`.

---

Хочешь — могу:
- Прислать **PDF-версию чек-листа и задач**
- Подготовить **10 типовых задач с решениями**
- Составить **еженедельный план с дедлайнами**

Просто скажи!


# распиши подробнее неделю 1

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


# Напиши решение всех задач

Отлично! Ниже — **полные решения всех задач** из **Недели 1: Современный C++ (C++17 / C++20 / C++23)**. Каждое решение включает:
- Полный код на C++,
- Комментарии,
- Рекомендации.

---

## ✅ **Решения задач Недели 1**

---

### **День 1: `auto`, `decltype`, `if constexpr`**

#### ✅ Задача 1: Замените явные типы на `auto`

```cpp
#include <iostream>
#include <map>
#include <vector>
#include <string>

int main() {
    // Было:
    // std::map<std::string, std::vector<int>> data;
    // auto it = data.begin();

    auto data = std::map<std::string, std::vector<int>>{
        {"Alice", {1, 2, 3}},
        {"Bob",   {4, 5}}
    };

    for (const auto& [name, vec] : data) {
        std::cout << name << ": ";
        for (auto value : vec) {
            std::cout << value << " ";
        }
        std::cout << "\n";
    }

    return 0;
}
```

---

#### ✅ Задача 2: Функция с `decltype(a + b)`

```cpp
#include <iostream>
#include <type_traits>

template <typename T, typename U>
auto add_and_return_type(T a, U b) -> decltype(a + b) {
    return a + b;
}

int main() {
    auto result = add_and_return_type(3, 4.5);  // double
    std::cout << result << "\n";  // 7.5
    return 0;
}
```

> 🔎 Используем trailing return type, потому что `a + b` ещё не видно в начале функции.

---

#### ✅ Задача 3: `if constexpr` для разных типов

```cpp
#include <iostream>
#include <type_traits>

template <typename T>
void print_type_info(T value) {
    if constexpr (std::is_integral_v<T>) {
        std::cout << "Integer: " << value << " (size: " << sizeof(T) << ")\n";
    } else if constexpr (std::is_floating_point_v<T>) {
        std::cout << "Float: " << value << " (precision: ~" << std::numeric_limits<T>::digits10 << ")\n";
    } else {
        std::cout << "Other type\n";
    }
}

int main() {
    print_type_info(42);      // Integer
    print_type_info(3.14f);   // Float
    print_type_info("hello"); // Other
    return 0;
}
```

---

### **День 2: `std::string_view`, `std::span`**

#### ✅ Задача 1: Перепишите функцию с `std::string_view`

```cpp
#include <iostream>
#include <string>
#include <string_view>

// Было: void process(const std::string& s)
void process(std::string_view sv) {
    std::cout << "Processing: '" << sv << "' (length: " << sv.size() << ")\n";
}

int main() {
    std::string s = "Hello";
    const char* cstr = "World";
    std::string_view sv = "Temp";

    process(s);        // OK
    process(cstr);     // OK
    process(sv);       // OK
    process("Hi");     // OK — не создаёт временный std::string
    return 0;
}
```

---

#### ✅ Задача 2: `max_in_span`

```cpp
#include <iostream>
#include <span>
#include <vector>
#include <algorithm>

int max_in_span(std::span<const int> sp) {
    if (sp.empty()) {
        throw std::invalid_argument("Empty span");
    }
    return *std::max_element(sp.begin(), sp.end());
}

int main() {
    std::vector v = {1, 5, 3, 8, 2};
    int arr[] = {10, -1, 7};

    std::cout << max_in_span(v) << "\n";  // 8
    std::cout << max_in_span(arr) << "\n"; // 10
    return 0;
}
```

---

#### ✅ Задача 3: Почему `std::string_view` быстрее?

> ✅ **Ответ:**  
> `const std::string&` требует, чтобы аргумент был `std::string`, иначе будет **временное преобразование** (например, `char*` → `std::string`), что включает **аллокацию памяти**.  
> `std::string_view` просто "смотрит" на уже существующие данные — **без копирования**, **без аллокации**.

---

### **День 3: Structured Bindings**

#### ✅ Задача 1–2: Цикл по `map` и `unordered_map`

```cpp
#include <iostream>
#include <map>
#include <unordered_map>

int main() {
    std::map<std::string, int> ages = {{"Alice", 25}, {"Bob", 30}};

    // Обход с structured binding
    for (const auto& [name, age] : ages) {
        std::cout << name << " -> " << age << "\n";
    }

    // То же для unordered_map
    std::unordered_map<std::string, double> prices = {{"Apple", 1.2}, {"Banana", 0.8}};
    for (const auto& [item, price] : prices) {
        std::cout << item << ": $" << price << "\n";
    }

    return 0;
}
```

---

#### ✅ Задача 3: Возврат `std::tuple` и распаковка

```cpp
#include <iostream>
#include <tuple>
#include <string>

std::tuple<int, double, std::string> get_data() {
    return {42, 3.14, "Hello"};
}

int main() {
    auto [id, pi, msg] = get_data();
    std::cout << id << ", " << pi << ", " << msg << "\n";
    return 0;
}
```

---

### **День 4: `std::optional`, `std::variant`, `std::any`**

#### ✅ Задача 1: `find_in_vector → std::optional<size_t>`

```cpp
#include <iostream>
#include <vector>
#include <optional>

std::optional<size_t> find_in_vector(const std::vector<int>& vec, int value) {
    for (size_t i = 0; i < vec.size(); ++i) {
        if (vec[i] == value) {
            return i;
        }
    }
    return std::nullopt;
}

int main() {
    std::vector v = {10, 20, 30, 40};
    if (auto pos = find_in_vector(v, 30); pos) {
        std::cout << "Found at index: " << *pos << "\n";
    } else {
        std::cout << "Not found\n";
    }
    return 0;
}
```

---

#### ✅ Задача 2: `std::variant` и `std::visit`

```cpp
#include <iostream>
#include <variant>
#include <string>

using VarType = std::variant<double, std::string, bool>;

struct Printer {
    void operator()(double d) const { std::cout << "Double: " << d << "\n"; }
    void operator()(const std::string& s) const { std::cout << "String: " << s << "\n"; }
    void operator()(bool b) const { std::cout << "Bool: " << (b ? "true" : "false") << "\n"; }
};

int main() {
    std::vector<VarType> values = {3.14, std::string("Hello"), true, 2.71};

    for (const auto& v : values) {
        std::visit(Printer{}, v);
    }

    return 0;
}
```

---

#### ✅ Задача 3: `std::any` с разными типами

```cpp
#include <iostream>
#include <vector>
#include <any>
#include <string>

void print_any(const std::any& a) {
    if (a.type() == typeid(int)) {
        std::cout << "int: " << std::any_cast<int>(a) << "\n";
    } else if (a.type() == typeid(std::string)) {
        std::cout << "string: " << std::any_cast<std::string>(a) << "\n";
    } else if (a.type() == typeid(double)) {
        std::cout << "double: " << std::any_cast<double>(a) << "\n";
    } else {
        std::cout << "Unknown type\n";
    }
}

int main() {
    std::vector<std::any> data = {42, std::string("Hi"), 3.14, true};

    for (const auto& item : data) {
        print_any(item);
    }

    return 0;
}
```

---

### **День 5: `std::filesystem`**

#### ✅ Задача 1: Найти `.txt` файлы

```cpp
#include <iostream>
#include <filesystem>

namespace fs = std::filesystem;

int main() {
    fs::path dir = ".";  // текущая директория

    if (!fs::exists(dir) || !fs::is_directory(dir)) {
        std::cerr << "Directory not found\n";
        return 1;
    }

    std::cout << "Text files:\n";
    for (const auto& entry : fs::directory_iterator(dir)) {
        if (entry.path().extension() == ".txt") {
            std::cout << entry.path().filename() << "\n";
        }
    }

    return 0;
}
```

> ⚠️ Компилируйте с `-std=c++17 -lstdc++fs` (на некоторых системах).

---

#### ✅ Задача 2: Общий размер файлов

```cpp
#include <iostream>
#include <filesystem>

namespace fs = std::filesystem;

int main() {
    fs::path dir = ".";
    uintmax_t total_size = 0;

    for (const auto& entry : fs::recursive_directory_iterator(dir)) {
        if (entry.is_regular_file()) {
            total_size += entry.file_size();
        }
    }

    std::cout << "Total size: " << total_size << " bytes\n";
    return 0;
}
```

---

#### ✅ Задача 3: `FileInfo` из `directory_entry`

```cpp
#include <iostream>
#include <filesystem>
#include <string>

namespace fs = std::filesystem;

struct FileInfo {
    std::string name;
    uintmax_t size;
    bool is_directory;
};

int main() {
    fs::path dir = ".";

    for (const auto& entry : fs::directory_iterator(dir)) {
        FileInfo info{
            entry.path().filename().string(),
            entry.file_size(),
            entry.is_directory()
        };
        std::cout << info.name << " | " << info.size << " B | " 
                  << (info.is_directory ? "DIR" : "FILE") << "\n";
    }

    return 0;
}
```

---

### **День 6: Концепты (C++20)**

#### ✅ Задача 1: Концепт `FloatingPoint`

```cpp
#include <iostream>
#include <concepts>

template <typename T>
concept FloatingPoint = std::is_floating_point_v<T>;

template <FloatingPoint T>
T add(T a, T b) {
    return a + b;
}

int main() {
    std::cout << add(3.14, 2.86) << "\n";  // OK
    // std::cout << add(3, 5) << "\n";     // Ошибка: int не FloatingPoint
    return 0;
}
```

---

#### ✅ Задача 2: `Addable` и `max`

```cpp
#include <iostream>
#include <concepts>

template <typename T>
concept Addable = requires(T a, T b) {
    a + b;
};

template <Addable T>
T max(T a, T b) {
    return (a > b) ? a : b;
}

int main() {
    std::cout << max(3, 5) << "\n";      // OK
    std::cout << max(2.5, 1.7) << "\n";  // OK
    // max("a", "b") — не работает, но можно добавить специализацию
    return 0;
}
```

---

#### ✅ Задача 3: Сравнение ошибок с `concept` и `static_assert`

```cpp
// Без concept — плохая ошибка
template <typename T>
T bad_add(T a, T b) {
    static_assert(std::is_arithmetic_v<T>, "T must be numeric");
    return a + b;
}

// С concept — понятная ошибка
template <std::arithmetic T>
T good_add(T a, T b) {
    return a + b;
}

int main() {
    good_add(3, 4);      // OK
    // good_add("a", "b"); // Ошибка: no matching function — сразу видно, что char* не arithmetic
    return 0;
}
```

> ✅ **Вывод:** `concept` даёт **гораздо более читаемые ошибки компиляции**.

---

### **День 7: Проект — Утилита анализа файлов**

```cpp
#include <iostream>
#include <filesystem>
#include <string>
#include <string_view>
#include <vector>
#include <variant>
#include <optional>
#include <fstream>
#include <chrono>

namespace fs = std::filesystem;

// Информация об успешной обработке
struct FileInfo {
    std::string filename;
    size_t line_count;
    size_t max_line_length;
    std::optional<std::string> first_line;
};

// Информация об ошибке
struct ErrorInfo {
    std::string filename;
    std::string message;
};

using Result = std::variant<FileInfo, ErrorInfo>;

std::optional<std::string> read_first_line(const fs::path& path) {
    std::ifstream file(path);
    std::string line;
    if (std::getline(file, line)) {
        return line;
    }
    return std::nullopt;
}

Result analyze_file(const fs::path& path) {
    try {
        if (!fs::exists(path)) {
            return ErrorInfo{path.filename().string(), "File does not exist"};
        }

        std::ifstream file(path);
        if (!file.is_open()) {
            return ErrorInfo{path.filename().string(), "Cannot open file"};
        }

        size_t line_count = 0;
        size_t max_len = 0;
        std::string first_line;
        std::string line;

        while (std::getline(file, line)) {
            if (line_count == 0) {
                first_line = line;
            }
            if (line.length() > max_len) {
                max_len = line.length();
            }
            ++line_count;
        }

        return FileInfo{
            path.filename().string(),
            line_count,
            max_len,
            line_count > 0 ? std::make_optional(first_line) : std::nullopt
        };

    } catch (const std::exception& e) {
        return ErrorInfo{path.filename().string(), e.what()};
    }
}

int main() {
    auto start = std::chrono::high_resolution_clock::now();

    fs::path dir = ".";
    std::vector<Result> results;

    for (const auto& entry : fs::directory_iterator(dir)) {
        if (entry.path().extension() == ".txt") {
            results.push_back(analyze_file(entry.path()));
        }
    }

    // Вывод результатов
    for (const auto& res : results) {
        std::visit([](const auto& data) {
            using T = std::decay_t<decltype(data)>;
            if constexpr (std::is_same_v<T, FileInfo>) {
                std::cout << data.filename
                          << ": " << data.line_count << " lines, "
                          << "longest: " << data.max_line_length << " chars";
                if (data.first_line) {
                    std::cout << ", first: '" << *data.first_line << "'";
                }
                std::cout << "\n";
            } else {
                std::cout << "ERROR [" << data.filename << "]: " << data.message << "\n";
            }
        }, res);
    }

    auto end = std::chrono::high_resolution_clock::now();
    auto duration = std::chrono::duration_cast<std::chrono::microseconds>(end - start);
    std::cout << "\nTotal time: " << duration.count() << " μs\n";

    return 0;
}
```

> 🔧 **Как компилировать:**
```bash
g++ -std=c++20 -lstdc++fs main.cpp -o analyzer
```

---

## 📌 **Итог**

Ты теперь:
- Используешь `std::string_view` вместо `const std::string&`,
- Применяешь `std::optional` и `std::variant` для безопасного возврата значений,
- Понимаешь `if constexpr` и концепты,
- Работаешь с файловой системой на C++17+,
- Пишешь чистый, современный C++.

---

Хочешь — могу:
- Подготовить **PDF с этими решениями**,
- Сделать **тест из 20 вопросов** по Modern C++,
- Дать **аналогичные решения для остальных недель**.

Просто скажи: **"Да, хочу PDF"** или **"Продолжи со следующей неделей"** 😊


# Что такое const, constexpr, mutable?

Отличный вопрос! Разберём подробно три ключевых ключевых слова в C++:  
**`const`**, **`constexpr`**, и **`mutable`** — что они означают, чем отличаются и как используются.

---

## 🔹 1. `const` — **константность**

### ✅ Что делает:
Объявляет, что **объект или значение не должно изменяться** после инициализации.

### 📌 Где используется:

#### 1. Переменные
```cpp
const int x = 10;
x = 20; // ОШИБКА: нельзя изменить const
```

#### 2. Указатели
```cpp
const int* ptr;        // указатель на const int (данные нельзя менять)
int* const ptr;        // const указатель (адрес нельзя менять)
const int* const ptr;  // и данные, и указатель — const
```

#### 3. Методы классов
```cpp
class MyClass {
    int value;
public:
    int get() const {  // гарантирует: метод НЕ изменит объект
        return value;
    }
};
```
> ✅ `const`-метод может вызываться на `const` объектах.

#### 4. Параметры функций
```cpp
void print(const std::string& s) {
    // s нельзя изменить — безопасно и эффективно
}
```

### 💡 Зачем:
- Защита от случайных изменений.
- Подсказка компилятору для оптимизации.
- Требование для работы с STL (например, `const` итераторы).

---

## 🔹 2. `constexpr` — **вычисление на этапе компиляции**

### ✅ Что делает:
Гарантирует, что **значение или функция могут быть вычислены во время компиляции**, если аргументы известны.

### 📌 Где используется:

#### 1. Переменные
```cpp
constexpr int square(int n) {
    return n * n;
}

constexpr int x = square(5);  // вычисляется на этапе компиляции → x = 25
```

> ✅ `constexpr` переменная **должна** быть инициализирована константным выражением.

#### 2. Функции
```cpp
constexpr double gravity() {
    return 9.81;
}

constexpr double potential_energy(double mass, double height) {
    return mass * gravity() * height;
}

constexpr double pe = potential_energy(10.0, 5.0); // OK, если аргументы известны на этапе компиляции
```

> ⚠️ В C++14+ `constexpr` функции могут содержать циклы, условия и т.д.

#### 3. Объекты
```cpp
struct Point {
    constexpr Point(double x, double y) : x(x), y(y) {}
    double x, y;
};

constexpr Point origin(0, 0); // объект создается на этапе компиляции
```

### 💡 Зачем:
- Производительность: вычисления "выполняются" ещё до запуска программы.
- Возможность использовать значения в местах, где требуется **compile-time constant**, например:
  - Размер массива: `int arr[constexpr_size];`
  - Шаблоны: `std::array<int, N>`

---

## 🔹 3. `mutable` — **исключение из константности**

### ✅ Что делает:
Позволяет **изменять поле класса даже внутри `const`-метода**.

### 📌 Зачем нужно:
Иногда нужно, чтобы **объект логически оставался "неизменным"**, но при этом **обновлял внутреннее состояние**, например:
- Кэширование,
- Счётчик вызовов,
- Мьютексы в потокобезопасных классах.

### 📌 Пример:

```cpp
class Logger {
    mutable int call_count;  // можно менять в const-методах
    mutable std::string cache;

public:
    Logger() : call_count(0) {}

    // const-метод, но может обновлять mutable поля
    void log(const std::string& msg) const {
        ++call_count;  // OK: mutable
        if (cache.empty()) {
            cache = "Cached: " + msg;  // OK: mutable
        }
        std::cout << msg << " (call #" << call_count << ")\n";
    }

    int get_call_count() const {
        return call_count;
    }
};

int main() {
    const Logger logger;  // объект const
    logger.log("Hello");  // OK: метод const, но меняет mutable поля
    logger.log("World");
    std::cout << "Total calls: " << logger.get_call_count() << "\n";
    return 0;
}
```

### 💡 Зачем:
- Логическая константность ≠ физическая.
- Позволяет реализовывать **потокобезопасные `const`-методы** (например, с `mutable std::mutex`).

---

## 🔄 Сравнение: `const` vs `constexpr` vs `mutable`

| Слово       | Где применяется       | Когда вычисляется     | Можно ли изменить?         | Пример использования |
|------------|------------------------|------------------------|-----------------------------|-----------------------|
| `const`    | Переменные, методы, параметры | Во время выполнения (или компиляции) | ❌ (обычно) | `const int size = 10;` |
| `constexpr`| Переменные, функции, конструкторы | **На этапе компиляции** (если возможно) | ❌ | `constexpr int sq = square(5);` |
| `mutable`  | Поля класса            | Во время выполнения    | ✅ даже в `const`-методах | `mutable int cache_hits;` |

---

## ✅ Пример, объединяющий все три:

```cpp
class Counter {
    mutable int access_count;  // считаем, сколько раз читали
    const int id;              // id нельзя изменить
public:
    constexpr Counter(int id) : id(id), access_count(0) {}

    int get_id() const {       // const-метод
        ++access_count;        // OK: mutable
        return id;             // OK: чтение const
    }

    int get_access_count() const {
        return access_count;
    }
};

int main() {
    constexpr Counter c(42);   // объект создается на этапе компиляции
    std::cout << c.get_id() << "\n";           // 42
    std::cout << c.get_access_count() << "\n"; // 1
    return 0;
}
```

---

## 💡 Подсказка на собеседование:
> **"const означает 'не изменяется', constexpr — 'вычисляется на этапе компиляции', а mutable — 'исключение из const'."**

---

Хочешь — могу дать **тест из 5 вопросов** по этим ключевым словам или **подборку задач** для закрепления.


# Чем отличается struct от class?

Отличный вопрос! В **C++** разница между `struct` и `class` — **очень тонкая, но важная**. На первый взгляд они почти одинаковы, но есть **одно ключевое отличие** и несколько **семантических соглашений**.

---

## 🔑 **Главное отличие: уровень доступа по умолчанию**

| Контекст       | `class`                     | `struct`                     |
|----------------|-----------------------------|------------------------------|
| **Члены (поля, методы)** | `private` по умолчанию       | `public` по умолчанию         |
| **Базовые классы (наследование)** | `private` по умолчанию | `public` по умолчанию         |

---

### ✅ Пример: члены по умолчанию

```cpp
class MyClass {
    int x;        // private по умолчанию
    void foo();   // тоже private
public:
    int y;        // явно public
};
```

```cpp
struct MyStruct {
    int x;        // public по умолчанию
    void foo();   // тоже public
private:
    int y;        // можно сделать private явно
};
```

> Оба работают одинаково, просто **уровень доступа по умолчанию разный**.

---

### ✅ Пример: наследование

```cpp
class Base {};
class Derived : Base {};  // эквивалентно: class Derived : private Base {}
```

```cpp
struct Base {};
struct Derived : Base {};  // эквивалентно: struct Derived : public Base {}
```

---

## 🔄 **Что ОБЩЕГО у `struct` и `class`?**

В C++ **`struct` — это не структура из C**. Это полноценный **тип класса**. То есть:

- У `struct` могут быть:
  - Конструкторы и деструкторы
  - Методы
  - `private`, `protected`, `public` члены
  - Виртуальные функции
  - Наследование
  - Шаблоны

```cpp
struct Point {
    double x, y;

    // Конструктор
    Point(double x, double y) : x(x), y(y) {}

    // Метод
    double distance() const {
        return std::sqrt(x*x + y*y);
    }

    // Оператор
    bool operator==(const Point& other) const {
        return x == other.x && y == other.y;
    }
};
```

✅ Это **полноценный класс**, просто объявленный через `struct`.

---

## 🧠 **Семантическое различие (по соглашению)**

Хотя технически `struct` и `class` взаимозаменяемы, в C++ принято использовать их **по смыслу**:

| Использование | Рекомендуется |
|---------------|---------------|
| **`struct`**  | Для **простых агрегатов данных (POD)**, где все поля `public`, нет сложной логики, инкапсуляции. Например: `Point`, `RGB`, `Person`. |
| **`class`**   | Для **объектов с поведением**, инкапсуляцией, методами, скрытыми данными. Например: `BankAccount`, `Logger`, `GameEngine`. |

### ✅ Примеры:

```cpp
// struct — данные
struct Point {
    double x, y;
};

struct Config {
    std::string host;
    int port;
    bool debug;
};
```

```cpp
// class — поведение и инкапсуляция
class BankAccount {
private:
    double balance;
    std::string owner;

public:
    void deposit(double amount);
    double get_balance() const;
};
```

---

## 🚀 Современный C++: `struct` тоже может быть сложным

Но ничто не мешает писать так:

```cpp
struct Counter {
    Counter() { ++count; }
    ~Counter() { --count; }
private:
    static int count;
public:
    static int get_count() { return count; }
};
```

✅ Это **полностью валидно** и используется, например, в шаблонах или метапрограммировании.

---

## 📌 Итог: чем отличается `struct` от `class`?

| Критерий                     | `struct`                          | `class`                           |
|-----------------------------|-----------------------------------|-----------------------------------|
| **Доступ к членам по умолчанию** | `public`                         | `private`                         |
| **Наследование по умолчанию**    | `public`                         | `private`                         |
| **Могут ли иметь методы?**       | ✅ Да                            | ✅ Да                             |
| **Могут ли быть шаблонами?**     | ✅ Да                            | ✅ Да                             |
| **Семантика (по соглашению)**    | Данные, POD, "открытая" структура | Объекты, инкапсуляция, поведение  |

---

## 💡 На собеседовании скажи так:

> «В C++ `struct` и `class` почти одинаковы. Единственное отличие — уровень доступа по умолчанию: у `class` он `private`, у `struct` — `public`. Также по соглашению `struct` используют для простых структур данных, а `class` — для объектов с инкапсуляцией и поведением».

---

Хочешь — могу дать **5 задач** на закрепление этой темы или **пример с наследованием `struct` от `class`**.



# Что такое static (переменная, метод, функция)?

Отличный вопрос! Ключевое слово `static` в C++ имеет **разный смысл в зависимости от контекста**, и его понимание критически важно как для новичков, так и для продвинутых разработчиков.

Разберём **все основные случаи использования `static`**:

---

## 🔹 1. `static` **внутри функции** (локальная статическая переменная)

### ✅ Что делает:
Переменная **создаётся один раз при первом вызове** и **сохраняет своё значение между вызовами**.

### 📌 Пример:
```cpp
void counter() {
    static int count = 0;  // инициализируется только один раз
    count++;
    std::cout << "Call #" << count << "\n";
}

int main() {
    counter(); // Call #1
    counter(); // Call #2
    counter(); // Call #3
    return 0;
}
```

### 💡 Особенности:
- Инициализируется **один раз** (при первом входе в функцию).
- Хранится в **статической памяти**, а не на стеке.
- Потокобезопасна в C++11+ (инициализация гарантированно потокобезопасна).

---

## 🔹 2. `static` **переменная класса** (статическое поле)

### ✅ Что делает:
Поле **принадлежит всему классу**, а не отдельному объекту. У всех экземпляров — **одно и то же значение**.

### 📌 Пример:
```cpp
class Counter {
public:
    static int total;  // объявление

    Counter() { total++; }
    ~Counter() { total--; }
};

// Определение (обязательно вне класса!)
int Counter::total = 0;

int main() {
    std::cout << Counter::total << "\n";  // 0

    Counter c1, c2;
    std::cout << Counter::total << "\n";  // 2

    {
        Counter c3;
        std::cout << Counter::total << "\n";  // 3
    }
    std::cout << Counter::total << "\n";  // 2 (c3 уничтожен)
    return 0;
}
```

### 💡 Особенности:
- Должна быть **определена один раз** в `.cpp` файле (если не `constexpr`).
- Доступна через имя класса: `Counter::total`.
- Полезна для счётчиков, конфигураций, кэшей и т.д.

> ⚠️ Начиная с C++17, можно использовать `inline static`, чтобы определить прямо в классе:
> ```cpp
> class Counter {
>     inline static int total = 0;  // больше не нужно определение вне класса
> };
> ```

---

## 🔹 3. `static` **метод класса**

### ✅ Что делает:
Метод, который **не работает с конкретным объектом** (`this` не доступен), и может вызываться без создания экземпляра.

### 📌 Пример:
```cpp
class Math {
public:
    static int square(int x) {
        return x * x;
    }

    static double pi() {
        return 3.14159;
    }
};

int main() {
    int sq = Math::square(5);  // 25
    double p = Math::pi();     // 3.14159
    return 0;
}
```

### 💡 Особенности:
- Не имеет доступа к **нестатическим полям и методам** (нет `this`).
- Часто используются как **вспомогательные функции**, связанные с классом.
- Могут быть полезны для **фабричных методов**:
  ```cpp
  class Point {
      double x, y;
      Point(double x, double y) : x(x), y(y) {}
  public:
      static Point origin() { return Point(0, 0); }
      static Point random();
  };
  ```

---

## 🔹 4. `static` **вне класса / в пространстве имён** (устаревшее использование)

> ⚠️ Это **C-style `static`**, который **не рекомендуется** в современном C++.

### ✅ Что делает:
Ограничивает **область видимости функции или переменной** файлом, в котором она объявлена (internal linkage).

### 📌 Пример:
```cpp
// helper.cpp
static int helper_counter = 0;  // видна только в helper.cpp

static void log_debug() {       // только в этом файле
    std::cout << "Debug: " << ++helper_counter << "\n";
}
```

> 🔁 Вместо этого в C++ рекомендуется использовать **анонимные пространства имён**:
> ```cpp
> namespace {
>     int counter = 0;
>     void log_debug() { ... }
> }
> ```

---

## 🔚 **Итоговая таблица: `static` в разных контекстах**

| Контекст                     | Что делает                                                                 | Пример |
|-----------------------------|---------------------------------------------------------------------------|--------|
| `static int x;` в функции   | Переменная сохраняет значение между вызовами                             | `static int count = 0;` |
| `static int x;` в классе    | Общее поле для всех объектов класса                                       | `static int total;` |
| `static void f();` в классе | Метод без `this`, вызывается через имя класса                            | `Math::sqrt(4)` |
| `static` на уровне файла    | Ограничивает видимость (internal linkage) — **устарело**                 | `static void helper()` |

---

## 💡 На собеседовании скажи так:

> «`static` в C++ зависит от контекста:
>
> - Внутри функции — переменная живёт всё время и сохраняет значение.
> - В классе — поле или метод, общий для всех объектов.
> - На уровне файла — ограничивает видимость (но лучше использовать анонимные namespace).
>
> Также с C++17 можно использовать `inline static` для статических полей, чтобы не определять их вне класса.»

---

Хочешь — могу дать:
- **5 задач на `static`** (от простых к сложным),
- **Пример синглтона на `static`**,
- **Объяснение, чем `static` и `const`/`constexpr` отличаются**.

Просто скажи!


# Что значит потокобезопасеость в c++?

Отличный вопрос! **Потокобезопасность (thread safety)** — это ключевая концепция в C++, особенно при разработке многопоточных приложений. Давай разберёмся, что это значит, как она работает и какие есть уровни.

---

## 🧠 Что такое потокобезопасность?

**Потокобезопасность** — это свойство кода (функции, класса, объекта), которое гарантирует корректную работу **при одновременном доступе из нескольких потоков** без приведения к:
- **Гонкам данных (data races)**,
- **Непредсказуемому поведению**,
- **Повреждению памяти**.

> ✅ **Потокобезопасный код** — это код, который **не сломается**, если его вызывать из нескольких потоков одновременно.

---

## ⚠️ Пример **небезопасного** кода

```cpp
#include <iostream>
#include <thread>

int counter = 0;

void increment() {
    for (int i = 0; i < 100000; ++i) {
        counter++;  // ⚠️ Гонка данных! НЕ атомарно
    }
}

int main() {
    std::thread t1(increment);
    std::thread t2(increment);

    t1.join();
    t2.join();

    std::cout << "Counter: " << counter << "\n";  // ❌ Не всегда 200000!
    return 0;
}
```

> 🔥 Почему? Операция `counter++` состоит из трёх шагов:
> 1. Чтение значения,
> 2. Увеличение,
> 3. Запись обратно.
>
> Два потока могут одновременно прочитать одно и то же значение → результат теряется.

---

## ✅ Как сделать код потокобезопасным?

### 1. **Использование мьютекса (`std::mutex`)**

```cpp
#include <iostream>
#include <thread>
#include <mutex>

int counter = 0;
std::mutex mtx;

void increment() {
    for (int i = 0; i < 100000; ++i) {
        std::lock_guard<std::mutex> lock(mtx);  // захватывает мьютекс
        counter++;
    }
}
```

> ✅ Теперь доступ к `counter` защищён — только один поток может его изменять в каждый момент.

---

### 2. **Использование атомарных переменных (`std::atomic`)**

```cpp
#include <atomic>

std::atomic<int> counter{0};  // ✅ атомарная операция

void increment() {
    for (int i = 0; i < 100000; ++i) {
        counter++;  // ✅ атомарно
    }
}
```

> ✅ Быстрее, чем мьютекс, если нужно только изменить одну переменную.

---

## 📚 Уровни потокобезопасности

Разные компоненты могут быть потокобезопасны по-разному:

| Уровень | Описание |
|--------|--------|
| **Не потокобезопасен** | Нельзя использовать из нескольких потоков без внешней синхронизации. Пример: `std::vector`, если два потока пишут одновременно. |
| **Потокобезопасен для чтения** | Несколько потоков могут **читать** один объект, но **запись требует синхронизации**. Пример: `std::string` — можно читать из нескольких потоков, но нельзя писать параллельно. |
| **Полностью потокобезопасен** | Все операции безопасны при многопоточном доступе (обычно за счёт внутренних мьютексов). Редко в стандартной библиотеке. |
| **Атомарные типы** | `std::atomic<T>` — потокобезопасны по определению. |

---

## 🧩 Потокобезопасность в STL

Вот как ведут себя контейнеры STL:

| Контейнер | Множественное чтение? | Параллельное чтение/запись? | Параллельная запись? |
|----------|------------------------|-------------------------------|------------------------|
| `std::vector`, `std::list` и др. | ✅ Да | ❌ Нет (только если разные объекты) | ❌ Нет |
| `std::string` | ✅ Чтение | ❌ Запись требует синхронизации | ❌ |
| `std::shared_ptr` | ✅ Чтение `shared_ptr` | ✅ Указатель на объект можно читать | ❌ Сам объект — не защищён! |

> 🔥 Важно: `std::shared_ptr<T>` **потокобезопасен**, если:
> - Несколько `shared_ptr`'ов ссылаются на **один объект**, но используются в разных потоках — **управление счётчиком ссылок потокобезопасно**.
> - Но **объект, на который он указывает**, **не защищён автоматически**!

```cpp
std::shared_ptr<MyClass> ptr = std::make_shared<MyClass>();

// Поток 1
auto p1 = ptr;  // ✅ OK: копирование shared_ptr — потокобезопасно

// Поток 2
auto p2 = ptr;  // ✅ OK

// Но если оба потока делают ptr->modify() — нужна синхронизация!
```

---

## 🛡️ Как достичь потокобезопасности?

| Способ | Когда использовать |
|-------|---------------------|
| `std::mutex` + `std::lock_guard` | Когда нужно защитить блок кода или данные |
| `std::atomic<T>` | Для простых типов (int, bool, указатели) |
| `std::shared_mutex` (C++17) | Когда много читателей, мало писателей (read-write lock) |
| `thread_local` | Когда каждому потоку нужна своя копия данных |
| Асинхронность (`std::async`, `std::future`) | Чтобы избежать ручной синхронизации |

---

## 💡 `thread_local` — отдельный вид "безопасности"

```cpp
thread_local int local_counter = 0;  // У каждой нити — своя копия

void worker() {
    local_counter = 10;
    std::cout << "Thread " << std::this_thread::get_id()
              << ": " << local_counter << "\n";
}
```

> ✅ Нет гонок, потому что у каждого потока своя переменная.

---

## ⚠️ Распространённые ошибки

1. **Думать, что `std::vector` потокобезопасен** — ❌  
   Только если разные потоки работают с **разными объектами**.

2. **Использовать `const` объект как "автоматически потокобезопасный"** — ❌  
   `const` не означает потокобезопасность. Если один поток читает, а другой пишет — всё равно гонка.

3. **Забыть про `mutable` и кэширование в `const`-методах** —  
   Если `const`-метод меняет `mutable std::string cache`, нужно защищать мьютексом.

```cpp
class CachedData {
    mutable std::string cache;
    mutable std::mutex mtx;
public:
    std::string get() const {
        std::lock_guard<std::mutex> lock(mtx);
        if (cache.empty()) {
            cache = heavy_computation();
        }
        return cache;
    }
};
```

---

## ✅ Итог: что значит потокобезопасность?

> **Потокобезопасность** — это способность кода корректно работать при одновременном доступе из нескольких потоков, без:
> - гонок данных,
> - повреждения состояния,
> - неопределённого поведения.

### 🔐 Достигается с помощью:
- `std::mutex`
- `std::atomic`
- `std::lock_guard`
- `thread_local`
- Правильного проектирования (разделение данных, минимизация общего состояния)

---

## 💬 На собеседовании скажи так:

> «Потокобезопасность означает, что код может безопасно использоваться из нескольких потоков. В C++ стандартная библиотека не делает объекты потокобезопасными автоматически — кроме случаев вроде `std::shared_ptr` (счётчик ссылок). Для защиты данных используют `mutex`, `atomic`, или `thread_local`. Главное — избегать data race, особенно при изменении общих переменных.»

---

Хочешь — могу:
- Дать **5 задач по потокобезопасности** (от простых до сложных),
- Прислать **пример пула потоков с очередью задач**,
- Объяснить **memory_order в std::atomic**.

Просто скажи!


# Что значит атомарный тип в c++?

Отличный вопрос! **Атомарный тип (atomic type)** в C++ — это ключевая часть многопоточного программирования, обеспечивающая **безопасность при одновременном доступе из нескольких потоков** без использования мьютексов.

---

## 🔹 Что такое атомарный тип?

**Атомарный тип** — это тип, операции над которым выполняются **как единая, неделимая операция** (поэтому и называется *атомарной*), и **не может быть прервана другим потоком**.

> ✅ Это гарантирует:  
> - **Нет гонки данных (data race)**,  
> - **Нет повреждения состояния**,  
> - **Корректное чтение/запись даже при параллельном доступе**.

---

## 📌 Простой пример: `std::atomic<int>`

```cpp
#include <iostream>
#include <thread>
#include <atomic>

std::atomic<int> counter{0};  // атомарная переменная

void increment() {
    for (int i = 0; i < 100000; ++i) {
        counter++;  // ✅ Атомарная операция
    }
}

int main() {
    std::thread t1(increment);
    std::thread t2(increment);

    t1.join();
    t2.join();

    std::cout << "Counter: " << counter << "\n";  // ✅ Всегда 200000
    return 0;
}
```

> ✅ Без `std::atomic` был бы **data race**, и результат был бы **непредсказуемым**.

---

## 🔧 Как работает `std::atomic<T>`?

`std::atomic<T>` — это **шаблонный класс** из заголовка `<atomic>`, который оборачивает тип `T` и делает операции над ним атомарными.

Поддерживаются:
- Целочисленные типы: `int`, `long`, `bool`, `char`, указатели и др.
- Некоторые пользовательские типы (ограниченно).

### Поддерживаемые операции:
```cpp
counter++;     // инкремент
counter += 5;  // сложение
counter.store(10);   // запись
int x = counter.load();  // чтение
counter.exchange(42);    // замена и возврат старого значения
counter.compare_exchange_weak(expected, desired);  // CAS
```

---

## 🔁 Основные методы `std::atomic`

| Метод | Что делает |
|------|-----------|
| `.store(val)` | Атомарно записывает значение |
| `.load()` | Атомарно читает значение |
| `.exchange(val)` | Заменяет значение и возвращает старое |
| `.compare_exchange_weak(expected, desired)` | Если текущее значение == `expected`, то заменяет на `desired` (CAS — Compare-And-Swap) |
| `++`, `--`, `+=` и др. | Атомарные операции (для арифметических типов) |

---

## ✅ Пример: `compare_exchange_weak`

Используется для **безблокировочных (lock-free)** структур данных.

```cpp
std::atomic<int> value{0};

int expected = value.load();
while (!value.compare_exchange_weak(expected, expected + 1)) {
    // если кто-то другой изменил value, expected обновится автоматически
    // и цикл повторится
}
// теперь value == expected + 1
```

> 🔁 Это классический шаблон для реализации атомарного инкремента вручную.

---

## 🚀 Преимущества `std::atomic` перед `std::mutex`

| Критерий | `std::atomic` | `std::mutex` |
|--------|---------------|--------------|
| **Скорость** | ✅ Очень быстро (часто реализуется через CPU-инструкции) | ❌ Медленнее (включает системные вызовы) |
| **Блокировки** | ❌ Нет блокировок (lock-free) | ✅ Блокирует потоки |
| **Использование** | Только для простых типов | Любой код, блок, структура |
| **Гибкость** | Ограничен | Высокая |

> 💡 Используй `std::atomic`, если нужно защитить **одну переменную**.  
> Используй `std::mutex`, если нужно защитить **несколько полей или сложную логику**.

---

## ⚠️ Ограничения и подводные камни

### 1. Не все типы поддерживаются
```cpp
std::atomic<std::string> s;  // ❌ Ошибка! std::string не атомарен
std::atomic<int> x;          // ✅ OK
```

> Для сложных типов используй `std::mutex`.

---

### 2. `std::atomic` не делает объект потокобезопасным
```cpp
struct Data {
    int a, b;
};

std::atomic<Data> data;  // ❌ Только если Data — тривиальный тип и lock-free
```

> Даже если возможно, изменение `a` и `b` **не атомарно вместе**. Лучше использовать мьютекс.

---

### 3. Порядок выполнения (memory ordering)
По умолчанию `std::atomic` использует `memory_order_seq_cst` — **строгая согласованность**, но можно указать более слабые режимы для производительности.

```cpp
counter.load(std::memory_order_relaxed);  // быстрее, но меньше гарантий
```

> ⚠️ Слабые порядки (`relaxed`, `acquire`, `release`) сложны в использовании — лучше начинать с `seq_cst`.

---

## 🧠 Когда использовать `std::atomic`?

| Ситуация | Решение |
|--------|--------|
| Счётчик вызовов | ✅ `std::atomic<int>` |
| Флаг завершения | ✅ `std::atomic<bool>` |
| Указатель в lock-free стеке | ✅ `std::atomic<Node*>` |
| Объект с несколькими полями | ❌ Лучше `std::mutex` |
| `std::string`, `std::vector` | ❌ Не поддерживаются напрямую |

---

## 💡 На собеседовании скажи так:

> «`std::atomic<T>` — это шаблон, который делает операции над типом `T` атомарными, то есть неделимыми и безопасными при многопоточном доступе. Он использует аппаратные инструкции процессора (например, CAS) и позволяет писать lock-free код. Чаще всего используется для счётчиков, флагов, указателей. В отличие от мьютекса — очень быстрый, но применим только к простым типам.»

---

## 📚 Пример: флаг остановки

```cpp
#include <iostream>
#include <thread>
#include <atomic>
#include <chrono>

std::atomic<bool> stop{false};

void worker() {
    while (!stop.load()) {
        std::cout << "Working...\n";
        std::this_thread::sleep_for(std::chrono::seconds(1));
    }
    std::cout << "Stopped.\n";
}

int main() {
    std::thread t(worker);

    std::this_thread::sleep_for(std::chrono::seconds(3));
    stop.store(true);  // сигнал остановки

    t.join();
    return 0;
}
```

> ✅ Безопасный способ остановить поток.

---

Хочешь — могу:
- Дать **5 задач на `std::atomic`**,
- Объяснить **разницу между `memory_order_relaxed`, `acquire`, `release`**,
- Показать **реализацию lock-free счётчика**.

Просто скажи!


# Как работает virtual и таблица виртуальных функций (vtable)?

Отличный вопрос! Понимание **`virtual`** и **таблицы виртуальных функций (vtable)** — ключ к глубокому пониманию **динамического полиморфизма** в C++. Давай разберём это подробно, с примерами и схемами.

---

## 🔍 Что делает `virtual`?

Ключевое слово `virtual` позволяет функции **вызываться по типу объекта в момент выполнения (runtime)**, а не по типу указателя/ссылки (как при статическом связывании).

### ✅ Простой пример:

```cpp
#include <iostream>

class Animal {
public:
    virtual void speak() {
        std::cout << "Animal speaks\n";
    }
};

class Dog : public Animal {
public:
    void speak() override {  // override — не обязательно, но рекомендуется
        std::cout << "Woof!\n";
    }
};

int main() {
    Animal* ptr = new Dog();
    ptr->speak();  // Вывод: "Woof!"
    
    delete ptr;
    return 0;
}
```

> ❓ Почему вывелось `"Woof!"`, а не `"Animal speaks"`?  
> Потому что `speak()` — **виртуальная функция**, и вызов происходит **по реальному типу объекта (`Dog`)**.

---

## 🧠 Как это работает "под капотом"? — Введение в `vtable`

Когда вы объявляете функцию как `virtual`, компилятор создаёт **таблицу виртуальных функций (vtable)** для каждого класса.

### 🔹 Что такое `vtable`?
- Это **массив указателей на функции**, создаваемый компилятором **для каждого класса, имеющего виртуальные функции**.
- Каждый объект такого класса содержит **скрытое поле — указатель на vtable (`vptr`)**.

---

## 📦 Структура объекта с `virtual`

Для класса с виртуальными функциями:
```cpp
class Animal {
    void* __vptr;         // Скрытый указатель на vtable
    std::string name;     // Ваши поля
};
```

> `__vptr` устанавливается автоматически при создании объекта.

---

## 🧩 Пример с `vtable`

```cpp
class Animal {
public:
    virtual void speak() { std::cout << "Animal\n"; }
    virtual void eat()   { std::cout << "Eating\n"; }
};

class Dog : public Animal {
public:
    void speak() override { std::cout << "Woof!\n"; }
    // eat() наследуется
};

class Cat : public Animal {
public:
    void speak() override { std::cout << "Meow!\n"; }
    void eat()   override { std::cout << "Cat eats fish\n"; }
};
```

### 🔹 Что создаёт компилятор?

#### 1. `vtable` для `Animal`:
| Функция       | Указатель на         |
|---------------|-----------------------|
| `speak()`     | `Animal::speak`       |
| `eat()`       | `Animal::eat`         |

#### 2. `vtable` для `Dog`:
| Функция       | Указатель на         |
|---------------|-----------------------|
| `speak()`     | `Dog::speak`          |
| `eat()`       | `Animal::eat`         | ← унаследовано

#### 3. `vtable` для `Cat`:
| Функция       | Указатель на         |
|---------------|-----------------------|
| `speak()`     | `Cat::speak`          |
| `eat()`       | `Cat::eat`            |

---

## ⚙️ Как происходит вызов `ptr->speak()`?

```cpp
Animal* ptr = new Dog();
ptr->speak();
```

Шаги:
1. Компилятор видит: `ptr` — указатель на `Animal`, но `speak()` — `virtual`.
2. Во время выполнения:
   - Берётся `ptr->__vptr` → указатель на `vtable` объекта.
   - Из `vtable` берётся указатель на `speak()` (в данном случае — на `Dog::speak`).
   - Вызывается найденная функция.
3. Результат: вызывается `Dog::speak()`.

> ✅ Это называется **поздним связыванием (late binding)** или **динамическим полиморфизмом**.

---

## 🧱 Что происходит при наследовании?

- Производный класс **наследует `vtable`**, но **перезаписывает** указатели на функции, которые он переопределяет.
- Если функция не переопределена — в `vtable` остаётся указатель на родительскую реализацию.

---

## 📉 Накладные расходы

| Стоимость | Описание |
|---------|--------|
| ✅ **Память** | Каждый объект с `virtual` функциями хранит `vptr` (обычно 8 байт на 64-битной системе). |
| ✅ **Скорость** | Вызов виртуальной функции — косвенный (через таблицу), поэтому **немного медленнее**, чем обычный вызов. |
| ❌ **Нельзя inlining** | Компилятор не может инлайнить виртуальные функции (тип неизвестен на этапе компиляции). |

---

## 🔥 Важные нюансы

### 1. `virtual` только для указателей и ссылок
```cpp
Dog d;
Animal& ref = d;
ref.speak();  // ✅ Виртуальный вызов → "Woof!"

d.speak();    // ❌ Прямой вызов → "Woof!", но не через vtable
```

> Виртуальность проявляется только при **косвенном вызове** (через базовый класс).

---

### 2. Деструктор должен быть `virtual`!
```cpp
class Base {
public:
    virtual ~Base() = default;  // ✅ Обязательно!
};

class Derived : public Base {
    ~Derived() override { /* cleanup */ }
};

Base* ptr = new Derived();
delete ptr;  // Без virtual: вызовется только ~Base!
```

> ❗ Без `virtual` деструктора — **неопределённое поведение** при удалении производного класса через базовый указатель.

---

### 3. `override` и `final`
```cpp
class Dog : public Animal {
public:
    void speak() override;        // явно указываем, что переопределяем
    void run()    final;          // запрещаем дальнейшее переопределение
};

class Bulldog : public Dog {
public:
    void run() override;  // ❌ Ошибка: run() — final
};
```

---

## 🧩 Пример: как выглядит память

```cpp
Dog dog;
```

| Память объекта `dog`         |
|------------------------------|
| `__vptr` → указывает на `Dog`'s vtable |
| `name` (если есть)           |
| другие поля                  |

---

## ✅ Итог: как работает `virtual` и `vtable`

| Шаг | Что происходит |
|-----|----------------|
| 1 | При наличии `virtual` функций компилятор создаёт `vtable` для класса |
| 2 | Каждый объект получает скрытое поле `vptr` — указатель на свою `vtable` |
| 3 | При вызове `ptr->virtual_func()` происходит: <br> `vptr → vtable → нужная функция` |
| 4 | Реализация выбирается **во время выполнения** (runtime) |

---

## 💬 На собеседовании скажи так:

> «Когда в классе есть `virtual` функции, компилятор создаёт таблицу виртуальных функций (vtable) — массив указателей на функции. Каждый объект такого класса содержит скрытое поле `vptr`, указывающее на свою `vtable`. При вызове виртуальной функции через базовый указатель или ссылку, вызов разрешается через `vptr` и `vtable`, что позволяет вызывать правильную (переопределённую) версию функции в производных классах. Это механизм динамического полиморфизма. Главное — не забывать делать деструктор `virtual`, если класс предназначен для наследования.»

---

Хочешь — могу:
- Нарисовать схему `vtable` в ASCII,
- Прислать **задачи на `virtual` и полиморфизм**,
- Показать, как выглядит `vtable` в ассемблере (через Compiler Explorer).

Просто скажи!


# Что такое override, final?

Отличный вопрос! Ключевые слова **`override`** и **`final`** — важные элементы современного C++, которые помогают писать **более безопасный и понятный код** при использовании наследования и виртуальных функций.

Они появились в **C++11** (`override`) и **C++11** (`final`), и являются **спецификаторами переопределения** (необязательными, но крайне рекомендуемыми).

---

## 🔹 1. `override` — гарантирует, что вы переопределяете виртуальную функцию

### ✅ Зачем нужен?
Чтобы **явно указать**, что вы хотите **переопределить виртуальную функцию из базового класса**, и **получить ошибку компиляции**, если вы ошиблись (например, написали неправильное имя или сигнатуру).

---

### ❌ Проблема без `override`:

```cpp
class Animal {
public:
    virtual void speak() {
        std::cout << "Animal\n";
    }
};

class Dog : public Animal {
public:
    // ОШИБКА: опечатка в имени — speak → speek
    void speek() {  // ← не переопределяет, а создает новую функцию!
        std::cout << "Woof!\n";
    }
};
```

> 🔴 Код **скомпилируется**, но `speek()` **не будет вызвана** при `ptr->speak()` — полиморфизм **не работает**!

---

### ✅ Решение: используем `override`

```cpp
class Dog : public Animal {
public:
    void speek() override {  // ⚠️ ОШИБКА КОМПИЛЯЦИИ!
        std::cout << "Woof!\n";
    }
};
```

> ❌ Компилятор скажет:
> ```
> error: 'void Dog::speek()' marked 'override', but does not override
> ```

Теперь ошибка **обнаруживается на этапе компиляции**, а не в рантайме.

---

### ✅ Правильное использование:

```cpp
class Dog : public Animal {
public:
    void speak() override {  // ✅ OK: действительно переопределяет
        std::cout << "Woof!\n";
    }
};
```

---

### 💡 Правила:
- `override` можно ставить **только в производном классе**.
- Только для **виртуальных функций** (или функций, которые переопределяют виртуальные).
- Не меняет поведение кода — только **проверяет корректность**.

---

## 🔹 2. `final` — запрещает дальнейшее переопределение

`final` может применяться к:
- **функции** — нельзя переопределять в наследниках,
- **классу** — нельзя наследоваться от этого класса.

---

### ✅ `final` для функции

```cpp
class Dog : public Animal {
public:
    void speak() override final {  // 🛑 Никто не может переопределить speak()
        std::cout << "Woof!\n";
    }
};

class Bulldog : public Dog {
public:
    void speak() override {  // ❌ ОШИБКА: speak() — final!
        std::cout << "Bark!\n";
    }
};
```

> 🔴 Ошибка компиляции: нельзя переопределять `final` функцию.

---

### ✅ `final` для класса

```cpp
class SealedClass final {
public:
    virtual void doWork() { /* ... */ }
};

class Derived : public SealedClass {  // ❌ ОШИБКА!
    // Нельзя наследоваться от final-класса
};
```

> 🔴 Ошибка: "cannot derive from 'final' class".

---

### 💡 Когда использовать `final`?

| Ситуация | Пример |
|--------|--------|
| Хочу запретить изменение поведения | Критическая бизнес-логика |
| Класс — конечная реализация | `class JsonParser final` |
| Оптимизация | Компилятор может **инлайнить** вызовы `final` методов |
| Защита от наследования | Синглтон, утилиты, конфиги |

---

## 🔄 Сравнение: `override` vs `final`

| Ключевое слово | Где используется | Эффект |
|----------------|------------------|-------|
| `override`     | В производном классе | Гарантирует, что функция **переопределяет** виртуальную функцию базового класса |
| `final`        | В любом классе (метод или класс) | **Запрещает** дальнейшее переопределение (для метода) или наследование (для класса) |

---

## 🧩 Пример: комбинированное использование

```cpp
class Animal {
public:
    virtual void speak() { std::cout << "Animal\n"; }
    virtual ~Animal() = default;
};

class Dog final : public Animal {  // 🛑 Никто не может унаследоваться от Dog
public:
    void speak() override final {  // 🛑 Никто не может переопределить speak()
        std::cout << "Woof!\n";
    }
};

// class Puppy : public Dog { ... }  // ❌ Ошибка: Dog — final
```

---

## 💬 На собеседовании скажи так:

> «`override` — это спецификатор, который говорит компилятору: "я хочу переопределить виртуальную функцию из базового класса". Если такой функции нет — ошибка компиляции. Это помогает избегать опечаток и ошибок проектирования.  
>  
> `final` — запрещает переопределение функции или наследование от класса. Полезно, когда вы хотите зафиксировать поведение или запретить расширение класса. Оба ключевых слова делают код безопаснее и понятнее.»

---

## ✅ Лучшие практики

1. ✅ Всегда используйте `override`, когда **переопределяете** виртуальную функцию.
2. ✅ Используйте `final`, если **не планируете дальнейшее наследование**.
3. ✅ Комбинируйте `override final`, если метод должен быть последним в цепочке.
4. ❌ Не используйте `final` без причины — это ограничивает гибкость.

---

Хочешь — могу:
- Дать **5 задач на `override` и `final`**,
- Показать, как `final` помогает компилятору оптимизировать код,
- Прислать **пример с иерархией классов животных** с `override`/`final`.

Просто скажи!


# Распиши подробнее week 2

Конечно! Ниже — **подробная расшифровка Недели 2** из программы для **продвинутого уровня C++**, посвящённой **умным указателям и RAII**.

Эта неделя — одна из самых важных в современном C++. Освоив её, вы перестанете использовать `new`/`delete` вручную, научитесь писать **безопасный, устойчивый к исключениям код** и поймёте, как C++ управляет ресурсами.

---

# 📘 **Неделя 2: Умные указатели и RAII**

**Цель недели:**  
Научиться использовать **умные указатели** (`std::unique_ptr`, `std::shared_ptr`, `std::weak_ptr`) и понять философию **RAII (Resource Acquisition Is Initialization)**. Вы научитесь автоматически управлять памятью, избегать утечек и писать исключительно безопасный код.

---

## 🗓️ **Расписание по дням**

---

### **День 1: Введение в RAII и Rule of Zero/Three/Five**

#### 🔹 Темы:
- Что такое RAII?
- Rule of Zero, Three, Five
- Почему ручное управление памятью — плохо

#### 📚 Теория:
**RAII (Resource Acquisition Is Initialization)** — это идиома C++, при которой **получение ресурса** (память, файл, сокет) **связывается с созданием объекта**, а **освобождение — с его уничтожением**.

```cpp
class File {
    FILE* f;
public:
    File(const char* name) {
        f = fopen(name, "r");
        if (!f) throw std::runtime_error("Cannot open file");
    }
    ~File() {
        if (f) fclose(f);  // гарантируется вызов, даже при исключении
    }
    // ...
};
```

> ✅ Если выбросится исключение — деструктор вызовется автоматически → файл закроется.

---

#### 🔹 Rule of Three / Five / Zero

| Правило | Когда применяется |
|--------|------------------|
| **Rule of Three** | Если вы определяете один из: деструктор, копирующий конструктор, копирующий оператор — вероятно, нужно определить и остальные |
| **Rule of Five** | То же, но с добавлением move-конструктора и move-оператора (C++11+) |
| **Rule of Zero** | Лучше не определять их вовсе — делегируйте управление ресурсами умным указателям и контейнерам |

```cpp
// ✅ Хорошо: Rule of Zero
class Buffer {
    std::unique_ptr<int[]> data;
    size_t size;
public:
    Buffer(size_t n) : data(std::make_unique<int[]>(n)), size(n) {}
    // Не нужно писать деструктор, копирование, move — всё по умолчанию!
};
```

> ❌ Плохо: ручное управление → риск утечек, ошибок.

---

#### ✅ Практика:
1. Найдите в старом коде класс с `new`/`delete` и перепишите его с `std::unique_ptr`.
2. Объясните, почему `std::vector` следует Rule of Zero.
3. Создайте класс `Logger`, который открывает файл в конструкторе и закрывает в деструкторе.

---

### **День 2: `std::unique_ptr` — уникальное владение**

#### 🔹 Темы:
- `std::unique_ptr<T>` — единственный владелец ресурса
- Передача владения через `std::move`
- `std::make_unique` (C++14)

#### 📚 Теория:
```cpp
#include <memory>

std::unique_ptr<int> ptr = std::make_unique<int>(42);
std::cout << *ptr << "\n";  // 42

// Уникальный указатель нельзя копировать
// std::unique_ptr<int> ptr2 = ptr;  // ❌ Ошибка

// Но можно передать владение
std::unique_ptr<int> ptr2 = std::move(ptr);  // ✅ OK
// Теперь ptr == nullptr, ptr2 владеет объектом
```

```cpp
// make_unique — безопаснее и идиоматичнее
auto ptr = std::make_unique<Widget>(arg1, arg2);
// Лучше, чем: std::unique_ptr<Widget>(new Widget(arg1, arg2))
// (избегает утечки при исключении в arg2)
```

---

#### ✅ Практика:
1. Создайте `std::unique_ptr<BankAccount>` и передайте его в функцию.
2. Напишите функцию, возвращающую `std::unique_ptr<Shape>`.
3. Реализуйте односвязный список с `std::unique_ptr<Node>`.

---

### **День 3: `std::shared_ptr` и `std::weak_ptr` — разделяемое владение**

#### 🔹 Темы:
- `std::shared_ptr<T>` — владение с подсчётом ссылок
- `std::weak_ptr<T>` — не увеличивает счётчик, решает циклические ссылки
- `std::make_shared`

#### 📚 Теория:
```cpp
auto ptr1 = std::make_shared<int>(100);
std::shared_ptr<int> ptr2 = ptr1;  // счётчик = 2

std::cout << *ptr1 << "\n";        // 100
std::cout << ptr1.use_count() << "\n";  // 2
```

```cpp
// weak_ptr — не увеличивает счётчик
std::weak_ptr<int> weak = ptr1;
if (auto locked = weak.lock()) {  // проверяем, жив ли объект
    std::cout << *locked << "\n";
} else {
    std::cout << "Object destroyed\n";
}
```

> 🔁 **Циклические ссылки — проблема:**
```cpp
struct Node {
    std::shared_ptr<Node> parent;
    std::shared_ptr<Node> child;
};
// Если parent и child ссылаются друг на друга — счётчик никогда не станет 0!
```

> ✅ Решение: один из указателей — `std::weak_ptr`.

---

#### ✅ Практика:
1. Реализуйте двусвязный список с `std::shared_ptr` и `std::weak_ptr`.
2. Напишите класс `Observer`, использующий `std::weak_ptr`, чтобы избежать утечки.
3. Создайте `std::shared_ptr`, разделяемый между потоками (с `mutable` и мьютексом).

---

### **День 4: Утечки памяти и анализ с Valgrind / AddressSanitizer**

#### 🔹 Темы:
- Что такое утечка памяти?
- Как найти утечки?
- Valgrind (Linux), AddressSanitizer (все платформы)

#### 📚 Теория:
```cpp
void leak() {
    int* p = new int(42);  // ❌ Утечка: нет delete
    return;  // p теряется
}
```

> 🔍 Как найти:
- **Valgrind** (Linux): `valgrind --leak-check=full ./program`
- **AddressSanitizer** (Clang/GCC): `-fsanitize=address`
- **Visual Studio**: встроенный детектор утечек

```bash
g++ -fsanitize=address -g main.cpp -o main
./main  # ASan покажет утечку с трассировкой
```

---

#### ✅ Практика:
1. Напишите код с утечкой и найдите её через AddressSanitizer.
2. Исправьте циклическую ссылку `shared_ptr`.
3. Проанализируйте программу с `new`/`delete` и найдите `use-after-free`.

---

### **День 5: RAII на практике — собственные ресурсы**

#### 🔹 Темы:
- RAII для файлов, сокетов, мьютексов
- RAII-обёртки: `lock_guard`, `fstream`
- Пользовательские RAII-классы

#### 📚 Теория:
```cpp
// RAII для мьютекса
std::mutex mtx;
{
    std::lock_guard<std::mutex> lock(mtx);  // захватывает
    // ... безопасный код
} // автоматическое освобождение
```

```cpp
// RAII для файла
{
    std::ofstream file("log.txt");
    file << "Hello\n";
} // файл автоматически закрывается
```

```cpp
// Свой RAII-класс
class Timer {
    std::chrono::steady_clock::time_point start;
public:
    Timer() : start(std::chrono::steady_clock::now()) {}
    ~Timer() {
        auto end = std::chrono::steady_clock::now();
        std::cout << "Time: "
                  << std::chrono::duration_cast<std::chrono::microseconds>(end - start).count()
                  << " μs\n";
    }
};

void slow_function() {
    Timer t;  // замер времени
    std::this_thread::sleep_for(std::chrono::milliseconds(100));
} // в деструкторе — вывод времени
```

---

#### ✅ Практика:
1. Напишите RAII-обёртку для `FILE*` (C-style файл).
2. Создайте `ConnectionGuard` для сокета.
3. Реализуйте `ScopedTimer` с выводом в `std::ostream`.

---

### **День 6: Rule of Zero — идеальный дизайн**

#### 🔹 Темы:
- Как писать классы, не определяя деструктор, копирование и move
- Использование умных указателей и STL-контейнеров
- Когда всё-таки нужно `= default` или `= delete`

#### 📚 Теория:
```cpp
class MyClass {
    std::unique_ptr<int[]> data;
    std::string name;
    std::vector<double> values;

public:
    MyClass(size_t n, const std::string& s)
        : data(std::make_unique<int[]>(n)), name(s) {}

    // Не нужно писать:
    // ~MyClass() — unique_ptr сам удалит
    // MyClass(const MyClass&) — по умолчанию копирует name и values, data — ошибка (unique_ptr не копируется)
    // Но можно добавить:
    MyClass(const MyClass&) = delete;             // запретить копирование
    MyClass(MyClass&&) = default;                 // разрешить move
    MyClass& operator=(MyClass&&) = default;
};
```

> ✅ Rule of Zero: делегируйте управление ресурсами STL.

---

#### ✅ Практика:
1. Перепишите класс с `int*` на `std::unique_ptr<int[]>`.
2. Добавьте `= delete` для копирования, если это не нужно.
3. Создайте `Container`, который хранит `std::vector<std::unique_ptr<Object>>`.

---

### **День 7: Проект — Умный контейнер**

#### 🔹 Задача недели: **"Свой безопасный контейнер"**

**Цель:** Использовать все изученные концепции в одном проекте.

**Функционал:**
- Класс `SafeArray<T>`, управляющий массивом через `std::unique_ptr`.
- Поддержка:
  - `push_back(T value)`
  - `at(size_t i)` с проверкой границ
  - `size()`, `empty()`
  - Move-семантика (move constructor, move assignment)
- Не разрешать копирование (либо удалить, либо реализовать глубокое копирование)
- RAII: автоматическое освобождение памяти

**Требования:**
- Использует `std::unique_ptr`
- Следует Rule of Zero/Five
- Имеет деструктор по умолчанию
- Покрыт простыми тестами

---

#### ✅ Пример решения:

```cpp
#include <iostream>
#include <memory>
#include <stdexcept>

template <typename T>
class SafeArray {
    std::unique_ptr<T[]> data;
    size_t sz;
    size_t capacity;

    void grow() {
        capacity = capacity == 0 ? 1 : capacity * 2;
        std::unique_ptr<T[]> new_data = std::make_unique<T[]>(capacity);
        for (size_t i = 0; i < sz; ++i) {
            new_data[i] = std::move(data[i]);
        }
        data = std::move(new_data);
    }

public:
    explicit SafeArray(size_t cap = 10) : data(std::make_unique<T[]>(cap)), sz(0), capacity(cap) {}

    void push_back(const T& value) {
        if (sz >= capacity) grow();
        data[sz++] = value;
    }

    T& at(size_t i) {
        if (i >= sz) throw std::out_of_range("Index out of range");
        return data[i];
    }

    const T& at(size_t i) const {
        if (i >= sz) throw std::out_of_range("Index out of range");
        return data[i];
    }

    size_t size() const { return sz; }
    bool empty() const { return sz == 0; }

    // Rule of Five
    ~SafeArray() = default;
    SafeArray(const SafeArray&) = delete;              // запрещаем копирование
    SafeArray& operator=(const SafeArray&) = delete;
    SafeArray(SafeArray&&) = default;                  // разрешаем move
    SafeArray& operator=(SafeArray&&) = default;
};

int main() {
    SafeArray<int> arr;
    arr.push_back(10);
    arr.push_back(20);
    std::cout << arr.at(0) << ", " << arr.at(1) << "\n";  // 10, 20
    return 0;
}
```

---

## 📚 **Ресурсы для этой недели**

- **Книга:** *«Effective Modern C++»* — Scott Meyers (Item 18–21)
- **Видео:** *CppCon — "Back to the Basics: RAII and the Rule of the Big Five"*
- **Инструменты:**
  - [Compiler Explorer (godbolt.org)](https://godbolt.org) — с AddressSanitizer
  - Valgrind: `valgrind --tool=memcheck --leak-check=full ./program`

---

## ✅ **Чек-лист по итогам недели**

Вы готовы к следующей неделе, если можете:

- [ ] Объяснить, что такое RAII и зачем он нужен
- [ ] Использовать `std::unique_ptr`, `std::shared_ptr`, `std::weak_ptr`
- [ ] Объяснить разницу между ними
- [ ] Писать код без `new`/`delete`
- [ ] Обнаруживать утечки с AddressSanitizer
- [ ] Следовать Rule of Zero
- [ ] Реализовать простой RAII-класс
- [ ] Решить проблему циклических ссылок через `std::weak_ptr`

---

Хочешь — могу:
- Прислать **PDF с этой неделей**,
- Дать **тест из 10 вопросов** по умным указателям,
- Продолжить с **Недели 3: Шаблоны и метапрограммирование**.

Просто скажи!


# Продолжи с **Недели 3: Шаблоны и метапрограммирование**.

Отлично! Продолжаем погружение в **продвинутый C++**.

---

# 📘 **Неделя 3: Шаблоны и метапрограммирование**

**Уровень:** Продвинутый  
**Длительность:** 7 дней  
**Цель недели:** Научиться писать **гибкие, эффективные и безопасные шаблонные классы и функции**, понять принципы **SFINAE**, **variadic templates** и начать использовать **шаблонное метапрограммирование (TMP)**.

---

## 🗓️ **Расписание по дням**

---

### **День 1: Введение в шаблоны (функции и классы)**

#### 🔹 Темы:
- Шаблонные функции
- Шаблонные классы
- Явная специализация
- Вывод типов (`T`, `auto`)

#### 📚 Теория:
```cpp
// Шаблонная функция
template <typename T>
T max(T a, T b) {
    return (a > b) ? a : b;
}

int x = max(3, 5);        // T = int
double y = max(3.14, 2.7); // T = double
```

```cpp
// Шаблонный класс
template <typename T, size_t N>
class Array {
    T data[N];
public:
    T& operator[](size_t i) { return data[i]; }
    size_t size() const { return N; }
};

Array<int, 10> arr;  // массив из 10 int
```

```cpp
// Явная специализация
template <>
std::string max<std::string>(std::string a, std::string b) {
    return a.length() > b.length() ? a : b;
}
```

#### ✅ Практика:
1. Напишите шаблонную функцию `swap(T&, T&)`.
2. Создайте `Pair<T1, T2>` с полями `first`, `second`.
3. Специализируйте `Pair<int, int>` для поддержки `operator+`.

---

### **День 2: Специализация шаблонов (частичная и полная)**

#### 🔹 Темы:
- Полная специализация
- Частичная специализация (только для классов)
- Когда и зачем использовать

#### 📚 Теория:
```cpp
// Полная специализация
template <>
class Array<bool, 10> {
    // оптимизированное хранение — биты
    uint32_t bits;
    // ...
};
```

```cpp
// Частичная специализация
template <typename T>
class Array<T, 0> {  // массив "неизвестного" размера
    std::vector<T> data;
public:
    void push_back(const T& x) { data.push_back(x); }
};
```

```cpp
// Частичная специализация по указателю
template <typename T>
class Wrapper<T*> {
    T* ptr;
public:
    void release() { delete ptr; }
};
```

> ⚠️ Частичная специализация **не работает для функций** — используйте перегрузку.

#### ✅ Практика:
1. Создайте `SmartPointer<T>` и частично специализируйте для `T[]`.
2. Специализируйте `Array<std::string, N>` для автоматического логирования.
3. Напишите `is_pointer<T>` через полную специализацию.

---

### **День 3: Variadic Templates (шаблоны с переменным числом параметров)**

#### 🔹 Темы:
- Параметрические пакеты (`T... Args`)
- Распаковка через `...`
- Рекурсивная обработка

#### 📚 Теория:
```cpp
// Печать всех аргументов
template <typename T>
void print(T value) {
    std::cout << value << "\n";
}

template <typename T, typename... Args>
void print(T first, Args... args) {
    std::cout << first << ", ";
    print(args...);  // рекурсивный вызов
}

print(1, "hello", 3.14, 'x');  // 1, hello, 3.14, x
```

```cpp
// Кортеж с помощью variadic templates
template <typename... Args>
void log(const std::string& msg, Args... args) {
    std::cout << "[LOG] " << msg << ": ";
    print(args...);
}
```

#### ✅ Практика:
1. Напишите `sum(1, 2, 3)` → `6`.
2. Реализуйте `make_array(1, 2.5, "hi")` → `std::array<std::variant<...>, 3>`.
3. Создайте `Timer` с логированием аргументов: `time_call("func", arg1, arg2)`.

---

### **День 4: SFINAE и `std::enable_if`**

#### 🔹 Темы:
- Что такое SFINAE (Substitution Failure Is Not An Error)?
- `std::enable_if` — включение/исключение шаблонов
- Проверка свойств типов (`std::is_integral`, `std::is_floating_point`)

#### 📚 Теория:
```cpp
// Только для целочисленных типов
template <typename T>
typename std::enable_if<std::is_integral_v<T>, T>::type
    abs(T x) {
    return x < 0 ? -x : x;
}

// C++14: короче
template <typename T>
std::enable_if_t<std::is_floating_point_v<T>, T>
    abs(T x) {
    return x < 0 ? -x : x;
}
```

```cpp
// Перегрузка с SFINAE
template <typename T>
auto get_size(const T& container) -> decltype(container.size()) {
    return container.size();  // работает для vector, string и т.д.
}

template <typename T, size_t N>
constexpr size_t get_size(T (&)[N]) {
    return N;  // работает для C-массивов
}
```

#### ✅ Практика:
1. Напишите `is_addable<T, U>`, проверяющий, можно ли `T + U`.
2. Создайте `print_if_container`, который работает только для контейнеров.
3. Реализуйте `safe_divide`, возвращающий `std::optional`, только для арифметических типов.

---

### **День 5: Шаблонное метапрограммирование (TMP)**

#### 🔹 Темы:
- Вычисления на этапе компиляции
- Рекурсивные шаблоны
- `constexpr` vs TMP

#### 📚 Теория:
```cpp
// Факториал через шаблоны
template <int N>
struct Factorial {
    static constexpr int value = N * Factorial<N-1>::value;
};

template <>
struct Factorial<0> {
    static constexpr int value = 1;
};

constexpr int f5 = Factorial<5>::value;  // 120
```

```cpp
// Проверка чётности
template <int N>
struct is_even {
    static constexpr bool value = (N % 2 == 0);
};
```

> ⚠️ В C++14+ лучше использовать `constexpr`, но TMP полезен для сложных условий и типов.

#### ✅ Практика:
1. Напишите `Fibonacci<N>`.
2. Создайте `static_assert(is_even<4>::value)`.
3. Реализуйте `Power<2, 5>::value` → `32`.

---

### **День 6: `decltype`, `declval`, `void_t`**

#### 🔹 Темы:
- `decltype(expr)` — тип выражения
- `std::declval<T>()` — "псевдо-объект" для SFINAE
- `std::void_t` — проверка валидности выражений

#### 📚 Теория:
```cpp
// Проверка, есть ли метод .size()
template <typename T, typename = void>
struct has_size : std::false_type {};

template <typename T>
struct has_size<T, std::void_t<decltype(std::declval<T>().size())>> : std::true_type {};

static_assert(has_size<std::vector<int>>::value);
static_assert(!has_size<int>::value);
```

```cpp
// Использование в enable_if
template <typename T>
std::enable_if_t<has_size<T>::value, void>
    print_size(const T& obj) {
    std::cout << obj.size() << "\n";
}
```

#### ✅ Практика:
1. Напишите `has_push_back<T>`.
2. Создайте `has_member_function<T, void(int), &T::process>`.
3. Реализуйте `is_iterable<T>` через `std::void_t`.

---

### **День 7: Проект — `Variant` на шаблонах**

#### 🔹 Задача недели: **`SimpleVariant`**

**Цель:** Реализовать упрощённый аналог `std::variant` с помощью шаблонов, variadic templates и SFINAE.

**Функционал:**
- `SimpleVariant<int, std::string, double>`
- `emplace<T>(value)`
- `get<T>()` — с проверкой типа
- `holds_alternative<T>()`
- Поддержка `std::visit` (базово)

**Требования:**
- Использовать variadic templates
- Поддержка move-семантики
- Безопасность типов

---

#### ✅ Пример решения (упрощённый):

```cpp
#include <iostream>
#include <string>
#include <type_traits>

template <typename... Types>
class SimpleVariant;

// Базовый случай
template <typename T, typename... Rest>
class SimpleVariant<T, Rest...> {
    union {
        T value;
        SimpleVariant<Rest...> rest;
    };
    bool holds_first = false;

public:
    template <typename U>
    void emplace(U&& u) {
        if constexpr (std::is_same_v<std::decay_t<U>, T>) {
            new (&value) T(std::forward<U>(u));
            holds_first = true;
        } else {
            rest.emplace(std::forward<U>(u));
            holds_first = false;
        }
    }

    template <typename U>
    U& get() {
        if constexpr (std::is_same_v<U, T>) {
            if (!holds_first) throw std::bad_variant_access();
            return value;
        } else {
            return rest.template get<U>();
        }
    }

    template <typename U>
    bool holds_alternative() const {
        if constexpr (std::is_same_v<U, T>) {
            return holds_first;
        } else {
            return !holds_first && rest.template holds_alternative<U>();
        }
    }

    ~SimpleVariant() {
        if (holds_first) value.~T();
        else rest.~SimpleVariant<Rest...>();
    }
};

// Специализация для одного типа
template <typename T>
class SimpleVariant<T> {
    T value;
public:
    template <typename U>
    void emplace(U&& u) {
        value = std::forward<U>(u);
    }

    template <typename U>
    U& get() {
        static_assert(std::is_same_v<U, T>);
        return value;
    }

    template <typename U>
    bool holds_alternative() const {
        return std::is_same_v<U, T>;
    }
};
```

> 💡 Это упрощённая версия. В реальности `std::variant` использует более сложные техники.

---

## 📚 **Ресурсы для этой недели**

- **Книга:** *«C++ Templates: The Complete Guide»* — Д. Джосутис, Д. Вандевурде
- **Видео:** *CppCon — "Template Metaprogramming is Serious Business"*
- **Сайт:** [https://en.cppreference.com](https://en.cppreference.com) — `std::enable_if`, `std::void_t`, `std::declval`

---

## ✅ **Чек-лист по итогам недели**

Вы готовы к следующей неделе, если можете:

- [ ] Написать шаблонную функцию и класс
- [ ] Использовать `variadic templates` для обработки нескольких аргументов
- [ ] Применять `std::enable_if` и SFINAE
- [ ] Понимать, как работает `std::void_t`
- [ ] Реализовать простое метапрограммирование (например, `Factorial<N>`)
- [ ] Объяснить разницу между `enable_if` и `concepts` (пока теоретически)

---

## 🚀 Что дальше?

> **Неделя 4: Концепты (C++20)** — замена SFINAE, более читаемые и безопасные шаблоны.

---

Хочешь — могу:
- Прислать **PDF с этой неделей**,
- Дать **10 задач по шаблонам** с решениями,
- Перейти к **Неделе 4: Концепты (C++20)**.

Просто скажи: **"Да, хочу PDF"** или **"Переходи к Неделе 4"**.


# Разверни подробнее неделю 3 с кратким описанием теории по каждой теме

Конечно! Ниже — **подробно развернутая Неделя 3: Шаблоны и метапрограммирование**, с **кратким, но ёмким описанием теории по каждой теме**, понятными примерами и структурированным подходом. Эта неделя построена так, чтобы вы постепенно переходили от основ шаблонов к сложным техникам вроде SFINAE и метапрограммирования.

---

# 📘 **Неделя 3: Шаблоны и метапрограммирование (подробно)**

**Цель:** Научиться писать **гибкие, безопасные и эффективные шаблонные конструкции**, понимать, как компилятор работает с шаблонами, и использовать **шаблонное метапрограммирование (TMP)** для проверки типов и вычислений на этапе компиляции.

---

## 🗓️ **День 1: Введение в шаблоны**

### 🔹 Теория: Что такое шаблоны?

Шаблоны — это **инструмент обобщённого программирования** в C++. Они позволяют писать код, **независимый от конкретных типов**.

- **Шаблонная функция** — работает с разными типами.
- **Шаблонный класс** — создаётся для каждого типа отдельно.
- Компилятор **генерирует код** для каждого конкретного типа при использовании.

### ✅ Пример:
```cpp
template <typename T>
T max(T a, T b) {
    return a > b ? a : b;
}

int x = max(3, 5);        // T = int
double y = max(3.14, 2.7); // T = double
```

### 🔑 Ключевые понятия:
- `template <typename T>` или `template <class T>` — синонимы.
- `T` — параметр шаблона (может быть типом, значением, шаблоном).
- **Инстанцирование** — создание конкретной версии шаблона для типа.

---

## 🗓️ **День 2: Специализация шаблонов**

### 🔹 Теория: Полная и частичная специализация

Позволяет **настроить поведение шаблона для конкретных типов или условий**.

#### 1. **Полная специализация**
Заменяет шаблон **полностью** для конкретного набора параметров.

```cpp
template <typename T>
struct Info { static void print() { std::cout << "General\n"; } };

// Полная специализация для int
template <>
struct Info<int> { static void print() { std::cout << "Integer!\n"; } };
```

#### 2. **Частичная специализация**
Работает **только для классов**, позволяет задать шаблон для **подмножества условий**.

```cpp
template <typename T>
struct Info<T*> {  // для всех указателей
    static void print() { std::cout << "Pointer!\n"; }
};
```

> ❌ Нельзя частично специализировать функции — используйте перегрузку.

---

## 🗓️ **День 3: Variadic Templates (шаблоны с переменным числом параметров)**

### 🔹 Теория: `T... Args` — пакет параметров

Позволяет создавать шаблоны, принимающие **любое количество аргументов любого типа**.

- `Args...` — пакет типов.
- `args...` — пакет значений.
- Распаковка: `func(args...)` → вызов с каждым аргументом.

### ✅ Пример: рекурсивная печать
```cpp
template <typename T>
void print(T value) {
    std::cout << value << "\n";
}

template <typename T, typename... Args>
void print(T first, Args... args) {
    std::cout << first << " ";
    print(args...);  // рекурсивно раскрываем пакет
}

print(1, "hello", 3.14);  // 1 hello 3.14
```

### 🔑 Использование:
- Логирование,
- Фабрики объектов,
- Обёртки вокруг вызовов (`std::make_tuple`, `std::forward`).

---

## 🗓️ **День 4: SFINAE и `std::enable_if`**

### 🔹 Теория: SFINAE — "Ошибка подстановки — не ошибка"

**SFINAE (Substitution Failure Is Not An Error)** — принцип, при котором **ошибка при подстановке типа в шаблон не приводит к ошибке компиляции**, а просто **исключает эту перегрузку из рассмотрения**.

#### `std::enable_if` — инструмент для управления SFINAE

```cpp
template <bool B, typename T = void>
struct enable_if {};

template <typename T>
struct enable_if<true, T> { using type = T; };
```

### ✅ Пример: только для целых чисел
```cpp
template <typename T>
typename std::enable_if<std::is_integral_v<T>, T>::type
    abs(T x) {
    return x < 0 ? -x : x;
}
```

> 🔍 Если `T` — не целое, `enable_if<false, T>::type` не существует → подстановка проваливается → SFINAE → другая перегрузка.

### 🔑 Аналог в C++20: `concepts` — чище и понятнее.

---

## 🗓️ **День 5: Шаблонное метапрограммирование (TMP)**

### 🔹 Теория: Вычисления на этапе компиляции

**Метапрограммирование** — написание программ, которые **генерируют или управляют другими программами**. В C++ это — **вычисления на этапе компиляции с помощью шаблонов**.

- Использует рекурсию шаблонов.
- Результат — `constexpr` значения или типы.
- Часто используется для оптимизации и проверки типов.

### ✅ Пример: факториал на этапе компиляции
```cpp
template <int N>
struct Factorial {
    static constexpr int value = N * Factorial<N - 1>::value;
};

template <>
struct Factorial<0> {
    static constexpr int value = 1;
};

constexpr int result = Factorial<5>::value;  // 120
```

> ⚠️ В C++14+ лучше использовать `constexpr` функции, но TMP остаётся мощным для сложных проверок типов.

---

## 🗓️ **День 6: `decltype`, `declval`, `void_t`**

### 🔹 Теория: Инструменты для метапрограммирования

#### 1. `decltype(expr)`
Возвращает тип выражения.

```cpp
int x = 5;
decltype(x) y = 10;  // y — int
```

#### 2. `std::declval<T>()`
Позволяет "создать" объект типа `T` без конструктора — используется в `decltype` для проверки операций.

```cpp
decltype(std::declval<T>().size())
```

#### 3. `std::void_t<...>`
Превращает любой список типов в `void`. Используется для **проверки валидности выражений**.

```cpp
template <typename T, typename = void>
struct has_size : std::false_type {};

template <typename T>
struct has_size<T, std::void_t<decltype(std::declval<T>().size())>> : std::true_type {};
```

> ✅ Это стандартный паттерн для **обнаружения методов/членов**.

---

## 🗓️ **День 7: Проект — `SimpleVariant`**

### 🔹 Цель:
Создать упрощённый аналог `std::variant`, используя:
- Variadic templates,
- Рекурсию шаблонов,
- SFINAE/проверки типов,
- RAII и move-семантику.

### 🔹 Реализуемые функции:
- `emplace<T>(value)` — создать значение внутри.
- `get<T>()` — получить значение (с проверкой).
- `holds_alternative<T>()` — проверить, хранится ли тип.
- Поддержка нескольких типов: `SimpleVariant<int, std::string, double>`.

### 🔹 Учебная ценность:
- Понимание, как работают `std::variant`, `std::tuple`.
- Практика рекурсивных шаблонов.
- Глубокое понимание владения и типобезопасности.

---

## 🧠 **Ключевые идеи недели**

| Концепция | Зачем нужна |
|---------|------------|
| **Шаблоны** | Повторное использование кода для разных типов |
| **Специализация** | Настройка поведения шаблона для конкретных случаев |
| **Variadic templates** | Поддержка произвольного числа аргументов |
| **SFINAE + enable_if** | Условное включение шаблонов |
| **TMP** | Вычисления и проверки на этапе компиляции |
| **`void_t`, `declval`** | Проверка наличия методов, операций, членов |

---

## 📚 **Лучшие практики**

1. ✅ Используйте `typename` в шаблонах, когда `T` — зависимый тип.
2. ✅ Предпочитайте `auto` и `constexpr` TMP, если возможно.
3. ✅ Используйте `static_assert` для понятных ошибок.
4. ✅ Избегайте сложных SFINAE — в C++20 лучше использовать `concepts`.
5. ✅ Тестируйте шаблоны с разными типами (скаляры, классы, указатели).

---

## ✅ **Чек-лист: что вы должны уметь к концу недели**

- [ ] Написать шаблонную функцию и класс
- [ ] Специализировать шаблон для конкретного типа
- [ ] Использовать `...` для распаковки пакета аргументов
- [ ] Применить `std::enable_if` для ограничения типов
- [ ] Проверить наличие метода с помощью `std::void_t`
- [ ] Реализовать простое метапрограммирование (например, `Factorial<N>`)
- [ ] Объяснить, как работает SFINAE

---

## 🚀 Что дальше?

> **Неделя 4: Концепты (C++20)** — современная альтернатива SFINAE, которая делает шаблоны **читаемыми, безопасными и понятными**.

---

Хочешь — могу:
- Прислать **PDF-версию этой недели**,
- Дать **10 задач с решениями** по шаблонам,
- Перейти к **Неделе 4: Концепты (C++20)**.

Просто скажи: **"Хочу PDF"** или **"Переходи к Неделе 4"**.


# Разверни подробнее неделю 4 с кратким описанием теории по каждой теме

Конечно! Ниже — **подробно развернутая Неделя 4: Концепты (C++20)** с **чётким и кратким описанием теории по каждой теме**, примерами, практическими задачами и логичной структурой. Эта неделя посвящена **современной альтернативе SFINAE** — мощной и читаемой системе ограничений типов в C++20.

---

# 📘 **Неделя 4: Концепты (C++20) — современные ограничения шаблонов**

**Уровень:** Продвинутый  
**Длительность:** 7 дней  
**Цель недели:** Заменить сложные и запутанные конструкции вроде `std::enable_if` и SFINAE на **понятные, безопасные и выразительные концепты (concepts)**. Научиться писать **типобезопасные шаблоны** с **ясными сообщениями об ошибках**.

---

## 🗓️ **День 1: Введение в концепты — зачем они нужны?**

### 🔹 Теория: Что такое концепты?

**Концепт (concept)** — это **именованное условие на шаблонный параметр**, которое определяет, какие типы могут использоваться в шаблоне.

> ✅ До C++20: проверки через SFINAE / `enable_if` → сложные, непонятные ошибки.  
> ✅ С C++20: **`template <Integral T>`** → понятно, читаемо, безопасно.

### 🔑 Основные преимущества:
- **Понятные ошибки компиляции** (не 100 строк SFINAE).
- **Читаемость кода**.
- **Раннее обнаружение ошибок**.
- **Перегрузка шаблонов по концептам**.

### ✅ Пример:
```cpp
template <typename T>
concept Integral = std::is_integral_v<T>;

template <Integral T>
T add(T a, T b) {
    return a + b;
}

add(3, 5);     // OK
add(3.5, 2.1); // Ошибка: double не удовлетворяет Integral
```

> 🔍 Ошибка:  
> `error: constraints not satisfied` — сразу понятно, в чём дело.

---

## 🗓️ **День 2: Синтаксис концептов**

### 🔹 Теория: Как объявлять концепты

Концепт объявляется с помощью ключевого слова `concept` и выражения, которое должно быть **истинным** для допустимых типов.

### Формы:
```cpp
template <typename T>
concept Имя = логическое_выражение;
```

### Примеры:

#### 1. Простой концепт
```cpp
template <typename T>
concept FloatingPoint = std::is_floating_point_v<T>;
```

#### 2. Через `requires`
```cpp
template <typename T>
concept Addable = requires(T a, T b) {
    a + b;  // выражение должно быть валидным
};
```

#### 3. С возвращаемым типом
```cpp
template <typename T>
concept Printable = requires(T t) {
    std::cout << t;
};
```

---

## 🗓️ **День 3: `requires`-выражения — продвинутая проверка**

### 🔹 Теория: Что можно проверять в `requires`?

`requires` позволяет проверять:
- **Синтаксис выражений**,
- **Типы результатов**,
- **Вложенные требования**.

### Виды требований:

#### 1. **Простое требование**
```cpp
requires(T a) { a + a; }
```

#### 2. **Типовое требование**
```cpp
requires { typename T::value_type; }
```

#### 3. **Составное требование**
```cpp
requires(T a) { { a++ } -> std::same_as<T>; }
```
> Проверяет, что `a++` валидно и возвращает `T`.

#### 4. **Вложенные требования**
```cpp
template <typename T>
concept RandomAccess = Bidirectional<T> && requires(T a) {
    { a + 1 } -> std::integral;
};
```

---

## 🗓️ **День 4: Встроенные концепты (стандартная библиотека)**

### 🔹 Теория: Готовые концепты из `<concepts>`

C++20 предоставляет **стандартные концепты**, которые покрывают большинство нужд.

| Концепт | Описание |
|--------|--------|
| `std::integral<T>` | Целочисленные типы |
| `std::floating_point<T>` | `float`, `double` и т.д. |
| `std::default_constructible<T>` | Можно создать `T{}` |
| `std::copyable<T>` | Можно копировать |
| `std::movable<T>` | Можно перемещать |
| `std::equality_comparable<T>` | Поддерживает `a == b` |
| `std::regular<T>` | `movable` + `equality_comparable` + другие |

### ✅ Пример:
```cpp
#include <concepts>

template <std::integral T>
T multiply(T a, T b) {
    return a * b;
}
```

---

## 🗓️ **День 5: Перегрузка шаблонов по концептам**

### 🔹 Теория: Выбор лучшей перегрузки

Концепты позволяют **перегружать шаблонные функции** на основе ограничений. Компилятор выбирает **наиболее специализированную** версию.

### ✅ Пример:
```cpp
template <typename T>
void sort(T& container) {
    // общая сортировка (например, пузырьком)
}

template <std::random_access_iterator I>
void sort(I first, I last) {
    // быстрая сортировка (например, std::sort)
}
```

> Если передать `std::vector<int>`, вызовется **вторая версия**, потому что она **более ограничена**.

### 🔑 Правило:  
Чем **конкретнее концепт**, тем **выше приоритет**.

---

## 🗓️ **День 6: Концепты vs SFINAE — сравнение и переход**

### 🔹 Теория: Почему концепты лучше SFINAE?

| Критерий | SFINAE (`enable_if`) | Концепты |
|--------|------------------------|---------|
| **Читаемость** | Низкая | Высокая |
| **Ошибки компиляции** | Длинные, непонятные | Краткие, ясные |
| **Поддержка IDE** | Плохая | Хорошая (подсветка, автодополнение) |
| **Перегрузка** | Сложная | Простая и логичная |
| **Производительность** | Не влияет | Не влияет |

### ✅ Пример перехода:

#### Было (SFINAE):
```cpp
template <typename T>
std::enable_if_t<std::is_arithmetic_v<T>, T>
abs(T x) { return x < 0 ? -x : x; }
```

#### Стало (concept):
```cpp
template <std::integral T>
T abs(T x) { return x < 0 ? -x : x; }
```

> ✅ Код стал **короче, понятнее, безопаснее**.

---

## 🗓️ **День 7: Проект — Библиотека алгоритмов с концептами**

### 🔹 Задача недели: **"Мини-STL с концептами"**

**Цель:** Переписать несколько стандартных алгоритмов, используя концепты вместо SFINAE или шаблонных проверок.

**Функционал:**
- `my_sort(container)` — только для `random_access_iterator`.
- `my_find(container, value)` — только если `value_type` сравним с `value`.
- `my_distance(first, last)` — только для итераторов.
- `static_assert` для проверки концептов.

### ✅ Пример решения:
```cpp
#include <concepts>
#include <vector>
#include <iostream>

template <std::random_access_iterator It>
void my_sort(It first, It last) {
    std::cout << "Fast sort (random access)\n";
    // std::sort(first, last);
}

template <std::input_iterator It>
void my_sort(It first, It last) {
    std::cout << "Slow sort (input iterator)\n";
    // bubble sort
}

template <typename Container, typename T>
    requires std::equality_comparable_with<typename Container::value_type, T>
auto my_find(Container& c, const T& value) {
    for (auto it = c.begin(); it != c.end(); ++it) {
        if (*it == value) return it;
    }
    return c.end();
}

int main() {
    std::vector v = {3, 1, 4, 1, 5};

    my_sort(v.begin(), v.end());  // вызовет random_access версию

    auto it = my_find(v, 4);
    if (it != v.end()) {
        std::cout << "Found: " << *it << "\n";
    }

    return 0;
}
```

---

## 🧠 **Ключевые идеи недели**

| Концепция | Зачем нужна |
|---------|------------|
| `concept` | Именованное ограничение на тип |
| `requires` | Проверка синтаксиса, типов, выражений |
| Встроенные концепты | Готовые решения: `integral`, `movable`, `equality_comparable` |
| Перегрузка по концептам | Автоматический выбор лучшей версии функции |
| Концепты vs SFINAE | Концепты — современная, читаемая замена |

---

## ✅ **Чек-лист: что вы должны уметь к концу недели**

- [ ] Объявить простой концепт через `bool`-выражение
- [ ] Использовать `requires` для проверки выражений
- [ ] Применить встроенные концепты (`std::integral`, `std::movable`)
- [ ] Перегрузить шаблонную функцию по разным концептам
- [ ] Сравнить концепты и SFINAE
- [ ] Написать алгоритм, использующий концепты для ограничения типов

---

## 🚀 Что дальше?

> **Неделя 5: Итераторы, аллокаторы и STL глубоко** — погружение в устройство стандартной библиотеки, реализация своих итераторов, понимание, как устроены `std::vector`, `std::map` и `std::string` под капотом.

---

Хочешь — могу:
- Прислать **PDF с этой неделей**,
- Дать **10 задач по концептам** с решениями,
- Перейти к **Неделе 5: Итераторы и STL глубоко**.

Просто скажи: **"Хочу PDF"** или **"Переходи к Неделе 5"**.


