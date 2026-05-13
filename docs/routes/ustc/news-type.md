# 中国科学技术大学 - 官网通知公告

## Coverage
`index-only`

## Route
- Namespace: `ustc`
- Namespace Name: `中国科学技术大学`
- Route Path: `/news/:type?`
- Route Name: `官网通知公告`
- Example: `/ustc/news/gl`
- URL: `ustc.edu.cn/`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `hang333, jasongzy`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/ustc/index.ts')`

## Description
| 教学类 | 科研类 | 管理类 | 服务类 |
| ------ | ------ | ------ | ------ |
| jx     | ky     | gl     | fw     |

## Parameters
- `type`: 分类，默认为管理类


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `ustc.edu.cn/`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 教学类 | 科研类 | 管理类 | 服务类 |\n| ------ | ------ | ------ | ------ |\n| jx     | ky     | gl     | fw     |",
  "example": "/ustc/news/gl",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "hang333",
    "jasongzy"
  ],
  "module": "() => import('@/routes/ustc/index.ts')",
  "name": "官网通知公告",
  "parameters": {
    "type": "分类，默认为管理类"
  },
  "path": "/news/:type?",
  "radar": [
    {
      "source": [
        "ustc.edu.cn/"
      ],
      "target": "/news"
    }
  ],
  "url": "ustc.edu.cn/"
}
```
