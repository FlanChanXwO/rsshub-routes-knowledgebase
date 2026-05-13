# MyGoPen - 分類

## Coverage
`index-only`

## Route
- Namespace: `mygopen`
- Namespace Name: `MyGoPen`
- Route Path: `/:label?`
- Route Name: `分類`
- Example: `/mygopen`
- URL: `mygopen.com`
- Language: `zh-TW`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/mygopen/index.ts')`

## Description
| 謠言 | 詐騙 | 真實資訊 | 教學 |
| ---- | ---- | -------- | ---- |

## Parameters
- `label`: 分類，见下表，默认为首页


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
  - `mygopen.com/search/label/:label`
  - `mygopen.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 謠言 | 詐騙 | 真實資訊 | 教學 |\n| ---- | ---- | -------- | ---- |",
  "example": "/mygopen",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/mygopen/index.ts')",
  "name": "分類",
  "parameters": {
    "label": "分類，见下表，默认为首页"
  },
  "path": "/:label?",
  "radar": [
    {
      "source": [
        "mygopen.com/search/label/:label",
        "mygopen.com/"
      ]
    }
  ]
}
```
