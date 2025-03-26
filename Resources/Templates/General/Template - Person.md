---
First Name:
Last Name:
Relationship:
MaritalStatus:
Birthday:
Company:
aliases:
tags: person
---

# BJ Monthly Notes Template

## Contact Information
> [!multi-column]
>>[!info]+ ### 🏢 Business
>>Company: `VIEW[{Company}]`
>>E-mail:: 
>>Mobile:
>>Street:
>>ZIP:
>>City:
>>Country:
>
>>[!info]+ ### 🔏 Private
>>E-mail: 
>>URL: 
>>Mobile: 
>>Street:
>>ZIP:
>>City:
>>Country:
>

## Family
> [!multi-column]
> > [!USER] ### Personal
> > Birthday: `VIEW[{Birthday}]`
> > Marital status: `VIEW[{MaritalStatus}]`
> > Anniversary: 
> 
> > [!USERS] ### Spouse
> > Name: 
> > Birthday:
> 
> > [!KIDS] ### Children
> > Name: 
> > Birthday: 

## Related Notes
```dataview
LIST
FROM [[]]
SORT file.link DESC
```
