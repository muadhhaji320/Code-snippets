# dart programming

```dart
[] hello world
main() { 
	print("Welcome to GeeksForGeeks"); 
} 
```
```dart
[] Dart - Comments
int main() 
{ 
double area = 3.14 * 4 * 4; 
// It prints the area
// of a circle of radius = 4 
print(area); 

return 0; 
}
```
```dart
[] Dart Multi-Line Comment:
int main() 
{ 
var lst = [1, 2, 3]; 

/* 
It prints 
the whole list 
at once 
*/
print(lst); 

return 0; }

```
```dart
[] Dart Multi-Line Comment: example 2
int main() 
{ 
var lst = [1, 2, 3]; 

/* 
It prints 
the whole list 
at once 
*/
print(lst); 

return 0; }

```
```dart
[] Dart Documentation Comment:
bool checkEven(n){ 
/// Returns true
/// if n is even 
if(n%2==0) 

	return true; 
/// Returns false if n is odd 
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
[] Dart - Variables
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
[] Dynamic type variable in Dart:
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
[] Using final keywords in a Dart program.
void main() {
// Assigning value to geek1 variable without datatype
final geek1 = "Geeks For Geeks";
// Printing variable geek1
print(geek1);

// Assigning value to geek2 variable with datatype
final String geek2 = "Geeks For Geeks Again!!";
// Printing variable geek2
print(geek2);
}
```
```dart
[] Using const keywords in a Dart program.
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
[] 
```
```dart
[] Operators in Dart
```
