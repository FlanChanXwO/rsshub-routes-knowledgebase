# MM 范 - 分类

## Coverage
`index-only`

## Route
- Namespace: `95mm`
- Namespace Name: `MM 范`
- Route Path: `/95mm/tab/:tab?`
- Route Name: `分类`
- Example: `/95mm/tab/热门`
- URL: `95mm.org/`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `nczitzk`
- Source Location: `tab.ts`
- Source Module: `_None_`

## Description
| 最新 | 热门 | 校花 | 森系 | 清纯 | 童颜 | 嫩模 | 少女 |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |

## Parameters
- `tab`: 分类，见下表，默认为最新


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `95mm.org/`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "description": "| 最新 | 热门 | 校花 | 森系 | 清纯 | 童颜 | 嫩模 | 少女 |\n| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |",
  "example": "/95mm/tab/热门",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 17,
  "location": "tab.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "分类",
  "parameters": {
    "tab": "分类，见下表，默认为最新"
  },
  "path": "/tab/:tab?",
  "radar": [
    {
      "source": [
        "95mm.org/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": null,
      "errorAt": "2025-06-08T19:57:25.619Z",
      "errorMessage": "[GET] \"https://www.95mm.vip/home-ajax/index.html?tabcid=热门&page=1\": 404 Not Found\n",
      "id": "154611732399652869",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://95mm/tab/%E7%83%AD%E9%97%A8"
    },
    {
      "description": null,
      "errorAt": "2025-07-14T11:50:59.607Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "167549568401875968",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://95mm/tab/%E6%9C%80%E6%96%B0"
    }
  ],
  "url": "95mm.org/"
}
```
