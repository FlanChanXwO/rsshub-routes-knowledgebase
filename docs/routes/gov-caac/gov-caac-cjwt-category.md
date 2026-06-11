# 中国民用航空局 - 公众留言

## Coverage
`index-only`

## Route
- Namespace: `gov/caac`
- Namespace Name: `中国民用航空局`
- Route Path: `/gov/caac/cjwt/:category?`
- Route Name: `公众留言`
- Example: `/gov/caac/cjwt`
- URL: `caac.gov.cn/HDJL/`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `cjwt.tsx`
- Source Module: `_None_`

## Description
| 机票 | 托运 | 无人机 | 体检 | 行政审批 | 投诉 |
| ---- | ---- | ------ | ---- | -------- | ---- |

## Parameters
- `category`: 分类，见下表，默认为全部


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
  - `caac.gov.cn/HDJL/`
- `target`: `/cjwt`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 机票 | 托运 | 无人机 | 体检 | 行政审批 | 投诉 |\n| ---- | ---- | ------ | ---- | -------- | ---- |",
  "example": "/gov/caac/cjwt",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "cjwt.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "公众留言",
  "parameters": {
    "category": "分类，见下表，默认为全部"
  },
  "path": "/cjwt/:category?",
  "radar": [
    {
      "source": [
        "caac.gov.cn/HDJL/"
      ],
      "target": "/cjwt"
    }
  ],
  "topFeeds": [],
  "url": "caac.gov.cn/HDJL/"
}
```
