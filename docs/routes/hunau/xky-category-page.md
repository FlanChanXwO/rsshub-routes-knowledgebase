# 湖南农业大学 - 信息与智能科学学院

## Coverage
`index-only`

## Route
- Namespace: `hunau`
- Namespace Name: `湖南农业大学`
- Route Path: `/xky/:category?/:page?`
- Route Name: `信息与智能科学学院`
- Example: `/hunau/xky`
- URL: `xky.hunau.edu.cn/`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `None`
- Source Location: `xky/index.ts`
- Source Module: `() => import('@/routes/hunau/xky/index.ts')`

## Description
| 分类 | 通知公告   | 学院新闻 | 其他分类通知... |
| ---- | ---------- | -------- | --------------- |
| 参数 | tzgg_8472 | xyxw     | 对应 URL        |

## Parameters
- `category`: 页面分类，默认为 `tzgg_8472`
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
  "description": "| 分类 | 通知公告   | 学院新闻 | 其他分类通知... |\n| ---- | ---------- | -------- | --------------- |\n| 参数 | tzgg_8472 | xyxw     | 对应 URL        |",
  "example": "/hunau/xky",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "xky/index.ts",
  "maintainers": [],
  "module": "() => import('@/routes/hunau/xky/index.ts')",
  "name": "信息与智能科学学院",
  "parameters": {
    "category": "页面分类，默认为 `tzgg_8472`",
    "page": "页码，默认为 `1`"
  },
  "path": "/xky/:category?/:page?",
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
