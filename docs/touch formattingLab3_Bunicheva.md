**Жирный текст**
*Курсив*
***Жирный курсив***
~~Зачёркнутый~~
`Console.WriteLine("Hello");`

```csharp

string name;
name = Console.ReadLine();
Console.WriteLine(name)
```

# Задание:Комментированная программа на C#
Создайте консольное приложение на C#, которое демонстрирует все форматы 
Markdown в комментариях к коду.

## Требования к программе:
Имя файла: FormatDemo.cs
Логика:
Запрашивает у пользователя два числа;
Выполняет их сложение;
Выводит результаты в форматированном виде.

## Пример структуры кода с комментариями в стиле Markdown:

```csharp
Console.Write("Введите первое число: ");
double number1 = Convert.ToDouble(Console.ReadLine());
Console.Write("Введите второе число:");
double number2 = Convert.ToDoble(Console.ReadLine());
double sum = number1 + number2;
Console.WriteLine($"**Результат операций: {sum}**");
```