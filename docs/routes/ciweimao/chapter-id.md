# 刺猬猫 - 章节

## Coverage
`index-only`

## Route
- Namespace: `ciweimao`
- Namespace Name: `刺猬猫`
- Route Path: `/chapter/:id`
- Route Name: `章节`
- Example: `/ciweimao/chapter/100043404`
- URL: `wap.ciweimao.com`
- Language: `zh-CN`
- Categories: `reading`
- Maintainers: `keocheung`
- Source Location: `chapter.ts`
- Source Module: `() => import('@/routes/ciweimao/chapter.ts')`

## Description
_None_

## Parameters
- `id`: 小说 id, 可在对应小说页 URL 中找到


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
  - `wap.ciweimao.com/book/:id`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "example": "/ciweimao/chapter/100043404",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "chapter.ts",
  "maintainers": [
    "keocheung"
  ],
  "module": "() => import('@/routes/ciweimao/chapter.ts')",
  "name": "章节",
  "parameters": {
    "id": "小说 id, 可在对应小说页 URL 中找到"
  },
  "path": "/chapter/:id",
  "radar": [
    {
      "source": [
        "wap.ciweimao.com/book/:id"
      ]
    }
  ]
}
```
