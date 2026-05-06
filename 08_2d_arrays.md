1. Concept

A 2D array (two-dimensional array) in C# is used to store data in rows and columns like a table. It is useful for organizing data in a grid format.

Each value is accessed using two indexes: one for the row and one for the column. The first index represents the row and the second represents the column.

2. Key C# Syntax

```csharp
int[,] numbers =
{
    { 1, 2, 3 },
    { 4, 5, 6 }
};

Console.WriteLine(numbers[0, 0]);
Console.WriteLine(numbers[1, 2]);
