# List

### Basic useage

```
void main() { 
  List itemList = [ 3 , "hello" , true , false , 'Mr Jhon' , 5.5];
  print(itemList);
}
```

{% hint style="success" %}
\[3, hello, true, false, Mr Jhon, 5.5]
{% endhint %}

```
void main() { 
  List<int> numberList = [ 6 , 99 , 33, 70, 1 ];
  print(numberList);
}
```

{% hint style="success" %}
\[6, 99, 33, 70, 1]
{% endhint %}

```
void main() { 
  List<String> cars = ['BMW','Audi','Ford', "Hundai"];
  print(cars);
}
```

{% hint style="success" %}
\[BMW, Audi, Ford, Hundai]
{% endhint %}

```
void main() { 
  
  List<String> cars = ['BMW','Audi','Ford', "Hundai"];
  
  print(cars[0]);
  print(cars[1]);
  print(cars[2]);
  print(cars[3]);
  
}
```

{% hint style="success" %}
BMW&#x20;

Audi&#x20;

Ford&#x20;

Hundai
{% endhint %}

```
void main() { 
 
  List<int> numbers = [4 , 5, 50 , 88, 3 , 130];
  for(var number in numbers){
    print(number);
  }

}
```

{% hint style="success" %}
4&#x20;

5&#x20;

50&#x20;

88&#x20;

3&#x20;

130
{% endhint %}

```
void main() { 
  List<String> cars = ['BMW','Audi','Ford', "Hundai"];
  for(int i = 0; i< cars.length ; i++){
    print(cars[i]);
  }
}
```

{% hint style="success" %}
BMW&#x20;

Audi&#x20;

Ford&#x20;

Hundai
{% endhint %}

```
void main() { 
  List<String> cars = ['BMW','Audi','Ford', "Hundai"];
  for(int i = 0; i< cars.length ; i++){
    print("${i+1}. ${cars[i]}");
  }
}
```

{% hint style="success" %}
1. BMW
2. Audi
3. Ford
4. Hundai
{% endhint %}

```
void main() { 
  List<String> cars = ['BMW','Audi','Ford', "Hundai"];
  List<String> owners = ['Sofia','Ava','Layla', "Eliliya"];
  for(int i = 0; i< cars.length ; i++){
    print("${i+1}. Owner of this ${cars[i]} car is ${owners[i]}");
  }
}
```

{% hint style="success" %}
1. Owner of this BMW car is Sofia
2. Owner of this Audi car is Ava
3. Owner of this Ford car is Layla
4. Owner of this Hundai car is Eliliya
{% endhint %}

### Additional options

```
void main() { 
  
  List<String> cars = ['BMW','Audi','Ford', "Hundai"];
  print(cars);
  cars.add("Jeep");
  print(cars);
  cars.addAll(['Nissan' , 'Tesla', "Volvo"]);
  print(cars);

}
```

{% hint style="success" %}
\[BMW, Audi, Ford, Hundai]&#x20;

\[BMW, Audi, Ford, Hundai, Jeep]&#x20;

\[BMW, Audi, Ford, Hundai, Jeep, Nissan, Tesla, Volvo]
{% endhint %}

```
void main() { 
  
  List<String> cars = ['BMW','Audi','Ford', "Hundai", 'Nissan' , 'Tesla', "Volvo"];
  print(cars.length);
  print(cars.isEmpty);
  print(cars.first);
  print(cars.last);
  print(cars.contains('BMW'));
  print(cars.contains('Nikola'));

}
```

{% hint style="success" %}
7&#x20;

false&#x20;

BMW&#x20;

Volvo&#x20;

true&#x20;

false
{% endhint %}

For more information visit here [List](https://api.dart.dev/be/156195/dart-core/List-class.html)

### Examples

#### Print Even Numbers

```
void main() { 
  List<int> numbers = [4 , 5, 50 , 88, 3 , 130];
  for(var number in numbers){
    if(number % 2 == 0){
      print(number);
    }
  }
}
```

{% hint style="success" %}
4&#x20;

50&#x20;

88&#x20;

130
{% endhint %}

#### Print Odd Numbers

```
void main() { 
  List<int> numbers = [4 , 5, 50 , 88, 3 , 130];
  for(var number in numbers){
    if(number % 2 == 1){
      print(number);
    }
  }
}
```

{% hint style="success" %}
5&#x20;

3
{% endhint %}

#### Print numbers that are more than 60

```
void main() { 
  List<int> numbers = [4 , 5, 50 , 88, 3 , 130];
  for(var number in numbers){
    if(number > 60){
      print(number);
    }
  }
}
```

{% hint style="success" %}
88&#x20;

130
{% endhint %}
