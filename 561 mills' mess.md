---
props: 4
beats: 6
siteswap: "615"
hands: (-30)(-10).(20)(10).(-30)(-10).
tags:
  - pass
  - async
  - symm
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
