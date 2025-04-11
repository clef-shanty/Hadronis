Name:: Stevo Nonkovic
Phone:: 
Email:: 
Department:: HandleBags
Position:: Adjuster
Machine:: 403,402,401, 405
#Termed 
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
   AND contains(Details, "Stevo Nonkovic")
  > GROUP BY file.name as Source
  > SORT rows.file.day desc
  > ```