[[<% tp.date.now("YYYY-MM-DD", -1) %>|<<]] | [[<% tp.date.now("YYYY-MM-DD", 1) %>|>>]]

---

```meta-bind-button
label: Launcher
icon: rocket
style: default
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: ""
id: launcher
hidden: false
actions:
  - type: command
    command: homepage:open-homepage

```

>[!Today's Links]
> -

>[!Files Created Today]
>```dataview
>Table type as "Type"
>Where file.cday = date("<% tp.date.now("YYYY-MM-DD") %>") and file.name != this.file.name
>Sort file.ctime desc
>```
