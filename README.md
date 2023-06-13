# Dart-Course

### 8-video

> To Print **'Hello world'**
```
print ('Hello world');
```

> **fatArrow function**
```
void main() => print('Hello World');
```
---
### 11-video
```
dynamic value =10;
//print('value:' + value.toString());
print('value: ${value.runtimeType}');
 
 value = 'Ahmed';
  print('value $value');
  print('value ${value.runtimeType}');
  ```
  ```
  num grade =1.5;
print('grade type: ${grade.runtimeType}');
```
---
### 12-video
```
dynamic value = 10;
print('value:' + value.toString());
```
---
### 14-video
```
void main() {           
   Day today = Day.monday;
print ('Today: ${(today.index)}');
}

enum Day{
 saturday,sunday,monday,tusday,wednesday,tursday,friday
  }
```
---
### 15-video
```
 double avg = 77;
  
  if(avg >= 60){
    print('Pass');
  }else if(avg >= 70){
    print('good');
  }else if(avg >= 80){
    print('v.good');
  }else if(avg >= 90){
    print('Exellent');
  }
```
```
double avg = 50;
  
  if(avg >= 60 && avg<70){
    print('Pass');
  }else if(avg >= 70 && avg<80){
    print('good');
  }else if(avg >= 80 && avg<90){
    print('v.good');
  }else if(avg >= 90 && avg<=100){
    print('Exellent');
  }else if(avg >=0 && avg<60){
    print('failed');
  }else{
    print('Error Value');
  }
  ```
  ---
  




