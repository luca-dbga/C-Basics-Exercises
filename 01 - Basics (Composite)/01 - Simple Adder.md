# Simple Adder

Create a function that takes an array of integers and returns the sum of its elements. Use a for loop to iterate through the array.

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
int SumArray(int[] numbers)
{
	int sum = 0;
	for (int i = 0; i < numbers.Length; i++)
	{
		sum += numbers[i];
	}
	return sum;
}

int[] numbers = { 1, 2, 3, 4, 5 };
int result = SumArray(numbers);
Console.WriteLine($"Sum: {result}");
```