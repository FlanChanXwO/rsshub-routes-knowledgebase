# JavDB - 番号

## Coverage
`index-only`

## Route
- Namespace: `javdb`
- Namespace Name: `JavDB`
- Route Path: `/video_codes/:code/:filter?`
- Route Name: `番号`
- Example: `/javdb/video_codes/SIVR`
- URL: `javdb.com/`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `sgpublic`
- Source Location: `videocodes.ts`
- Source Module: `() => import('@/routes/javdb/videocodes.ts')`

## Description
| 全部 | 可播放   | 單體作品 | 可下載   | 字幕  | 預覽圖  |
| ---- | -------- | -------- | -------- | ----- | ------- |
|      | playable | single   | download | cnsub | preview |

## Parameters
- `id`: 番号前缀
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
  "description": "| 全部 | 可播放   | 單體作品 | 可下載   | 字幕  | 預覽圖  |\n| ---- | -------- | -------- | -------- | ----- | ------- |\n|      | playable | single   | download | cnsub | preview |",
  "example": "/javdb/video_codes/SIVR",
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
  "location": "videocodes.ts",
  "maintainers": [
    "sgpublic"
  ],
  "module": "() => import('@/routes/javdb/videocodes.ts')",
  "name": "番号",
  "parameters": {
    "filter": "过滤，见下表，默认为 `全部`",
    "id": "番号前缀"
  },
  "path": "/video_codes/:code/:filter?",
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
