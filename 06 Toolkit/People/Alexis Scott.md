---
Name: Alexis Scott
Department: SOS
Machine: [126, 132, 134, 142]
Position: Operator
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
   AND contains(Details, "Alexis Scott")
  GROUP BY file.name as Source
  SORT rows.file.day desc
  ```