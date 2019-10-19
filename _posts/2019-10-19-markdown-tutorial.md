---
layout: post
title:  "Làm quen với ngôn ngữ Markdown"
date:   2019-10-19 02:30:13 +0800
categories: Developer
tags: Dev Web Markdown
---

**1. Giới thiệu (Introduction):**  
Sử dụng Markdown là một cách để viết nội dung cho trang web. Nó được viết bằng cách sử dụng "plaintext", một kiểu viết rất gần gũi với cách thức chúng ta đọc và viết. Plaintext chỉ sử dụng các ký tự thông thường và một số ký tự đặc biệt như asterisks (*) và backticks (`).

Không giống như các ứng dụng xử lý văn bản khác, nội dung viết bằng Markdown có thể dễ dàng được đọc bởi máy tính, điện thoại và con người. Do đó, nó nhanh chóng trở thành chuẩn viết văn bản phổ biến. Các website như GitHub và reddit cũng đã sử dụng Markdown cho mục comments của họ.

Định dạng văn bản trong Markdown rất đơn giản, không cần phải thực hiện các thao tác như đổi font chữ, màu chữ hay kích thước. Tất cả những gì bạn cần nắm chỉ là cách thức hiển thị nội dung văn bản như in đậm chữ, tạo tiêu đề và sắp xếp danh sách.

Nếu bạn có 10 phút, bạn có thể học được Markdown!

Trong mỗi bài học, bạn sẽ được giới thiệu các khái niệm riêng lẻ trong Markdown.

Bạn có thể sử dụng trang web [https://dillinger.io/](https://dillinger.io/) để kiểm tra thử kết quả hiển thị của mình (khi viết bài này mình cũng sử dụng  nó :v).

**2. In nghiêng và in đậm (Italics and Bold)**  
Để in nghiêng cụm từ: kẹp cụm từ đó giữa các dấu gạch dưới (_) (underscore). VD: ```_chữ in nghiêng_```

Để in đậm cụm từ: kẹp cụm từ giữa các cụm 2 dấu sao (**) (two asterisks). VD: ```**chữ in đậm**```

Có thể kết hợp vừa in nghiêng, vừa in đậm cụm từ. VD: **_\*\*\_This is a\__ legendary\*\***

**3. Tiêu đề (Headers)**  
Headers được sử dụng thường xuyên trên websites, các bài viết tạp chí, thông báo... nhằm mục đích thu hút sự chú ý.  
Có 6 loại headers trong Markdown với cỡ chữ giảm dần.

Để tạo headers trong Markdown:  bắt đầu dòng với các dấu thăng (#) (hash mark). 1 dấu # tức là level 1 - cỡ chữ lớn nhất, 6 dấu thăng tức là level 6, cỡ chữ bé nhất.  
VD:

    #Header 1 - biggest size
    ###### Header 6 - smallest size

Các từ trong Headers cũng có thể in nghiêng và in đậm bằng cách như đã nói ở mục 2.

**4. Liên kết (links)**  
Có 2 loại liên kết khác nhau trong Markdown nhưng cách thực hiện của chúng giống nhau.  
* **Loại thứ 1: _inline link_.** Để tạo _inline link_, link text được đặt trong dấu ngoặc vuông ( **[ ]** ) (brackets) và link được đặt trong dấu ngoặc tròn ( **()** ) (parenthesis).  
VD: ```[Visit GitHub!](www.github.com)```

    Các từ trong Liên kết cũng có thể in nghiêng và in đậm. Headers cũng có thể là 1 liên kết. 
    VD1: ```[You're **really, really** going to want to see this.](www.github.com)```  
    VD2: ```###[The Latest News from the BBC](www.github.com)```

* **Loại thứ 2: _reference link_.** Loại đường dẫn này không sử dụng trực tiếp đường dẫn như inline link mà sẽ tham chiếu đến một nơi khác trong văn bản, tại đó sẽ có đường dẫn cụ thể. Việc này giúp sử dụng lại một đường dẫn nhiều lần, từ đó sẽ dễ dàng hơn cho việc cập nhật lại đường dẫn. Đọc ví dụ sau để hiểu rõ hơn.  
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
Cú pháp để tạo hình ảnh trong Markdown tương tự như tạo liên kết, hình ảnh trong Markdown cũng có 2 loại tương tự như đối với liên kết. Sự khác biệt giữa hình ảnh và liên kết là hình ảnh được bắt đầu bằng dấu chấm thang (**!**) (exclamation point).  
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
Để tạo ra một đoạn trích dẫn trong Markdown, đặt dấu lớn hơn (**>**) ("greater than" caret) ở đầu đoạn đó.  
VD:
```
    I like this Benjamin's sentense:
    >"By failling to prepare, you are preparing to fail."
```

Nếu như đoạn trích dẫn gồm nhiêu đoạn nhỏ thì ta cũng sử dụng dấu (>) cho cả các dòng trống.  
VD:
```
    > Ngày xửa ngày xưa...
    >
    > Rồi sao nữa nhỉ???
    >
    > Quên bà nó rồi...
```
Trong trích dẫn vẫn có thể in đậm và in nghiêng ký tự, chèn hình ảnh và liên kết như đã nói ở các phần trước.

**7. Danh sách (Lists)**  
Có 2 loại danh sách trong Markdown: **không có thứ tự** (unordered/lists with bullet points) và **có thứ tự** (ordered/lists with numbers).  
* **Tạo danh sách không có thứ tự:** bắt đầu mỗi mục của danh sách với dấu sao (*) (asterisk).  
VD:  
```
         * Milk
         * Eggs
         * Salmon
         * Butter
```

* **Tạo danh sách có thứ tự:** bắt đầu mỗi danh mục bằng số đếm.  
VD:  
 ```
 1. Xoay bánh
 2. Chấm sữa
 3. Liếm kem
 4. Nhoàm nhoàm
 ```

Mỗi mục trong danh sách cũng có thể được in đậm, in nghiêng hoặc chèn liên kết
Trong trường hợp danh sách lồng trong danh sách, dấu sao của danh sách con cần phải nằm **sâu hơn một dấu cách** (one space more) (nếu 1 không được thì thêm vào miễn được thì thôi :v) so với danh mục trước đó.  
VD:  
```
* List 1
  * Sub-list 1
    * Item 1
    * Item 2
    * Item 3
      * item 3.1
      * item 3.2
 * Sub-list 2
 * ...
 ```
**8. Đoạn văn (Paragraphs)**  
Trong Markdown, nếu xuống dòng một lần (sử dụng Enter 1 lần) thì kết quả hiển thị các dòng vẫn sẽ nằm trên cùng một dòng. Tuy nhiên, nếu xuống dòng 2 lần trong Markdown ( sử dụng Enter 2 lần) thì kết quả hiển thị các dòng sẽ bị ngăn các bởi 1 dòng trống. Đây chính là **_hard break_ (các dòng cách nhau bởi 1 dòng trống)**.  

Nếu muốn ở kết quả hiển thị, **các dòng không bị ngăn cách bởi các dòng trống (_soft break_)** thì ở cuối mỗi dòng trong Markdown, ta sử dụng 2 dấu cách trước khi xuống dòng. Vì dấu cách không thể nhìn thấy được nên trong ví dụ mình sử dụng <space> thay cho dấu cách.

VD:  
```
Con cá đối nằm trên cối đá<space><space>
Con mèo cái nằm trên mái kèo<space><space>
```
    
**9. Bổ sung một số cú pháp hay thường dùng:**  
* **Chú thích:** sử dụng ``` kẹp đoạn văn cần chú thích hoặc câu cần chú thích.  
    * VD1:  
    ```
        \```
            Dòng chú thích 1
            ...
            Dòng dòng chú thích n
        \```
    ```

    * VD2: **\`\`\` Lời chú thích \`\`\`**

* **Cú pháp highlight**: sử dụng để trích dẫn code trong ngôn ngữ khác  
    * VD:  
    ```
       \{\% highlight python linenos \%}
       def print_hi(name):
         print("Hi, {}".format(name))

       print_hi('Tom')
       # prints 'Hi, Tom' to STDOUT.
       \{\% endhighlight \%}
    ```


**Links tham khảo:**  
https://www.markdowntutorial.com/  
https://namnguyen.gitbooks.io/hoc-su-dung-markdown/content/index.html  
https://shawnteoh.github.io/matjek/2017/03/24/syntax-test
