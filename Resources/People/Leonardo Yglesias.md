Name:: Leonardo Yglesias
Phone:: 
Email:: 
Department:: HandleBags
Position:: Operator
Machine:: 401
#Employee
# Notes
# Issues
# Discussions
# Attendance

> ```dataview
> TABLE
> WITHOUT ID
> link(Source, dateformat(date(Source), "yyyy-MM-dd")) as "",
> rows.Details as "Details"
> FROM !"Templates"
> FLATTEN log as Details
> WHERE contains(Details, "#Proampac/attendance")
   AND contains(Details, "Leonardo Yglesias")
> GROUP BY file.name as Source
> SORT rows.file.day desc
> ```