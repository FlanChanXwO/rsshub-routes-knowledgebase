# 国家能源局 - 深圳市考试院

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/shenzhen/hrss/szksy/:caty/:page?`
- Route Name: `深圳市考试院`
- Example: `/gov/shenzhen/hrss/szksy/bmxx/2`
- URL: `hrss.sz.gov.cn/*`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `zlasd`
- Source Location: `shenzhen/hrss/szksy/index.ts`
- Source Module: `() => import('@/routes/gov/shenzhen/hrss/szksy/index.ts')`

## Description
| 通知公告 | 报名信息 | 成绩信息 | 合格标准 | 合格人员公示 | 证书发放信息 |
| :------: | :------: | :------: | :------: | :----------: | :----------: |
|   tzgg   |   bmxx   |   cjxx   |   hgbz   |    hgrygs    |     zsff     |

## Parameters
- `caty`: 信息类别
- `page`: 页码


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
  - `xxgk.sz.gov.cn/cn/xxgk/zfxxgj/:caty`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 通知公告 | 报名信息 | 成绩信息 | 合格标准 | 合格人员公示 | 证书发放信息 |\n| :------: | :------: | :------: | :------: | :----------: | :----------: |\n|   tzgg   |   bmxx   |   cjxx   |   hgbz   |    hgrygs    |     zsff     |",
  "example": "/gov/shenzhen/hrss/szksy/bmxx/2",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "shenzhen/hrss/szksy/index.ts",
  "maintainers": [
    "zlasd"
  ],
  "module": "() => import('@/routes/gov/shenzhen/hrss/szksy/index.ts')",
  "name": "深圳市考试院",
  "parameters": {
    "caty": "信息类别",
    "page": "页码"
  },
  "path": "/shenzhen/hrss/szksy/:caty/:page?",
  "radar": [
    {
      "source": [
        "xxgk.sz.gov.cn/cn/xxgk/zfxxgj/:caty"
      ]
    }
  ],
  "url": "hrss.sz.gov.cn/*"
}
```
