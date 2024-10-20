# For Loop

Use nested for loops to print a 3x3 matrix.

> [!TIP]
> Remember, when a `for` or `foreach` statement is followed by only one instruction *(one line)*, the curly braces are not mandatory. In that case, adding them is a matter of preference.

> [!WARNING]  
> Try to limit nesting as it's bad both for readability and performance.

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
for (int i = 1; i <= 3; i++)
{
	for (int j = 1; j <= 3; j++)
	{
		Console.Write($"{i * j} ");
	}
	Console.WriteLine();
}
```