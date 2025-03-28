---
Class: Employee
Phone: 
Email: 
Department: HandleBags
Position: Packaging Inspector
Machine: "403"
Name: Katerin Rodriquez
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
   AND contains(Details, "Katerin Rodriguez")
  GROUP BY file.name as Source
  SORT rows.file.day desc
  ```