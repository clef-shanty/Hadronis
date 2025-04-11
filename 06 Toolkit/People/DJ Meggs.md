---
Name: DJ Meggs
Phone: 
Email: 
Department:
  - "[[Sacks]]"
  - "[[SOS]]"
Position: "[[Operator]]"
Machine:
  - "[[314]]"
  - "[[316]]"
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
  FROM !"x-raw/templates"
  FLATTEN log as Details
  WHERE contains(Details, "#Proampac/attendance")
   AND contains(Details, this.file.name)
  GROUP BY file.name as Source
  SORT rows.file.day desc
  ```