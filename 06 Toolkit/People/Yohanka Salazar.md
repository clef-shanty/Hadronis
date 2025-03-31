---
Name: Yohanka Salazar
Department: HandleBags
Machine: [405]
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
   AND contains(Details, "Yohanka Salazar")
  GROUP BY file.name as Source
  SORT rows.file.day desc
  ```