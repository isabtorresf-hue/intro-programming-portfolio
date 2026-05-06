1. Concept

The switch statement in C# is used to select one block of code to execute from many options. It works by checking the value of a variable and comparing it with different cases. Each case represents a possible value. If a match is found, that block of code runs. The break keyword is used to stop the switch once a case is executed. If no case matches, the default block runs. It is useful when you have many conditions based on one variable.

2. Key C# Syntax

```csharp
int day = 3;

switch (day)
{
    case 1:
        Console.WriteLine("Monday");
        break;
    case 2:
        Console.WriteLine("Tuesday");
        break;
    case 3:
        Console.WriteLine("Wednesday");
        break;
    default:
        Console.WriteLine("Invalid day");
        break;
}
