Name:: L J Wright
Phone:: 
Email:: 
Department:: HandleBags
Position:: Packaging Inspector
Machine:: 406
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
   AND contains(Details, "L J Wright")
  > GROUP BY file.name as Source
  > SORT rows.file.day desc
  > ```