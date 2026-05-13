# 浙江工业大学 - 浙江工业大学计算机科学与技术学院、软件学院

## Coverage
`index-only`

## Route
- Namespace: `zjut`
- Namespace Name: `浙江工业大学`
- Route Path: `/cs/:type`
- Route Name: `浙江工业大学计算机科学与技术学院、软件学院`
- Example: `/zjut/cs/54`
- URL: `cs.zjut.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `zhullyb`
- Source Location: `cs/index.ts`
- Source Module: `() => import('@/routes/zjut/cs/index.ts')`

## Description
| 新闻资讯 | 学术动态 | 通知公告 |
| ------- | ------- | ------- |
| 54      | 55      | 53      |

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
  - `cs.zjut.edu.cn/jsp/newsclass.jsp`
- `target`: `/cs/:type`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 新闻资讯 | 学术动态 | 通知公告 |\n| ------- | ------- | ------- |\n| 54      | 55      | 53      |",
  "example": "/zjut/cs/54",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "cs/index.ts",
  "maintainers": [
    "zhullyb"
  ],
  "module": "() => import('@/routes/zjut/cs/index.ts')",
  "name": "浙江工业大学计算机科学与技术学院、软件学院",
  "parameters": {
    "type": "分类，见下表"
  },
  "path": "/cs/:type",
  "radar": [
    {
      "source": [
        "cs.zjut.edu.cn/jsp/newsclass.jsp"
      ],
      "target": "/cs/:type"
    }
  ],
  "url": "cs.zjut.edu.cn"
}
```
