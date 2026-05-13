# 上海外国语大学 - SISU TODAY | FEATURED STORIES

## Coverage
`index-only`

## Route
- Namespace: `shisu`
- Namespace Name: `上海外国语大学`
- Route Path: `/en/:section`
- Route Name: `SISU TODAY | FEATURED STORIES`
- Example: `/shisu/en/news`
- URL: `shisu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `Duuckjing`
- Source Location: `en.ts`
- Source Module: `() => import('@/routes/shisu/en.ts')`

## Description
- features: Read a series of in-depth stories about SISU faculty, students, alumni and beyond campus.
  - news: SISU TODAY English site.

## Parameters
- `section`: The name of resources


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `en.shisu.edu.cn/resources/:section/`
- `target`: `/en/:section`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "- features: Read a series of in-depth stories about SISU faculty, students, alumni and beyond campus.\n  - news: SISU TODAY English site.",
  "example": "/shisu/en/news",
  "location": "en.ts",
  "maintainers": [
    "Duuckjing"
  ],
  "module": "() => import('@/routes/shisu/en.ts')",
  "name": "SISU TODAY | FEATURED STORIES",
  "parameters": {
    "section": "The name of resources"
  },
  "path": "/en/:section",
  "radar": [
    {
      "source": [
        "en.shisu.edu.cn/resources/:section/"
      ],
      "target": "/en/:section"
    }
  ]
}
```
