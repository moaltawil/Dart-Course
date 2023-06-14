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
  ### 16-video
  
```
String gender = 'M';
  
  switch(gender){
    case 'M':
    case 'm':
      print('Male');
      break;
      
    case 'F':
    case 'f':
      print('Female');
      break;
      
    default:
      print('ERROR VALUE');
      break;
  }
```

```
String gender = 'M';
  
  switch(gender){
    case 'M':
    case 'm':
      print('Male');
      continue Male;
      
    case 'F':
    case 'f':
      print('Female');
      break;
      
      Male:
    case 'Male':
      print('Mr:name');
      break;
      
    default:
      print('ERROR VALUE');
      break;
  }
```
---
### 17-video
> Old Version In Dart **'It was without default with num'**
```
 num avg = 50;
  
  switch(avg){
    case 50:
      print('50');
      break;
      
    case 51:
      print('51');
      break;
  }

```
> new Version In Dart **'must be default with num'**
```
num avg = 50;

  switch (avg) {
    case 50:
      print('The value is 50');
      break;
    case 51:
      print('The value is 51');
      break;
    default:
      print('The value is something else');
  }
```
> Old Version In Dart **'double was rejected'** but in a new Version In Dart **'double are allowed!'**
```
double avg = 50;

  switch (avg) {
    case 50:
      print('The value is 50');
      break;
    case 51:
      print('The value is 51');
      break;

  }
```
```
 bool graduated = false;

  switch (graduated) {
    case true:
      print('Graduated');
      break;
      
    case false:
      print('Not Graduated');
      break;

  }
  ```
 ```
   bool graduated = true;
  String statuse = graduated ? 'Graduated' : 'Not Graduated';
  print('Statuse: $statuse');
 ```
---
### 18-video
```
for(int i=0;i<20;i++){
  print('Value $i');
}
```
---
### 19-video
```
  int index = 0;
  print(index++);
  print(index);
  ```
  ---
  ### 20-video
  ```
  int num1=10;
  int num2=20;
  int sum = num1+num2;
  print(sum);
  ```
  ```
  int num1=10;
  int num2=20;
  num1+=num2;
  print(num1);
  ```
  
  ```
   for(int i=0;i<20;i+=2){
    print('Value $i');
  }
  ```
  ```
   for(int i=20;i>=0;i--){
    print('Value $i');
  }
  ```
  ```
  for(int i=0;i<20;i++){
    if(i==5){
      continue;
    }
    print('Value $i');
  }
  ```
  ```
  for(int i=0;i<20;i++){
    if(i %2 ==0){
       print('$i is even');
    }
  
  }
  ```
  ```
   for(int i=0;i<20;i++){
    if(i %2 !=0){
     continue;
    }
   print('$i is even');
  }
  ```
  
  ---
  ### 21-video
  ```
   int counter =0;
  while(counter<10){
    print('value: $counter');
    counter++;
    
  }
  ```
  ```
   int counter =0;
while(counter<10){
  if(counter == 5){
    ++counter;
    continue;
  }
  print('value: $counter');
  counter++;
  
}
```
  
---
  ### 22-video
  
  
---



