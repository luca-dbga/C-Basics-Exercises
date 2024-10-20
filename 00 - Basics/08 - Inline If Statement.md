# Inline If Statement

Use an inline if statement to check if a number is even or odd.

> [!NOTE]  
> Inline if is written in the form `condition ? valueIfTrue : valueIfFalse`.  
> `valueIfTrue` and `valueIfFalse` can be literals, variables or expressions but must evaluate as the same type of each other.

> [!TIP]
> Remember, to check if a number is even, you can check if the rest of the division by two is 0. You can find the rest of a division with the **modulus operator**: `%`.

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
int number = 4;
Console.WriteLine(number % 2 == 0 ? "Even" : "Odd");
```