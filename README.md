# Flutter-Widgets
a collection of flutter widgets, that i used or want to use in the future

- <a href="https://api.flutter.dev/flutter/material/ListTile-class.html" target="_blank">ListTile</a>
A single fixed-height row that typically contains some text as well as a leading or trailing icon (see <a href ="https://api.flutter.dev/flutter/widgets/ListView-class.html">Listview</a>).

- <a href="https://api.flutter.dev/flutter/rendering/TextOverflow-class.html">TextOverflow</a> : A TextOverflow can be passed to <a href="https://api.flutter.dev/flutter/widgets/Text-class.html">Text</a> and <a href="https://api.flutter.dev/flutter/widgets/RichText-class.html">RichText</a> via their <a href="https://api.flutter.dev/flutter/widgets/Text/overflow.html">Text.overflow</a> and <a href="https://api.flutter.dev/flutter/widgets/RichText/overflow.html">RichText.overflow</a> properties respectively.
  - Example : 
  ```
  Text(
      '$title',
      maxLines: 2,
  --> overflow : TextOverflow.ellipsis,
      style: const TextStyle(
      fontWeight: FontWeight.bold,
      ),
  ),
  ```
  



