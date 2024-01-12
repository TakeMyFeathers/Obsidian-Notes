---
cssclasses: cards, table-max, max
---

# Currently Reading
```dataview  
table ("![](" + cover +")") as Cover, author as Author where cover != null and econtains(shelves, "currently-reading") sort rating desc
```

# Want to Read

```dataview  
table ("![](" + cover +")") as Cover, author as Author where cover != null and contains(status, "to-read") or econtains(shelves, "to-read") sort rating desc
```

# Read

```dataview  
table ("![](" + cover +")") as Cover, author as Author where cover != null and econtains(shelves, "read") sort rating desc
```
