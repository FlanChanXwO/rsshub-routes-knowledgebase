# 湖南农业大学 - 国际交流与合作处、国际教育学院、港澳台事务办公室

## Coverage
`index-only`

## Route
- Namespace: `hunau`
- Namespace Name: `湖南农业大学`
- Route Path: `/ied/:type?/:category?/:page?`
- Route Name: `国际交流与合作处、国际教育学院、港澳台事务办公室`
- Example: `/hunau/ied`
- URL: `xky.hunau.edu.cn/`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `lcandy2`
- Source Location: `ied.ts`
- Source Module: `() => import('@/routes/hunau/ied.ts')`

## Description
| 分类     | 公告通知 | 新闻快讯 | 其他分类... |
| -------- | -------- | -------- | ----------- |
| type     | xwzx     | xwzx     | 对应 URL    |
| category | tzgg     | xwkx     | 对应 URL    |

## Parameters
- `type`: 页面归属，默认为 `xwzx`
- `category`: 页面分类，默认为 `ggtz`
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
  "description": "| 分类     | 公告通知 | 新闻快讯 | 其他分类... |\n| -------- | -------- | -------- | ----------- |\n| type     | xwzx     | xwzx     | 对应 URL    |\n| category | tzgg     | xwkx     | 对应 URL    |",
  "example": "/hunau/ied",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "ied.ts",
  "maintainers": [
    "lcandy2"
  ],
  "module": "() => import('@/routes/hunau/ied.ts')",
  "name": "国际交流与合作处、国际教育学院、港澳台事务办公室",
  "parameters": {
    "category": "页面分类，默认为 `ggtz`",
    "page": "页码，默认为 `1`",
    "type": "页面归属，默认为 `xwzx`"
  },
  "path": "/ied/:type?/:category?/:page?",
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
