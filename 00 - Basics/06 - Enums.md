# Enums

Declare an enum for days of the week and print a value.

> [!NOTE]
> Remember, enums are types and types are written in [pascal case](https://en.wikipedia.org/wiki/Camel_case), so with all the characters lower case except the first character of each word.
> **Example**: `ThisIsPascalCase`

Try to give explicit values to enum labels.

Try to store an enum into an int variable.

Try to store an int value into an enum variable.

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
enum Day
{
	Monday = 1,
	Tuesday,
	Wednesday,
	Thursday,
	Friday,
	Saturday,
	Sunday
}

Day today = Day.Monday;
Console.WriteLine($"Today is: {today}");

int todayWeekDay = (int)today;
Console.WriteLine($"Today is the {todayWeekDay}° day of the week");

Day thirdDayOfTheWeek = (Day)3;
Console.WriteLine($"The third day of the week is: {today}");
```