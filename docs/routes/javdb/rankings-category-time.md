# JavDB - 排行榜

## Coverage
`index-only`

## Route
- Namespace: `javdb`
- Namespace Name: `JavDB`
- Route Path: `/rankings/:category?/:time?`
- Route Name: `排行榜`
- Example: `/javdb/rankings`
- URL: `javdb.com/`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `rankings.ts`
- Source Module: `() => import('@/routes/javdb/rankings.ts')`

## Description
分类

| 有碼     | 無碼       | 歐美    |
| -------- | ---------- | ------- |
| censored | uncensored | western |

  时间

| 日榜  | 週榜   | 月榜    |
| ----- | ------ | ------- |
| daily | weekly | monthly |

## Parameters
- `category`: 分类，见下表，默认为 `有碼`
- `time`: 时间，见下表，默认为 `日榜`


## Features
- `requireConfig`: [{"description": "JavDB登陆后的session值，可在控制台的cookie下查找 `_jdb_session` 的值，即可获取", "name": "JAVDB_SESSION", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `javdb.com/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "分类\n\n| 有碼     | 無碼       | 歐美    |\n| -------- | ---------- | ------- |\n| censored | uncensored | western |\n\n  时间\n\n| 日榜  | 週榜   | 月榜    |\n| ----- | ------ | ------- |\n| daily | weekly | monthly |",
  "example": "/javdb/rankings",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requireConfig": [
      {
        "description": "JavDB登陆后的session值，可在控制台的cookie下查找 `_jdb_session` 的值，即可获取",
        "name": "JAVDB_SESSION",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "rankings.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/javdb/rankings.ts')",
  "name": "排行榜",
  "parameters": {
    "category": "分类，见下表，默认为 `有碼`",
    "time": "时间，见下表，默认为 `日榜`"
  },
  "path": "/rankings/:category?/:time?",
  "radar": [
    {
      "source": [
        "javdb.com/"
      ],
      "target": ""
    }
  ],
  "url": "javdb.com/"
}
```
