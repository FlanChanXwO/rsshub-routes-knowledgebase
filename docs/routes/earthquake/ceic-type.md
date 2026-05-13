# 地震速报 - 中国地震台

## Coverage
`index-only`

## Route
- Namespace: `earthquake`
- Namespace Name: `地震速报`
- Route Path: `/ceic/:type?`
- Route Name: `中国地震台`
- Example: `/earthquake/ceic/1`
- URL: `www.cea.gov.cn/cea/xwzx/zqsd/index.html`
- Language: `zh-CN`
- Categories: `forecast`
- Maintainers: `SettingDust`
- Source Location: `ceic.ts`
- Source Module: `() => import('@/routes/earthquake/ceic.ts')`

## Description
| 参数 | 类型                        |
| ---- | --------------------------- |
| 1    | 最近 24 小时地震信息        |
| 2    | 最近 48 小时地震信息        |
| 5    | 最近一年 3.0 级以上地震信息 |
| 7    | 最近一年 3.0 级以下地震     |
| 8    | 最近一年 4.0 级以上地震信息 |
| 9    | 最近一年 5.0 级以上地震信息 |
| 0    | 最近一年 6.0 级以上地震信息 |

  可通过全局过滤参数订阅您感兴趣的地区.

## Parameters
- `type`: 类型，见下表


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
  - `www.cea.gov.cn/cea/xwzx/zqsd/index.html`
  - `www.cea.gov.cn/`
- `target`: ``

## Raw JSON
```json
{
  "categories": [
    "forecast"
  ],
  "description": "| 参数 | 类型                        |\n| ---- | --------------------------- |\n| 1    | 最近 24 小时地震信息        |\n| 2    | 最近 48 小时地震信息        |\n| 5    | 最近一年 3.0 级以上地震信息 |\n| 7    | 最近一年 3.0 级以下地震     |\n| 8    | 最近一年 4.0 级以上地震信息 |\n| 9    | 最近一年 5.0 级以上地震信息 |\n| 0    | 最近一年 6.0 级以上地震信息 |\n\n  可通过全局过滤参数订阅您感兴趣的地区.",
  "example": "/earthquake/ceic/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "ceic.ts",
  "maintainers": [
    "SettingDust"
  ],
  "module": "() => import('@/routes/earthquake/ceic.ts')",
  "name": "中国地震台",
  "parameters": {
    "type": "类型，见下表"
  },
  "path": "/ceic/:type?",
  "radar": [
    {
      "source": [
        "www.cea.gov.cn/cea/xwzx/zqsd/index.html",
        "www.cea.gov.cn/"
      ],
      "target": ""
    }
  ],
  "url": "www.cea.gov.cn/cea/xwzx/zqsd/index.html"
}
```
