# iThome 台灣 - 标签

## Coverage
`index-only`

## Route
- Namespace: `ithome`
- Namespace Name: `iThome 台灣`
- Route Path: `/tag/:name`
- Route Name: `标签`
- Example: `/ithome/tag/win11`
- URL: `ithome.com`
- Language: `zh-TW`
- Categories: `new-media`
- Maintainers: `Fatpandac`
- Source Location: `tag.ts`
- Source Module: `() => import('@/routes/ithome/tag.ts')`

## Description
_None_

## Parameters
- `name`: 标签名称，可从网址链接中获取


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
  - `ithome.com/tag/:name`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/ithome/tag/win11",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "tag.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "module": "() => import('@/routes/ithome/tag.ts')",
  "name": "标签",
  "parameters": {
    "name": "标签名称，可从网址链接中获取"
  },
  "path": "/tag/:name",
  "radar": [
    {
      "source": [
        "ithome.com/tag/:name"
      ]
    }
  ]
}
```
