# JavDB - 系列

## Coverage
`index-only`

## Route
- Namespace: `javdb`
- Namespace Name: `JavDB`
- Route Path: `/series/:id/:filter?`
- Route Name: `系列`
- Example: `/javdb/series/1NW`
- URL: `javdb.com/`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `series.ts`
- Source Module: `() => import('@/routes/javdb/series.ts')`

## Description
| 全部 | 可播放   | 單體作品 | 可下載   | 字幕  | 預覽圖  |
| ---- | -------- | -------- | -------- | ----- | ------- |
|      | playable | single   | download | cnsub | preview |

  所有系列编号参见 [系列庫](https://javdb.com/series)

## Parameters
- `id`: 编号，可在系列页 URL 中找到
- `filter`: 过滤，见下表，默认为 `全部`


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
  "description": "| 全部 | 可播放   | 單體作品 | 可下載   | 字幕  | 預覽圖  |\n| ---- | -------- | -------- | -------- | ----- | ------- |\n|      | playable | single   | download | cnsub | preview |\n\n  所有系列编号参见 [系列庫](https://javdb.com/series)",
  "example": "/javdb/series/1NW",
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
  "location": "series.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/javdb/series.ts')",
  "name": "系列",
  "parameters": {
    "filter": "过滤，见下表，默认为 `全部`",
    "id": "编号，可在系列页 URL 中找到"
  },
  "path": "/series/:id/:filter?",
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
