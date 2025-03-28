---
Class: Employee
Phone: 
Email: 
Department: Sacks, SOS
Position: Operator
Machine: All
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
  WHERE contains(Details, "#Proampac/attendance") and contains(Details, "Mario Galliazzi")
  GROUP BY file.name as Source
  SORT rows.file.day desc
  ```