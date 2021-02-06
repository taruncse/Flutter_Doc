# Flutter_Doc

## Topics
------------------------------
* AssetImage :

```Dart
AssetImage( 'images/ts.png',),
```

* CircleAvatar :
```Dart
CircleAvatar(
   radius: 80,
   backgroundImage: AssetImage(
   'images/ts.png',
    ),
 ),
```
        
* Text : 
```Dart
Text(
     "My Name",
     style: TextStyle(
     fontSize: 35,
     color: Colors.white,
     fontWeight: FontWeight.bold,
     fontFamily: 'Pacifico'),
   ),
```

* Divider :
```Dart
     Divider(
       color: Colors.teal.shade100,
     ),
```

* SizedBox : 

```Dart
SizedBox(
            height: 20.0,
            width: 150.0,
            child: Divider(
            color: Colors.teal.shade100,
         ),
       ),```
