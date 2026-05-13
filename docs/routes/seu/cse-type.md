# 东南大学 - 计算机技术与工程学院

## Coverage
`index-only`

## Route
- Namespace: `seu`
- Namespace Name: `东南大学`
- Route Path: `/cse/:type?`
- Route Name: `计算机技术与工程学院`
- Example: `/seu/cse/xyxw`
- URL: `cse.seu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `LogicJake`
- Source Location: `cse/index.ts`
- Source Module: `() => import('@/routes/seu/cse/index.ts')`

## Description
| 学院新闻 | 通知公告 | 教务信息 | 就业信息 | 学工事务 |
| -------- | -------- | -------- | -------- | -------- |
| xyxw     | tzgg     | jwxx     | jyxx     | xgsw     |

## Parameters
- `type`: 分类名，默认为 `xyxw`


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
  - `cse.seu.edu.cn/:type/list.htm`
  - `cse.seu.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 学院新闻 | 通知公告 | 教务信息 | 就业信息 | 学工事务 |\n| -------- | -------- | -------- | -------- | -------- |\n| xyxw     | tzgg     | jwxx     | jyxx     | xgsw     |",
  "example": "/seu/cse/xyxw",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "cse/index.ts",
  "maintainers": [
    "LogicJake"
  ],
  "module": "() => import('@/routes/seu/cse/index.ts')",
  "name": "计算机技术与工程学院",
  "parameters": {
    "type": "分类名，默认为 `xyxw`"
  },
  "path": "/cse/:type?",
  "radar": [
    {
      "source": [
        "cse.seu.edu.cn/:type/list.htm",
        "cse.seu.edu.cn/"
      ]
    }
  ]
}
```
