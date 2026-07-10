# 不太灵影视 - 影视资源下载列表

## Coverage
`index-only`

## Route
- Namespace: `bt0`
- Namespace Name: `不太灵影视`
- Route Path: `/bt0/mv/:number/:domain?`
- Route Name: `影视资源下载列表`
- Example: `/bt0/mv/35575567/2`
- URL: `2bt0.com`
- Language: `_None_`
- Categories: `multimedia`
- Maintainers: `miemieYaho`
- Source Location: `mv.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `number`: 影视详情id, 网页路径为`/mv/{id}.html`其中的id部分, 一般为8位纯数字
- `domain`: 数字1-9, 比如1表示请求域名为 1bt0.com, 默认为 2


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: true
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `2bt0.com/mv/`

## Raw JSON
```json
{
  "categories": [
    "multimedia"
  ],
  "example": "/bt0/mv/35575567/2",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": true,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 5,
  "location": "mv.ts",
  "maintainers": [
    "miemieYaho"
  ],
  "name": "影视资源下载列表",
  "parameters": {
    "domain": "数字1-9, 比如1表示请求域名为 1bt0.com, 默认为 2",
    "number": "影视详情id, 网页路径为`/mv/{id}.html`其中的id部分, 一般为8位纯数字"
  },
  "path": "/mv/:number/:domain?",
  "radar": [
    {
      "source": [
        "2bt0.com/mv/"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "沙丘2 - Powered by RSSHub",
      "errorAt": "2025-03-18T21:05:00.308Z",
      "errorMessage": "api error\n",
      "id": "66767312028595200",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.2bt0.com/mv/35575567.html",
      "title": "沙丘2",
      "type": "feed",
      "url": "rsshub://bt0/mv/35575567/2"
    },
    {
      "description": "企鹅人 - Powered by RSSHub",
      "errorAt": "2025-02-09T15:57:33.039Z",
      "errorMessage": "api error\n",
      "id": "76153441985198080",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.2bt0.com/mv/35604181.html",
      "title": "企鹅人",
      "type": "feed",
      "url": "rsshub://bt0/mv/35604181"
    }
  ]
}
```
