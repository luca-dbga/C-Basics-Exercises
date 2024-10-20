# Arrays

Declare an array of 5 integers.

Initialize the array assigning values to each element.

Change the value of the first, third and fifth elements.

> [!WARNING]
> Arrays are indexed starting from 0.
> The first element of any array is 0, the last element of any array is its length - 1.

Print the values of the second and the fourth elements.

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
int[] numbers = { 1, 2, 3, 4, 5 };

numbers[0] = 9;
numbers[2] = 8;
numbers[4] = 7;

Console.WriteLine($"Second element's value: {numbers[1]}");
Console.WriteLine($"Fourth element's value: {numbers[3]}");
```