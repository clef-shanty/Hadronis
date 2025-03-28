Name:: Charlie Staten
Phone:: 
Email:: 
Department:: SOS
Position:: Operator
Machine:: 134, 132, 126
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
   AND contains(Details, "Charlie Staten")
  > GROUP BY file.name as Source
  > SORT rows.file.day desc
  > ```