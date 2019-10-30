---
layout: post
title:  "Minna no Nihongo 1 - Kanji"
date:   2019-10-31 01:30:13 +0800
categories: Nihongo
tags: JLPT-N5 Kanji
comments: 5
---
<html>
<head>
<style>
table, th, td {
  border: 1px solid black;  
}
th, td {
  padding: 5px;
  text-align: left;    
}
</style>
</head>
<body>

<h2>Giáo trình Minna no Nihongo Shokyuu 1 - Kanji</h2>
<p>(Click vào ví dụ để biết cách đọc)</p>

<h3>Bài 1</h3>
<table id="table-01" style="width:100%">
  <tr>
    <th style="font-size:20px;">日 - NHẬT</th>
    <td style="width:50%" onclick="flip_words(0, 1, '日曜日', 'にちようび')">日曜日</td>
    <th rowspan="5"></th>
    <th  style="font-size:20px;">金 - KIM</th>
    <td colspan="2" style="width:50%" onclick="flip_words(0, 4, '金曜日', 'きんようび')">金曜日</td>
  </tr>
  <tr>
    <th style="font-size:20px;">月 - NGUYỆT</th>
    <td onclick="flip_words(1, 1, '月曜日', 'げつようび')">月曜日</td>
    <th style="font-size:20px;">土 - THỔ</th>
    <td colspan="2" onclick="flip_words(1, 3, '土曜日', 'どようび')">土曜日</td>
  </tr>
  <tr>
    <th style="font-size:20px;">火 - HỎA</th>
    <td onclick="flip_words(2, 1, '火曜日', 'かようび')">火曜日</td>
    <th style="font-size:20px;">山 - SƠN</th>
    <td style="width:25%" onclick="flip_words(2, 3, '山田さん', 'やまださん')">山田さん</td>
    <td onclick="flip_words(2, 4, '山川さん', 'やまがわさん')">山川さん</td>
  </tr>
  <tr>
    <th style="font-size:20px;">水 - THỦY</th>
    <td onclick="flip_words(3, 1, '水曜日', 'すいようび')">水曜日</td>
    <th style="font-size:20px;">川 - XUYÊN</th>
    <td colspan="2" onclick="flip_words(3, 3, '中川さん', 'なかがわさん')">中川さん</td>
  </tr>
  <tr>
    <th style="font-size:20px;">木 - MỘC</th>
    <td onclick="flip_words(4, 1, '木曜日', 'もくようび')">木曜日</td>
    <th style="font-size:20px;">田 - ĐIỀN</th>
    <td colspan="2" onclick="flip_words(4, 3, '田中さん', 'たなかさん')">田中さん</td>
  </tr>
</table>

<script>
function flip_words(pos_row, pos_col, word1, word2) {
    var current_row = document.getElementById("table-01").rows[pos_row].cells;
    if (current_row[pos_col].innerHTML == word1){
        current_row[pos_col].innerHTML = word2;
    }
    else
    {
        current_row[pos_col].innerHTML = word1;
    }
}
</script>
</body>
</html>
