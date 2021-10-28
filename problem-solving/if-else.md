# If / Else

### Task 1

Write a program that reads two numbers from the user and based on the input it prints “first input is large” if the first number is larger or prints “second input is large” if the second number is large .

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

### Task 2

Write a program that reads two numbers from the user. Your program should then print “first is greater” if the first input is larger,  “second is greater” if the second input is larger,  and “the numbers are equal” otherwise.

### **Task 3**

Write a program that reads two numbers and subtracts the smaller number from the larger one, and prints the result.

### Task 4

Write a program that reads a number and prints “The number is even” or “The number is odd” depending on whether the number is even or odd. (Hint: use the modulus operator)

### Task 5

Write a program that reads an integer, and if the number is even and greater than 10, prints “An even number greater than 10”. If the number is even but lesser than 10, print “An even number not greater than 10”. If the number is greater than 10 but odd, print “An odd number greater than 10”. If the number is odd and also less than 10, print “An odd number less than 10”.

### **Task 6**

Write a program that reads an integer, and prints the integer if it is a multiple of either 2 or 5. Example : 2, 4, 5, 6, 8, 10, 12, 14, 15, 16, 18, 20, 22 …

### Task 7

Write a program that reads an integer, and prints the integer if it is a multiple of either 2 or 5 but not both. For example, 2, 4, 5, 6, 8, 12, 14, 15, 16, 18, 22
