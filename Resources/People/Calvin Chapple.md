---
Class: Employee
Phone: 
Email: 
Department: QC
Position: Baler
Machine:
---
- # Notes
	- Employee put his two weeks notice in on 11/5/24. 
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
   AND contains(Details, "Calvin Chapple")
  GROUP BY file.name as Source
  SORT rows.file.day desc
  ```