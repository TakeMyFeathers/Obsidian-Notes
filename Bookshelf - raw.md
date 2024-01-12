---
cssclasses: table-max, max
---

# Currently Reading
```dataview  
table author as Author where econtains(shelves, "currently-reading") sort rating desc
```

# Want to Read

```dataview  
table author as Author where contains(status, "to-read") or econtains(shelves, "to-read") sort rating desc
```

# Read

```dataview  
table author as Author where cover != null and econtains(shelves, "read") sort rating desc
```
