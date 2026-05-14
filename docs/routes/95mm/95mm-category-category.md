# MM 范 - 集合

## Coverage
`index-only`

## Route
- Namespace: `95mm`
- Namespace Name: `MM 范`
- Route Path: `/95mm/category/:category`
- Route Name: `集合`
- Example: `/95mm/category/1`
- URL: `95mm.org/`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `nczitzk`
- Source Location: `category.ts`
- Source Module: `_None_`

## Description
| 清纯唯美 | 摄影私房 | 明星写真 | 三次元 | 异域美景 | 性感妖姬 | 游戏主题 | 美女壁纸 |
| -------- | -------- | -------- | ------ | -------- | -------- | -------- | -------- |
| 1        | 2        | 4        | 5      | 6        | 7        | 9        | 11       |

## Parameters
- `category`: 集合，见下表


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
  "description": "| 清纯唯美 | 摄影私房 | 明星写真 | 三次元 | 异域美景 | 性感妖姬 | 游戏主题 | 美女壁纸 |\n| -------- | -------- | -------- | ------ | -------- | -------- | -------- | -------- |\n| 1        | 2        | 4        | 5      | 6        | 7        | 9        | 11       |",
  "example": "/95mm/category/1",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 142,
  "location": "category.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "集合",
  "parameters": {
    "category": "集合，见下表"
  },
  "path": "/category/:category",
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
      "errorAt": "2025-06-08T19:57:28.293Z",
      "errorMessage": "[GET] \"https://www.95mm.vip/category-2/list-1/index.html?page=1\": 404 Not Found\n[GET] \"https://www.95mm.vip/category-2/list-1/index.html?page=1\": 404 Not Found\n",
      "id": "154611732399652877",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://95mm/category/2"
    },
    {
      "description": null,
      "errorAt": "2025-06-08T19:57:27.501Z",
      "errorMessage": "[GET] \"https://www.95mm.vip/category-1/list-1/index.html?page=1\": 403 Forbidden\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "154611732399652876",
      "image": null,
      "ownerUserId": null,
      "siteUrl": null,
      "title": "Importing",
      "type": "feed",
      "url": "rsshub://95mm/category/1"
    }
  ],
  "url": "95mm.org/"
}
```
