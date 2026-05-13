# 网猴线报 - 线报

## Coverage
`index-only`

## Route
- Namespace: `iehou`
- Namespace Name: `网猴线报`
- Route Path: `/:category?`
- Route Name: `线报`
- Example: `/iehou`
- URL: `iehou.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/iehou/index.ts')`

## Description
::: tip
  若订阅 [24小时热门线报](https://iehou.com/page-dayhot.htm)，网址为 `https://iehou.com/page-dayhot.htm`。截取 `https://iehou.com/page-` 到末尾 `.htm` 的部分 `dayhot` 作为参数填入，此时路由为 [`/iehou/dayhot`](https://rsshub.app/iehou/dayhot)。
:::
  
| [最新线报](https://iehou.com/) | [24 小时热门](https://iehou.com/page-dayhot.htm) | [一周热门](https://iehou.com/page-weekhot.htm) |
| ------------------------------ | ------------------------------------------------ | ---------------------------------------------- |
| [](https://rsshub.app/iehou)   | [dayhot](https://rsshub.app/iehou/dayhot)        | [weekhot](https://rsshub.app/iehou/weekhot)    |

## Parameters
- `category`: 分类，默认为空，即最新线报，可在对应分类页 URL 中找到


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
- `title`: `最新线报`
- `source`:
  - `iehou.com`
- `target`: `/`
### Rule 2
- `title`: `24小时热门`
- `source`:
  - `iehou.com/page-dayhot.htm`
- `target`: `/dayhot`
### Rule 3
- `title`: `一周热门`
- `source`:
  - `iehou.com/page-weekhot.htm`
- `target`: `/weekhot`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n  若订阅 [24小时热门线报](https://iehou.com/page-dayhot.htm)，网址为 `https://iehou.com/page-dayhot.htm`。截取 `https://iehou.com/page-` 到末尾 `.htm` 的部分 `dayhot` 作为参数填入，此时路由为 [`/iehou/dayhot`](https://rsshub.app/iehou/dayhot)。\n:::\n  \n| [最新线报](https://iehou.com/) | [24 小时热门](https://iehou.com/page-dayhot.htm) | [一周热门](https://iehou.com/page-weekhot.htm) |\n| ------------------------------ | ------------------------------------------------ | ---------------------------------------------- |\n| [](https://rsshub.app/iehou)   | [dayhot](https://rsshub.app/iehou/dayhot)        | [weekhot](https://rsshub.app/iehou/weekhot)    |\n  ",
  "example": "/iehou",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/iehou/index.ts')",
  "name": "线报",
  "parameters": {
    "category": "分类，默认为空，即最新线报，可在对应分类页 URL 中找到"
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "iehou.com"
      ],
      "target": "/",
      "title": "最新线报"
    },
    {
      "source": [
        "iehou.com/page-dayhot.htm"
      ],
      "target": "/dayhot",
      "title": "24小时热门"
    },
    {
      "source": [
        "iehou.com/page-weekhot.htm"
      ],
      "target": "/weekhot",
      "title": "一周热门"
    }
  ],
  "url": "iehou.com"
}
```
