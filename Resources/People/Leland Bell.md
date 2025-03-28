---
Class: Employee
Name: Leland Bell
Department: Warehouse
Position: Forklift Driver
---
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
   AND contains(Details, "Leland Bell")
  GROUP BY file.name as Source
  SORT rows.file.day desc
  ```