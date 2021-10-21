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
