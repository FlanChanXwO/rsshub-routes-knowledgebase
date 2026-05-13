# 豆瓣 - 豆瓣每月推荐片单

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/recommended/:type?/:routeParams?`
- Route Name: `豆瓣每月推荐片单`
- Example: `/douban/recommended/tv`
- URL: `www.douban.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `honue`
- Source Location: `other/recommended.ts`
- Source Module: `() => import('@/routes/douban/other/recommended.ts')`

## Description
| 额外参数 | 含义                   | 接受的值 | 默认值 |
| -------- | ---------------------- | -------- | ------ |
| playable | 仅看有可播放片源的影片 | 0/1      | 0      |
| score    | 筛选评分               | 0-10     | 0      |

  用例：`/douban/recommended/tv/playable=0&score=8`

::: tip
  整合了 /douban/list/ 路由，省去每月手动更新 id 参数，因为当月推荐剧集片单中，会有还未播出 / 开评分剧集、海外平台播出剧集，请自行考虑是否使用额外参数。
:::

## Parameters
- `type`: 片单类型剧集/电影，tv或movie，默认为tv
- `routeParams`: 额外参数；请参阅以下说明和表格


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "| 额外参数 | 含义                   | 接受的值 | 默认值 |\n| -------- | ---------------------- | -------- | ------ |\n| playable | 仅看有可播放片源的影片 | 0/1      | 0      |\n| score    | 筛选评分               | 0-10     | 0      |\n\n  用例：`/douban/recommended/tv/playable=0&score=8`\n\n::: tip\n  整合了 /douban/list/ 路由，省去每月手动更新 id 参数，因为当月推荐剧集片单中，会有还未播出 / 开评分剧集、海外平台播出剧集，请自行考虑是否使用额外参数。\n:::",
  "example": "/douban/recommended/tv",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "other/recommended.ts",
  "maintainers": [
    "honue"
  ],
  "module": "() => import('@/routes/douban/other/recommended.ts')",
  "name": "豆瓣每月推荐片单",
  "parameters": {
    "routeParams": "额外参数；请参阅以下说明和表格",
    "type": "片单类型剧集/电影，tv或movie，默认为tv"
  },
  "path": "/recommended/:type?/:routeParams?"
}
```
