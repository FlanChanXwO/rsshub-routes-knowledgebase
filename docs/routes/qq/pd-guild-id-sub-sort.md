# 腾讯网 - 腾讯频道

## Coverage
`index-only`

## Route
- Namespace: `qq`
- Namespace Name: `腾讯网`
- Route Path: `/pd/guild/:id/:sub?/:sort?`
- Route Name: `腾讯频道`
- Example: `/qq/pd/guild/qrp4pkq01d/650967831/created`
- URL: `pd.qq.com/`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `mobyw`
- Source Location: `pd/guild.ts`
- Source Module: `() => import('@/routes/qq/pd/guild.ts')`

## Description
_None_

## Parameters
- `id`: 频道号
- `sub`: 子频道 ID，网页端 URL `subc` 参数的值，默认为 `hot`（全部）
- `sort`: 排序方式，`hot`（热门），`created`（最新发布），`replied`（最新回复），默认为 `created`


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
  - `pd.qq.com/`

## Raw JSON
```json
{
  "categories": [
    "bbs"
  ],
  "example": "/qq/pd/guild/qrp4pkq01d/650967831/created",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "pd/guild.ts",
  "maintainers": [
    "mobyw"
  ],
  "module": "() => import('@/routes/qq/pd/guild.ts')",
  "name": "腾讯频道",
  "parameters": {
    "id": "频道号",
    "sort": "排序方式，`hot`（热门），`created`（最新发布），`replied`（最新回复），默认为 `created`",
    "sub": "子频道 ID，网页端 URL `subc` 参数的值，默认为 `hot`（全部）"
  },
  "path": [
    "/pd/guild/:id/:sub?/:sort?"
  ],
  "radar": [
    {
      "source": [
        "pd.qq.com/"
      ]
    }
  ],
  "url": "pd.qq.com/"
}
```
