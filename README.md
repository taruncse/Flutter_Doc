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
             ),
     ```

* Icon: 

    ```Dart
      Icon(
           Icons.phone,
           color: Colors.teal.shade900,
           size: 20.0,
        ),
    ```
* Card margin : set margin of a view

    ```Dart
      margin: EdgeInsets.symmetric(horizontal: 30.0, vertical: 10.0),
    ```

* Row: a row of a view , you can replace Row as Column

    ```Dart
      Row(
           children: [
             Icon(
               Icons.phone,
               color: Colors.teal.shade900,
               size: 20.0,
             ),
             SizedBox(
               width: 20,
             ),
             Text(
               "+8801719144274",
               style: TextStyle(
                 color: Colors.teal.shade900,
                 fontSize: 20.0,
               ),
             ),
           ],
         ),
    ```

* ListTile : set view as small view like tile

   ```Dart
      ListTile(
               leading: Icon(
                 Icons.mail,
                 color: Colors.teal.shade900,
                 size: 19.0,
               ),
               title: Text(
                 "tulshisanatithi@gmail.com",
                 style: TextStyle(
                   color: Colors.teal.shade900,
                   fontSize: 20.0,
                 ),
               ),
             ),
    ```

* Card : View like card, and making automatic rounded boarder

    ```Dart
      Card(
             margin: EdgeInsets.symmetric(horizontal: 30.0, vertical: 10.0),
             child: ListTile(
               leading: Icon(
                 Icons.mail,
                 color: Colors.teal.shade900,
                 size: 19.0,
               ),
               title: Text(
                 "tulshisanatithi@gmail.com",
                 style: TextStyle(
                   color: Colors.teal.shade900,
                   fontSize: 20.0,
                 ),
               ),
             ),
           ),
    ```

* FloatingActionButton : floading or fab button

 ```Dart 
   FloatingActionButton(
       backgroundColor: Colors.yellow,
       child: Icon(
         Icons.add,
         color: Colors.blue,
       ),
     ),
 ```

* Image Asset and Fonts config in .yaml : Configuration for image and fonts in pubspect.yaml file

 ```
     assets:
       - images/

     fonts:
     - family: Pacifico
       fonts:
       - asset: fonts/Pacifico-Regular.ttf
 ```
 
* Expanded : Equally distribute the views over the screen

```Dart
      Expanded(
          flex: 1,
          child: Image(
            image: AssetImage(
              'images/dice1.png',
            ),
          ),
        ),
```

* Asset Image : load image from asset
```Dart
      Image.asset(
         'images/dice1.png',
      )
```
* Center : Make the view in center position 

```Dart
      Center(
          child: Row(),
      )
```
