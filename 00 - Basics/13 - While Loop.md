# While Loop
Use a while loop to print consecutive numbers until the number is both a multiple of 2 and 3.

> [!TIP]
> Remember, to check if a number is a multiple of another number, you can check if the rest of the division of the first number by the second is 0. You can find the rest of a division with the **modulus operator**: `%`.

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
int i = 1;
while(i % 2 != 0 || i % 3 != 0)
{
	Console.WriteLine(i);
	i++;
	/*
	//	OR
	Console.WriteLine(i++);	//	Placing the ++ operator after the variable the increment happens after its written
	*/
}
```