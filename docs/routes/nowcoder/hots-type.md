# 牛客网 - 牛客热榜

## Coverage
`index-only`

## Route
- Namespace: `nowcoder`
- Namespace Name: `牛客网`
- Route Path: `/hots/:type?`
- Route Name: `牛客热榜`
- Example: `/nowcoder/hots/1?limit=20`
- URL: `nowcoder.com/`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `xia0ne`
- Source Location: `hots.ts`
- Source Module: `() => import('@/routes/nowcoder/hots.ts')`

## Description
牛客热榜，包括热议话题和全站热贴

## Parameters
- `type`: 热榜类型，`1` 指热议话题，`2` 指全站热贴，默认为 `1`


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
  - `mnowpick.nowcoder.com/m/discuss/hot`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "description": "牛客热榜，包括热议话题和全站热贴",
  "example": "/nowcoder/hots/1?limit=20",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "hots.ts",
  "maintainers": [
    "xia0ne"
  ],
  "module": "() => import('@/routes/nowcoder/hots.ts')",
  "name": "牛客热榜",
  "parameters": {
    "type": "热榜类型，`1` 指热议话题，`2` 指全站热贴，默认为 `1`"
  },
  "path": "/hots/:type?",
  "radar": [
    {
      "source": [
        "mnowpick.nowcoder.com/m/discuss/hot"
      ]
    }
  ],
  "url": "nowcoder.com/"
}
```
