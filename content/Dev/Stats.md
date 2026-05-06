---
tags:
---
```dataview  
TABLE length(rows.file.name) as numfiles  
, join(rows.file.link, ", ") as files  
flatten file.tags as tag  
group by tag  
```
