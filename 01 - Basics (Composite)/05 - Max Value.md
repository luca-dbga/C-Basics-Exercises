# Max Value

Create a function that takes an array of integers and returns the maximum value.

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
int MaxValue(int[] numbers)
{
	int max = int.MinValue;
	foreach(int number in numbers)
	{
		if(number > max)
		{
			max = number;
		}
	}
	return max;
}

int[] numbers = { 1, 3, 5, 7, 9 };
int maxValue = MaxValue(numbers);
Console.WriteLine($"Max value: {maxValue}");
```