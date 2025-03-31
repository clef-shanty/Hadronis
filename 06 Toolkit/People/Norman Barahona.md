---
Class: Employee
Phone: 
Email: 
Department: Maintenance
Position: Mechanic
Machine: 
Name: Norman Barahona
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
   AND contains(Details, "Norman Barahona")
  GROUP BY file.name as Source
  SORT rows.file.day desc
  ```