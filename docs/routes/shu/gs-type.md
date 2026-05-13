# 上海大学 - 研究生院

## Coverage
`index-only`

## Route
- Namespace: `shu`
- Namespace Name: `上海大学`
- Route Path: `/gs/:type?`
- Route Name: `研究生院`
- Example: `/shu/gs/zhxw`
- URL: `gs.shu.edu.cn/`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `GhhG123`
- Source Location: `gs.ts`
- Source Module: `() => import('@/routes/shu/gs.ts')`

## Description
| 综合新闻 | 培养管理 | 国际交流 |
| -------- | --------- | --------- |
| zhxw     | pygl      | gjjl      |

## Parameters
- `type`: 分类，默认为学术公告


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
  - `gs.shu.edu.cn/`
- `target`: `/gs`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 综合新闻 | 培养管理 | 国际交流 |\n| -------- | --------- | --------- |\n| zhxw     | pygl      | gjjl      |",
  "example": "/shu/gs/zhxw",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "gs.ts",
  "maintainers": [
    "GhhG123"
  ],
  "module": "() => import('@/routes/shu/gs.ts')",
  "name": "研究生院",
  "parameters": {
    "type": "分类，默认为学术公告"
  },
  "path": "/gs/:type?",
  "radar": [
    {
      "source": [
        "gs.shu.edu.cn/"
      ],
      "target": "/gs"
    }
  ],
  "url": "gs.shu.edu.cn/"
}
```
