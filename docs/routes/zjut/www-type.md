# 浙江工业大学 - 浙江工业大学首页

## Coverage
`index-only`

## Route
- Namespace: `zjut`
- Namespace Name: `浙江工业大学`
- Route Path: `/www/:type`
- Route Name: `浙江工业大学首页`
- Example: `/zjut/www/4528`
- URL: `www.zjut.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `zhullyb`
- Source Location: `www/index.ts`
- Source Module: `() => import('@/routes/zjut/www/index.ts')`

## Description
| 板块 | 参数 |
| ------- | ------- |
| 学术动态 | xsdt_4662 |
| 三创·人物 | 4527 |
| 通知公告 | 4528 |
| 美誉工大 | 5389 |
| 智库工大 | 5390 |
| 工大校历 | 4520 |
| 校区班车 | xqbc |

## Parameters
- `type`: 分类，见下表


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
  - `www.zjut.edu.cn/:type/list.htm`
- `target`: `/www/:type`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 板块 | 参数 |\n| ------- | ------- |\n| 学术动态 | xsdt_4662 |\n| 三创·人物 | 4527 |\n| 通知公告 | 4528 |\n| 美誉工大 | 5389 |\n| 智库工大 | 5390 |\n| 工大校历 | 4520 |\n| 校区班车 | xqbc |",
  "example": "/zjut/www/4528",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "www/index.ts",
  "maintainers": [
    "zhullyb"
  ],
  "module": "() => import('@/routes/zjut/www/index.ts')",
  "name": "浙江工业大学首页",
  "parameters": {
    "type": "分类，见下表"
  },
  "path": "/www/:type",
  "radar": [
    {
      "source": [
        "www.zjut.edu.cn/:type/list.htm"
      ],
      "target": "/www/:type"
    }
  ],
  "url": "www.zjut.edu.cn"
}
```
