# JavDB - 搜索

## Coverage
`index-only`

## Route
- Namespace: `javdb`
- Namespace Name: `JavDB`
- Route Path: `/search/:keyword?/:filter?/:sort?`
- Route Name: `搜索`
- Example: `/javdb/search/巨乳`
- URL: `javdb.com/`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `nczitzk`
- Source Location: `search.ts`
- Source Module: `() => import('@/routes/javdb/search.ts')`

## Description
过滤

| 全部 | 占位 | 可播放   | 單體作品 | 演員  | 片商  | 導演     | 系列   | 番號 | 可下載   | 字幕  | 預覽圖  |
| ---- | ---- | -------- | -------- | ----- | ----- | -------- | ------ | ---- | -------- | ----- | ------- |
|      | none | playable | single   | actor | maker | director | series | code | download | cnsub | preview |

  排序

| 按相关度排序 | 按发布时间排序 |
| ------------ | -------------- |
| 0            | 1              |

## Parameters
- `keyword`: 关键字，默认为空
- `filter`: 过滤，见下表，默认为 `可播放`
- `sort`: 排序，见下表，默认为 `按相关度排序`


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
  "description": "过滤\n\n| 全部 | 占位 | 可播放   | 單體作品 | 演員  | 片商  | 導演     | 系列   | 番號 | 可下載   | 字幕  | 預覽圖  |\n| ---- | ---- | -------- | -------- | ----- | ----- | -------- | ------ | ---- | -------- | ----- | ------- |\n|      | none | playable | single   | actor | maker | director | series | code | download | cnsub | preview |\n\n  排序\n\n| 按相关度排序 | 按发布时间排序 |\n| ------------ | -------------- |\n| 0            | 1              |",
  "example": "/javdb/search/巨乳",
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
  "location": "search.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/javdb/search.ts')",
  "name": "搜索",
  "parameters": {
    "filter": "过滤，见下表，默认为 `可播放`",
    "keyword": "关键字，默认为空",
    "sort": "排序，见下表，默认为 `按相关度排序`"
  },
  "path": "/search/:keyword?/:filter?/:sort?",
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
