Name:: Jose Diaz
Phone:: 
Email:: 
Department:: HandleBags
Position:: Operator
Machine:: 405, 406
#Employee
- # Notes
- # Issues
- # Discussions
- # Attendance
  
  > ```dataview
  > TABLE
  > WITHOUT ID
  > link(Source, dateformat(date(Source), "yyyy-MM-dd")) as "",
  > rows.Details as "Details"
  > FROM !"Templates"
  > FLATTEN log as Details
  > WHERE contains(Details, "#Proampac/attendance")
   AND contains(Details, "Jose Diaz")
  > GROUP BY file.name as Source
  > SORT rows.file.day desc
  > ```