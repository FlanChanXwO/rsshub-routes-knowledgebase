# 中国经济网 - 地方经济

## Coverage
`index-only`

## Route
- Namespace: `ce`
- Namespace Name: `中国经济网`
- Route Path: `/district/:category?`
- Route Name: `地方经济`
- Example: `/ce/district`
- URL: `district.ce.cn`
- Language: `zh-CN`
- Categories: `traditional-media`
- Maintainers: `cscnk52`
- Source Location: `district.ts`
- Source Module: `() => import('@/routes/ce/district.ts')`

## Description
| 即时新闻 | 经济动态 | 独家视角 | 专题 | 数说地方 | 地方播报 | 专稿 | 港澳台 |
|----------|----------|----------|------|----------|----------|------|--------|
| roll     | jjdt     | poll     | ch   | ssdf     | dfbb     | zg   | gat    |

## Parameters
- `category`: 栏目标识，默认为 roll（即时新闻）


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
  - `district.ce.cn/newarea/:category/index.shtml`
- `target`: `/district/:category?`
### Rule 2
- `source`:
  - `district.ce.cn/newarea/:category`
- `target`: `/district/:category?`
### Rule 3
- `source`:
  - `district.ce.cn`
- `target`: `/district`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| 即时新闻 | 经济动态 | 独家视角 | 专题 | 数说地方 | 地方播报 | 专稿 | 港澳台 |\n|----------|----------|----------|------|----------|----------|------|--------|\n| roll     | jjdt     | poll     | ch   | ssdf     | dfbb     | zg   | gat    |",
  "example": "/ce/district",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "district.ts",
  "maintainers": [
    "cscnk52"
  ],
  "module": "() => import('@/routes/ce/district.ts')",
  "name": "地方经济",
  "parameters": {
    "category": "栏目标识，默认为 roll（即时新闻）"
  },
  "path": "/district/:category?",
  "radar": [
    {
      "source": [
        "district.ce.cn/newarea/:category/index.shtml"
      ],
      "target": "/district/:category?"
    },
    {
      "source": [
        "district.ce.cn/newarea/:category"
      ],
      "target": "/district/:category?"
    },
    {
      "source": [
        "district.ce.cn"
      ],
      "target": "/district"
    }
  ],
  "url": "district.ce.cn",
  "view": 0
}
```
