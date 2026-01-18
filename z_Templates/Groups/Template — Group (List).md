---
entity: group
group type: list
base:
---

# 🌐 Group Directory

## All Known Groups
```dataview
table status, locale, synopsis
from "Groups"
where type = "group"
sort locale asc, name
