# 中国科学技术大学 - 教务处通知新闻

## Coverage
`index-only`

## Route
- Namespace: `ustc`
- Namespace Name: `中国科学技术大学`
- Route Path: `/jwc/:type?`
- Route Name: `教务处通知新闻`
- Example: `/ustc/jwc/info`
- URL: `www.teach.ustc.edu.cn/`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `hang333`
- Source Location: `jwc.ts`
- Source Module: `() => import('@/routes/ustc/jwc.ts')`

## Description
| 信息 | 教学     | 考试 | 交流     |
| ---- | -------- | ---- | -------- |
| info | teaching | exam | exchange |

## Parameters
- `type`: 分类，默认显示所有种类


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
  - `www.teach.ustc.edu.cn/`
- `target`: `/jwc`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 信息 | 教学     | 考试 | 交流     |\n| ---- | -------- | ---- | -------- |\n| info | teaching | exam | exchange |",
  "example": "/ustc/jwc/info",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "jwc.ts",
  "maintainers": [
    "hang333"
  ],
  "module": "() => import('@/routes/ustc/jwc.ts')",
  "name": "教务处通知新闻",
  "parameters": {
    "type": "分类，默认显示所有种类"
  },
  "path": "/jwc/:type?",
  "radar": [
    {
      "source": [
        "www.teach.ustc.edu.cn/"
      ],
      "target": "/jwc"
    }
  ],
  "url": "www.teach.ustc.edu.cn/"
}
```
