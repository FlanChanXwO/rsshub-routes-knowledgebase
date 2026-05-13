# BT 之家 1LOU 站 - 通用

## Coverage
`index-only`

## Route
- Namespace: `1lou`
- Namespace Name: `BT 之家 1LOU 站`
- Route Path: `/1lou/:params{.+}?`
- Route Name: `通用`
- Example: `/1lou/forum-2-1`
- URL: `1lou.me`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `falling, nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
::: tip
`1lou.me/` 后的内容填入 params 参数，以下是几个例子：

若订阅 [大陆电视剧](https://www.1lou.me/forum-2-1.htm?tagids=0_97_0_0)，网址为 `https://www.1lou.me/forum-2-1.htm?tagids=0_97_0_0`。截取 `https://www.1lou.me/` 到末尾 `.htm` 的部分 `forum-2-1` 作为参数，并补充 `tagids`，此时路由为 [`/1lou/forum-2-1?tagids=0_97_0_0`](https://rsshub.app/1lou/forum-2-1?tagids=0_97_0_0)。

若订阅 [最新发帖电视剧](https://www.1lou.me/forum-2-1.htm?orderby=tid\&digest=0)，网址为 `https://www.1lou.me/forum-2-1.htm?orderby=tid&digest=0`。截取 `https://www.1lou.me/` 到末尾 `.htm` 的部分 `forum-2-1` 作为参数，并补充 `orderby`，此时路由为 [`/1lou/forum-2-1?orderby=tid`](https://rsshub.app/1lou/forum-2-1?orderby=tid)。

若订阅 [搜素繁花主题贴](https://www.1lou.me/search-_E7_B9_81_E8_8A_B1-1.htm)，网址为 `https://www.1lou.me/search-_E7_B9_81_E8_8A_B1-1.htm`。截取 `https://www.1lou.me/` 到末尾 `.htm` 的部分 `search-_E7_B9_81_E8_8A_B1-1` 作为参数，此时路由为 [`/1lou/search-_E7_B9_81_E8_8A_B1-1`](https://rsshub.app/1lou/search-_E7_B9_81_E8_8A_B1-1)。
:::

## Parameters
- `params`: 路径参数，可以在对应页面的 URL 中找到


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
  - `1lou.me/:params`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "description": "::: tip\n`1lou.me/` 后的内容填入 params 参数，以下是几个例子：\n\n若订阅 [大陆电视剧](https://www.1lou.me/forum-2-1.htm?tagids=0_97_0_0)，网址为 `https://www.1lou.me/forum-2-1.htm?tagids=0_97_0_0`。截取 `https://www.1lou.me/` 到末尾 `.htm` 的部分 `forum-2-1` 作为参数，并补充 `tagids`，此时路由为 [`/1lou/forum-2-1?tagids=0_97_0_0`](https://rsshub.app/1lou/forum-2-1?tagids=0_97_0_0)。\n\n若订阅 [最新发帖电视剧](https://www.1lou.me/forum-2-1.htm?orderby=tid\\&digest=0)，网址为 `https://www.1lou.me/forum-2-1.htm?orderby=tid&digest=0`。截取 `https://www.1lou.me/` 到末尾 `.htm` 的部分 `forum-2-1` 作为参数，并补充 `orderby`，此时路由为 [`/1lou/forum-2-1?orderby=tid`](https://rsshub.app/1lou/forum-2-1?orderby=tid)。\n\n若订阅 [搜素繁花主题贴](https://www.1lou.me/search-_E7_B9_81_E8_8A_B1-1.htm)，网址为 `https://www.1lou.me/search-_E7_B9_81_E8_8A_B1-1.htm`。截取 `https://www.1lou.me/` 到末尾 `.htm` 的部分 `search-_E7_B9_81_E8_8A_B1-1` 作为参数，此时路由为 [`/1lou/search-_E7_B9_81_E8_8A_B1-1`](https://rsshub.app/1lou/search-_E7_B9_81_E8_8A_B1-1)。\n:::",
  "example": "/1lou/forum-2-1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 504,
  "location": "index.ts",
  "maintainers": [
    "falling",
    "nczitzk"
  ],
  "name": "通用",
  "parameters": {
    "params": "路径参数，可以在对应页面的 URL 中找到"
  },
  "path": "/:params{.+}?",
  "radar": [
    {
      "source": [
        "1lou.me/:params"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "分享快乐，如此简单 ! BT之家单版社区平台，提供全网最快 最新 最全 高清 电影、动漫、韩剧、日剧、美剧、无损音乐、小说等BT/网盘下载以及资讯！影视爱好者的聚集地的~BT电影天堂之家，BT之家官网：1lOU.ME，BT之家BTBTT，BT之家BTBBT， BTHome，BTHouse - Powered by RSSHub",
      "errorAt": "2026-04-03T15:31:49.462Z",
      "errorMessage": "[GET] \"https://www.1lou.me/forum-1.htm?format=json\": 403 Forbidden\n[GET] \"https://www.1lou.me/forum-1.htm?format=json\": 403 Forbidden\n[GET] \"https://www.1lou.me/forum-1.htm?format=json\": <no response> fetch failed\n[GET] \"https://www.1lou.me/forum-1.htm?format=json\": 403 Forbidden\n",
      "id": "62495339293222913",
      "image": "https://www.1lou.me/view/img/logo.png",
      "ownerUserId": null,
      "siteUrl": "https://www.1lou.me/forum-1.htm?format=json",
      "title": "BT之家1LOU站 - BT 之家 1LOU 站",
      "type": "feed",
      "url": "rsshub://1lou/forum-1"
    },
    {
      "description": "分享快乐，如此简单 ! BT之家单版社区平台，提供全网最快 最新 最全 高清 电影、动漫、韩剧、日剧、美剧、无损音乐、小说等BT/网盘下载以及资讯！影视爱好者的聚集地的~BT电影天堂之家，BT之家官网：1lOU.ME，BT之家BTBTT，BT之家BTBBT， BTHome，BTHouse - Powered by RSSHub",
      "errorAt": "2026-04-03T15:32:07.046Z",
      "errorMessage": "[GET] \"https://www.1lou.me/forum-2-1.htm?format=json\": 403 Forbidden\n[GET] \"https://www.1lou.me/forum-2-1.htm?format=json\": 403 Forbidden\n",
      "id": "64249408253921283",
      "image": "https://www.1lou.me/view/img/logo.png",
      "ownerUserId": null,
      "siteUrl": "https://www.1lou.me/forum-2-1.htm?format=json",
      "title": "BT之家1LOU站 - BT 之家 1LOU 站",
      "type": "feed",
      "url": "rsshub://1lou/forum-2-1"
    }
  ],
  "url": "1lou.me"
}
```
