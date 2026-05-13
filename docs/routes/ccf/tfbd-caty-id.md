# 中国计算机学会 - 大数据专家委员会

## Coverage
`index-only`

## Route
- Namespace: `ccf`
- Namespace Name: `中国计算机学会`
- Route Path: `/tfbd/:caty/:id`
- Route Name: `大数据专家委员会`
- Example: `/ccf/tfbd/xwdt/tzgg`
- URL: `ccf.org.cn`
- Language: `zh-CN`
- Categories: `study`
- Maintainers: `tudou027`
- Source Location: `tfbd/index.ts`
- Source Module: `() => import('@/routes/ccf/tfbd/index.ts')`

## Description
_None_

## Parameters
- `caty`: 主分类，可在 URL 找到
- `id`: 子分类，可在 URL 找到


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
  - `tfbd.ccf.org.cn/tfbd/:caty/:id`
  - `tfbd.ccf.org.cn/`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "example": "/ccf/tfbd/xwdt/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "tfbd/index.ts",
  "maintainers": [
    "tudou027"
  ],
  "module": "() => import('@/routes/ccf/tfbd/index.ts')",
  "name": "大数据专家委员会",
  "parameters": {
    "caty": "主分类，可在 URL 找到",
    "id": "子分类，可在 URL 找到"
  },
  "path": "/tfbd/:caty/:id",
  "radar": [
    {
      "source": [
        "tfbd.ccf.org.cn/tfbd/:caty/:id",
        "tfbd.ccf.org.cn/"
      ]
    }
  ]
}
```
