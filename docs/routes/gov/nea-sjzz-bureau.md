# 国家能源局 - 司工作进展

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/nea/sjzz/:bureau`
- Route Name: `司工作进展`
- Example: `/gov/nea/sjzz/ghs`
- URL: `www.nea.gov.cn/`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `nczitzk, pseudoyu`
- Source Location: `nea/bureau.ts`
- Source Module: `() => import('@/routes/gov/nea/bureau.ts')`

## Description
_None_

## Parameters
- `bureau`: {"description": "司局", "options": [{"label": "综合司", "value": "zhs"}, {"label": "法改司", "value": "fgs"}, {"label": "规划司", "value": "ghs"}, {"label": "科技司", "value": "kjs"}, {"label": "电力司", "value": "dls"}, {"label": "核电司", "value": "hds"}, {"label": "煤炭司", "value": "mts"}, {"label": "油气司", "value": "yqs"}, {"label": "新能源司", "value": "xny"}, {"label": "监管司", "value": "jgs"}, {"label": "安全司", "value": "aqs"}, {"label": "国际司", "value": "gjs"}, {"label": "机关党委（人事司）", "value": "jgdw"}]}


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
  - `nea.gov.cn/sjzz/:bureau/index.htm`
- `target`: `/nea/sjzz/:bureau`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/gov/nea/sjzz/ghs",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "nea/bureau.ts",
  "maintainers": [
    "nczitzk",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/gov/nea/bureau.ts')",
  "name": "司工作进展",
  "parameters": {
    "bureau": {
      "description": "司局",
      "options": [
        {
          "label": "综合司",
          "value": "zhs"
        },
        {
          "label": "法改司",
          "value": "fgs"
        },
        {
          "label": "规划司",
          "value": "ghs"
        },
        {
          "label": "科技司",
          "value": "kjs"
        },
        {
          "label": "电力司",
          "value": "dls"
        },
        {
          "label": "核电司",
          "value": "hds"
        },
        {
          "label": "煤炭司",
          "value": "mts"
        },
        {
          "label": "油气司",
          "value": "yqs"
        },
        {
          "label": "新能源司",
          "value": "xny"
        },
        {
          "label": "监管司",
          "value": "jgs"
        },
        {
          "label": "安全司",
          "value": "aqs"
        },
        {
          "label": "国际司",
          "value": "gjs"
        },
        {
          "label": "机关党委（人事司）",
          "value": "jgdw"
        }
      ]
    }
  },
  "path": "/nea/sjzz/:bureau",
  "radar": [
    {
      "source": [
        "nea.gov.cn/sjzz/:bureau/index.htm"
      ],
      "target": "/nea/sjzz/:bureau"
    }
  ],
  "url": "www.nea.gov.cn/"
}
```
