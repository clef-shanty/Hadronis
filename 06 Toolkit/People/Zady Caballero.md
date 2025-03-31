---
Name: Zady Caballero
Department: HandleBags
Machine: [401]
Position: Packaging Inspector
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
   AND contains(Details, "Zady Caballero")
  GROUP BY file.name as Source
  SORT rows.file.day desc
  ```