# 中国人民银行 - 中华人民共和国农业农村部国际合作司

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `中国人民银行`
- Route Path: `/gov/moa/gjs/:category{.+}?`
- Route Name: `中华人民共和国农业农村部国际合作司`
- Example: `/gov/moa/gjs/gzdt`
- URL: `www.gjs.moa.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `moa/gjs.ts`
- Source Module: `_None_`

## Description
::: tip
若订阅 [中华人民共和国农业农村部国际合作司工作动态](https://www.gjs.moa.gov.cn/gzdt/)，网址为 `https://www.gjs.moa.gov.cn/gzdt/`，请截取 `https://www.gjs.moa.gov.cn/` 到末尾 `/` 的部分 `gzdt` 作为 `category` 参数填入，此时目标路由为 [`/gov/moa/gjs/gzdt`](https://rsshub.app/gov/moa/gjs/gzdt)。
:::

| [工作动态](http://www.gjs.moa.gov.cn/gzdt/) | [通知公告](http://www.gjs.moa.gov.cn/tzgg/) | [“一带一路” 合作和农业走出去](http://www.gjs.moa.gov.cn/ydylhzhhnyzcq/) | [农业国际贸易监测与展望](http://www.gjs.moa.gov.cn/ncpmy/) | [多双边合作](http://www.gjs.moa.gov.cn/dsbhz/) |
| ------------------------------------------- | ------------------------------------------- | ----------------------------------------------------------------------- | ---------------------------------------------------------- | ---------------------------------------------- |
| [gzdt](https://rsshub.app/gov/moa/gjs/gzdt) | [tzgg](https://rsshub.app/gov/moa/gjs/tzgg) | [ydylhzhhnyzcq](https://rsshub.app/gov/moa/gjs/ydylhzhhnyzcq)           | [ncpmy](https://rsshub.app/gov/moa/gjs/ncpmy)              | [dsbhz](https://rsshub.app/gov/moa/gjs/dsbhz)  |

## Parameters
- `category`: {"description": "分类，默认为 `gzdt`，即工作动态，可在对应分类页 URL 中找到", "options": [{"label": "工作动态", "value": "gzdt"}, {"label": "通知公告", "value": "tzgg"}, {"label": "“一带一路”合作和农业走出去", "value": "ydylhzhhnyzcq"}, {"label": "农业国际贸易监测与展望", "value": "ncpmy"}, {"label": "多双边合作", "value": "dsbhz"}]}


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
  - `www.gjs.moa.gov.cn/:category{.+}?`
### Rule 2
- `title`: `工作动态`
- `source`:
  - `www.gjs.moa.gov.cn/gzdt/`
- `target`: `/moa/gjs/gzdt`
### Rule 3
- `title`: `通知公告`
- `source`:
  - `www.gjs.moa.gov.cn/tzgg/`
- `target`: `/moa/gjs/tzgg`
### Rule 4
- `title`: `“一带一路”合作和农业走出去`
- `source`:
  - `www.gjs.moa.gov.cn/ydylhzhhnyzcq/`
- `target`: `/moa/gjs/ydylhzhhnyzcq`
### Rule 5
- `title`: `农业国际贸易监测与展望`
- `source`:
  - `www.gjs.moa.gov.cn/ncpmy/`
- `target`: `/moa/gjs/ncpmy`
### Rule 6
- `title`: `多双边合作`
- `source`:
  - `www.gjs.moa.gov.cn/dsbhz/`
- `target`: `/moa/gjs/dsbhz`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "::: tip\n若订阅 [中华人民共和国农业农村部国际合作司工作动态](https://www.gjs.moa.gov.cn/gzdt/)，网址为 `https://www.gjs.moa.gov.cn/gzdt/`，请截取 `https://www.gjs.moa.gov.cn/` 到末尾 `/` 的部分 `gzdt` 作为 `category` 参数填入，此时目标路由为 [`/gov/moa/gjs/gzdt`](https://rsshub.app/gov/moa/gjs/gzdt)。\n:::\n\n| [工作动态](http://www.gjs.moa.gov.cn/gzdt/) | [通知公告](http://www.gjs.moa.gov.cn/tzgg/) | [“一带一路” 合作和农业走出去](http://www.gjs.moa.gov.cn/ydylhzhhnyzcq/) | [农业国际贸易监测与展望](http://www.gjs.moa.gov.cn/ncpmy/) | [多双边合作](http://www.gjs.moa.gov.cn/dsbhz/) |\n| ------------------------------------------- | ------------------------------------------- | ----------------------------------------------------------------------- | ---------------------------------------------------------- | ---------------------------------------------- |\n| [gzdt](https://rsshub.app/gov/moa/gjs/gzdt) | [tzgg](https://rsshub.app/gov/moa/gjs/tzgg) | [ydylhzhhnyzcq](https://rsshub.app/gov/moa/gjs/ydylhzhhnyzcq)           | [ncpmy](https://rsshub.app/gov/moa/gjs/ncpmy)              | [dsbhz](https://rsshub.app/gov/moa/gjs/dsbhz)  |",
  "example": "/gov/moa/gjs/gzdt",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "moa/gjs.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "中华人民共和国农业农村部国际合作司",
  "parameters": {
    "category": {
      "description": "分类，默认为 `gzdt`，即工作动态，可在对应分类页 URL 中找到",
      "options": [
        {
          "label": "工作动态",
          "value": "gzdt"
        },
        {
          "label": "通知公告",
          "value": "tzgg"
        },
        {
          "label": "“一带一路”合作和农业走出去",
          "value": "ydylhzhhnyzcq"
        },
        {
          "label": "农业国际贸易监测与展望",
          "value": "ncpmy"
        },
        {
          "label": "多双边合作",
          "value": "dsbhz"
        }
      ]
    }
  },
  "path": "/moa/gjs/:category{.+}?",
  "radar": [
    {
      "source": [
        "www.gjs.moa.gov.cn/:category{.+}?"
      ]
    },
    {
      "source": [
        "www.gjs.moa.gov.cn/gzdt/"
      ],
      "target": "/moa/gjs/gzdt",
      "title": "工作动态"
    },
    {
      "source": [
        "www.gjs.moa.gov.cn/tzgg/"
      ],
      "target": "/moa/gjs/tzgg",
      "title": "通知公告"
    },
    {
      "source": [
        "www.gjs.moa.gov.cn/ydylhzhhnyzcq/"
      ],
      "target": "/moa/gjs/ydylhzhhnyzcq",
      "title": "“一带一路”合作和农业走出去"
    },
    {
      "source": [
        "www.gjs.moa.gov.cn/ncpmy/"
      ],
      "target": "/moa/gjs/ncpmy",
      "title": "农业国际贸易监测与展望"
    },
    {
      "source": [
        "www.gjs.moa.gov.cn/dsbhz/"
      ],
      "target": "/moa/gjs/dsbhz",
      "title": "多双边合作"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [],
  "url": "www.gjs.moa.gov.cn",
  "view": 0
}
```
