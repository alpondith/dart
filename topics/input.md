# Input

### Input Sample :&#x20;

```
import 'dart:io';

void main() {
  var name;

  print("Please give your name : ");
  name = stdin.readLineSync()!;

  print("My name is $name");
}
```

### Take input Name and Age : &#x20;

```
import 'dart:io';

void main() {
  var name, age;

  print("Please give your name : ");
  name = stdin.readLineSync()!;

  print("Please give your age : ");
  age = stdin.readLineSync()!;

  print("My name is $name and age is $age");
}
```

### Take 3 name and print them :&#x20;

```
void main() {
  var name1, name2, name3;

  print("Give Name 1 :");
  name1 = stdin.readLineSync()!;

  print("Give Name 2 :");
  name2 = stdin.readLineSync()!;

  print("Give Name 3 :");
  name3 = stdin.readLineSync()!;

  print(" $name1 , $name2, $name3 ");
}
```

### Take 2 numbers and add them&#x20;

```
import 'dart:io';

void main() {
  var number1, number2, result;

  print("please give a number :");
  number1 = stdin.readLineSync()!;
  number1 = int.parse(number1);

  print("please give another number :");
  number2 = stdin.readLineSync()!;
  number2 = int.parse(number2);

  result = number1 + number2;

  print("$number1 + $number2 = $result");
}

```

### Build your Personal Information Card

```
import 'dart:io';

void main() {
  var name, age, fatherName, motherName, bloodGroup, address;

  print("Please type your name : ");
  name = stdin.readLineSync()!;

  print("Please type your age : ");
  age = stdin.readLineSync()!;

  print("Please type your Father name : ");
  fatherName = stdin.readLineSync()!;

  print("Please type your Mother Name : ");
  motherName = stdin.readLineSync()!;

  print("Please type your Blood group : ");
  bloodGroup = stdin.readLineSync()!;

  print("Please type your Address : ");
  address = stdin.readLineSync()!;

  print("       Personal Details    ");
  print("name        : $name");
  print("age         : $age");
  print("father name : $fatherName");
  print("mother name : $motherName");
  print("blood group : $bloodGroup");
  print("address     : $address");
}
```

{% hint style="success" %}
Please type your name :&#x20;

Mr Jhon&#x20;

Please type your age :&#x20;

40&#x20;

Please type your Father name :&#x20;

Mr A&#x20;

Please type your Mother Name :&#x20;

Mrs B&#x20;

Please type your Blood group :&#x20;

O+&#x20;

Please type your Address :&#x20;

Gazipur&#x20;

&#x20;             Personal Details\
name                :  Mr Jhon&#x20;

age                   :  40&#x20;

father name     :  Mr A&#x20;

mother name   :  Mrs B&#x20;

blood group     :  O+&#x20;

address            :  Gazipur
{% endhint %}
