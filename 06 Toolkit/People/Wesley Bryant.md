---
Class: Employee
Name: Wesley Bryant
Department: Garbax
Machine:
  - 319
Position: Operator
---
Name:: Wesley Bryant
Phone:: 
Email:: 
Department:: 
Position:: 
Machine:: 
#Employee
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
   AND contains(Details, "Wesley Bryant")
  GROUP BY file.name as Source
  SORT rows.file.day desc
  ```