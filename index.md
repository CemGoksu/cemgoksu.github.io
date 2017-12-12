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

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### [](#header-4)Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### [](#header-5)Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### [](#header-6)Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![](https://assets-cdn.github.com/images/icons/emoji/octocat.png)

### Large image

![](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
