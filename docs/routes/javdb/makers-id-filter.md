# JavDB - 片商

## Coverage
`index-only`

## Route
- Namespace: `javdb`
- Namespace Name: `JavDB`
- Route Path: `/makers/:id/:filter?`
- Route Name: `片商`
- Example: `/javdb/makers/7R`
- URL: `javdb.com/`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `makers.ts`
- Source Module: `() => import('@/routes/javdb/makers.ts')`

## Description
| 全部 | 可播放   | 單體作品 | 可下載   | 字幕  | 預覽圖  |
| ---- | -------- | -------- | -------- | ----- | ------- |
|      | playable | single   | download | cnsub | preview |

  所有片商编号参见 [片商庫](https://javdb.com/makers)

## Parameters
- `id`: 编号，可在片商页 URL 中找到
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
  "description": "| 全部 | 可播放   | 單體作品 | 可下載   | 字幕  | 預覽圖  |\n| ---- | -------- | -------- | -------- | ----- | ------- |\n|      | playable | single   | download | cnsub | preview |\n\n  所有片商编号参见 [片商庫](https://javdb.com/makers)",
  "example": "/javdb/makers/7R",
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
  "location": "makers.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/javdb/makers.ts')",
  "name": "片商",
  "parameters": {
    "filter": "过滤，见下表，默认为 `全部`",
    "id": "编号，可在片商页 URL 中找到"
  },
  "path": "/makers/:id/:filter?",
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
