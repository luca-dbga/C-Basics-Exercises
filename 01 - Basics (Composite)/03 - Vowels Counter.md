# Vowels Counter

Create a function that takes a string and returns the number of vowels in it. Use a foreach loop to iterate through the string.

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
int CountVowels(string input)
{
	int count = 0;
	foreach (char c in input)
	{
		if ("aeiouAEIOU".Contains(c))
		{
			count++;
		}
	}
	return count;
}

string input = "Hello World";
int vowelCount = CountVowels(input);
Console.WriteLine($"The sentence {input} has {vowelCount} vowels");
```