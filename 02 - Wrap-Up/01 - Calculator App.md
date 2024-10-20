# Calculator

Write a simple program which allows to make basic calculations.

The program must support the following operaotrs:
- `+` *(Addition)*
- `-` *(Subtraction)*
- `*` *(Multiplication)*
- `/` *(Division)*

The program asks the user for an operator and two integral numbers, performs the operation and prints the result.

> [!CAUTION]
> The application must not crash on invalid user input so remember to validate input and opearations.

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
namespace Calculator
{
	public class Program
	{
		public delegate void Operator(int a, int b);

		static int Main(string[] args)
		{
			//	Get numbers
			int number1 = 0;
			int number2 = 0;

			GetNumericInput("Number 1:", out number1);
			GetNumericInput("Number 2:", out number2);

			//	Get operator (+ - * /)
			string operatorSymbol = "";
			Operator op = null;
			do
			{
				Console.WriteLine("Operator:");
				operatorSymbol = Console.ReadLine();
				switch(operatorSymbol.ToLower())
				{
					case "+":
					case "add":
						op = Add;
						break;
					case "-":
					case "sub":
						op = Subtract;
						break;
					case "*":
					case "mul":
						op = Multiply;
						break;
					case "/":
					case "div":
						op = Divide;
						break;
					default:
						operatorSymbol = string.Empty;
						break;
				}
			} while(string.IsNullOrEmpty(operatorSymbol));

			//	Write result
			if(op != null)
				op(number1, number2);
			//op?.Invoke(number1, number2);

			return 0;
		}

		private static void GetNumericInput(string prompt, out int number)
		{
			do { Console.WriteLine(prompt); }
			while(!int.TryParse(Console.ReadLine(), out number));
		}

		private static void Add(int a, int b) => Console.WriteLine($"{a} + {b} = {a + b}");
		private static void Subtract(int a, int b) => Console.WriteLine($"{a} - {b} = {a - b}");
		private static void Multiply(int a, int b) => Console.WriteLine($"{a} * {b} = {a * b}");
		private static void Divide(int a, int b)
		{
			if(b != 0)
				Console.WriteLine($"{a} / {b} = {a / b}");
			else
				Console.WriteLine("Cannot divide by 0");
		}
	}
}
```