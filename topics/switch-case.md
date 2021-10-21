# Switch Case

### Examples

```
void main() {
  int number = 2;
  switch(number) {
    case 0:
      print('zero!');
      break;
    case 1:
      print('one!');
      break;
    case 2:
      print('two!');
      break;
    default:
      print('choose a different number!');
  }
}
```

{% hint style="success" %}
two!
{% endhint %}

```
void main() { 
   var grade = "B"; 
   switch(grade) { 
       
      case "A": print("Excellent"); 
      break; 
     
      case "B": print("Good"); 
      break; 
     
      case "C": print("Fair"); 
      break; 
     
      case "D": print("Poor");
      break; 
     
      default: print("Invalid choice");
      break;

   } 
} 
```

{% hint style="success" %}
Good
{% endhint %}

```
void main(){
    var dayOfWeek = 5;
    switch(dayOfWeek){
      case 1:{
        print("Today is Monday.");
      }
      break;
        
      case 2:
        print("Today is Tuesday.");
        break;
        
      case 3:{
        print("Today is Wednesday.");
      }
      break;
        
      case 4:{
        print("Today is Thursday."); 
      }
      break;
        
      case 5:{
        print("Today is Friday.");  
      }
      break;
        
      case 6:{
        print("Today is Saturday.");  
      }
      break;
        
      case 7:{
        print("Today is Sunday.");  
      }
      break;
        
      default:{
        print("Invalid Weekday."); 
      }
      break;
    }
}
```

{% hint style="success" %}
Today is Friday.
{% endhint %}
