# The Initium - 作者

## Coverage
`index-only`

## Route
- Namespace: `theinitium`
- Namespace Name: `The Initium`
- Route Path: `/theinitium/author/:type/:language?`
- Route Name: `作者`
- Example: `/theinitium/author/initium-newsroom`
- URL: `theinitium.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `AgFlore, pseudoyu`
- Source Location: `author.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: 作者 slug，可从作者主页 URL 中获取，如 `https://theinitium.com/author/initium-newsroom/`
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
  - `theinitium.com/author/:type`
- `target`: `/author/:type`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/theinitium/author/initium-newsroom",
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
  "location": "author.ts",
  "maintainers": [
    "AgFlore",
    "pseudoyu"
  ],
  "name": "作者",
  "parameters": {
    "language": "语言，简体`zh-hans`，繁体`zh-hant`，缺省为不限",
    "type": "作者 slug，可从作者主页 URL 中获取，如 `https://theinitium.com/author/initium-newsroom/`"
  },
  "path": "/author/:type/:language?",
  "radar": [
    {
      "source": [
        "theinitium.com/author/:type"
      ],
      "target": "/author/:type"
    }
  ],
  "topFeeds": [],
  "url": "theinitium.com"
}
```
