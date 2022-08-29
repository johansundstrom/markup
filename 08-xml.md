# Utdraget Uppmärkningsspråk

---

* Extensible Markup Language
* Uppmärkning av data
* Delmängd av SGML
* Syfte: Beskriver strukturerad information
* Open standard

---

## Användningsområden

XML kan vara uppmärkning av

* Document
* Data
* Konfigurationslistor
* Transaktioner
* Formulärdata
* et cetera

---

## SGML

<pre><code data-trim><script type="text/template">
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE notis [
  <!ENTITY nbsp "&#xA0;">
  <!ENTITY copy "&#169;">
  <!ENTITY company "&#197;&#196;&#214;-Company">
  <!ENTITY right-notice "&copy;&nbsp;2022&nbsp;&company;">
]>
<notis>
  &right-notice;
</notis>
</script></code></pre>

---

(c) Johan Sundström