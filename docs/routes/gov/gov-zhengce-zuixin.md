# 中国人民银行 - 最新政策

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `中国人民银行`
- Route Path: `/gov/zhengce/zuixin`
- Route Name: `最新政策`
- Example: `/gov/zhengce/zuixin`
- URL: `www.gov.cn/zhengce/zuixin.htm`
- Language: `_None_`
- Categories: `government, popular`
- Maintainers: `SettingDust, nczitzk`
- Source Location: `zhengce/index.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


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
  - `www.gov.cn/zhengce/zuixin.htm`
  - `www.gov.cn/`

## Raw JSON
```json
{
  "categories": [
    "government",
    "popular"
  ],
  "example": "/gov/zhengce/zuixin",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2223,
  "location": "zhengce/index.ts",
  "maintainers": [
    "SettingDust",
    "nczitzk"
  ],
  "name": "最新政策",
  "parameters": {},
  "path": [
    "/zhengce/zuixin",
    "/zhengce/:category{.+}?"
  ],
  "radar": [
    {
      "source": [
        "www.gov.cn/zhengce/zuixin.htm",
        "www.gov.cn/"
      ]
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "中共中央和国务院最近发布的政策 - Powered by RSSHub",
      "errorAt": "2026-02-04T15:26:39.860Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\nthis route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\nFailed to fetch\n",
      "id": "55178154410946580",
      "image": "https://www.gov.cn/images/gtrs_logo_rt.png",
      "ownerUserId": null,
      "siteUrl": "https://www.gov.cn/zhengce/zuixin/",
      "title": "中国政府网 - 最新政策",
      "type": "feed",
      "url": "rsshub://gov/zhengce/zuixin"
    }
  ],
  "url": "www.gov.cn/zhengce/zuixin.htm"
}
```
