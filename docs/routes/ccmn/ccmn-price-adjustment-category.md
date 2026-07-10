# 长江有色网 - 调价动态

## Coverage
`index-only`

## Route
- Namespace: `ccmn`
- Namespace Name: `长江有色网`
- Route Path: `/ccmn/price-adjustment/:category`
- Route Name: `调价动态`
- Example: `/ccmn/price-adjustment/copper`
- URL: `www.ccmn.cn`
- Language: `_None_`
- Categories: `other`
- Maintainers: `chrisis58`
- Source Location: `price-adjustment.tsx`
- Source Module: `_None_`

## Description
长江有色网的金属调价动态，包括铜、铝、锌、锡、铅、镍等金属。

## Parameters
- `category`: {"description": "金属类别", "options": [{"label": "铜", "value": "copper"}, {"label": "铝", "value": "alu"}, {"label": "锌", "value": "zn"}, {"label": "锡", "value": "sn"}, {"label": "铅", "value": "pb"}, {"label": "镍", "value": "ni"}]}


## Features
- `supportRadar`: true
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: false

## Radar
### Rule 1
- `source`:
  - `copper.ccmn.cn/:suffix`
  - `copper.ccmn.cn/:suffix/:subsuffix?`
- `target`: `/price-adjustment/copper`
### Rule 2
- `source`:
  - `alu.ccmn.cn/:suffix`
  - `alu.ccmn.cn/:suffix/:subsuffix?`
- `target`: `/price-adjustment/alu`
### Rule 3
- `source`:
  - `zn.ccmn.cn/:suffix`
  - `zn.ccmn.cn/:suffix/:subsuffix?`
- `target`: `/price-adjustment/zn`
### Rule 4
- `source`:
  - `sn.ccmn.cn/:suffix`
  - `sn.ccmn.cn/:suffix/:subsuffix?`
- `target`: `/price-adjustment/sn`
### Rule 5
- `source`:
  - `pb.ccmn.cn/:suffix`
  - `pb.ccmn.cn/:suffix/:subsuffix?`
- `target`: `/price-adjustment/pb`
### Rule 6
- `source`:
  - `ni.ccmn.cn/:suffix`
  - `ni.ccmn.cn/:suffix/:subsuffix?`
- `target`: `/price-adjustment/ni`

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "长江有色网的金属调价动态，包括铜、铝、锌、锡、铅、镍等金属。",
  "example": "/ccmn/price-adjustment/copper",
  "features": {
    "antiCrawler": false,
    "nsfw": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "price-adjustment.tsx",
  "maintainers": [
    "chrisis58"
  ],
  "name": "调价动态",
  "parameters": {
    "category": {
      "description": "金属类别",
      "options": [
        {
          "label": "铜",
          "value": "copper"
        },
        {
          "label": "铝",
          "value": "alu"
        },
        {
          "label": "锌",
          "value": "zn"
        },
        {
          "label": "锡",
          "value": "sn"
        },
        {
          "label": "铅",
          "value": "pb"
        },
        {
          "label": "镍",
          "value": "ni"
        }
      ]
    }
  },
  "path": "/price-adjustment/:category",
  "radar": [
    {
      "source": [
        "copper.ccmn.cn/:suffix",
        "copper.ccmn.cn/:suffix/:subsuffix?"
      ],
      "target": "/price-adjustment/copper"
    },
    {
      "source": [
        "alu.ccmn.cn/:suffix",
        "alu.ccmn.cn/:suffix/:subsuffix?"
      ],
      "target": "/price-adjustment/alu"
    },
    {
      "source": [
        "zn.ccmn.cn/:suffix",
        "zn.ccmn.cn/:suffix/:subsuffix?"
      ],
      "target": "/price-adjustment/zn"
    },
    {
      "source": [
        "sn.ccmn.cn/:suffix",
        "sn.ccmn.cn/:suffix/:subsuffix?"
      ],
      "target": "/price-adjustment/sn"
    },
    {
      "source": [
        "pb.ccmn.cn/:suffix",
        "pb.ccmn.cn/:suffix/:subsuffix?"
      ],
      "target": "/price-adjustment/pb"
    },
    {
      "source": [
        "ni.ccmn.cn/:suffix",
        "ni.ccmn.cn/:suffix/:subsuffix?"
      ],
      "target": "/price-adjustment/ni"
    }
  ],
  "topFeeds": []
}
```
