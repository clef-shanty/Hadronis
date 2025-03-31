---
tags: BJ/Monthly
---

```calendar-nav
```

# 2025-March
## Highlights
```dataview
TABLE WITHOUT ID
  file.link AS "Date",
  Note AS "🗒️"
FROM "06 BJ/10 Daily"
WHERE contains(MyMonth,this.file.name)
  AND Note != null
SORT file.name ASC
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
WHERE contains(MyMonth,this.file.name)
SORT file.name ASC
```
