# 小米 - 小米众筹

## Coverage
`index-only`

## Route
- Namespace: `mi`
- Namespace Name: `小米`
- Route Path: `/crowdfunding`
- Route Name: `小米众筹`
- Example: `/mi/crowdfunding`
- URL: `mi.com`
- Language: `zh-CN`
- Categories: `shopping`
- Maintainers: `DIYgod, nuomi1`
- Source Location: `crowdfunding.ts`
- Source Module: `() => import('@/routes/mi/crowdfunding.ts')`

## Description
_None_

## Parameters
_None_


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
  - `m.mi.com/crowdfunding/home`
- `target`: `/crowdfunding`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "example": "/mi/crowdfunding",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "crowdfunding.ts",
  "maintainers": [
    "DIYgod",
    "nuomi1"
  ],
  "module": "() => import('@/routes/mi/crowdfunding.ts')",
  "name": "小米众筹",
  "path": "/crowdfunding",
  "radar": [
    {
      "source": [
        "m.mi.com/crowdfunding/home"
      ],
      "target": "/crowdfunding"
    }
  ],
  "view": 5
}
```
