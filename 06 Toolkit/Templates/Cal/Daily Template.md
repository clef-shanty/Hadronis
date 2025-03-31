[[<% tp.date.now("YYYY-MM-DD", -1) %>|<<]] | [[<% tp.date.now("YYYY-MM-DD", 1) %>|>>]]

---

`BUTTON[launchpad]` | `BUTTON[proampac]`

>[!Today's Links]
 -

---

>[!Files Created Today]
>```dataview
>Table type as "Type"
>Where file.cday = date("<% tp.date.now("YYYY-MM-DD") %>") and file.name != this.file.name
>Sort file.ctime desc
>```
