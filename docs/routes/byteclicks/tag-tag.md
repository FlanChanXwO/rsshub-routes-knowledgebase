# 字节点击 - 标签

## Coverage
`index-only`

## Route
- Namespace: `byteclicks`
- Namespace Name: `字节点击`
- Route Path: `/tag/:tag`
- Route Name: `标签`
- Example: `/byteclicks/tag/人工智能`
- URL: `byteclicks.com/`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `tag.ts`
- Source Module: `() => import('@/routes/byteclicks/tag.ts')`

## Description
_None_

## Parameters
- `tag`: 标签，可在URL中找到


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
  - `byteclicks.com/tag/:tag`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/byteclicks/tag/人工智能",
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
    "TonyRL"
  ],
  "module": "() => import('@/routes/byteclicks/tag.ts')",
  "name": "标签",
  "parameters": {
    "tag": "标签，可在URL中找到"
  },
  "path": "/tag/:tag",
  "radar": [
    {
      "source": [
        "byteclicks.com/tag/:tag"
      ]
    }
  ],
  "url": "byteclicks.com/"
}
```
