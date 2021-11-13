# Class & Objects

```
void main() {
  Human man1 = Human("Mr A", 34, 5.6);
  Human man2 = Human("Mr B", 20, 5.9);
  Human man3 = Human("Mr C", 50, 5.4);

  print(man1.name);
  print(man1.age);
  print(man1.height);

  print("name : ${man2.name} , age : ${man2.age} , height : ${man2.height}");

  print("name : ${man3.name} , age : ${man3.age} , height : ${man3.height}");
}

class Human {
  String? name;
  int? age;
  double? height;

  Human(String this.name, int this.age, double this.height);
}

```
