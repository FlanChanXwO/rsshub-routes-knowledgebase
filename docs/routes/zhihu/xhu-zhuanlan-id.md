# 知乎 - xhu- 专栏

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/xhu/zhuanlan/:id`
- Route Name: `xhu- 专栏`
- Example: `/zhihu/xhu/zhuanlan/githubdaily`
- URL: `www.zhihu.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `JimenezLi`
- Source Location: `xhu/zhuanlan.ts`
- Source Module: `() => import('@/routes/zhihu/xhu/zhuanlan.ts')`

## Description
_None_

## Parameters
- `id`: 专栏 id, 可在专栏主页 URL 中找到


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
  - `zhuanlan.zhihu.com/:id`
- `target`: `/zhuanlan/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/zhihu/xhu/zhuanlan/githubdaily",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "xhu/zhuanlan.ts",
  "maintainers": [
    "JimenezLi"
  ],
  "module": "() => import('@/routes/zhihu/xhu/zhuanlan.ts')",
  "name": "xhu- 专栏",
  "parameters": {
    "id": "专栏 id, 可在专栏主页 URL 中找到"
  },
  "path": "/xhu/zhuanlan/:id",
  "radar": [
    {
      "source": [
        "zhuanlan.zhihu.com/:id"
      ],
      "target": "/zhuanlan/:id"
    }
  ]
}
```
