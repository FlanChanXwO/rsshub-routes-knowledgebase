# 未知文明 - 分类

## Coverage
`index-only`

## Route
- Namespace: `xwenming`
- Namespace Name: `未知文明`
- Route Path: `/:category?`
- Route Name: `分类`
- Example: `/xwenming/news`
- URL: `www.xwenming.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/xwenming/index.ts')`

## Description
::: tip
订阅 [科技前沿](https://www.xwenming.com/index.php/category/news)，其源网址为 `https://www.xwenming.com/index.php/category/news`，请参考该 URL 指定部分构成参数，此时路由为 [`/xwenming/category/news`](https://rsshub.app/xwenming/category/news) 或 [`/xwenming/category/科技前沿`](https://rsshub.app/xwenming/category/科技前沿)。
:::

| 分类                                                                | ID                                                                  |
| ------------------------------------------------------------------- | ------------------------------------------------------------------- |
| [全部](https://www.xwenming.com)                                    | [<空>](https://rsshub.app/xwenming)                                 |
| [科技前沿](https://www.xwenming.com/index.php/category/news)        | [news](https://rsshub.app/xwenming/category/news)                   |
| [疑难杂症](https://www.xwenming.com/index.php/category/solve)       | [solve](https://rsshub.app/xwenming/category/solve)                 |
| [通知专栏](https://www.xwenming.com/index.php/category/notice)      | [notice](https://rsshub.app/xwenming/category/notice)               |
| [未分类](https://www.xwenming.com/index.php/category/uncategorized) | [uncategorized](https://rsshub.app/xwenming/category/uncategorized) |

## Parameters
- `category`: {"description": "分类，默认为全部，可在对应分类页 URL 中找到", "options": [{"label": "全部", "value": ""}, {"label": "科技前沿", "value": "news"}, {"label": "疑难杂症", "value": "solve"}, {"label": "通知专栏", "value": "notice"}, {"label": "未分类", "value": "uncategorized"}]}


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
  - `www.xwenming.com`
  - `www.xwenming.com/index.php/category/:category`
- `target`: `/:category`
### Rule 2
- `title`: `全部`
- `source`:
  - `www.xwenming.com`
- `target`: `/`
### Rule 3
- `title`: `科技前沿`
- `source`:
  - `www.xwenming.com/index.php/category/news`
- `target`: `/news`
### Rule 4
- `title`: `疑难杂症`
- `source`:
  - `www.xwenming.com/index.php/category/solve`
- `target`: `/solve`
### Rule 5
- `title`: `通知专栏`
- `source`:
  - `www.xwenming.com/index.php/category/notice`
- `target`: `/notice`
### Rule 6
- `title`: `未分类`
- `source`:
  - `www.xwenming.com/index.php/category/uncategorized`
- `target`: `/uncategorized`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n订阅 [科技前沿](https://www.xwenming.com/index.php/category/news)，其源网址为 `https://www.xwenming.com/index.php/category/news`，请参考该 URL 指定部分构成参数，此时路由为 [`/xwenming/category/news`](https://rsshub.app/xwenming/category/news) 或 [`/xwenming/category/科技前沿`](https://rsshub.app/xwenming/category/科技前沿)。\n:::\n\n| 分类                                                                | ID                                                                  |\n| ------------------------------------------------------------------- | ------------------------------------------------------------------- |\n| [全部](https://www.xwenming.com)                                    | [<空>](https://rsshub.app/xwenming)                                 |\n| [科技前沿](https://www.xwenming.com/index.php/category/news)        | [news](https://rsshub.app/xwenming/category/news)                   |\n| [疑难杂症](https://www.xwenming.com/index.php/category/solve)       | [solve](https://rsshub.app/xwenming/category/solve)                 |\n| [通知专栏](https://www.xwenming.com/index.php/category/notice)      | [notice](https://rsshub.app/xwenming/category/notice)               |\n| [未分类](https://www.xwenming.com/index.php/category/uncategorized) | [uncategorized](https://rsshub.app/xwenming/category/uncategorized) |\n",
  "example": "/xwenming/news",
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
  "module": "() => import('@/routes/xwenming/index.ts')",
  "name": "分类",
  "parameters": {
    "category": {
      "description": "分类，默认为全部，可在对应分类页 URL 中找到",
      "options": [
        {
          "label": "全部",
          "value": ""
        },
        {
          "label": "科技前沿",
          "value": "news"
        },
        {
          "label": "疑难杂症",
          "value": "solve"
        },
        {
          "label": "通知专栏",
          "value": "notice"
        },
        {
          "label": "未分类",
          "value": "uncategorized"
        }
      ]
    }
  },
  "path": "/:category?",
  "radar": [
    {
      "source": [
        "www.xwenming.com",
        "www.xwenming.com/index.php/category/:category"
      ],
      "target": "/:category"
    },
    {
      "source": [
        "www.xwenming.com"
      ],
      "target": "/",
      "title": "全部"
    },
    {
      "source": [
        "www.xwenming.com/index.php/category/news"
      ],
      "target": "/news",
      "title": "科技前沿"
    },
    {
      "source": [
        "www.xwenming.com/index.php/category/solve"
      ],
      "target": "/solve",
      "title": "疑难杂症"
    },
    {
      "source": [
        "www.xwenming.com/index.php/category/notice"
      ],
      "target": "/notice",
      "title": "通知专栏"
    },
    {
      "source": [
        "www.xwenming.com/index.php/category/uncategorized"
      ],
      "target": "/uncategorized",
      "title": "未分类"
    }
  ],
  "url": "www.xwenming.com",
  "view": 0
}
```
