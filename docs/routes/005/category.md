# 幻之羁绊动漫网 - 资讯

## Coverage
`index-only`

## Route
- Namespace: `005`
- Namespace Name: `幻之羁绊动漫网`
- Route Path: `/:category?`
- Route Name: `资讯`
- Example: `/005/zx`
- URL: `005.tv`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `nczitzk`
- Source Location: `index.tsx`
- Source Module: `() => import('@/routes/005/index.tsx')`

## Description
| 二次元资讯 | 慢慢说 | 道听途说 | 展会资讯 |
| ---------- | ------ | -------- | -------- |
| zx         | zwh    | dtts     | zh       |

## Parameters
- `category`: 分类，可在对应分类页 URL 中找到，默认为二次元资讯


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `005.tv/:category`
### Rule 2
- `title`: `二次元资讯`
- `source`:
  - `005.tv/zx/`
- `target`: `/005/zx`
### Rule 3
- `title`: `慢慢说`
- `source`:
  - `005.tv/zwh/`
- `target`: `/005/zwh`
### Rule 4
- `title`: `道听途说`
- `source`:
  - `005.tv/dtts/`
- `target`: `/005/dtts`
### Rule 5
- `title`: `展会资讯`
- `source`:
  - `005.tv/zh/`
- `target`: `/005/zh`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "\n| 二次元资讯 | 慢慢说 | 道听途说 | 展会资讯 |\n| ---------- | ------ | -------- | -------- |\n| zx         | zwh    | dtts     | zh       |\n    ",
  "example": "/005/zx",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "index.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/005/index.tsx')",
  "name": "资讯",
  "parameters": {
    "category": "分类，可在对应分类页 URL 中找到，默认为二次元资讯"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "005.tv/:category"
      ]
    },
    {
      "source": [
        "005.tv/zx/"
      ],
      "target": "/005/zx",
      "title": "二次元资讯"
    },
    {
      "source": [
        "005.tv/zwh/"
      ],
      "target": "/005/zwh",
      "title": "慢慢说"
    },
    {
      "source": [
        "005.tv/dtts/"
      ],
      "target": "/005/dtts",
      "title": "道听途说"
    },
    {
      "source": [
        "005.tv/zh/"
      ],
      "target": "/005/zh",
      "title": "展会资讯"
    }
  ],
  "url": "005.tv"
}
```
