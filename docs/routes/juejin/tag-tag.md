# 掘金 - 标签

## Coverage
`index-only`

## Route
- Namespace: `juejin`
- Namespace Name: `掘金`
- Route Path: `/tag/:tag`
- Route Name: `标签`
- Example: `/juejin/tag/JavaScript`
- URL: `juejin.cn`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `isheng5`
- Source Location: `tag.ts`
- Source Module: `() => import('@/routes/juejin/tag.ts')`

## Description
_None_

## Parameters
- `tag`: 标签名，可在标签 URL 中找到


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
  - `juejin.cn/tag/:tag`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/juejin/tag/JavaScript",
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
    "isheng5"
  ],
  "module": "() => import('@/routes/juejin/tag.ts')",
  "name": "标签",
  "parameters": {
    "tag": "标签名，可在标签 URL 中找到"
  },
  "path": "/tag/:tag",
  "radar": [
    {
      "source": [
        "juejin.cn/tag/:tag"
      ]
    }
  ]
}
```
