---
cssclasses:
  - dashboard
banner: "![[aed1.jpg]]"
banner_x: 0.5
banner_y: 0
tags:
  - home
---
![[aed1.jpg]]

`BUTTON[today]` | `BUTTON[proampac]` | `BUTTON[openObf]`

# Family
- 🏈 Sunday Game
	- [[Spicy-Sweet Buffalo Popcorn]]
	- [[Guest list]]
	- [Jalapeno Popper Wantons](https://www.allrecipes.com/recipe/166991/jalapeno-popper-wontons/)
- 👨‍👩‍👦 Objectives
	- [[Family Recipes]]
	- [[Family Calendar]]
	- [Financial Transactions](https://1drv.ms/x/s!Aj0L6Z7V6r2akMkWk4Gxpun0wC5y2w?e=mRxSzT)
	- [[Yearly Budget]]
- 🌅 Exotic Vacations 
	- [[Peru]]
	- [[Austria]]
	- [[Texas]]  
- 🎥 Movies to Watch
	- [Sleepless in Seattle](https://www.imdb.com/title/tt0108160/)
	- [Joe vs the Volcano](https://www.imdb.com/title/tt0099892/)

 # Personal Projects
- 🏡 Remodeling Projects
	- [[Bathroom Remodel]]
	- [[Paint entryway]]
	- [[Research building Garage]] 
 - ✍️ Writing Projects
	- [[5 ways to love PKM more]]
	- Read: [Obisidian core principles](https://tfthacker.medium.com/obsidian-understanding-its-core-design-principles-7f3fafbd6e36)
- 📚 Learning
	- [[Early American History]]
	- [[Spanish - Entry Level]]

# Work
## 💼 Projects
	- [[Cloud backup]]
	- [[Firewall upgrades]]
	- [[IT Cybersecurity training]]
## 🏗️ Proampac Docs

```dataview
		Table WITHOUT ID file.link as "Walkthrough Notes"
		from "Work/Walkthroughs"
		sort file.ctime desc
		limit 5
```
## 👥 Personnel
	- [[Sally Smith]]
	- [[Bill Hansen]]
	- [[Brad Jefferson]]
	- [[Olga Olson]]

# Vault Info
- 🗄️ Recent file updates
 `$=dv.list(dv.pages('').sort(f=>f.file.mtime.ts,"desc").limit(4).file.link)`
- 🔖 Tagged:  favorite 
 `$=dv.list(dv.pages('#favorite').sort(f=>f.file.name,"desc").limit(4).file.link)`
- 〽️ Stats
	-  File Count: `$=dv.pages().length`
	-  Personal recipes: `$=dv.pages('"Family/Recipes"').length`
