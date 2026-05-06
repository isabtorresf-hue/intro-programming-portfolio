1. Concept

The foreach loop in C# is used to go through each element in an array or collection. It is simpler than a for loop because you do not need to use indexes.

It automatically goes through every item one by one and performs an action on each element. It is commonly used when you only need to read data from a collection.

2. Key C# Syntax

```csharp
int[] numbers = { 10, 20, 30, 40 };

foreach (int number in numbers)
{
    Console.WriteLine(number);
}
