# 雪球 - 用户动态

## Coverage
`index-only`

## Route
- Namespace: `xueqiu`
- Namespace Name: `雪球`
- Route Path: `/xueqiu/user/:id/:type?`
- Route Name: `用户动态`
- Example: `/xueqiu/user/8152922548`
- URL: `danjuanapp.com`
- Language: `_None_`
- Categories: `finance, popular`
- Maintainers: `imlonghao`
- Source Location: `user.ts`
- Source Module: `_None_`

## Description
| 原发布 | 长文 | 问答 | 热门 | 交易 |
| ------ | ---- | ---- | ---- | ---- |
| 0      | 2    | 4    | 9    | 11   |

## Parameters
- `id`: 用户 id, 可在用户主页 URL 中找到
- `type`: 动态的类型, 不填则默认全部


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `xueqiu.com/u/:id`
- `target`: `/user/:id`

## Raw JSON
```json
{
  "categories": [
    "finance",
    "popular"
  ],
  "description": "| 原发布 | 长文 | 问答 | 热门 | 交易 |\n| ------ | ---- | ---- | ---- | ---- |\n| 0      | 2    | 4    | 9    | 11   |",
  "example": "/xueqiu/user/8152922548",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2779,
  "location": "user.ts",
  "maintainers": [
    "imlonghao"
  ],
  "name": "用户动态",
  "parameters": {
    "id": "用户 id, 可在用户主页 URL 中找到",
    "type": "动态的类型, 不填则默认全部"
  },
  "path": "/user/:id/:type?",
  "radar": [
    {
      "source": [
        "xueqiu.com/u/:id"
      ],
      "target": "/user/:id"
    }
  ],
  "topFeeds": [
    {
      "description": "大道无形我有型 的雪球全部动态 - Powered by RSSHub",
      "errorAt": "2026-06-09T07:35:01.653Z",
      "errorMessage": "Failed to fetch\nUnexpected token '<', \"<textarea \"... is not valid JSON\n522 <none>\nNavigating frame was detached\nFailed to fetch\nCould not find Chrome (ver. 136.0.7103.49). This can occur if either\n 1. you did not perform an installation before running the script (e.g. `npx puppeteer browsers install chrome`) or\n 2. your cache path is incorrectly configured (which is: /app/node_modules/.cache/puppeteer).\nFor (2), check out our guide on configuring puppeteer at https://pptr.dev/guides/configuration.\nUnexpected token '<', \"<textarea \"... is not valid JSON\n502 Bad Gateway\npage.evaluate: SyntaxError: Unexpected token '<', \"<textarea \"... is not valid JSON\n",
      "id": "54945423974379543",
      "image": "https://xavatar.imedao.com/community/20263/1777391133564-1777391133895.jpg!180x180.png",
      "ownerUserId": null,
      "siteUrl": "https://xueqiu.com/u/1247347556",
      "title": "大道无形我有型 的雪球全部动态",
      "type": "feed",
      "url": "rsshub://xueqiu/user/1247347556"
    },
    {
      "description": "超级鹿鼎公 的雪球全部动态 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "60231927983439872",
      "image": "https://xavatar.imedao.com/community/20147/1408271545017-1408271562251.jpg!180x180.png",
      "ownerUserId": null,
      "siteUrl": "https://xueqiu.com/u/8790885129",
      "title": "超级鹿鼎公 的雪球全部动态",
      "type": "feed",
      "url": "rsshub://xueqiu/user/8790885129"
    }
  ]
}
```
