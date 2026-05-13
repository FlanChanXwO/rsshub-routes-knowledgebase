# 中国国家图书馆 - 读者云平台

## Coverage
`index-only`

## Route
- Namespace: `nlc`
- Namespace Name: `中国国家图书馆`
- Route Path: `/nlc/read/:type?`
- Route Name: `读者云平台`
- Example: `/nlc/read/电子图书`
- URL: `read.nlc.cn`
- Language: `_None_`
- Categories: `other`
- Maintainers: `nczitzk`
- Source Location: `read.tsx`
- Source Module: `_None_`

## Description
| [电子图书](http://read.nlc.cn/outRes/outResList?type=电子图书) | [电子期刊](http://read.nlc.cn/outRes/outResList?type=电子期刊) | [电子论文](http://read.nlc.cn/outRes/outResList?type=电子论文) | [电子报纸](http://read.nlc.cn/outRes/outResList?type=电子报纸) | [音视频](http://read.nlc.cn/outRes/outResList?type=音视频) |
| -------------------------------------------------------------- | -------------------------------------------------------------- | -------------------------------------------------------------- | -------------------------------------------------------------- | ---------------------------------------------------------- |

| [标准专利](http://read.nlc.cn/outRes/outResList?type=标准专利) | [工具书](http://read.nlc.cn/outRes/outResList?type=工具书) | [少儿资源](http://read.nlc.cn/outRes/outResList?type=少儿资源) |
| -------------------------------------------------------------- | ---------------------------------------------------------- | -------------------------------------------------------------- |

## Parameters
- `type`: 分类，见下表，默认为电子图书


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "| [电子图书](http://read.nlc.cn/outRes/outResList?type=电子图书) | [电子期刊](http://read.nlc.cn/outRes/outResList?type=电子期刊) | [电子论文](http://read.nlc.cn/outRes/outResList?type=电子论文) | [电子报纸](http://read.nlc.cn/outRes/outResList?type=电子报纸) | [音视频](http://read.nlc.cn/outRes/outResList?type=音视频) |\n| -------------------------------------------------------------- | -------------------------------------------------------------- | -------------------------------------------------------------- | -------------------------------------------------------------- | ---------------------------------------------------------- |\n\n| [标准专利](http://read.nlc.cn/outRes/outResList?type=标准专利) | [工具书](http://read.nlc.cn/outRes/outResList?type=工具书) | [少儿资源](http://read.nlc.cn/outRes/outResList?type=少儿资源) |\n| -------------------------------------------------------------- | ---------------------------------------------------------- | -------------------------------------------------------------- |",
  "example": "/nlc/read/电子图书",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "read.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "name": "读者云平台",
  "parameters": {
    "type": "分类，见下表，默认为电子图书"
  },
  "path": "/read/:type?",
  "test": {
    "code": 0
  },
  "topFeeds": []
}
```
