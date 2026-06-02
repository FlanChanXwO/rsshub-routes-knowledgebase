# 知乎 - 知乎热榜

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/zhihu/hot/:category?`
- Route Name: `知乎热榜`
- Example: `/zhihu/hot`
- URL: `www.zhihu.com`
- Language: `_None_`
- Categories: `social-media, popular`
- Maintainers: `nczitzk, pseudoyu, DIYgod`
- Source Location: `hot.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: [{"description": "", "name": "ZHIHU_COOKIES", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "social-media",
    "popular"
  ],
  "example": "/zhihu/hot",
  "features": {
    "antiCrawler": true,
    "requireConfig": [
      {
        "description": "",
        "name": "ZHIHU_COOKIES",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 15560,
  "location": "hot.ts",
  "maintainers": [
    "nczitzk",
    "pseudoyu",
    "DIYgod"
  ],
  "name": "知乎热榜",
  "path": "/hot/:category?",
  "topFeeds": [
    {
      "description": "知乎热榜 - Powered by RSSHub",
      "errorAt": "2026-06-01T03:31:53.945Z",
      "errorMessage": "Failed query: select \"subscriptions\".\"user_id\", \"rsshub_usage\".\"rsshub_id\", \"rsshub\".\"base_url\", \"rsshub\".\"access_key\", \"rsshub\".\"error_message\" from \"subscriptions\" left join \"rsshub_usage\" on \"subscriptions\".\"user_id\" = \"rsshub_usage\".\"user_id\" left join \"rsshub\" on \"rsshub\".\"id\" = \"rsshub_usage\".\"rsshub_id\" where \"subscriptions\".\"feed_id\" = $1\nparams: 41358761177015296",
      "id": "41358761177015296",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.zhihu.com/hot",
      "title": "知乎热榜",
      "type": "feed",
      "url": "rsshub://zhihu/hot"
    }
  ],
  "view": 0
}
```
