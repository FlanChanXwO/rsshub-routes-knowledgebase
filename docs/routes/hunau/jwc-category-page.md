# 湖南农业大学 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `hunau`
- Namespace Name: `湖南农业大学`
- Route Path: `/jwc/:category?/:page?`
- Route Name: `教务处`
- Example: `/hunau/jwc`
- URL: `xky.hunau.edu.cn/`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `None`
- Source Location: `jwc.ts`
- Source Module: `() => import('@/routes/hunau/jwc.ts')`

## Description
| 分类 | 通知公告 | 教务动态 | 其他教务通知... |
| ---- | -------- | -------- | --------------- |
| 参数 | tzgg     | jwds     | 对应 URL        |

## Parameters
- `category`: 页面分类，默认为 `tzgg`
- `page`: 页码，默认为 `1`


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
  - `xky.hunau.edu.cn/`
  - `xky.hunau.edu.cn/tzgg_8472`
  - `xky.hunau.edu.cn/:category`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 分类 | 通知公告 | 教务动态 | 其他教务通知... |\n| ---- | -------- | -------- | --------------- |\n| 参数 | tzgg     | jwds     | 对应 URL        |",
  "example": "/hunau/jwc",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "jwc.ts",
  "maintainers": [],
  "module": "() => import('@/routes/hunau/jwc.ts')",
  "name": "教务处",
  "parameters": {
    "category": "页面分类，默认为 `tzgg`",
    "page": "页码，默认为 `1`"
  },
  "path": "/jwc/:category?/:page?",
  "radar": [
    {
      "source": [
        "xky.hunau.edu.cn/",
        "xky.hunau.edu.cn/tzgg_8472",
        "xky.hunau.edu.cn/:category"
      ],
      "target": "/:category"
    }
  ],
  "url": "xky.hunau.edu.cn/"
}
```
