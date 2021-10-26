# If / Else

### Task 1

**Write a program that reads two numbers from the user and based on the input it prints “first input is large” if the first number is larger or prints “second input is large” if the second number is large .**

```
import 'dart:io';

void main() {
  var number1, number2;

  print("Please give first number : ");
  number1 = stdin.readLineSync()!;
  number1 = double.parse(number1);

  print("Please give second number : ");
  number2 = stdin.readLineSync()!;
  number2 = double.parse(number2);

  if (number1 > number2) {
    print("$number1 : first input is large ");
  } else {
    print("second input is large");
  }
}
```
