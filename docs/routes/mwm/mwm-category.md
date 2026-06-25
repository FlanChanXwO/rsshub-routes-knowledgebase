# 管理世界 - 分类

## Coverage
`index-only`

## Route
- Namespace: `mwm`
- Namespace Name: `管理世界`
- Route Path: `/mwm/:category?`
- Route Name: `分类`
- Example: `/mwm`
- URL: `mwm.net.cn`
- Language: `_None_`
- Categories: `journal`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
| 本期要目 | 网络首发 | 学术活动 | 通知公告 |
| -------- | -------- | -------- | -------- |
| bqym     | wlsf     | xshd     | tzgg     |

## Parameters
- `category`: 分类，见下表，默认为本期要目


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
  - `mwm.net.cn/web/:category`
  - `mwm.net.cn/`

## Raw JSON
```json
{
  "categories": [
    "journal"
  ],
  "description": "| 本期要目 | 网络首发 | 学术活动 | 通知公告 |\n| -------- | -------- | -------- | -------- |\n| bqym     | wlsf     | xshd     | tzgg     |",
  "example": "/mwm",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 36,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "分类",
  "parameters": {
    "category": "分类，见下表，默认为本期要目"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "mwm.net.cn/web/:category",
        "mwm.net.cn/"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "管理世界杂志社-本期要目 - Powered by RSSHub",
      "errorAt": "2025-12-24T23:47:57.228Z",
      "errorMessage": "[GET] \"http://www.mwm.net.cn/web/bqym?pagesize=100\": <no response> fetch failed\n[GET] \"http://www.mwm.net.cn/web/bqym?pagesize=100\": <no response> fetch failed\n",
      "id": "136403935744074752",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.mwm.net.cn/web/bqym?pagesize=100",
      "title": "管理世界杂志社-本期要目",
      "type": "feed",
      "url": "rsshub://mwm/bqym"
    },
    {
      "description": "管理世界杂志社-网络首发 - Powered by RSSHub",
      "errorAt": "2026-01-06T14:24:58.913Z",
      "errorMessage": "[GET] \"http://www.mwm.net.cn/web/wlsf\": <no response> fetch failed\n",
      "id": "136404008065290240",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.mwm.net.cn/web/wlsf",
      "title": "管理世界杂志社-网络首发",
      "type": "feed",
      "url": "rsshub://mwm/wlsf"
    }
  ]
}
```
