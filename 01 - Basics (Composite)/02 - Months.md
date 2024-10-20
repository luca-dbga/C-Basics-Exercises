# Exercise 2

Use an enum to represent the months of the year. Create a function that takes a month number and returns the corresponding month name using a switch statement.

> [!CAUTION]
> Do not use teh `.ToString()` method of enums. Use flow control to implement this function.

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
enum Month
{
	January = 1,
	February,
	March,
	April,
	May,
	June,
	July,
	August,
	September,
	October,
	November,
	December
}

string GetMonthName(int monthNumber)
{
	switch (monthNumber)
	{
		case 1: return "January";
		case 2: return "February";
		case 3: return "March";
		case 4: return "April";
		case 5: return "May";
		case 6: return "June";
		case 7: return "July";
		case 8: return "August";
		case 9: return "September";
		case 10: return "October";
		case 11: return "November";
		case 12: return "December";
		default: return "Invalid month";
	}
}

Month month = Month.October;
string monthName = GetMonthName((int)month);
Console.WriteLine($"Month: {monthName}");
```