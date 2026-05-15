# 4Gamers - 标签

## Coverage
`index-only`

## Route
- Namespace: `4gamers`
- Namespace Name: `4Gamers`
- Route Path: `/4gamers/tag/:tag`
- Route Name: `标签`
- Example: `/4gamers/tag/限時免費`
- URL: `www.4gamers.com.tw/news`
- Language: `_None_`
- Categories: `game`
- Maintainers: `hoilc`
- Source Location: `tag.ts`
- Source Module: `_None_`

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
  - `www.4gamers.com.tw/news/tag/:tag`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "example": "/4gamers/tag/限時免費",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 33,
  "location": "tag.ts",
  "maintainers": [
    "hoilc"
  ],
  "name": "标签",
  "parameters": {
    "tag": "标签名，可在标签 URL 中找到"
  },
  "path": "/tag/:tag",
  "radar": [
    {
      "source": [
        "www.4gamers.com.tw/news/tag/:tag"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "4Gamers - #限時免費 - Powered by RSSHub",
      "errorAt": "2026-02-26T04:40:22.335Z",
      "errorMessage": "Unhandled section type: InsertOneAdsSection on https://www.4gamers.com.tw/news/detail/78994/trash-goblin-and-arranger-are-free-to-keep-on-epic-games-store-this-week\nUnhandled section type: InsertOneAdsSection on https://www.4gamers.com.tw/news/detail/79037/livingbattle-is-free-to-keep-on-steam\nUnhandled section type: InsertOneAdsSection on https://www.4gamers.com.tw/news/detail/79044/just-move-fall-dungeon-endless-abyss-is-free-to-keep-on-steam\n",
      "id": "66771599303537674",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.4gamers.com.tw/news/tag/%E9%99%90%E6%99%82%E5%85%8D%E8%B2%BB",
      "title": "4Gamers - #限時免費",
      "type": "feed",
      "url": "rsshub://4gamers/tag/%E9%99%90%E6%99%82%E5%85%8D%E8%B2%BB"
    },
    {
      "description": "4Gamers - #Steam - Powered by RSSHub",
      "errorAt": "2026-03-11T20:13:27.851Z",
      "errorMessage": "Unhandled section type: InsertOneAdsSection on https://www.4gamers.com.tw/news/detail/78834/apex-legend-season-29-update-new-legend-axle-and-death-box-respawn\n",
      "id": "168549471693848576",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.4gamers.com.tw/news/tag/Steam",
      "title": "4Gamers - #Steam",
      "type": "feed",
      "url": "rsshub://4gamers/tag/Steam"
    }
  ],
  "url": "www.4gamers.com.tw/news"
}
```
