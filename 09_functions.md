1. Concept

Functions in C# are blocks of code that perform a specific task. They help organize code and make it reusable. Instead of writing the same code many times, you can call a function whenever you need it.

A function can take parameters (input values) and can also return a result. This makes programs cleaner and easier to manage.

2. Key C# Syntax

```csharp
static int Add(int a, int b)
{
    return a + b;
}

int result = Add(5, 3);
Console.WriteLine(result);
