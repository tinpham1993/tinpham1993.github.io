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
<title>Minna no Nihongo 1 - Kanji</title>
<style>
table, th, td {
  border: 1px solid black;  
}

th, td {
  padding: 5px;
  text-align: left;
}
.collapsible {
  background-color: #777;
  color: white;
  cursor: pointer;
  padding: 18px;
  width: 100%;
  border: 2px solid white;
  text-align: left;
  outline: none;
  font-size: 15px;
}

.active, .collapsible:hover {
  background-color: #555;
}

.content {
  padding: 0 0px;
  display: none;
  overflow: hidden;
  background-color: #ffffff;
}
</style>
</head>
<body>

<p>(Click vào Hán tự để xem cách nhớ - tham khảo https://j-dict.com/)</p>
<p>(Click vào ví dụ để biết cách đọc)</p>

<button type="button" class="collapsible">Bài 1</button>
<table id="table-01" style="width:100%" class="content">
  <tr>
    <th style="font-size:20px;width:20%;height:70px;" onclick = "flip_image('table-01',0,0,'日 - NHẬT', 'http://storage.dekiru.vn/Data/2018/03/01/kanji5017-636554925070407655.jpg')">日 - NHẬT</th>
    <td style="width:30%" onclick="flip_words('table-01',0, 1, '日曜日', 'にちようび')">日曜日</td>
    <th rowspan="6"></th>
    <th style="font-size:20px;width:20%;" onclick = "flip_image('table-01',0,3,'金 - KIM', 'http://storage.dekiru.vn/Data/2018/03/01/kanji5022-636554925072048139.jpg')">金 - KIM</th>
    <td style="width:30%" onclick="flip_words('table-01',0, 4, '金曜日', 'きんようび')">金曜日</td>
  </tr>
  <tr>
    <th style="font-size:20px;height:70px;" onclick = "flip_image('table-01',1,0,'月 - NGUYỆT', 'http://storage.dekiru.vn/Data/2018/03/01/kanji5018-636554925070867760.jpg')">月 - NGUYỆT</th>
    <td onclick="flip_words('table-01',1, 1, '月曜日', 'げつようび')">月曜日</td>
    <th style="font-size:20px;" onclick = "flip_image('table-01',1,2,'土 - THỔ', 'http://storage.dekiru.vn/Data/2018/03/01/kanji5023-636554925077219574.jpg')">土 - THỔ</th>
    <td onclick="flip_words('table-01',1, 3, '土曜日', 'どようび')">土曜日</td>
  </tr>
  <tr>
    <th rowspan="2" style="font-size:20px;height:70px;" onclick = "flip_image('table-01',2,0,'火 - HỎA', 'http://storage.dekiru.vn/Data/2018/03/01/kanji5019-636554925081430792.jpg')">火 - HỎA</th>
    <td rowspan="2" onclick="flip_words('table-01',2, 1, '火曜日', 'かようび')">火曜日</td>
    <th rowspan="2" style="font-size:20px;" onclick = "flip_image('table-01',2,2,'山 - SƠN', 'http://storage.dekiru.vn/Data/2018/03/01/kanji5145-636554925135217249.jpg')">山 - SƠN</th>
    <td style="width:20%" onclick="flip_words('table-01',2, 3, '山田さん', 'やまださん')">山田さん</td>
  </tr>
  <tr>
    <td onclick="flip_words('table-01',3, 0, '山川さん', 'やまがわさん')">山川さん</td>
  </tr>
  <tr>
    <th style="font-size:20px;height:70px;" onclick = "flip_image('table-01',4,0,'水 - THỦY', 'http://storage.dekiru.vn/Data/2018/03/01/kanji5020-636554925071557962.jpg')">水 - THỦY</th>
    <td onclick="flip_words('table-01',4, 1, '水曜日', 'すいようび')">水曜日</td>
    <th style="font-size:20px;" onclick = "flip_image('table-01',4,2,'川 - XUYÊN', 'http://storage.dekiru.vn/Data/2018/03/01/kanji5146-636554925135426251.jpg')">川 - XUYÊN</th>
    <td onclick="flip_words('table-01',4, 3, '中川さん', 'なかがわさん')">中川さん</td>
  </tr>
  <tr>
    <th style="font-size:20px;height:70px;" onclick = "flip_image('table-01',5,0,'木 - MỘC', 'http://storage.dekiru.vn/Data/2018/03/01/kanji5021-636554925071748075.jpg')">木 - MỘC</th>
    <td onclick="flip_words('table-01',5, 1, '木曜日', 'もくようび')">木曜日</td>
    <th style="font-size:20px;" onclick = "flip_image('table-01',5,2,'田 - ĐIỀN', 'http://storage.dekiru.vn/Data/2018/03/01/kanji5049-636554925084131573.jpg')">田 - ĐIỀN</th>
    <td onclick="flip_words('table-01',5, 3, '田中さん', 'たなかさん')">田中さん</td>
  </tr>
</table>

<button type="button" class="collapsible">Bài 2</button>
<table id="table-02" style="width:100%" class="content">
  <tr>
    <th style="font-size:20px;width:20%;height:70px;" rowspan = "2" onclick = "flip_image('table-02',0,0,'一 - NHẤT', 'http://storage.dekiru.vn/Data/2018/03/01/kanji5001-636554925065666296.jpg')">一 - NHẤT</th>
    <td style="width:30%" onclick="flip_words('table-02',0, 1, '一月', 'いちがつ')">一月</td>
    <th rowspan="21"></th>
    <th style="font-size:20px;width:20%;" rowspan = "2" onclick = "flip_image('table-02',0,3,'八 - BÁT', 'http://storage.dekiru.vn/Data/2018/03/01/kanji5008-636554925066426515.jpg')">八 - BÁT</th>
    <td style="width:30%;" onclick="flip_words('table-02',0, 4, '八月', 'はちがつ')">八月</td>
  </tr>
  <tr>
      <td onclick="flip_words('table-02',1, 0, '一日', 'ついたち')">一日</td>
      <td onclick="flip_words('table-02',1, 1, '八日', 'ようか')">八日</td>
  </tr>
  <tr>
    <th style="font-size:20px;height:70px;" rowspan = "2" onclick = "flip_image('table-02',2,0,'二 - NHỊ', 'http://storage.dekiru.vn/Data/2018/03/01/kanji5002-636554925075979246.jpg')">二 - NHỊ</th>
    <td onclick="flip_words('table-02',2, 1, '二月', 'にがつ')">二月</td>
    <th style="font-size:20px;" rowspan = "2" onclick = "flip_image('table-02',2,2,'九 - CỬU', 'http://storage.dekiru.vn/Data/2018/03/01/kanji5009-636554925066696623.jpg')">九 - CỬU</th>
    <td onclick="flip_words('table-02',2, 3, '九月', 'くがつ')">九月</td>
  </tr>
  <tr>
      <td onclick="flip_words('table-02',3, 0, '二日', 'ふつか')">二日</td>
      <td onclick="flip_words('table-02',3, 1, '九日', 'ここのか')">九日</td>
  </tr>
  <tr>
    <th style="font-size:20px;height:70px;" rowspan = "2" onclick = "flip_image('table-02',4,0,'三 - TAM', 'http://storage.dekiru.vn/Data/2018/03/01/kanji5003-636554925065926356.jpg')">三 - TAM</th>
    <td onclick="flip_words('table-02',4, 1, '三月', 'さんがつ')">三月</td>
    <th style="font-size:20px;" rowspan = "2" onclick = "flip_image('table-02',4,2,'十 - THẬP', 'http://storage.dekiru.vn/Data/2018/03/01/kanji5010-636554925082050992.jpg')">十 - THẬP</th>
    <td onclick="flip_words('table-02',4, 3, '十月', 'じゅうがつ')">十月</td>
  </tr>
  <tr>
      <td onclick="flip_words('table-02',5, 0, '三日', 'みっか')">三日</td>
      <td onclick="flip_words('table-02',5, 1, '十日', 'とおか')">十日</td>
  </tr>
  <tr>
    <th style="font-size:20px;height:70px;" rowspan = "3" onclick = "flip_image('table-02',6,0,'四 - TỨ', 'http://storage.dekiru.vn/Data/2018/03/01/kanji5004-636554925071267862.jpg')">四 - TỨ</th>
    <td onclick="flip_words('table-02',6, 1, '四月', 'しがつ')">四月</td>
    <th style="font-size:20px;" rowspan = "3" onclick = "flip_image('table-02',6,2,'百 - BÁCH', 'http://storage.dekiru.vn/Data/2018/03/01/kanji5011-636554925067226711.jpg')">百 - BÁCH</th>
    <td onclick="flip_words('table-02',6, 3, '三百', 'さんびゃく')">三百</td>
  </tr>
  <tr>
      <td rowspan = "2" onclick="flip_words('table-02',7, 0, '四日', 'よっか')">四日</td>
      <td onclick="flip_words('table-02',7, 1, '六百', 'ろっぴゃく')">六百</td>
  </tr>
  <tr>
      <td onclick="flip_words('table-02',8, 0, '八百', 'はっぴゃく')">八百</td>
  </tr>
  <tr>
    <th style="font-size:20px;height:70px;" rowspan = "2" onclick = "flip_image('table-02',9,0,'五 - NGŨ', 'http://storage.dekiru.vn/Data/2018/03/01/kanji5005-636554925091283637.jpg')">五 - NGŨ</th>
    <td onclick="flip_words('table-02',9, 1, '五月', 'ごがつ')">五月</td>
    <th style="font-size:20px;" rowspan = "2" onclick = "flip_image('table-02',9,2,'千 - THIÊN', 'http://storage.dekiru.vn/Data/2018/03/01/kanji5012-636554925067806996.jpg')">千 - THIÊN</th>
    <td onclick="flip_words('table-02',9, 3, '三千', 'さんぜん')">三千</td>
  </tr>
  <tr>
      <td onclick="flip_words('table-02',10, 0, '五日', 'いつか')">五日</td>
      <td onclick="flip_words('table-02',10, 1, '八千', 'はっせん')">八千</td>
  </tr>
  <tr>
    <th style="font-size:20px;height:70px;" rowspan = "2" onclick = "flip_image('table-02',11,0,'六 - LỤC', 'http://storage.dekiru.vn/Data/2018/03/01/kanji5006-636554925071097819.jpg')">六 - LỤC</th>
    <td onclick="flip_words('table-02',11, 1, '六月', 'ろくがつ')">六月</td>
    <th style="font-size:20px;" rowspan = "2" onclick = "flip_image('table-02',11,2,'万 - VẠN', 'http://storage.dekiru.vn/Data/2018/03/01/kanji5013-636554925068387066.jpg')">万 - VẠN</th>
    <td onclick="flip_words('table-02',11, 3, '一万', 'いちまん')">一万</td>
  </tr>
  <tr>
      <td onclick="flip_words('table-02',12, 0, '六日', 'むいか')">六日</td>
      <td onclick="flip_words('table-02',12, 1, '五十万', 'ごじゅうまん')">五十万</td>
  </tr>
  <tr>
    <th style="font-size:20px;height:70px;" rowspan = "2" onclick = "flip_image('table-02',13,0,'七 - THẤT', 'http://storage.dekiru.vn/Data/2018/03/01/kanji5007-636554925066226443.jpg')">七 - THẤT</th>
    <td onclick="flip_words('table-02',13, 1, '七月', 'しちがつ')">七月</td>
    <th style="font-size:20px;" rowspan = "2" onclick = "flip_image('table-02',13,2,'円 - VIÊN', 'http://storage.dekiru.vn/Data/2018/03/01/kanji5014-636554925068957211.jpg')">円 - VIÊN</th>
    <td onclick="flip_words('table-02',13, 3, '千円', 'せんえん')">千円</td>
  </tr>
  <tr>
      <td onclick="flip_words('table-02',14, 0, '七日', 'なのか')">七日</td>
      <td onclick="flip_words('table-02',14, 1, '百万円', 'ひゃくまんえん')">百万円</td>
  </tr>
</table>

<script>
function flip_words(table_name, pos_row, pos_col, word1, word2) {
    var current_row = document.getElementById(table_name).rows[pos_row].cells;
    if (current_row[pos_col].innerHTML == word1){
        current_row[pos_col].innerHTML = word2;
    }
    else
    {
        current_row[pos_col].innerHTML = word1;
    }
}
function flip_image(table_name, pos_row, pos_col, word1, img_link) {
    var current_row = document.getElementById(table_name).rows[pos_row].cells;
    var img = '<img src="' + img_link + '" width="100" height="50">';
    if (current_row[pos_col].innerHTML == word1){
        current_row[pos_col].innerHTML = img;
    }
    else
    {
        current_row[pos_col].innerHTML = word1;
    }
}
</script>

<script>
var coll = document.getElementsByClassName("collapsible");
var i;

for (i = 0; i < coll.length; i++) {
  coll[i].addEventListener("click", function() {
    this.classList.toggle("active");
    var content = this.nextElementSibling;
    if (content.style.display === "block") {
      content.style.display = "none";
    } else {
      content.style.display = "block";
    }
  });
}
</script>
</body>
</html>
