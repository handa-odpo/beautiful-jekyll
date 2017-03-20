---
layout: post
title: 記事投稿の確認
subtitle: jekyllとマークダウンの記法のメモ
bigimg: /img/path.jpg
image: /img/hello_world.jpeg
tags: [メモ]
---

# 投稿の種類

投稿できる記事の種類は4種類

* 投稿
* ページ
* 最低限の情報
* HTML

# 見出しの種類

~~~
# 見出し1
## 見出し2
### 見出し3
#### 見出し4
##### 見出し5
###### 見出し6
~~~

# 見出し1
## 見出し2
### 見出し3
#### 見出し4
##### 見出し5
###### 見出し6

# 文字の装飾

~~~
1 *はんだオープンデータ活用推進研究会*
2 _はんだオープンデータ活用推進研究会_
3 **はんだオープンデータ活用推進研究会**
4 __はんだオープンデータ活用推進研究会__
5 ~~はんだオープンデータ活用推進研究会~~
~~~

1 *はんだオープンデータ活用推進研究会*

2 _はんだオープンデータ活用推進研究会_

3 **はんだオープンデータ活用推進研究会**

4 __はんだオープンデータ活用推進研究会__

5 ~~はんだオープンデータ活用推進研究会~~

# リスト

```
* リスト1
* リスト2
* リスト3
```

* リスト1
* リスト2
* リスト3

```
- リスト1
- リスト2
- リスト3
```

- リスト1
- リスト2
- リスト3

```
1. リスト1
1. リスト2
1. リスト3
```

1. リスト1
1. リスト2
1. リスト3

# リンク

```
[はんだオープンデータ活用推進研究会](https://handa-odpo.github.io)
```

[はんだオープンデータ活用推進研究会](https://handa-odpo.github.io)

# 表
``` 
| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |
```


| Number | Next number | Previous number |
| :------ |:--- | :--- |
| Five | Six | Four |
| Ten | Eleven | Nine |
| Seven | Eight | Six |
| Two | Three | One |

How about a yummy crepe?

![Crepe](http://s3-media3.fl.yelpcdn.com/bphoto/cQ1Yoa75m2yUFFbY2xwuqw/348s.jpg)

Here's a code chunk:

~~~
var foo = function(x) {
  return(x + 5);
}
foo(3)
~~~

And here is the same code with syntax highlighting:

```javascript
var foo = function(x) {
  return(x + 5);
}
foo(3)
```

And here is the same code yet again but with line numbers:

{% highlight javascript linenos %}
var foo = function(x) {
  return(x + 5);
}
foo(3)
{% endhighlight %}
