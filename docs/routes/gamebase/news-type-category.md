# 遊戲基地 Gamebase - 新聞

## Coverage
`index-only`

## Route
- Namespace: `gamebase`
- Namespace Name: `遊戲基地 Gamebase`
- Route Path: `/news/:type?/:category?`
- Route Name: `新聞`
- Example: `/gamebase/news`
- URL: `news.gamebase.com.tw`
- Language: `zh-TW`
- Categories: `game`
- Maintainers: `nczitzk`
- Source Location: `news.tsx`
- Source Module: `() => import('@/routes/gamebase/news.tsx')`

## Description
::: tip
若訂閱 [手機遊戲新聞](https://news.gamebase.com.tw/news/newslist?type=mobile)，網址為 `https://news.gamebase.com.tw/news/newslist?type=mobile`，請截取 `https://news.gamebase.com.tw/news/` 到末尾的部分 `newslist` 作為 `type` 參數填入，`mobile` 作為 `category` 參數填入，此時目標路由為 [`/gamebase/news/newslist/mobile`](https://rsshub.app/gamebase/news/newslist/mobile)。
:::

| newslist | r18list |
| -------- | ------- |

## Parameters
- `type`: 類型，見下表，預設為 newslist
- `category`: 分類，預設為 `all`，即全部，可在對應分類頁 URL 中找到


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
  - `news.gamebase.com.tw/news`
  - `news.gamebase.com.tw/news/:type`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "::: tip\n若訂閱 [手機遊戲新聞](https://news.gamebase.com.tw/news/newslist?type=mobile)，網址為 `https://news.gamebase.com.tw/news/newslist?type=mobile`，請截取 `https://news.gamebase.com.tw/news/` 到末尾的部分 `newslist` 作為 `type` 參數填入，`mobile` 作為 `category` 參數填入，此時目標路由為 [`/gamebase/news/newslist/mobile`](https://rsshub.app/gamebase/news/newslist/mobile)。\n:::\n\n| newslist | r18list |\n| -------- | ------- |\n",
  "example": "/gamebase/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "news.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/gamebase/news.tsx')",
  "name": "新聞",
  "parameters": {
    "category": "分類，預設為 `all`，即全部，可在對應分類頁 URL 中找到",
    "type": "類型，見下表，預設為 newslist"
  },
  "path": "/news/:type?/:category?",
  "radar": [
    {
      "source": [
        "news.gamebase.com.tw/news",
        "news.gamebase.com.tw/news/:type"
      ]
    }
  ],
  "url": "news.gamebase.com.tw",
  "view": 0,
  "zh": {
    "description": "::: tip\n若订阅 [手机游戏新闻](https://news.gamebase.com.tw/news/newslist?type=mobile)，网址为 `https://news.gamebase.com.tw/news/newslist?type=mobile`，请截取 `https://news.gamebase.com.tw/news/` 到末尾的部分 `newslist` 作为 `type` 参数填入，`mobile` 作为 `category` 参数填入，此时目标路由为 [`/gamebase/news/newslist/mobile`](https://rsshub.app/gamebase/news/newslist/mobile)。\n:::\n\n| newslist | r18list |\n| -------- | ------- |\n",
    "example": "/gamebase/news",
    "maintainers": [
      "nczitzk"
    ],
    "name": "新闻",
    "parameters": {
      "category": "分类，默认为 `all`，即全部，可在对应分类页 URL 中找到",
      "type": "类型，见下表，默认为 newslist"
    },
    "path": "/news/:type?/:category?",
    "url": "news.gamebase.com.tw"
  }
}
```
