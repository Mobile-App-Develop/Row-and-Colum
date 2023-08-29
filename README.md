# Row-and-Colum
import 'package:flutter/material.dart';

void main() {
  runApp(
    MaterialApp(
      home: Scaffold(
        appBar: AppBar(
          title: Text("my app"),
        ),
        body: Material(
          child: Container(
            padding: EdgeInsets.all(4),
            color: Colors.grey,
            alignment: Alignment.center,
            child: Column(children: [
              Row(children: [
                Expanded(
                  child: Container(
                    padding: EdgeInsets.all(4),
                    color: Colors.green,
                    child: Center(child: Text("1")),
                   
                  ),
                ),
                Expanded(
                  child: Container(
                    padding: EdgeInsets.all(4),
                    color: Colors.orange,
                    child: Text(
                      "2",
                      textAlign: TextAlign.center,
                    ),
                  ),
                ),
                Expanded(
                  child: Container(
                    padding: EdgeInsets.all(4),
                    color: Colors.yellow,
                    child: Text(
                      "3",
                      textAlign: TextAlign.center,
                    ),
                  ),
                ),
                Expanded(
                  child: Container(
                    padding: EdgeInsets.all(4),
                    color: Colors.redAccent,
                    child: Text(
                      "4",
                      textAlign: TextAlign.center,
                    ),
                  ),
                ),
              ]),
              Row(children: [
                Expanded(
                  child: Container(
                    padding: EdgeInsets.all(4),
                    color: Colors.green,
                    child: Text(
                      "1",
                      textAlign: TextAlign.center,
                    ),
                  ),
                ),
                Expanded(
                  child: Container(
                    padding: EdgeInsets.all(4),
                    color: Colors.orange,
                    child: Text(
                      "2",
                      textAlign: TextAlign.center,
                    ),
                  ),
                ),
                Expanded(
                  child: Container(
                    padding: EdgeInsets.all(4),
                    color: Colors.yellow,
                    child: Text(
                      "3",
                      textAlign: TextAlign.center,
                    ),
                  ),
                ),
                Expanded(
                  child: Container(
                    padding: EdgeInsets.all(4),
                    color: Colors.redAccent,
                    child: Text(
                      "4",
                      textAlign: TextAlign.center,
                    ),
                  ),
                ),
              ]),
              Row(children: [
                Expanded(
                  child: Container(
                    padding: EdgeInsets.all(4),
                    color: Colors.green,
                    child: Text(
                      "1",
                      textAlign: TextAlign.center,
                    ),
                  ),
                ),
                Expanded(
                  child: Container(
                    padding: EdgeInsets.all(4),
                    color: Colors.orange,
                    child: Text(
                      "2",
                      textAlign: TextAlign.center,
                    ),
                  ),
                ),
                Expanded(
                  child: Container(
                    padding: EdgeInsets.all(4),
                    color: Colors.yellow,
                    child: Text(
                      "3",
                      textAlign: TextAlign.center,
                    ),
                  ),
                ),
                Expanded(
                  child: Container(
                    padding: EdgeInsets.all(4),
                    color: Colors.redAccent,
                    child: Text(
                      "4",
                      textAlign: TextAlign.center,
                    ),
                  ),
                ),
              ]),
            ]),
          ),
        ),
      ),
    ),
  );
}
