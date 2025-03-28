---
Class: Employee
Phone: 
Email: 
Department: HandleBags
Position: Adjuster
Machine: All
Name: Erick Garcia
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
   AND contains(Details, "Erick Garcia")
  GROUP BY file.name as Source
  SORT rows.file.day desc
  ```