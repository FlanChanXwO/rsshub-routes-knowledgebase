# Asianfanfics - 关键词

## Coverage
`index-only`

## Route
- Namespace: `asianfanfics`
- Namespace Name: `Asianfanfics`
- Route Path: `/text-search/:keyword`
- Route Name: `关键词`
- Example: `/asianfanfics/text-search/milklove`
- URL: `asianfanfics.com`
- Language: `en`
- Categories: `reading`
- Maintainers: `KazooTTT`
- Source Location: `text-search.ts`
- Source Module: `() => import('@/routes/asianfanfics/text-search.ts')`

## Description
匹配asianfanfics搜索关键词

## Parameters
- `keyword`: 关键词


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.asianfanfics.com/browse/text_search?q=:keyword`
- `target`: `/text-search/:keyword`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "description": "匹配asianfanfics搜索关键词",
  "example": "/asianfanfics/text-search/milklove",
  "location": "text-search.ts",
  "maintainers": [
    "KazooTTT"
  ],
  "module": "() => import('@/routes/asianfanfics/text-search.ts')",
  "name": "关键词",
  "parameters": {
    "keyword": "关键词"
  },
  "path": "/text-search/:keyword",
  "radar": [
    {
      "source": [
        "www.asianfanfics.com/browse/text_search?q=:keyword"
      ],
      "target": "/text-search/:keyword"
    }
  ]
}
```
