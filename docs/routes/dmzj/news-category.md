# 动漫之家 - 新闻站

## Coverage
`index-only`

## Route
- Namespace: `dmzj`
- Namespace Name: `动漫之家`
- Route Path: `/news/:category?`
- Route Name: `新闻站`
- Example: `/dmzj/news/donghuaqingbao`
- URL: `news.dmzj.com/`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `vzz64`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/dmzj/news.ts')`

## Description
| 漫画情报      | 轻小说情报          | 动漫周边       | 声优情报        | 音乐资讯    | 游戏资讯   | 美图欣赏      | 漫展情报       | 大杂烩  |
| ------------- | ------------------- | -------------- | --------------- | ----------- | ---------- | ------------- | -------------- | ------- |
| manhuaqingbao | qingxiaoshuoqingbao | manhuazhoubian | shengyouqingbao | yinyuezixun | youxizixun | meituxinshang | manzhanqingbao | dazahui |

## Parameters
- `category`: 类别


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
  - `news.dmzj.com/`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "| 漫画情报      | 轻小说情报          | 动漫周边       | 声优情报        | 音乐资讯    | 游戏资讯   | 美图欣赏      | 漫展情报       | 大杂烩  |\n| ------------- | ------------------- | -------------- | --------------- | ----------- | ---------- | ------------- | -------------- | ------- |\n| manhuaqingbao | qingxiaoshuoqingbao | manhuazhoubian | shengyouqingbao | yinyuezixun | youxizixun | meituxinshang | manzhanqingbao | dazahui |",
  "example": "/dmzj/news/donghuaqingbao",
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
    "vzz64"
  ],
  "module": "() => import('@/routes/dmzj/news.ts')",
  "name": "新闻站",
  "parameters": {
    "category": "类别"
  },
  "path": "/news/:category?",
  "radar": [
    {
      "source": [
        "news.dmzj.com/"
      ],
      "target": "/news"
    }
  ],
  "url": "news.dmzj.com/"
}
```
