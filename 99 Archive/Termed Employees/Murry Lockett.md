---
Class: Employee
Phone: 
Email: 
Department: 
Position: 
Machine: 
Name: Murry Locket
tags:
  - Termed
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
   AND contains(Details, "Murry Lockett")
  GROUP BY file.name as Source
  SORT rows.file.day desc
  ```