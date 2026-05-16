# 腾讯网 - 排行榜

## Coverage
`index-only`

## Route
- Namespace: `qq`
- Namespace Name: `腾讯网`
- Route Path: `/qq/ac/rank/:type?/:time?`
- Route Name: `排行榜`
- Example: `/qq/ac/rank`
- URL: `qq.com`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `nczitzk`
- Source Location: `ac/rank.ts`
- Source Module: `_None_`

## Description
| 月票榜 | 飙升榜 | 新作榜 | 畅销榜 | TOP100 | 男生榜 | 女生榜 |
| ------ | ------ | ------ | ------ | ------ | ------ | ------ |
| mt     | rise   | new    | pay    | top    | male   | female |

::: tip
`time` 参数仅在 `type` 参数选为 **月票榜** 的时候生效。
:::

## Parameters
- `type`: 分类，见下表，默认为月票榜
- `time`: 时间，`cur` 为当周、`prev` 为上周


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
  - `ac.qq.com/Rank/comicRank/type/:type`
  - `ac.qq.com/`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "| 月票榜 | 飙升榜 | 新作榜 | 畅销榜 | TOP100 | 男生榜 | 女生榜 |\n| ------ | ------ | ------ | ------ | ------ | ------ | ------ |\n| mt     | rise   | new    | pay    | top    | male   | female |\n\n::: tip\n`time` 参数仅在 `type` 参数选为 **月票榜** 的时候生效。\n:::",
  "example": "/qq/ac/rank",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 3,
  "location": "ac/rank.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "排行榜",
  "parameters": {
    "time": "时间，`cur` 为当周、`prev` 为上周",
    "type": "分类，见下表，默认为月票榜"
  },
  "path": "/ac/rank/:type?/:time?",
  "radar": [
    {
      "source": [
        "ac.qq.com/Rank/comicRank/type/:type",
        "ac.qq.com/"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "月票榜 - 腾讯动漫 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "85553804520926208",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://ac.qq.com/Rank/comicRank/type/mt",
      "title": "月票榜 - 腾讯动漫",
      "type": "feed",
      "url": "rsshub://qq/ac/rank"
    }
  ]
}
```
