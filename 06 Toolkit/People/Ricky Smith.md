---
Class: Employee
Phone: 
Email: 
Department:
  - "[[Sacks]]"
  - "[[SOS]]"
Position: "[[Operator]]"
Machine:
  - "[[316]]"
  - "[[314]]"
  - "[[318]]"
tags:
  - Employee
---
- # Notes
- # Issues
- # Discussions
- # Attendance
  
  ```dataview
  TABLE
  WITHOUT ID
  link(Source, dateformat(date(Source), "yyyy-MM-dd")) as "",
  rows.Details as "Details"
  FROM !"Templates"
  FLATTEN log as Details
  WHERE contains(Details, "#Proampac/attendance")
   AND contains(Details, "Ricky Smith")
  GROUP BY file.name as Source
  SORT rows.file.day desc
  ```
  