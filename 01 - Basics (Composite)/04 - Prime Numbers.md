# Prime Numbers

Create a function that takes an integer and returns whether it is prime. Use a nested for loop to check for factors.

> [!TIP]
> Prime numbers are numbers that can be divided only by 1 and themselves.
> To find if a number is a divider of another, you can check if the rest of the division of one number by the other is 0. You can find the rest of a division with the **modulus operator**: `%`.

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
bool IsPrime(int number)
{
	if(number <= 1)
		return false;
	for(int i = 2; i <= Math.Sqrt(number); i++)
	{
		if(number % i == 0)
			return false;
	}
	return true;
}

int number = 7;
bool isPrime = IsPrime(number);
Console.WriteLine($"{number} is prime: {isPrime}");
```