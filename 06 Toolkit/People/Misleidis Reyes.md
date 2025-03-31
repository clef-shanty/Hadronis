Name:: Misleidis Reyes
Phone:: 
Email:: 
Department:: SOS, Sacks
Position:: Operator
Machine:: 142, 132, 126, 134
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
   AND contains(Details, "Misleidis Reyes")
  > GROUP BY file.name as Source
  > SORT rows.file.day desc
  > ```