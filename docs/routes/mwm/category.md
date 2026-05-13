# 管理世界 - 分类

## Coverage
`index-only`

## Route
- Namespace: `mwm`
- Namespace Name: `管理世界`
- Route Path: `/:category?`
- Route Name: `分类`
- Example: `/mwm`
- URL: `mwm.net.cn`
- Language: `zh-CN`
- Categories: `journal`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/mwm/index.ts')`

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
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/mwm/index.ts')",
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
  ]
}
```
