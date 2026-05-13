# 中国计算机学会 - 计算机视觉专委会 - 学术动态 - 分类

## Coverage
`index-only`

## Route
- Namespace: `ccf`
- Namespace Name: `中国计算机学会`
- Route Path: `/ccfcv/:channel/:category`
- Route Name: `计算机视觉专委会 - 学术动态 - 分类`
- Example: `/ccf/ccfcv/xsdt/xsqy`
- URL: `ccf.org.cn`
- Language: `zh-CN`
- Categories: `study`
- Maintainers: `elxy`
- Source Location: `ccfcv/index.tsx`
- Source Module: `() => import('@/routes/ccf/ccfcv/index.tsx')`

## Description
| 学术前沿 | 热点征文 | 学术会议 |
| -------- | -------- | -------- |
| xsqy     | rdzw     | xshy     |

## Parameters
- `channel`: 频道，仅支持 `xsdt`
- `category`: 分类，见下表，亦可在网站 url 里找到


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
    "study"
  ],
  "description": "| 学术前沿 | 热点征文 | 学术会议 |\n| -------- | -------- | -------- |\n| xsqy     | rdzw     | xshy     |",
  "example": "/ccf/ccfcv/xsdt/xsqy",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "ccfcv/index.tsx",
  "maintainers": [
    "elxy"
  ],
  "module": "() => import('@/routes/ccf/ccfcv/index.tsx')",
  "name": "计算机视觉专委会 - 学术动态 - 分类",
  "parameters": {
    "category": "分类，见下表，亦可在网站 url 里找到",
    "channel": "频道，仅支持 `xsdt`"
  },
  "path": "/ccfcv/:channel/:category"
}
```
