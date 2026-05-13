# 聯合新聞網 - 轉角國際 - 標籤

## Coverage
`index-only`

## Route
- Namespace: `udn`
- Namespace Name: `聯合新聞網`
- Route Path: `/global/tag/:tag?`
- Route Name: `轉角國際 - 標籤`
- Example: `/udn/global/tag/過去24小時`
- URL: `udn.com`
- Language: `zh-TW`
- Categories: `traditional-media`
- Maintainers: `emdoe, nczitzk, pseudoyu`
- Source Location: `global/tag.ts`
- Source Module: `() => import('@/routes/udn/global/tag.ts')`

## Description
| 過去 24 小時 | 鏡頭背後 | 深度專欄 | 重磅廣播 |
| ------------ | -------- | -------- | -------- |

## Parameters
- `tag`: 标签，可在对应标签页 URL 中找到


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
  - `global.udn.com/search/tagging/1020/:tag`
  - `global.udn.com/`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| 過去 24 小時 | 鏡頭背後 | 深度專欄 | 重磅廣播 |\n| ------------ | -------- | -------- | -------- |",
  "example": "/udn/global/tag/過去24小時",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "global/tag.ts",
  "maintainers": [
    "emdoe",
    "nczitzk",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/udn/global/tag.ts')",
  "name": "轉角國際 - 標籤",
  "parameters": {
    "tag": "标签，可在对应标签页 URL 中找到"
  },
  "path": "/global/tag/:tag?",
  "radar": [
    {
      "source": [
        "global.udn.com/search/tagging/1020/:tag",
        "global.udn.com/"
      ]
    }
  ]
}
```
