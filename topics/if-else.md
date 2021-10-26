# If / Else

### Examples

```
void main(){

  var number = 26;
  
  if(number > 50){
    print("Number Greater than 50");
  }else{
    print("Number Less than 50");
  }
  
}
```

{% hint style="success" %}
Number Less than 50
{% endhint %}

```
void main(){
  
    var a = 10;
    var b = 20;
 	
    if(a > b){
      print("a is greater than b");
    }else {
      print("b is greater than a");
    }

}
```

{% hint style="success" %}
b is greater than a
{% endhint %}

```
void main()
{
    var a = 10;
  	var b = 10;
 	
    if(a > b){
      print("a is greater than b");
    }else if(a == b){
      print("a and b are equal");
    }else {
      print("b is greater than a");
    }

}
```

{% hint style="success" %}
a and b are equal
{% endhint %}

```
void main() {
  
  int age = 15;

  if (age > 40) {
    print("Old man");
  } else if (age > 19) {
    print("young man");
  } else if (age > 12) {
    print("teen age");
  } else {
    print("Baby");
  }
  
}
```

{% hint style="success" %}
teen age
{% endhint %}

```
import 'dart:io';

void main() {
  var input;
  print("Please Type a number :");
  input = stdin.readLineSync()!;
  input = double.parse(input);

  if (100 >= input && input >= 80) {
    print("A");
  }
  if (80 > input && input >= 70) {
    print("B");
  }
  if (70 > input && input >= 60) {
    print("C");
  }
  if (60 > input && input >= 50) {
    print("D");
  }
  if (50 > input && input >= 33) {
    print("E");
  }
  if (33 > input && input >= 0) {
    print("F");
  }
}
```

Sample outputs based on input&#x20;

{% hint style="success" %}
Please Type a number :&#x20;

55&#x20;

D
{% endhint %}

{% hint style="success" %}
Please Type a number :&#x20;

22&#x20;

F
{% endhint %}
