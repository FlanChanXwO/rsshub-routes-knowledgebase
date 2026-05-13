# Go 语言中文网 - 板块

## Coverage
`index-only`

## Route
- Namespace: `studygolang`
- Namespace Name: `Go 语言中文网`
- Route Path: `/go/:id?`
- Route Name: `板块`
- Example: `/studygolang/go/daily`
- URL: `studygolang.com`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `nczitzk`
- Source Location: `go.ts`
- Source Module: `() => import('@/routes/studygolang/go.ts')`

## Description
_None_

## Parameters
- `id`: 板块 id，默认为周刊


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `studygolang.com/go/:id`
  - `studygolang.com/`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/studygolang/go/daily",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "go.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/studygolang/go.ts')",
  "name": "板块",
  "parameters": {
    "id": "板块 id，默认为周刊"
  },
  "path": "/go/:id?",
  "radar": [
    {
      "source": [
        "studygolang.com/go/:id",
        "studygolang.com/"
      ]
    }
  ]
}
```
