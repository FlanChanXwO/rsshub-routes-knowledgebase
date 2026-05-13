# 泉州师范学院 - 首页

## Coverage
`index-only`

## Route
- Namespace: `qztc`
- Namespace Name: `泉州师范学院`
- Route Path: `/home/:type`
- Route Name: `首页`
- Example: `/qztc/home/2093`
- URL: `www.qztc.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `iQNRen`
- Source Location: `home/index.ts`
- Source Module: `() => import('@/routes/qztc/home/index.ts')`

## Description
| 板块 | 参数 |
| ------- | ------- |
| 泉师新闻 | 2093 |
| 通知公告 | 2094 |
| 采购公告 | 2095 |
| 学术资讯 | xszx |
| 招聘信息 | 2226 |

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
  - `www.qztc.edu.cn/:type/list.htm`
- `target`: `/home/:type`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 板块 | 参数 |\n| ------- | ------- |\n| 泉师新闻 | 2093 |\n| 通知公告 | 2094 |\n| 采购公告 | 2095 |\n| 学术资讯 | xszx |\n| 招聘信息 | 2226 |\n",
  "example": "/qztc/home/2093",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "home/index.ts",
  "maintainers": [
    "iQNRen"
  ],
  "module": "() => import('@/routes/qztc/home/index.ts')",
  "name": "首页",
  "parameters": {
    "type": "分类，见下表"
  },
  "path": "/home/:type",
  "radar": [
    {
      "source": [
        "www.qztc.edu.cn/:type/list.htm"
      ],
      "target": "/home/:type"
    }
  ],
  "url": "www.qztc.edu.cn"
}
```
