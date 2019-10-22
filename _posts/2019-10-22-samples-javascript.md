---
layout: post
title:  "Một số ví dụ về Javascript"
date:   2019-10-22 02:30:13 +0800
categories: Developer
tags: Javascript Web
comments: 5
---
Ở bài viết này mình sẽ đưa ra một số ví dụ về Javascript dùng để tham khảo.

**1. Thay đổi chữ khi click chuột vào:**

Lợi ích: có thể sử dụng như một dạng flashcard hỗ trợ cho việc học từ vựng.

{% highlight html linenos %}
<p id="demo" onclick="myFunction('đồ ăn', 'tabemono')">đồ ăn</p>

<script>
function myFunction(word1, word2) {
  var text;
  if (document.getElementById("demo").innerHTML == word1){
    document.getElementById("demo").innerHTML = word2;
  }
  else
  {
    document.getElementById("demo").innerHTML = word1;
  }
}
</script>

</body>
</html>
{% endhighlight %}
