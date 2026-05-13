# 国家能源局 - 文件发布

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/miit/wjfb/:ministry`
- Route Name: `文件发布`
- Example: `/gov/miit/wjfb/ghs`
- URL: `www.nea.gov.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `Fatpandac`
- Source Location: `miit/wjfb.ts`
- Source Module: `() => import('@/routes/gov/miit/wjfb.ts')`

## Description
_None_

## Parameters
- `ministry`: 部门缩写，可以在对应 URL 中获取


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
  - `miit.gov.cn/jgsj/:ministry/wjfb/index.html`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/gov/miit/wjfb/ghs",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "miit/wjfb.ts",
  "maintainers": [
    "Fatpandac"
  ],
  "module": "() => import('@/routes/gov/miit/wjfb.ts')",
  "name": "文件发布",
  "parameters": {
    "ministry": "部门缩写，可以在对应 URL 中获取"
  },
  "path": "/miit/wjfb/:ministry",
  "radar": [
    {
      "source": [
        "miit.gov.cn/jgsj/:ministry/wjfb/index.html"
      ]
    }
  ]
}
```
