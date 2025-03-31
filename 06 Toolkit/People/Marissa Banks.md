Name:: Marissa Banks
Phone:: 
Email:: 
Department:: HandleBags
Position:: Packaging Inspector
Machine:: 409
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
   AND contains(Details, "Marissa Banks")
  > GROUP BY file.name as Source
  > SORT rows.file.day desc
  > ```