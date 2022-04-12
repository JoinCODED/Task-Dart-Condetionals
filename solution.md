1. Your main method should look like this:

```dart
void main() {
int mark = 78;
}
```

2. Start with you first conditions:

```
if `mark` is more than or equal to 80
```

```dart
void main() {
int mark = 78;
if (mark >= 80){
    print("A");
}
}
```

3. Move to the next condition:

```
if `mark` is more than or equal to 70 and less than 80
```

let's translate that with code:

if: if

mark: mark

more than: >

or equal to: =

and: &&

less than: <

```dart
void main() {
int mark = 78;
if (mark >= 80){
    print("A");
} else if (mark >= 70 && mark < 80){
    print("B");
}
}
```

4. Do the same for the next conditions:

```dart
void main() {
int mark = 78;
if (mark >= 80){
    print("A");
} else if (mark >= 70){
    print("B");
} else if (mark >= 60){
    print("C");
} else if (mark >= 50){
    print("D");
}
}
```

5. And we use `else` for the last condition:

```dart
void main() {
int mark = 78;
if (mark >= 80){
    print("A");
} else if (mark >= 70){
    print("B");
} else if (mark >= 60){
    print("C");
} else if (mark >= 50){
    print("D");
} else {
    print("F");
}
}
```

### 🍋 More Practice: FizzBuzz

1. Your main method should look like this:

```dart
void main() {
int i = 9;
}
```

2. Our first condition is:

```
if i is divisible by 3 and 5
```

To know if a number is divisible by 3 we use the modula `%`.

```
if a number % 3 = 0 , then it's divisible by 3
```

Let's implement that in dart:

```dart
void main() {
int i = 9;
if (i % 3 == 0 && i % 5 == 0 ){
    print("fizz buzz");
} else if (i % 3 == 0){
    print('fizz');
} else if (i % 5 == 0){
    print('buzz');
} else {
    print(i);
}
}
```
