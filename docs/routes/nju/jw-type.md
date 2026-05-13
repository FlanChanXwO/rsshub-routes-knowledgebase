# 南京大学 - 本科生院

## Coverage
`index-only`

## Route
- Namespace: `nju`
- Namespace Name: `南京大学`
- Route Path: `/jw/:type`
- Route Name: `本科生院`
- Example: `/nju/jw/ggtz`
- URL: `admission.nju.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `cqjjjzr`
- Source Location: `jw.ts`
- Source Module: `() => import('@/routes/nju/jw.ts')`

## Description
| 公告通知 | 教学动态 |
| -------- | -------- |
| ggtz     | jxdt     |

## Parameters
- `type`: 分类名


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
  - `jw.nju.edu.cn/:type/list.htm`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 公告通知 | 教学动态 |\n| -------- | -------- |\n| ggtz     | jxdt     |",
  "example": "/nju/jw/ggtz",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "jw.ts",
  "maintainers": [
    "cqjjjzr"
  ],
  "module": "() => import('@/routes/nju/jw.ts')",
  "name": "本科生院",
  "parameters": {
    "type": "分类名"
  },
  "path": "/jw/:type",
  "radar": [
    {
      "source": [
        "jw.nju.edu.cn/:type/list.htm"
      ]
    }
  ]
}
```
