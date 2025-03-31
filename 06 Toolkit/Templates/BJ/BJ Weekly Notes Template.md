---
tags: BJ/Weekly
---

```calendar-nav
```
# Invalid date - Invalid date
```dynamic-embed
[[Notes - Created This Week]]
```

## Trackers
```dataview
TABLE WITHOUT ID
	file.link AS "Date",
	choice(Walk,"🟢","🔴") AS "🚶",
	choice(Workout,"🟢","🔴") AS "🏋️‍♀️",
	choice(Challenge1,"🟢","🔴") AS "🍴",
	Sleep AS "😴",
	REL AS "🧑‍🤝‍🧑",
	Challenge2 AS "PU",
	Challenge3 AS "CR",
	Note AS "🗒️"
FROM "06 BJ/10 Daily"
WHERE Week = "Invalid date"
SORT file.name ASC
```
