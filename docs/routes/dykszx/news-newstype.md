# 德阳人事考试网 - 考试新闻发布

## Coverage
`index-only`

## Route
- Namespace: `dykszx`
- Namespace Name: `德阳人事考试网`
- Route Path: `/news/:newsType?`
- Route Name: `考试新闻发布`
- Example: `/dykszx/news`
- URL: `www.dykszx.com`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `zytomorrow`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/dykszx/news.ts')`

## Description
| 新闻中心 | 公务员考试 | 事业单位 | （职）业资格、职称考试 | 其他 |
| :------: | :------: | :------: |:------: |:------: |
|   all   |   gwy   |  sydw | zyzc  | other |

## Parameters
- `newsType`: 考试类型。默认新闻中心(all)


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
  - `www.dykszx.com/`
- `target`: `/news/all`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 新闻中心 | 公务员考试 | 事业单位 | （职）业资格、职称考试 | 其他 |\n| :------: | :------: | :------: |:------: |:------: |\n|   all   |   gwy   |  sydw | zyzc  | other |",
  "example": "/dykszx/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news.ts",
  "maintainers": [
    "zytomorrow"
  ],
  "module": "() => import('@/routes/dykszx/news.ts')",
  "name": "考试新闻发布",
  "parameters": {
    "newsType": "考试类型。默认新闻中心(all)"
  },
  "path": "/news/:newsType?",
  "radar": [
    {
      "source": [
        "www.dykszx.com/"
      ],
      "target": "/news/all"
    }
  ],
  "url": "www.dykszx.com"
}
```
