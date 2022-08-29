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

<pre><code class="language-html" data-trim><script type="text/template">
<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE exempel [
    <!ENTITY copy "&#169;">
    <!ENTITY company "&#197;&#196;&#214;-Company">
    <!ENTITY &copyright-notice "&copy; 2022, &company;">
]>
<exempel>
  &copyright-notice;
</exempel>
</script></code></pre>

---

(c) Johan Sundström