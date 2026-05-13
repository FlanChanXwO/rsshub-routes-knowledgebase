# 南京理工大学 - 电光学院研学网

## Coverage
`index-only`

## Route
- Namespace: `njust`
- Namespace Name: `南京理工大学`
- Route Path: `/dgxg/:type?`
- Route Name: `电光学院研学网`
- Example: `/njust/dgxg/gstz`
- URL: `jwc.njust.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `jasongzy`
- Source Location: `dgxg.ts`
- Source Module: `() => import('@/routes/njust/dgxg.ts')`

## Description
| 公示通知 | 学术文化 | 就业指导 |
| -------- | -------- | -------- |
| gstz     | xswh     | jyzd     |

## Parameters
- `type`: 分类名，见下表，默认为公示通知


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 公示通知 | 学术文化 | 就业指导 |\n| -------- | -------- | -------- |\n| gstz     | xswh     | jyzd     |",
  "example": "/njust/dgxg/gstz",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "dgxg.ts",
  "maintainers": [
    "jasongzy"
  ],
  "module": "() => import('@/routes/njust/dgxg.ts')",
  "name": "电光学院研学网",
  "parameters": {
    "type": "分类名，见下表，默认为公示通知"
  },
  "path": "/dgxg/:type?"
}
```
