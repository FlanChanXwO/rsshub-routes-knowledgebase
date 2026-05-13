# 得物 - 技术博客

## Coverage
`index-only`

## Route
- Namespace: `dewu`
- Namespace Name: `得物`
- Route Path: `/techblog/:categoryId?`
- Route Name: `技术博客`
- Example: `/dewu/techblog`
- URL: `dewu.com`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `zhenlohuang`
- Source Location: `techblog.ts`
- Source Module: `() => import('@/routes/dewu/techblog.ts')`

## Description
| 分类 | ID |
| --- | --- |
| 大前端 | 1 |
| Java | 2 |
| 音视频 | 3 |
| 测试 | 4 |
| Golang | 5 |
| AI&数据 | 6 |
| 运维&稳定生产 | 7 |
| 技术思考 | 8 |

## Parameters
- `categoryId`: 分类 ID，见下表，默认为全部


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `tech.dewu.com/`
- `target`: `/techblog`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "| 分类 | ID |\n| --- | --- |\n| 大前端 | 1 |\n| Java | 2 |\n| 音视频 | 3 |\n| 测试 | 4 |\n| Golang | 5 |\n| AI&数据 | 6 |\n| 运维&稳定生产 | 7 |\n| 技术思考 | 8 |",
  "example": "/dewu/techblog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "techblog.ts",
  "maintainers": [
    "zhenlohuang"
  ],
  "module": "() => import('@/routes/dewu/techblog.ts')",
  "name": "技术博客",
  "parameters": {
    "categoryId": "分类 ID，见下表，默认为全部"
  },
  "path": "/techblog/:categoryId?",
  "radar": [
    {
      "source": [
        "tech.dewu.com/"
      ],
      "target": "/techblog"
    }
  ]
}
```
