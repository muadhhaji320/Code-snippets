# 100+ EXERCISES of DART LANGUAGE
### BASICS OF DART
```dart
void main() {
//●print string "Hello, World!"
	print('Hello World!');
}
```
```dart
int main()
{
double area = 3.14 * 4 * 4;
/*●It prints the area
 of a circle of radius = 4 */
print(area);

return 0;
}
```
```dart
int main()
{
var lst = [1, 2, 3];

/*●It prints
the whole list
at once
*/
print(lst);

return 0; }
```
```dart
bool checkEven(n){
/*●Returns true
if n is even*/
if(n%2==0)

	return true;
//●Returns false if n is odd
else

	return false; }

int main()
{
int n = 43;
print(checkEven(n));
return 0;
}
```
```dart
EXERCISE(5)
[] Printing default and assigned values in Dart of variables of different data types.
-------------------------------------------------------------------------------------
void main()
{
	// Declaring and initialising a variable
	int gfg1 = 10;

	// Declaring another variable
	double gfg2 = 0.2; // must declare double a value or it
					// will throw error
	bool gfg3 = false; // must declare boolean a value or it
					// will throw error

	// Declaring multiple variable
	String gfg4 = "0", gfg5 = "Geeks for Geeks";

	// Printing values of all the variables
	print(gfg1); // Print 10
	print(gfg2); // Print default double value
	print(gfg3); // Print default string value
	print(gfg4); // Print default bool value
	print(gfg5); // Print Geeks for Geeks
}
```
```dart
EXERCISE(6)
[] Showing how datatype are dynamically change using dynamic keyword.
---------------------------------------------------------------------
void main()
{
	// Assigning value to geek variable
	dynamic geek = "Geeks For Geeks";

	// Printing variable geek
	print(geek);

	// Reassigning the data to variable and printing it
	geek = 3.14157;
	print(geek);
}
```
```dart
EXERCISE(7)
[] Using final keywords in a Dart program.
------------------------------------------
void main() {
// Assigning value to geek1 variable without datatype
final geek1 = "Geeks For Geeks";
// Printing variable geek1
print(geek1);

// Assigning value to geek2 variable with data type
final String geek2 = "Geeks For Geeks Again!!";
// Printing variable geek2
print(geek2);
}
```
```dart
EXERCISE(8)
[] Using const keywords in a Dart program.
------------------------------------------
void main() {
// Assigning value to geek1 variable without datatype
const geek1 = "Geeks For Geeks";
// Printing variable geek1
print(geek1);

// Assigning value to geek2 variable with datatype
const geek2 = "Geeks For Geeks Again!!";
// Printing variable geek2
print(geek2);
}
```
```dart
EXERCISE(9)
[] Using Arithmetic Operators in the program.
---------------------------------------------
void main()
{
	int a = 2;
	int b = 3;

	// Adding a and b
	var c = a + b;
	print("Sum of a and b is $c");

	// Subtracting a and b
	var d = a - b;
	print("The difference between a and b is $d");

	// Using unary minus
	var e = -d;
	print("The negation of difference between a and b is $e");

	// Multiplication of a and b
	var f = a * b;
	print("The product of a and b is $f");

	// Division of a and b
	var g = b / a;
	print("The quotient of a and b is $g");

	// Using ~/ to divide a and b
	var h = b ~/ a;
	print("The quotient of a and b is $h");

	// Remainder of a and b
	var i = b % a;
	print("The remainder of a and b is $i");
}
```

