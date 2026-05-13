# SegmentFault - 博客

## Coverage
`index-only`

## Route
- Namespace: `segmentfault`
- Namespace Name: `SegmentFault`
- Route Path: `/blogs/:tag`
- Route Name: `博客`
- Example: `/segmentfault/blogs/go`
- URL: `segmentfault.com`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `shiluanzzz`
- Source Location: `blogs.ts`
- Source Module: `() => import('@/routes/segmentfault/blogs.ts')`

## Description
_None_

## Parameters
- `tag`: 标签名称，在 [标签](https://segmentfault.com/tags) 中可以找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `segmentfault.com/t/:tag/blogs`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/segmentfault/blogs/go",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "blogs.ts",
  "maintainers": [
    "shiluanzzz"
  ],
  "module": "() => import('@/routes/segmentfault/blogs.ts')",
  "name": "博客",
  "parameters": {
    "tag": "标签名称，在 [标签](https://segmentfault.com/tags) 中可以找到"
  },
  "path": "/blogs/:tag",
  "radar": [
    {
      "source": [
        "segmentfault.com/t/:tag/blogs"
      ]
    }
  ]
}
```
