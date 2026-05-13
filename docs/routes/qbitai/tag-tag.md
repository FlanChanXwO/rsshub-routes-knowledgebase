# 量子位 - 标签

## Coverage
`index-only`

## Route
- Namespace: `qbitai`
- Namespace Name: `量子位`
- Route Path: `/tag/:tag`
- Route Name: `标签`
- Example: `/qbitai/tag/大语言模型`
- URL: `qbitai.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `FuryMartin`
- Source Location: `tag.ts`
- Source Module: `() => import('@/routes/qbitai/tag.ts')`

## Description
_None_

## Parameters
- `tag`: 标签名


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
  - `qbitai.com/tag/:tag`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/qbitai/tag/大语言模型",
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
    "FuryMartin"
  ],
  "module": "() => import('@/routes/qbitai/tag.ts')",
  "name": "标签",
  "parameters": {
    "tag": "标签名"
  },
  "path": "/tag/:tag",
  "radar": [
    {
      "source": [
        "qbitai.com/tag/:tag"
      ]
    }
  ]
}
```
