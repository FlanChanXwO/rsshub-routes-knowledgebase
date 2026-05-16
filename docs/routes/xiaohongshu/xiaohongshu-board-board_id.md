# 小红书 - 专辑

## Coverage
`index-only`

## Route
- Namespace: `xiaohongshu`
- Namespace Name: `小红书`
- Route Path: `/xiaohongshu/board/:board_id`
- Route Name: `专辑`
- Example: `/xiaohongshu/board/5db6f79200000000020032df`
- URL: `xiaohongshu.com`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `lotosbin`
- Source Location: `board.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `board_id`: 专辑 ID


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `xiaohongshu.com/board/:board_id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/xiaohongshu/board/5db6f79200000000020032df",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "board.ts",
  "maintainers": [
    "lotosbin"
  ],
  "name": "专辑",
  "parameters": {
    "board_id": "专辑 ID"
  },
  "path": "/board/:board_id",
  "radar": [
    {
      "source": [
        "xiaohongshu.com/board/:board_id"
      ]
    }
  ],
  "topFeeds": []
}
```
