# If/Else If/Else Statement

Use an if/else if/else statement to check a number and print if it's positive, negative, or zero.

> [!TIP]
> Remember, when an `if`, `else if` or `else` statement is followed by only one instruction *(one line)*, the curly braces are not mandatory. In that case, adding them is a matter of preference.

[(view solution)](#solution)

~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  
~  

## Solution

```csharp
int number = 5;

if(number > 0)
{
    Console.WriteLine($"{number} is POSITIVE");
}
else if(number < 0)
{
    Console.WriteLine($"{number} is NEGATIVE");
}
else
{
    Console.WriteLine($"{number} is ZERO");
}
```