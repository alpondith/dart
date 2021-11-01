# Loop

### Task 1

Write a program that prints numbers from 1 to 20. Example : 1 2 3 4  ......  19 20 &#x20;

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

Write a program that prints numbers from -1 to -20. example : -1  -2  -3  -4  ......  -19 -20

### Task 3

Write a program that prints all even numbers from 1 to 20. Example : 0  2 4  ......  18  20

### Task 4

Write a program that prints all odd numbers from 1 to 20. Example : 1 3  5  ......  17 19

### Task 5

Write a program that prints all even & odd numbers from 1 to 20.&#x20;

Example Output:&#x20;

Even numbers : 0  2  4  ......  18 20

Odd numbers : 1  3  5  ......  17  19
