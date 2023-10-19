# 100+ FLUTTER CONCEPTS

```dart
Text widget:
---------------
import 'package:flutter/material.dart';

void main() => runApp(MaterialApp(
  home: Text('hey ninjas!!')
));
```
```dart
AppBar widget:
--------------
import 'package:flutter/material.dart';

void main() => runApp(MaterialApp(
  debugShowCheckedModeBanner: false,
  home: Scaffold(
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
child: Properties of Container widget
-------------------------------------
Container(  
    child: Text("Hello! I am in the container widget", style: TextStyle(fontSize: 25)),  
)  
```
```dart
color: Properties of Container widget
-------------------------------------
Container(  
    color: Colors.green,   
    child: Text("Hello! I am in the container widget", style: TextStyle(fontSize: 25)),  
) 
```
