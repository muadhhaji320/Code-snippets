# 100+ FLUTTER CONCEPTS

```dart
import 'package:flutter/material.dart';

void main() => runApp(MaterialApp(
  //●Text widget
  home: Text('hey ninjas!!')
));
```
```dart

--------------
import 'package:flutter/material.dart';

void main() => runApp(MaterialApp(
  debugShowCheckedModeBanner: false,
  home: Scaffold(
    //●AppBar widget:
    appBar: AppBar(
      title: Text('my first app'),
      centerTitle: true,
    ),
    body: Center(
      child: Text('hello, ninjas!'),
    ),
    floatingActionButton: FloatingActionButton(
      onPressed: () {},
      child: Text('click'),
    ),
  ),
));
```
```dart
Container(
    //●child: Properties of Container widget
    child: Text("Hello! I am in the container widget", style: TextStyle(fontSize: 25)),  
)  
```
```dart
Container(
    //●color: Properties of Container widget
    color: Colors.green,   
    child: Text("Hello! I am in the container widget", style: TextStyle(fontSize: 25)),  
) 
```
```dart
Container(
    //●height and width: Properties of Container widget
    width: 200.0,  
    height: 100.0,  
    color: Colors.green,   
    child: Text("Hello! I am in the container widget", style: TextStyle(fontSize: 25)),  
)  
```
```dart
Container(  
    width: 200.0,  
    height: 100.0,  
    color: Colors.green,   
    margin: EdgeInsets.all(20),  //●margin: Properties of Container widget
    child: Text("Hello! I am in the container widget", style: TextStyle(fontSize: 25)),  
)
```
