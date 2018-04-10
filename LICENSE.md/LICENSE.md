# BulbTask
+Switch  a bulb on and off using javascript

+<!DOCTYPE html>
+<html lang="en" dir="ltr">
+  <head>
+    <meta charset="utf-8">
+    <title> On/Off using Javascript</title>
+  </head>
+  <body>
+
+
+    <h1> Simple image changing program</h1>
+    <br>
+    <p>
+         <img id="image1" src="off.png" alt=" original image" onmouseover="changeImage(this)" onmouseout="restImage(this)">
+
+     </p>
+
+     <p> Bring the cursor on the image</p>
+
+  <script type="text/javascript" src="index.js">
+
+  </script>
+
+
+  </body>
+</html>

+function changeImage() {
+  document.getElementById('image1').src="off.png";
+
+
+}
+
+function restImage() {
+
+  document.getElementById('image1').src="on.png";
+
+}

