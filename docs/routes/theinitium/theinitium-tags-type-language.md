# The Initium - 话题・标签

## Coverage
`index-only`

## Route
- Namespace: `theinitium`
- Namespace Name: `The Initium`
- Route Path: `/theinitium/tags/:type/:language?`
- Route Name: `话题・标签`
- Example: `/theinitium/tags/south-korea`
- URL: `theinitium.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `AgFlore, pseudoyu`
- Source Location: `tags.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: 标签 slug，可从标签页 URL 中获取，如 `https://theinitium.com/tag/south-korea/` 则为 `south-korea`
- `language`: 语言，简体`zh-hans`，繁体`zh-hant`，缺省为不限


## Features
- `requireConfig`: [{"description": "端传媒会员登录后的 Cookie，用于获取付费文章全文。", "name": "INITIUM_MEMBER_COOKIE", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `theinitium.com/tag/:type`
- `target`: `/tags/:type`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/theinitium/tags/south-korea",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "端传媒会员登录后的 Cookie，用于获取付费文章全文。",
        "name": "INITIUM_MEMBER_COOKIE",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "tags.ts",
  "maintainers": [
    "AgFlore",
    "pseudoyu"
  ],
  "name": "话题・标签",
  "parameters": {
    "language": "语言，简体`zh-hans`，繁体`zh-hant`，缺省为不限",
    "type": "标签 slug，可从标签页 URL 中获取，如 `https://theinitium.com/tag/south-korea/` 则为 `south-korea`"
  },
  "path": "/tags/:type/:language?",
  "radar": [
    {
      "source": [
        "theinitium.com/tag/:type"
      ],
      "target": "/tags/:type"
    }
  ],
  "topFeeds": [],
  "url": "theinitium.com"
}
```
