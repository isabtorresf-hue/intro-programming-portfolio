1. Concept

The if statement in C# is used to make decisions in a program. It checks a condition and runs code only when the condition is true. If the condition is false, that block is skipped. You can also use else to run another block when the condition is false. The program follows a top-down flow but can change depending on conditions. This helps control the logic of the program.

2. Key C# Syntax

```csharp
int age = 18;

if (age >= 18)
{
    Console.WriteLine("Adult");
}
else
{
    Console.WriteLine("Minor");
}
