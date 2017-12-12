---
layout: default
---
# [](#header-1)Cem GÖKSU Kişisel Not Defterim
# [](#header-1)Internal CSS nedir, nasıl kullanılır? 

This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

Bir önceki notum Inline CSS hakkındaydı Internal CSS .”html” dosyasındaki tüm etiketleri içerir. bir index.html dosyamız olduğunu varsayalım. Index.html dosyamızın kodlama bölümüne geçelim. (Kodlama bölümü için brackets programını indirin ve html dosyanızı brackets ile açın.) http://brackets.io/ adresine giderek Brackets’ı indirebilirsiniz.

 

 ```
 
<html>
<title>Internal Css</title>
<style type=”text/css”>
p {
color:blue;
font-size: 10px;
text-align: left;
}
h1{
color:green;
font-size: 150%;
}
</style>
</head>
<body>
<h1> h1 etiketi CSS </h1>
<p> p etiketi CSS </p>
<p> p etiketi CSS </p>
<p style=”color:blue;font-size:10px;”> p etiketi CSS </p> (Bu kod satırında hem internal hemde inline CSS var index.html içinde bu satırı denediğinizde inline css in internal CSS’i ezdiğini göreceksiniz)
<p> p etiketi CSS </p>
</body>
</html>
// 
```

 

Inline CSS’te istediğimiz değerleri p etiketi içine yazıyorduk ama Internal CSS’te head etiketleri içine <style type=”text/css”> style etiketi açarak css değerlerimizi girebiliyoruz.Bu şekilde her etiket için ayrı ayrı CSS kodu yazmamış oluyoruz Ayrıca yine değineceğim Internal CSS yazsak bile örnek olarak p etiketi için her satırda Internal değerler geçerlidir. Ancak inline olarak yazdığımız değer ne olursa olsun her zaman Internal CSS değerlerimizi ezer.
### [](#header-3)Header 3
