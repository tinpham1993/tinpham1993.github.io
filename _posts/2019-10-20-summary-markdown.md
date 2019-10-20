---
layout: post
title:  "Sử dụng ngôn ngữ Markdown - Tổng hợp"
date:   2019-10-20 02:30:13 +0800
categories: Developer
tags: Dev Web Markdown
comments: 5
---

**1. Markdown online:**  
[https://dillinger.io/](https://dillinger.io/).

**2. In nghiêng và in đậm (Italics and Bold)**  
In nghiêng: kẹp cụm từ giữa các dấu gạch dưới (_) (underscore). VD: ```_chữ in nghiêng_```

In đậm: kẹp cụm từ giữa các cụm 2 dấu sao (**) (two asterisks). VD: ```**chữ in đậm**```

**3. Tiêu đề (Headers)**  
Tạo headers: bắt đầu dòng với các dấu thăng (#) (hash mark). Có 6 level headers: 1 dấu # tức là level 1 - cỡ chữ lớn nhất, 6 dấu thăng tức là level 6, cỡ chữ bé nhất.  
VD:

    #Header 1 - biggest size
    ###### Header 6 - smallest size

**4. Liên kết (links)**  
* **Loại thứ 1: _inline link_.** Link text được đặt trong dấu ngoặc vuông ( **[ ]** ) (brackets) và link được đặt trong dấu ngoặc tròn ( **()** ) (parenthesis).  
VD: ```[Visit GitHub!](www.github.com)```

* **Loại thứ 2: _reference link_.** Không sử dụng trực tiếp đường dẫn như inline link mà tham chiếu đến đường dẫn cụ thể ở một nơi khác trong văn bản, giúp sử dụng lại và cập nhật đường dễ dàng.  
VD:  
```
    Đây là đường dẫn đến [nơi làm việc][trang github].
    Đây là đường dẫn đến [nơi giải trí][trang youtube].
    Giờ hãy đến [đường dẫn thứ nhất][trang github].
    ...
    [trang github]: www.github.com
    [trang youtube]: www.youtube.com
```
_Reference link_ trong ví dụ trên chính là **[trang github]** và **[trang youtube]**.

**5. Hình ảnh (Images)**  
Cú pháp để tạo hình ảnh tương tự như tạo liên kết. Tuy nhiên có 1 điểm khác biệt là hình ảnh được bắt đầu bằng dấu chấm thang (**!**) (exclamation point).  
   * **Loại thứ 1: _inline image link_.**  
   VD: ```![Benjamin Bannekat](https://octodex.github.com/images/bannekat.png).```

   * **Loại thứ 2: _reference image_.**  
   VD:
   ```
       ![The founding father][Father]
       ...
       [Father]: http://octodex.github.com/images/founding-father.jpg
   ```

**6. Trích dẫn (Blockquotes)**  
Tạo ra một đoạn trích dẫn: đặt dấu lớn hơn (**>**) ("greater than" caret) ở đầu đoạn. Nếu như đoạn trích dẫn gồm nhiêu đoạn nhỏ thì ta cũng sử dụng dấu (>) cho cả các dòng trống.  
VD:
```
    I like this Benjamin's sentense:
    >"By failling to prepare, you are preparing to fail."
```

**7. Danh sách (Lists)**  
* **Tạo danh sách không có thứ tự:** bắt đầu mỗi mục của danh sách với dấu sao (*) (asterisk).  
VD:  
```
     * Milk
       * Chocolate Milk
       * Plain Milk
     * Eggs
     * Salmon
```

* **Tạo danh sách có thứ tự:** bắt đầu mỗi danh mục bằng số đếm.  
VD:  
 ```
 1. Xoay bánh
 2. Chấm sữa
 3. Liếm kem
   * Cũng tạm được
   * Ngon đấy
 ```
 
**8. Đoạn văn (Paragraphs)**  
**_Hard break_ (các dòng cách nhau bởi 1 dòng trống)**: trong Markdown xuống dòng 2 lần (Enter 2 lần)

**_Soft break_ (các dòng không bị ngăn cách bởi các dòng trống)**: thì ở cuối mỗi dòng trong Markdown, ta sử dụng 2 dấu cách trước khi xuống dòng.  
VD:  
```
Con cá đối nằm trên cối đá<space><space>
Con mèo cái nằm trên mái kèo<space><space>
```
    
**9. Chú thích:**  
Sử dụng ``` kẹp đoạn văn cần chú thích hoặc câu cần chú thích.  
VD:  
```
    \```
        Dòng chú thích 1
        Dòng chú thích 2
    \```
```

VD: **\`\`\` Lời chú thích \`\`\`**

Cũng có lúc sử dụng dấu tab trước mỗi dòng để thể hiển chú thích.
VD:
```
<tab> Dòng chú thích 1
<tab> Dòng chú thích 2
```

**10. Cú pháp highlight**:  
Sử dụng để trích dẫn code trong ngôn ngữ khác như ruby, python, C...  
VD: Đối với python và có đánh số dòng, bắt đầu với **{% highlight python linenos %}** và kết thúc bởi **{% endhighlight %}**  

  ```
     \{\% highlight python linenos \%}
     def print_hi(name):
       print("Hi, {}".format(name))

     print_hi('Tom')
     # prints 'Hi, Tom' to STDOUT.
     \{\% endhighlight \%}
  ```
  
  **11. Có cái gì mới sẽ thêm vào sau...**
