1. Concept

The if statement in C# is used to make decisions in a program. It checks a condition and runs a block of code only if the condition is true. If the condition is false, that block is skipped.

You can also use else to run another block when the condition is not true. This helps control the flow of the program based on different situations.

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
