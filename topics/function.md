# Function

```
void main() {
  print("===========================");
  printer();
  print("===========================");
  printer();
}

void printer() {
  for (int i = 0; i < 5; i++) {
    print("Hello");
  }
}
```

```
void main() {
  printer("Hello");
  printer("Mr A");
}

void printer(String message) {
  for (int i = 0; i < 5; i++) {
    print(message);
  }
}

```

```
void main() {
  printer("Hello", 5);
  printer("Mr A", 3);
}

void printer(String message, int count) {
  for (int i = 0; i < count; i++) {
    print(message);
  }
}
```

```
void main() {
  printer("Mr.", "Obydul", "Kader");
  printer("Dr.", "Dipu", "Moni");
  printer("Mrs.", "Momtaz", "Begum");
}

void printer(String surName, String firstName, String lastName) {
  print("Hi $lastName, your full name is $surName $firstName $lastName.");
}
```

```
void main() {
  printer(firstName: "Obydul",surName: "Mr.",lastName: "Kader",);
  printer(surName: "Dr.",firstName: "Dipu",lastName: "Moni");
}

void printer({required String surName,required String firstName,required String lastName}) {
  print("Hi $lastName, your full name is $surName $firstName $lastName.");
}
```

