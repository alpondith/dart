# Map

```
void main(){

  var gifts = {
    'father': 'Mobile',
    'mother': 'Laptop',
    'sister': 'golden rings'
  };
  
  print(gifts);
}
```

{% hint style="success" %}
{father: Mobile, mother: Laptop, sister: golden rings}
{% endhint %}

```
void main(){
  
  var gifts = {
    'father': 'Mobile',
    'mother': 'Laptop',
    'sister': 'golden rings'
  };

  print(gifts['first']);
  print(gifts['father']);
  print(gifts['sister']);
}
```

{% hint style="success" %}
null&#x20;

Mobile&#x20;

golden rings
{% endhint %}

```
void main(){
  
  var nobleGases = {
    2: 'helium',
    10: 'neon',
    18: 'argon',
  };
  
  print(nobleGases);

}
```

{% hint style="success" %}
{2: helium, 10: neon, 18: argon}
{% endhint %}

```
void main(){
  
  var nobleGases = {
    2: 'helium',
    10: 'neon',
    18: 'argon',
  };
  
  print(nobleGases[10]);
  print(nobleGases[18]);
  print(nobleGases[5]);

}
```

{% hint style="success" %}
neon&#x20;

argon&#x20;

null
{% endhint %}

```
void main(){
  
  Map numbers = Map<int , String>();

  numbers[1] = "One";
  numbers[2] = "Two";
  numbers[3] = "Three";
  numbers[4] = "four";
  numbers[5] = "five";
  
  print(numbers);

}
```

{% hint style="success" %}
{1: One, 2: Two, 3: Three, 4: four, 5: five}
{% endhint %}