```dart
EXERCISE(10)
[] Using Relational Operators in the program.
---------------------------------------------
void main()
{
	int a = 2;
	int b = 3;

	// Greater between a and b
	var c = a > b;
	print("a is greater than b is $c");

	// Smaller between a and b
	var d = a < b;
	print("a is smaller than b is $d");

	// Greater than or equal to between a and b
	var e = a >= b;
	print("a is greater than b is $e");

	// Less than or equal to between a and b
	var f = a <= b;
	print("a is smaller than b is $f");

	// Equality between a and b
	var g = b == a;
	print("a and b are equal is $g");

	// Unequality between a and b
	var h = b != a;
	print("a and b are not equal is $h");
}
```
```dart
EXERCISE(11)
[] Using Type Test Operators in the program.
--------------------------------------------
void main()
{
	String a = 'GFG';
	double b = 3.3;

	// Using is to compare
	print(a is String);

	// Using is! to compare
	print(b is !int);
}
```
```dart
EXERCISE(12)
[]Using Bitwise Operators in the program.
-----------------------------------------
void main()
{
	int a = 5;
	int b = 7;

	// Performing Bitwise AND on a and b
	var c = a & b;
	print(c); // output: 5

	// Performing Bitwise OR on a and b
	var d = a | b;
	print(d); // output: 7

	// Performing Bitwise XOR on a and b
	var e = a ^ b;
	print(e); // output: 2

	// Performing Bitwise NOT on a
	var f = ~a;
	print(f); // output: -6

	// Performing left shift on a
	var g = a << b;
	print(g); // output: 640

	// Performing right shift on a
	var h = a >> b;
	print(h); // output: 0
}
```
```dart
EXERCISE(13)
[] Using Assignment Operators in the program.
---------------------------------------------
void main()
{
	int a = 5;
	int b = 7;

	// Assigning value to variable c
	var c = a * b;
	print(c); // output: 35

	// Assigning value to variable d
	var d;
	d ? ? = a + b; // Value is assign as it is null
	print(d); // output: 12
	// Again trying to assign value to d
	d ? ? = a - b; // Value is not assign as it is not null
	print(d); // output: 12
}
```
```dart
EXERCISE(14)
[]Using Logical Operators in the program.
-----------------------------------------
void main()
{
	int a = 5;
	int b = 7;

	// Using And Operator
	bool c = a > 10 && b < 10;
	print(c); // false

	// Using Or Operator
	bool d = a > 10 || b < 10;
	print(d); // true

	// Using Not Operator
	bool e = !(a > 10);
	print(e); // true
}
```
```dart
EXERCISE(15)
[]Using Conditional Operators in the program.
---------------------------------------------
void main()
{
	int a = 5;
	int b = 7;

	// Conditional Statement
	var c = (a < 10) ? "Statement is Correct, Geek" : "Statement is Wrong, Geek";
	print(c); // output: Statement is Correct, Geek 

	
	// Conditional statement 
	int? n;
	// Warning: Operand of null-aware operation '??' has type 'int' which excludes null.
	// For batter practice make both same type to avoid warning
	// var d = n ?? 10;
	var d = n ?? "n has Null value";
	print(d); // output: n has Null value

	// After assigning value to n
	n = 10;
	// we make it all ready null safe
	//d = n ? ? "n has Null value";
	d = n;
	print(d); // output: 10
}
```
```dart
EXERCISE(16)
[] Using Cascade Notation Operators in the program.
---------------------------------------------------
class GFG {
	var a;
	var b;

	void set(x, y)
	{
		this.a = x;
		this.b = y;
	}

	void add()
	{
		var z = this.a + this.b;
		print(z);
	}
}

void main()
{
	// Creating objects of class GFG
	GFG geek1 = new GFG();
	GFG geek2 = new GFG();

	// Without using Cascade Notation
	geek1.set(1, 2);
	geek1.add(); // output: 3

	// Using Cascade Notation
	geek2..set(3, 4)
		..add(); // output: 7
}
```
```dart
EXERCISE(17)
[]Taking a string input from user:
----------------------------------
// importing dart:io file
import 'dart:io';

void main()
{
	print("Enter your name?");
	// Reading name of the Geek
	String? name = stdin.readLineSync(); // null safety in name string

	// Printing the name
	print("Hello, $name! \nWelcome to GeeksforGeeks!!");
}
```

```dart
EXERCISE(18)
[] Taking integer value as input:
---------------------------------
// Importing dart:io file
import 'dart:io';

void main()
{
	// Asking for favourite number
	print("Enter your favourite number:");

// Scanning number
	int? n = int.parse(stdin.readLineSync()!);
// Here ? and ! are for null safety

	// Printing that number
	print("Your favourite number is $n");
}
```

```dart
EXERCISE(19)
[]ask user his/her name,age  and his/her occupation
---------------------------------------------------
// importing dart:io file
import 'dart:io';

void main()
{
	print("What is your name? ");
	// Reading name of the Geek
	String? name = stdin.readLineSync();
	print("How old are you? ");
	int? age = int.parse(stdin.readLineSync()!);
      print("What is your occupation? ");
	String? occupation = stdin.readLineSync(); 

      print("-------------Your information------------");
	print("Name = $name");
	print("Age = $age");
	print("Occupation = $occupation");
}
```

```dart
EXERCISE(20)
[]In the following program, we take a string 'abcdef' in variable myString, and get the character in this string at index=3.
-----------------------------------------------------------------------------------------------------------------------------
void main() {
    var myString = 'abcdefg';
    var index = 3;
    if (index >= 0 && index < myString.length) {
      var output = myString[index];
      print('myString[$index] = $output');
    } else {
      print('index out of range for given string.');
    }
}
```
```html
<h1>welcome </htm>
```
```python
print(ali)
```
