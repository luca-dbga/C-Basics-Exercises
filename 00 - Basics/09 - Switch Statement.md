# Switch Statement

Use a switch statement to print the name of a day based on its number (1-7).

> [!IMPORTANT]  
> Remember to handle the `default` case!

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
int day = 3;

switch (day)
{
	case 1:
		Console.WriteLine("Sunday");
		break;
	case 2:
		Console.WriteLine("Monday");
		break;
	case 3:
		Console.WriteLine("Tuesday");
		break;
	case 4:
		Console.WriteLine("Wednesday");
		break;
	case 5:
		Console.WriteLine("Thursday");
		break;
	case 6:
		Console.WriteLine("Friday");
		break;
	case 7:
		Console.WriteLine("Saturday");
		break;
	default:
		Console.WriteLine("Invalid day");
		break;
}
```