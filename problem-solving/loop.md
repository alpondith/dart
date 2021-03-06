# Loop

### Task 1

Write a program that prints numbers from 1 to 20. Example : 1 2 3 4  ......  19 20 &#x20;

Solution using while loop

```
void main() {
  String result = "";
  int index = 1;
  while (index <= 4) {
    result = result + " $index";
    index++;
  }
  print(result);
}
```

{% hint style="success" %}
1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 18 19 20
{% endhint %}

Using for loop

```
void main() {
  String result = "";
  for (int index = 1; index <= 4; index++) {
    result = result + " $index";
  }
  print(result);
}
```

{% hint style="success" %}
1 2 3 4 5 6 7 8 9 10 11 12 13 14 15 16 17 18 19 20
{% endhint %}

### Task 2

2.1 Write a program that prints numbers from 20 to 1. example : 20 19 ....... 4 3 2 1

```
void main() {
  String result = "";
  for (int index = 20; index >= 1; index--) {
    result = result + " $index";
  }
  print(result);
}
```

{% hint style="success" %}
20 19 18 17 16 15 14 13 12 11 10 9 8 7 6 5 4 3 2 1
{% endhint %}

2.2 Write a program that prints numbers from -1 to -20. example : -1  -2  -3  -4  ......  -19 -20

```
void main() {
  String result = "";
  for (int index = -1; index >= -20; index--) {
    result = result + " $index";
  }
  print(result);
}

```

{% hint style="success" %}
\-1 -2 -3 -4 -5 -6 -7 -8 -9 -10 -11 -12 -13 -14 -15 -16 -17 -18 -19 -20
{% endhint %}

### Task 3

Write a program that prints all even numbers from 1 to 20. Example : 0  2 4  ......  18  20

```
void main() {
  String result = "";
  for (int index = 0; index <= 20; index++) {
    if (index.isEven) {
      result = result + " $index";
    }
  }
  print(result);
}
```

```
void main() {
  String result = "";
  for (int index = 0; index <= 20; index++) {
    if (index % 2 == 0) {
      result = result + " $index";
    }
  }
  print(result);
}

```

```
void main() {
  String result = "";
  for (int index = 0; index <= 20; index = index + 2) {
    result = result + " $index";
  }
  print(result);
}
```

### Task 4

Write a program that prints all odd numbers from 1 to 20. Example : 1 3  5  ......  17 19

### Task 5

Write a program that prints all even & odd numbers from 1 to 20.&#x20;

Example Output:&#x20;

Even numbers : 0  2  4  ......  18 20

Odd numbers : 1  3  5  ......  17  19
