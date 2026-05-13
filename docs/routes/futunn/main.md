# Futubull 富途牛牛 - 要闻

## Coverage
`index-only`

## Route
- Namespace: `futunn`
- Namespace Name: `Futubull 富途牛牛`
- Route Path: `/main`
- Route Name: `要闻`
- Example: `/futunn/main`
- URL: `news.futunn.com`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `Wsine, nczitzk, kennyfong19931`
- Source Location: `main.ts`
- Source Module: `() => import('@/routes/futunn/main.ts')`

## Description
_None_

## Parameters
_None_


## Features
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `news.futunn.com/main`
  - `news.futunn.com/:lang/main`
- `target`: `/main`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/futunn/main",
  "features": {
    "supportRadar": true
  },
  "location": "main.ts",
  "maintainers": [
    "Wsine",
    "nczitzk",
    "kennyfong19931"
  ],
  "module": "() => import('@/routes/futunn/main.ts')",
  "name": "要闻",
  "path": [
    "/main",
    "/"
  ],
  "radar": [
    {
      "source": [
        "news.futunn.com/main",
        "news.futunn.com/:lang/main"
      ],
      "target": "/main"
    }
  ]
}
```
