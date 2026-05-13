# 东北大学 - 研究生招生信息网

## Coverage
`index-only`

## Route
- Namespace: `neu`
- Namespace Name: `东北大学`
- Route Path: `/yz/:type`
- Route Name: `研究生招生信息网`
- Example: `/neu/yz/master1`
- URL: `yz.neu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `paintstar`
- Source Location: `yz.ts`
- Source Module: `() => import('@/routes/neu/yz.ts')`

## Description
| 分类名                     | 分类id      |
| ------------------------- | ---------- |
| 硕士公告                   | master1     |
| 硕士简章                   | master2     |
| 博士公告                   | phd1        |
| 博士简章                   | phd2        |
| 下载中心                   | download    |

## Parameters
- `type`: 分类id,见下表


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
  - `yz.neu.edu.cn/:type/list.htm`
- `target`: `/yz/:type`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "\n| 分类名                     | 分类id      |\n| ------------------------- | ---------- |\n| 硕士公告                   | master1     |\n| 硕士简章                   | master2     |\n| 博士公告                   | phd1        |\n| 博士简章                   | phd2        |\n| 下载中心                   | download    |",
  "example": "/neu/yz/master1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "yz.ts",
  "maintainers": [
    "paintstar"
  ],
  "module": "() => import('@/routes/neu/yz.ts')",
  "name": "研究生招生信息网",
  "parameters": {
    "type": "分类id,见下表"
  },
  "path": "/yz/:type",
  "radar": [
    {
      "source": [
        "yz.neu.edu.cn/:type/list.htm"
      ],
      "target": "/yz/:type"
    }
  ],
  "url": "yz.neu.edu.cn"
}
```
