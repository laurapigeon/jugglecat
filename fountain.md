---
aliases:
  - 4b fountain
props: 4
beats: 2
siteswap: "4"
hands: (10)(30).
sync pair:
  - "[[fountain sync]]"
prop pair:
  - "[[6b fountain]]"
tags:
  - async
  - symm
LoJ difficulty: 7
siteswap pair:
  - "[[4b mills' mess windmill]]"
  - "[[4b windmill]]"
  - "[[4b mills' mess]]"
  - "[[4b half mess]]"
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
