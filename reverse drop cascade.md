---
props: 3
beats: 2
siteswap: (4x,2T)*
hands: (-30)(-10).(-10,40)(20)(-10,40).
tags:
  - sync
  - symm
  - active2
---

siteswap pair:
```dataview
LIST
WHERE siteswap = this.siteswap
WHERE file.name != this.file.name
```
```dataviewjs
dv.paragraph("```siteswap\npattern: " + dv.current().siteswap + "\nhands: " + dv.current().hands + "\ncolors: mixed\n```");
```
