---
title: Contact
date: 2024-10-01T16:01:23+08:00
draft: false
tags: 
categories: 
toc: false
show_social: "false"
---
Contact me


```js
function helloWorld () {
  alert("Hello, World!")
}
```

<!--more-->

```java
public class HelloWorld {
  public static void main(String[] args) {
    System.out.println("Hello, World!");
  }
}
```

```kotlin
package hello

fun main(args: Array<String>) {
  println("Hello World!")
}
```

```c
#include <stdio.h>

/* Hello */
int main(void){
  printf("Hello, World!");
  return 0;
}
```

```cpp
// 'Hello World!' program 
 
#include <iostream>
 
int main(){
  std::cout << "Hello World!" << std::endl;
  return 0;
}
```

```cs
using System;
class HelloWorld{
  public static void Main(){ 
    System.Console.WriteLine("Hello, World!");
  }
}
```

```html
<html>
<body>
  Hello, World!
</body>
</html>
```

```go
package main
import fmt "fmt"

func main() 
{
   fmt.Printf("Hello, World!\n");
}
```

```scala
object HelloWorld with Application {
  Console.println("Hello, World!");
}
```

```php
<?php
  echo 'Hello, World!';
?>
```

```python
print("Hello, World!") 
```

```clojure
(defn hello-world
  "A function print 'Hello world'."
  []
  (prn "Hello world"))
```

```go-html-template
<!DOCTYPE html>
<html>
<head>
  <title>{{ .Title }}</title>
</head>
<body>
  <h1>{{ .Title }}</h1>
  {{ .Content }}
</body>
</html>
```

```go-html-template
{{ partial "header.html" . }}

  <h1>posts</h1>
  {{ range first 10 .Data.Pages }}
    {{ if eq .Type "post"}}
      <h2><a href="{{ .Permalink }}">{{ .Title }}</a></h2>
    {{ end }}
  {{ end }}

  <h1>pages</h1>
  {{ range .Data.Pages }}
    {{ if or (eq .Type "page") (eq .Type "about") }}
      <h2><a href="{{ .Permalink }}">{{ .Type }} - {{ .Title }} - {{ .RelPermalink }}</a></h2>
    {{ end }}
  {{ end }}

{{ partial "footer.html" . }}
```

---

Detect the language

```
package hello

fun main(args: Array<String>) {
  println("Hello World!")
}
```

```
<?php
  echo 'Hello, World!';
?>
```

---

Here is very long code block:

```plaintext
var a = 1;
var b = 2;
var c = 3;
var d = 4;
var e = 5;
var f = 6;
var g = 7;
var h = 8;
var i = 9;
var j = 10;
var str = 'this is a very long long long long long long long long long long long long long long long long string';
var k = 11;
var l = 12;
var m = 13;
var n = 14;
var o = 15;
var p = 16;
var q = 17;
var r = 18;
var s = 19;
var t = 20;
```

---

By `{{</* highlight go-html-template "linenos=table,hl_lines=1 3-7,linenostart=199" */>}}..{{</* / highlight */>}}`

{{< highlight go-html-template "linenos=table,hl_lines=1 3-7,linenostart=199" >}}
<section id="main">
  <div>
   <h1 id="title">{{ .Title }}</h1>
    {{ range .Data.Pages }}
        {{ .Render "summary"}}
    {{ end }}
  </div>
</section>
{{< / highlight >}}

This is the inline code: `footer` and `header`.

Now this is a example site running on `hugo server`.