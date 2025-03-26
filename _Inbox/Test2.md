
# Templater
// Date now
<% tp.date.now() %>
// Date now with format
<% tp.date.now("Do MMMM YYYY") %>
// Last week
<% tp.date.now("YYYY-MM-DD", -7) %>
// Next week
<% tp.date.now("YYYY-MM-DD", 7) %>
// Last month
<% tp.date.now("YYYY-MM-DD", "P-1M") %>
// Next year
<% tp.date.now("YYYY-MM-DD", "P1Y") %>
// File's title date + 1 day (tomorrow)
<% tp.date.now("YYYY-MM-DD", 1, tp.file.title, "YYYY-MM-DD") %>
// File's title date - 1 day (yesterday)
<% tp.date.now("YYYY-MM-DD", -1, tp.file.title, "YYYY-MM-DD") %>


---
<% tp.date.now("YYYY-MM-DD", -1) %>
<% tp.date.now("YYYY-MM-DD", 1) %>
---
# Meta Bind Buttons

```meta-bind-button
label: Test
icon: pencil
style: primary
class: my-colored-button
cssStyle: ""
backgroundImage: ""
tooltip: ""
id: ""
hidden: false
actions:
  - type: command
    command: app:open-settings
```

```css
.mb-button.my-colored-button > button {
  background-color: lightblue;
  color: darkblue;
  border: 1px solid blue;
}
```


```meta-bind-button
style: primary
label: Open Meta Bind FAQ
class: green-button
action:
  type: command
  command: obsidian-meta-bind-plugin:open-faq
```


```css
.mb-button.green-button > button {
	background-color: #ACFF9F;
	color: black;
	border: 1px solid #DFFF00;
}
```

`BUTTON[2obf]`