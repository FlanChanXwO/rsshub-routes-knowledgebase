# 格隆汇 - 主题文章

## Coverage
`index-only`

## Route
- Namespace: `gelonghui`
- Namespace Name: `格隆汇`
- Route Path: `/subject/:id`
- Route Name: `主题文章`
- Example: `/gelonghui/subject/4`
- URL: `gelonghui.com`
- Language: `zh-CN`
- Categories: `finance`
- Maintainers: `nczitzk`
- Source Location: `subject.ts`
- Source Module: `() => import('@/routes/gelonghui/subject.ts')`

## Description
_None_

## Parameters
- `id`: 主题编号，可在主题页 URL 中找到


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
  - `gelonghui.com/subject/:id`

## Raw JSON
```json
{
  "categories": [
    "finance"
  ],
  "example": "/gelonghui/subject/4",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "subject.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/gelonghui/subject.ts')",
  "name": "主题文章",
  "parameters": {
    "id": "主题编号，可在主题页 URL 中找到"
  },
  "path": "/subject/:id",
  "radar": [
    {
      "source": [
        "gelonghui.com/subject/:id"
      ]
    }
  ],
  "view": 0
}
```
