# JavDB - 主页

## Coverage
`index-only`

## Route
- Namespace: `javdb`
- Namespace Name: `JavDB`
- Route Path: `/javdb/home/:category?/:sort?/:filter?`
- Route Name: `主页`
- Example: `/javdb/home`
- URL: `javdb.com/`
- Language: `_None_`
- Categories: `multimedia, popular`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
分类

| 有碼     | 無碼       | 歐美    |
| -------- | ---------- | ------- |
| censored | uncensored | western |

排序

| 发布日期排序 | 磁鏈更新排序 |
| ------------ | ------------ |
| 1            | 2            |

过滤

| 全部 | 可下载 | 含字幕 | 含短評 |
| ---- | ------ | ------ | ------ |
| 0    | 1      | 2      | 3      |

## Parameters
- `category`: 分类，见下表，默认为 `有碼`
- `sort`: 排序，见下表，默认为 `磁鏈更新排序`
- `filter`: 过滤，见下表，默认为 `可下载`


## Features
- `nsfw`: true
- `requirePuppeteer`: true

## Radar
### Rule 1
- `source`:
  - `javdb.com/`

## Raw JSON
```json
{
  "categories": [
    "multimedia",
    "popular"
  ],
  "description": "分类\n\n| 有碼     | 無碼       | 歐美    |\n| -------- | ---------- | ------- |\n| censored | uncensored | western |\n\n排序\n\n| 发布日期排序 | 磁鏈更新排序 |\n| ------------ | ------------ |\n| 1            | 2            |\n\n过滤\n\n| 全部 | 可下载 | 含字幕 | 含短評 |\n| ---- | ------ | ------ | ------ |\n| 0    | 1      | 2      | 3      |",
  "example": "/javdb/home",
  "features": {
    "nsfw": true,
    "requirePuppeteer": true
  },
  "heat": 1332,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "主页",
  "parameters": {
    "category": "分类，见下表，默认为 `有碼`",
    "filter": "过滤，见下表，默认为 `可下载`",
    "sort": "排序，见下表，默认为 `磁鏈更新排序`"
  },
  "path": "/home/:category?/:sort?/:filter?",
  "radar": [
    {
      "source": [
        "javdb.com/"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": [
    {
      "description": "有碼 - JavDB - 可下载 | 磁鏈更新排序 - Powered by RSSHub",
      "errorAt": "2026-07-15T05:16:34.552Z",
      "errorMessage": "browserType.connect: WebSocket error: ws://browserless:3000/ 429 Too Many Requests\n\r\nToo Many Requests\nCall log:\n  - <ws connecting> ws://browserless:3000/\n  - <ws unexpected response> ws://browserless:3000/ 429 Too Many Requests\n\r\nToo Many Requests\n  - <ws error> ws://browserless:3000/ error WebSocket was closed before the connection was established\n  - <ws connect error> ws://browserless:3000/ WebSocket was closed before the connection was established\n  - <ws disconnected> ws://browserless:3000/ code=1006 reason=\n\n[GET] \"https://javdb.com/?vft=1&vst=2\": 403 Forbidden\nFailed to fetch\nFailed to fetch\n",
      "id": "73931561418737664",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://javdb.com/?vft=1&vst=2",
      "title": "有碼 - JavDB - 可下载 | 磁鏈更新排序",
      "type": "feed",
      "url": "rsshub://javdb/home/censored"
    },
    {
      "description": "有碼 - JavDB - 可下载 | 磁鏈更新排序 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55906664666988544",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://javdb.com/?vft=1&vst=2",
      "title": "有碼 - JavDB - 可下载 | 磁鏈更新排序",
      "type": "feed",
      "url": "rsshub://javdb/home"
    }
  ],
  "url": "javdb.com/"
}
```
