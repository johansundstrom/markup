# Sidbeskrivnings språk

---

<img class="myColor" data-src="assets/images/postscript-logo.png">

* Skapades 1982 som ett *sidbeskrivningsspråk*
* Språk samt *Interpreter* (tolk)
* Uppmärkning och presentation

---

<img class="myColor" data-src="assets/images/postscript-logo.png">

<pre><code class="language-html" data-trim><script type="text/template">
%!PS
/Courier findfont 
  20 scalefont 
setfont 
  72 500 moveto 
  (Hello world!) show 
showpage 
</script></code></pre>

---

<img class="myColor" width="150" data-src="assets/images/Acrbat-reader-logo.png">

* Adobe Acrobat skapades 1993
* Portable Document Format
* En delmängd av PostScript
* Öppen standard

---

<img class="myColor" width="150" data-src="assets/images/Acrbat-reader-logo.png">

```
%PDF−1.4
...
5 0 obj
  << /Length 73 >>
stream
  BT
    /F1 24 Tf
    100 100 Td
    (Hello World) Tj
  ET
endstream
endobj
...
%EOF
```

---

(c) Johan Sundström
