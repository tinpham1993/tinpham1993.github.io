---
layout: post
title:  "Minna no Nihongo Overview"
date:   2019-10-19 01:30:13 +0800
categories: Nihongo
tags: JLPT-N5 JLPT-N4
comments: 5
---
"Minna no Nihongo" is neccessary book for new students in learning Japanese. After complete all 50 units in this book, the students can passed JLPT N4 and it is the basic level in learning Japanese.
<!DOCTYPE html>
<!-- Ref: https://www.w3schools.com/jsref/coll_table_rows.asp -->
<html>
<head>
<style>
table, td {
  border: 1px solid black;
}
</style>
</head>
<body>

<p>Click the button to change the content of the first table cell.</p>

<table id="myTable">
  <tr>
    <td>Row1 cell1</td>
    <td>Row1 cell2</td>
  </tr>
  <tr>
    <td>Row2 cell1</td>
    <td>Row2 cell2</td>
  </tr>
  <tr>
    <td>Row3 cell1</td>
    <td>Row3 cell2</td>
  </tr>
</table>
<br> 

<button onclick="myFunction()">Try it</button>

<script>
function myFunction() {
  var x = document.getElementById("myTable").rows[0].cells;
  x[0].innerHTML = "NEW CONTENT";
}
</script>

</body>
</html>
