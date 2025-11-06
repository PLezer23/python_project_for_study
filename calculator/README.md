```
# 🧮 Multi-Language Calculator / Многоязычный Калькулятор

A simple console-based calculator that supports two languages: English and Russian. The calculator performs basic mathematical operations with support for multiple numbers.

Простой консольный калькулятор с поддержкой двух языков: английского и русского. Выполняет основные математические операции с поддержкой нескольких чисел.

## 🌟 Features / Возможности

- **Bilingual Support** / **Поддержка двух языков**: Choose between English and Russian interface / Выбор между английским и русским интерфейсом
- **Multiple Operations** / **Множество операций**: 
  - Addition / Сложение
  - Subtraction / Вычитание
  - Division / Деление
  - Multiplication / Умножение
  - Exponentiation / Возведение в степень
  - Integer Division / Целочисленное деление
- **Batch Processing** / **Групповая обработка**: Perform operations on multiple numbers at once (except exponentiation and integer division) / Выполнение операций с несколькими числами одновременно (кроме возведения в степень и целочисленного деления)
- **User-Friendly** / **Удобный интерфейс**: Simple console interface with clear instructions / Простой консольный интерфейс с понятными инструкциями

## 🚀 Getting Started / Начало работы

### Prerequisites / Требования
- Python 3.x installed on your system / Python 3.x установленный на вашей системе

### Installation / Установка
1. Clone or download this repository / Клонируйте или скачайте этот репозиторий
2. Navigate to the project directory / Перейдите в директорию проекта
3. Run the calculator / Запустите калькулятор:

```bash
python calculator.py
```

## 📋 How to Use / Как использовать

### Step 1: Language Selection / Шаг 1: Выбор языка
```
Выберите ваш язык
choose your language
1- English
2 - Русский
```
Choose your preferred language by entering `1` for English or `2` for Russian. / Выберите предпочитаемый язык, введя `1` для английского или `2` для русского.

### Step 2: Operation Selection / Шаг 2: Выбор операции
Depending on your language choice, you'll see available operations: / В зависимости от выбора языка, вы увидите доступные операции:

**English:**
```
Select the operation you need
1 - Addition
2 - Subtraction
3 - Division
4 - Multiplication
5 - Exponentiation
6 - Integer division
7 - Exit
```

**Russian:**
```
Выберите нужную вам операцию
1 - Сложение
2 - Вычитание
3 - Деление
4 - Умножение
5 - Возведение в степень
6 - Целочисленное деление
7 - Выход
```

### Step 3: Input Numbers / Шаг 3: Ввод чисел
- **For operations 1-4** / **Для операций 1-4**: Enter numbers separated by spaces / Введите числа через пробел
  - Example / Пример: `10 20 30 40`
- **For operations 5-6** / **Для операций 5-6**: Enter two numbers when prompted / Введите два числа когда будет предложено

## 🎯 Available Operations / Доступные операции

### 1. Addition / Сложение ✅
Adds multiple numbers together. / Складывает несколько чисел.
- Input / Ввод: Multiple numbers separated by spaces / Несколько чисел через пробел
- Example / Пример: `5 10 15` → Result / Результат: `30`

### 2. Subtraction / Вычитание ➖
Subtracts subsequent numbers from the first number. / Вычитает последующие числа из первого числа.
- Input / Ввод: Multiple numbers separated by spaces / Несколько чисел через пробел
- Example / Пример: `100 20 10` → Result / Результат: `70`

### 3. Division / Деление ➗
Divides the first number by subsequent numbers. / Делит первое число на последующие числа.
- Input / Ввод: Multiple numbers separated by spaces / Несколько чисел через пробел
- Example / Пример: `100 2 5` → Result / Результат: `10`

### 4. Multiplication / Умножение ✖️
Multiplies all numbers together. / Перемножает все числа.
- Input / Ввод: Multiple numbers separated by spaces / Несколько чисел через пробел
- Example / Пример: `2 3 4` → Result / Результат: `24`

### 5. Exponentiation / Возведение в степень 🔢
Raises a number to a power. / Возводит число в степень.
- Input / Ввод: Two numbers (base and exponent) / Два числа (основание и степень)
- Example / Пример: Base / Основание: `2`, Exponent / Степень: `3` → Result / Результат: `8`

### 6. Integer Division / Целочисленное деление 🔽
Performs integer (floor) division. / Выполняет целочисленное деление.
- Input / Ввод: Two numbers (dividend and divisor) / Два числа (делимое и делитель)
- Example / Пример: `7 2` → Result / Результат: `3`

### 7. Exit / Выход 🚪
Exits the calculator program. / Выход из программы калькулятора.

## 💡 Usage Examples / Примеры использования

### English Mode / Английский режим:
```
Choose your language: 1
Select operation: 1
Enter numbers: 5 10 15 20
Sum: 50.0
```

### Russian Mode / Русский режим:
```
Выберите язык: 2
Выберите операцию: 4  
Введите числа: 2 3 4
Результат умножения: 24.0
```

## 🛠️ Technical Details / Технические детали

- **Language** / **Язык**: Python 3
- **Input Handling** / **Обработка ввода**: Uses `input().split()` for multiple numbers / Использует `input().split()` для нескольких чисел
- **Type Conversion** / **Преобразование типов**: Automatically converts strings to floats/integers / Автоматически преобразует строки в числа с плавающей точкой/целые числа
- **Error Handling** / **Обработка ошибок**: Basic input validation / Базовая проверка ввода
- **Loop Structure** / **Структура цикла**: Infinite loop until user chooses to exit / Бесконечный цикл до выбора выхода пользователем

## 📝 Notes / Примечания

- The calculator continues running until you explicitly choose to exit / Калькулятор продолжает работать пока вы явно не выберете выход
- You can perform multiple calculations in one session / Вы можете выполнять несколько вычислений за одну сессию
- Supports both integers and floating-point numbers / Поддерживает как целые числа, так и числа с плавающей точкой
- Division by zero is not handled (will cause program crash) / Деление на ноль не обрабатывается (вызовет сбой программы)

## 🔄 Program Flow / Работа программы

1. Language selection / Выбор языка
2. Operation selection / Выбор операции
3. Number input / Ввод чисел
4. Calculation / Вычисление
5. Result display / Отображение результата
6. Return to language selection / Возврат к выбору языка

## 👨‍💻 Development / Разработка

This is a beginner-friendly Python project that demonstrates: / Это beginner-friendly проект на Python, который демонстрирует:
- Basic I/O operations / Базовые операции ввода/вывода
- Conditional statements / Условные операторы
- Loops / Циклы
- List comprehensions / Генераторы списков
- Type conversion / Преобразование типов
- Simple arithmetic operations / Простые арифметические операции

Feel free to modify and enhance the calculator with additional features! / Не стесняйтесь изменять и улучшать калькулятор дополнительными функциями!
