1. Concept

The do-while loop in C# is used to repeat a block of code while a condition is true. The main difference from a while loop is that do-while always runs the code at least once before checking the condition. First, the code inside the loop is executed, then the condition is checked. If the condition is true, the loop repeats. If it is false, the loop stops. This is useful when you need the code to run at least one time.

2. Key C# Syntax

```csharp
int i = 1;

do
{
    Console.WriteLine(i);
    i++;
}
while (i <= 5);
