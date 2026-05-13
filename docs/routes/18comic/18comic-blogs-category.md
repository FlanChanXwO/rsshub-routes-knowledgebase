# 禁漫天堂 - 文庫

## Coverage
`index-only`

## Route
- Namespace: `18comic`
- Namespace Name: `禁漫天堂`
- Route Path: `/18comic/blogs/:category?`
- Route Name: `文庫`
- Example: `/18comic/blogs`
- URL: `jmcomic.group/`
- Language: `_None_`
- Categories: `anime`
- Maintainers: `nczitzk, pseudoyu`
- Source Location: `blogs.ts`
- Source Module: `_None_`

## Description
分类

| 全部 | 紳夜食堂 | 遊戲文庫 | JG GAMES | 模型山下 |
| ---- | -------- | -------- | -------- | -------- |
|      | dinner   | raiders  | jg       | figure   |

## Parameters
- `category`: 分类，见下表，默认为空即全部


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `jmcomic.group/`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "分类\n\n| 全部 | 紳夜食堂 | 遊戲文庫 | JG GAMES | 模型山下 |\n| ---- | -------- | -------- | -------- | -------- |\n|      | dinner   | raiders  | jg       | figure   |",
  "example": "/18comic/blogs",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 21,
  "location": "blogs.ts",
  "maintainers": [
    "nczitzk",
    "pseudoyu"
  ],
  "name": "文庫",
  "parameters": {
    "category": "分类，见下表，默认为空即全部"
  },
  "path": "/blogs/:category?",
  "radar": [
    {
      "source": [
        "jmcomic.group/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "最新 Blogs - 免費成人H漫線上看 - Powered by RSSHub",
      "errorAt": "2026-05-09T06:17:31.932Z",
      "errorMessage": "[GET] \"https://jmcomic1.me/blogs\": 403 Forbidden\n",
      "id": "181721376290441216",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://jmcomic1.me/blogs",
      "title": "最新 Blogs - 禁漫天堂",
      "type": "feed",
      "url": "rsshub://18comic/blogs"
    }
  ],
  "url": "jmcomic.group/"
}
```
