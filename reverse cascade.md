---
aliases:
  - 3b reverse cascade
props: 3
beats: 2
siteswap: "3"
hands: (30)(10).
alt siteswaps:
  - "522"
symm pair:
  - "[[half shower]]"
prop pair:
  - "[[5b reverse cascade]]"
reverse pair:
  - "[[cascade]]"
siteswap pair:
  - "[[windmill]]"
  - "[[underarm tennis]]"
  - "[[tennis]]"
  - "[[mills' mess]]"
  - "[[mills' mess windmill]]"
  - "[[mills' mess reverse crosscade]]"
  - "[[half shower]]"
  - "[[half mess]]"
  - "[[flo's mess]]"
  - "[[crossed arm cascade]]"
  - "[[crossed arm reverse cascade]]"
  - "[[cherry picker]]"
  - "[[charley]]"
  - "[[cascade]]"
  - "[[boston mess]]"
tags:
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
