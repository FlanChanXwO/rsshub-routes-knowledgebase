# 西北师范大学 - 计算机科学与工程学院

## Coverage
`index-only`

## Route
- Namespace: `nwnu`
- Namespace Name: `西北师范大学`
- Route Path: `/college/csse/:column`
- Route Name: `计算机科学与工程学院`
- Example: `/college/csse/2435`
- URL: `www.nwnu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `PrinOrange`
- Source Location: `routes/college/csse.ts`
- Source Module: `() => import('@/routes/nwnu/routes/college/csse.ts')`

## Description
| column | 标题       | 描述                                          |
| ------ | ---------- | --------------------------------------------- |
| 2435   | 学院新闻   | 计算机科学与工程 学院新闻                     |
| 2436   | 通知公告   | 计算机科学与工程 通知公告                     |
| 2437   | 学术动态   | 计算机科学与工程 学术动态                     |
| 2446   | 研究生招生 | 计算机科学与工程学院 研究生招生动态及相关新闻 |
| 8411   | 评估动态   | 计算机科学与工程学院 院系学科评估动态         |

## Parameters
_None_


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
  - `jsj.nwnu.edu.cn/:column/list`
- `target`: `/college/csse/:column`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "\n| column | 标题       | 描述                                          |\n| ------ | ---------- | --------------------------------------------- |\n| 2435   | 学院新闻   | 计算机科学与工程 学院新闻                     |\n| 2436   | 通知公告   | 计算机科学与工程 通知公告                     |\n| 2437   | 学术动态   | 计算机科学与工程 学术动态                     |\n| 2446   | 研究生招生 | 计算机科学与工程学院 研究生招生动态及相关新闻 |\n| 8411   | 评估动态   | 计算机科学与工程学院 院系学科评估动态         |",
  "example": "/college/csse/2435",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "routes/college/csse.ts",
  "maintainers": [
    "PrinOrange"
  ],
  "module": "() => import('@/routes/nwnu/routes/college/csse.ts')",
  "name": "计算机科学与工程学院",
  "path": "/college/csse/:column",
  "radar": [
    {
      "source": [
        "jsj.nwnu.edu.cn/:column/list"
      ],
      "target": "/college/csse/:column"
    }
  ]
}
```
