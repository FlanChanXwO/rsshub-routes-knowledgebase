# Sankei Shimbun 産経新聞 - News

## Coverage
`index-only`

## Route
- Namespace: `sankei`
- Namespace Name: `Sankei Shimbun 産経新聞`
- Route Path: `/news/:category`
- Route Name: `News`
- Example: `/sankei/news/flash`
- URL: `sankei.com`
- Language: `ja`
- Categories: `traditional-media`
- Maintainers: `yuikisaito`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/sankei/news.ts')`

## Description
_None_

## Parameters
- `category`: Category name (as it will appear in URLs). For example, for "Breaking News" https://www.sankei.com/flash/, the category name would be "flash".


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.sankei.com/:category`
- `target`: `/news/:category`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/sankei/news/flash",
  "location": "news.ts",
  "maintainers": [
    "yuikisaito"
  ],
  "module": "() => import('@/routes/sankei/news.ts')",
  "name": "News",
  "parameters": {
    "category": "Category name (as it will appear in URLs). For example, for \"Breaking News\" https://www.sankei.com/flash/, the category name would be \"flash\"."
  },
  "path": "/news/:category",
  "radar": [
    {
      "source": [
        "www.sankei.com/:category"
      ],
      "target": "/news/:category"
    }
  ]
}
```
