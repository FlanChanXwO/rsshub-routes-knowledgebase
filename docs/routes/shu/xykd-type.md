# 上海大学 - 校园看点

## Coverage
`index-only`

## Route
- Namespace: `shu`
- Namespace Name: `上海大学`
- Route Path: `/xykd/:type?`
- Route Name: `校园看点`
- Example: `/shu/xykd/xsbg`
- URL: `www.shu.edu.cn/`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `GhhG123`
- Source Location: `xykd.ts`
- Source Module: `() => import('@/routes/shu/xykd.ts')`

## Description
| 文化信息 | 学术报告 |
| -------- | --------- |
| whxx     | xsbg      |

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
  - `www.shu.edu.cn/`
- `target`: `/xykd`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 文化信息 | 学术报告 |\n| -------- | --------- |\n| whxx     | xsbg      |",
  "example": "/shu/xykd/xsbg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "xykd.ts",
  "maintainers": [
    "GhhG123"
  ],
  "module": "() => import('@/routes/shu/xykd.ts')",
  "name": "校园看点",
  "parameters": {
    "type": "分类，默认为学术公告"
  },
  "path": "/xykd/:type?",
  "radar": [
    {
      "source": [
        "www.shu.edu.cn/"
      ],
      "target": "/xykd"
    }
  ],
  "url": "www.shu.edu.cn/"
}
```
