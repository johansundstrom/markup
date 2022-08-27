# Postscript - PDF

---

<img class="myColor" data-src="assets/images/postscript-logo.png">

* Skapades 1982 som ett *sidbeskrivningsspråk*
* Språk samt *Interpreter* (översättare)

---

<img class="myColor" data-src="assets/images/postscript-logo.png">

```
%!PS
/Courier findfont 
  20 scalefont 
setfont 
  72 500 moveto 
  (Hello world!) show 
showpage 
```

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

## Måttenheter

<img class="myColor" data-src="assets/images/ruler.png">

### Point

1 Point (pt) = 1/72 inch (~0.3mm)

### Pica

1 Pica (pc) = 12 points

---

(c) Johan Sundström
