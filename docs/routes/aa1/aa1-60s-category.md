# 夏柔 - 每日新闻

## Coverage
`index-only`

## Route
- Namespace: `aa1`
- Namespace Name: `夏柔`
- Route Path: `/aa1/60s/:category?`
- Route Name: `每日新闻`
- Example: `/aa1/60s/news`
- URL: `60s.aa1.cn`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `60s.ts`
- Source Module: `_None_`

## Description
::: tip
订阅 [每天 60 秒读懂世界](https://60s.aa1.cn/category/news)，其源网址为 `https://60s.aa1.cn/category/news`，请参考该 URL 指定部分构成参数，此时路由为 [`/aa1/60s/news`](https://rsshub.app/aa1/60s/news) 或 [`/aa1/60s/每天60秒读懂世界`](https://rsshub.app/aa1/60s/每天60秒读懂世界)。
:::

| 分类                                                       | ID                                                      |
| ---------------------------------------------------------- | ------------------------------------------------------- |
| [全部](https://60s.aa1.cn)                                 | [<空>](https://rsshub.app/aa1/60s)                      |
| [新闻词文章数据](https://60s.aa1.cn/category/freenewsdata) | [freenewsdata](https://rsshub.app/aa1/60s/freenewsdata) |
| [最新](https://60s.aa1.cn/category/new)                    | [new](https://rsshub.app/aa1/60s/new)                   |
| [本平台同款自动发文章插件](https://60s.aa1.cn/category/1)  | [1](https://rsshub.app/aa1/60s/1)                       |
| [每天 60 秒读懂世界](https://60s.aa1.cn/category/news)     | [news](https://rsshub.app/aa1/60s/news)                 |

## Parameters
- `category`: {"description": "分类，默认为全部，可在对应分类页 URL 中找到", "options": [{"label": "全部", "value": ""}, {"label": "新闻词文章数据", "value": "freenewsdata"}, {"label": "最新", "value": "new"}, {"label": "本平台同款自动发文章插件", "value": "1"}, {"label": "每天60秒读懂世界", "value": "news"}]}


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
  - `60s.aa1.cn`
  - `60s.aa1.cn/category/:category`
- `target`: `/60s/:category`
### Rule 2
- `title`: `全部`
- `source`:
  - `60s.aa1.cn`
- `target`: `/60s`
### Rule 3
- `title`: `新闻词文章数据`
- `source`:
  - `60s.aa1.cn/category/freenewsdata`
- `target`: `/60s/freenewsdata`
### Rule 4
- `title`: `最新`
- `source`:
  - `60s.aa1.cn/category/new`
- `target`: `/60s/new`
### Rule 5
- `title`: `本平台同款自动发文章插件`
- `source`:
  - `60s.aa1.cn/category/1`
- `target`: `/60s/1`
### Rule 6
- `title`: `每天60秒读懂世界`
- `source`:
  - `60s.aa1.cn/category/news`
- `target`: `/60s/news`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n订阅 [每天 60 秒读懂世界](https://60s.aa1.cn/category/news)，其源网址为 `https://60s.aa1.cn/category/news`，请参考该 URL 指定部分构成参数，此时路由为 [`/aa1/60s/news`](https://rsshub.app/aa1/60s/news) 或 [`/aa1/60s/每天60秒读懂世界`](https://rsshub.app/aa1/60s/每天60秒读懂世界)。\n:::\n\n| 分类                                                       | ID                                                      |\n| ---------------------------------------------------------- | ------------------------------------------------------- |\n| [全部](https://60s.aa1.cn)                                 | [<空>](https://rsshub.app/aa1/60s)                      |\n| [新闻词文章数据](https://60s.aa1.cn/category/freenewsdata) | [freenewsdata](https://rsshub.app/aa1/60s/freenewsdata) |\n| [最新](https://60s.aa1.cn/category/new)                    | [new](https://rsshub.app/aa1/60s/new)                   |\n| [本平台同款自动发文章插件](https://60s.aa1.cn/category/1)  | [1](https://rsshub.app/aa1/60s/1)                       |\n| [每天 60 秒读懂世界](https://60s.aa1.cn/category/news)     | [news](https://rsshub.app/aa1/60s/news)                 |",
  "example": "/aa1/60s/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "60s.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "每日新闻",
  "parameters": {
    "category": {
      "description": "分类，默认为全部，可在对应分类页 URL 中找到",
      "options": [
        {
          "label": "全部",
          "value": ""
        },
        {
          "label": "新闻词文章数据",
          "value": "freenewsdata"
        },
        {
          "label": "最新",
          "value": "new"
        },
        {
          "label": "本平台同款自动发文章插件",
          "value": "1"
        },
        {
          "label": "每天60秒读懂世界",
          "value": "news"
        }
      ]
    }
  },
  "path": "/60s/:category?",
  "radar": [
    {
      "source": [
        "60s.aa1.cn",
        "60s.aa1.cn/category/:category"
      ],
      "target": "/60s/:category"
    },
    {
      "source": [
        "60s.aa1.cn"
      ],
      "target": "/60s",
      "title": "全部"
    },
    {
      "source": [
        "60s.aa1.cn/category/freenewsdata"
      ],
      "target": "/60s/freenewsdata",
      "title": "新闻词文章数据"
    },
    {
      "source": [
        "60s.aa1.cn/category/new"
      ],
      "target": "/60s/new",
      "title": "最新"
    },
    {
      "source": [
        "60s.aa1.cn/category/1"
      ],
      "target": "/60s/1",
      "title": "本平台同款自动发文章插件"
    },
    {
      "source": [
        "60s.aa1.cn/category/news"
      ],
      "target": "/60s/news",
      "title": "每天60秒读懂世界"
    }
  ],
  "topFeeds": [],
  "url": "60s.aa1.cn",
  "view": 0
}
```
