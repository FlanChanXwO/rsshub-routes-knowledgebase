# 懂球帝 - 球员新闻

## Coverage
`index-only`

## Route
- Namespace: `dongqiudi`
- Namespace Name: `懂球帝`
- Route Path: `/dongqiudi/player_news/:id`
- Route Name: `球员新闻`
- Example: `/dongqiudi/player_news/50000339`
- URL: `m.dongqiudi.com`
- Language: `_None_`
- Categories: `sport`
- Maintainers: `HenryQW`
- Source Location: `player-news.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `id`: 球员 id, 可在[懂球帝数据](https://www.dongqiudi.com/data)中通过其队伍找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.dongqiudi.com/player/*id`

## Raw JSON
```json
{
  "categories": [
    "sport"
  ],
  "example": "/dongqiudi/player_news/50000339",
  "heat": 0,
  "location": "player-news.ts",
  "maintainers": [
    "HenryQW"
  ],
  "name": "球员新闻",
  "parameters": {
    "id": "球员 id, 可在[懂球帝数据](https://www.dongqiudi.com/data)中通过其队伍找到"
  },
  "path": "/player_news/:id",
  "radar": [
    {
      "source": [
        "www.dongqiudi.com/player/*id"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": []
}
```
