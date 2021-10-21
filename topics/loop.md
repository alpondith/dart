# Loop

### For Loop

```
void main() {
  for (int i = 0; i < 5; i++) {
    print('hello');
  }
}
```

{% hint style="success" %}
hello&#x20;

hello&#x20;

hello&#x20;

hello&#x20;

hello
{% endhint %}

```
void main() {
  for (int index = 1; index <= 5; index++) {
    print("Hello $index");
  }
}
```

{% hint style="success" %}
Hello 1&#x20;

Hello 2&#x20;

Hello 3&#x20;

Hello 4&#x20;

Hello 5
{% endhint %}

```
void main(){
  int i = 1;
  for(;i <= 5;){
    print(i);
    i++;
  }
}
```

{% hint style="success" %}
1&#x20;

2&#x20;

3&#x20;

4&#x20;

5
{% endhint %}

### While Loop

```
void main()   
{  
    int i = 1;  
    while (i <= 5)  
    {  
        print("Helloo $i");  
        i++;  
    }  
} 
```

{% hint style="success" %}
Helloo 1&#x20;

Helloo 2&#x20;

Helloo 3&#x20;

Helloo 4&#x20;

Helloo 5
{% endhint %}

### Do While Loop

```
void main() { 
  
   var n = 5; 
  
   do { 
      print("hello $n"); 
      n--; 
   }
   while(n>=0); 
  
}
```

{% hint style="success" %}
hello 5&#x20;

hello 4&#x20;

hello 3&#x20;

hello 2&#x20;

hello 1&#x20;

hello 0
{% endhint %}

### Generating Math Table

```
void main() {
  int result;
  for (int i = 1; i <= 10; i++) {
    result = i * 10;
    print(result);
  }
}
```

{% hint style="success" %}
10&#x20;

20&#x20;

30&#x20;

40&#x20;

50&#x20;

60&#x20;

70&#x20;

80&#x20;

90&#x20;

100
{% endhint %}

```
void main() {
  int result;
  for (int i = 1; i <= 10; i++) {
    result = i * 10;
    print(" $i x 10 = $result");
  }
}
```

{% hint style="success" %}
1 x 10 = 10&#x20;

2 x 10 = 20&#x20;

3 x 10 = 30&#x20;

4 x 10 = 40&#x20;

5 x 10 = 50&#x20;

6 x 10 = 60&#x20;

7 x 10 = 70&#x20;

8 x 10 = 80&#x20;

9 x 10 = 90&#x20;

10 x 10 = 100
{% endhint %}

```
void main() {
  int result, number;
  number = 5;
  for (int i = 1; i <= 10; i++) {
    result = i * number;
    print(" $i x $number = $result");
  }
}
```

{% hint style="success" %}
1 x 5 = 5&#x20;

2 x 5 = 10&#x20;

3 x 5 = 15&#x20;

4 x 5 = 20&#x20;

5 x 5 = 25&#x20;

6 x 5 = 30&#x20;

7 x 5 = 35&#x20;

8 x 5 = 40&#x20;

9 x 5 = 45&#x20;

10 x 5 = 50
{% endhint %}

```
import 'dart:io';
void main(){

  print("Please give a number : ");
  var input = stdin.readLineSync()!;
  int number = int.parse(input);

  int result;
  for (int i = 1; i <= 10; i++) {
    result = i * number;
    print(" $number x $i = $result");
  }
  
}
```

{% hint style="info" %}
output will be according to the input given on console.&#x20;
{% endhint %}
