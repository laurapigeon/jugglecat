---
props: 4
beats: 8
siteswap: "4"
hands: (-30)(-10).(30)(10).(-30)(10).(30)(-10).(30)(10).(-30)(-10).(30)(-10).(-30)(10).
siteswap pair:
  - "[[4b windmill]]"
  - "[[fountain]]"
  - "[[4b mills' mess]]"
  - "[[4b half mess]]"
tags:
  - asymm
  - async
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
