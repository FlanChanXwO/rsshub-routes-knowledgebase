# 异次元软件世界 - 标签

## Coverage
`index-only`

## Route
- Namespace: `iplaysoft`
- Namespace Name: `异次元软件世界`
- Route Path: `/tag/:slug`
- Route Name: `标签`
- Example: `/iplaysoft/tag/windows`
- URL: `www.iplaysoft.com`
- Language: `zh-CN`
- Categories: `program-update`
- Maintainers: `cscnk52`
- Source Location: `tag.ts`
- Source Module: `() => import('@/routes/iplaysoft/tag.ts')`

## Description
_None_

## Parameters
- `slug`: 标签名称


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
  - `www.iplaysoft.com/tag/:slug`
- `target`: `/tag/:slug`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/iplaysoft/tag/windows",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "tag.ts",
  "maintainers": [
    "cscnk52"
  ],
  "module": "() => import('@/routes/iplaysoft/tag.ts')",
  "name": "标签",
  "parameters": {
    "slug": "标签名称"
  },
  "path": "/tag/:slug",
  "radar": [
    {
      "source": [
        "www.iplaysoft.com/tag/:slug"
      ],
      "target": "/tag/:slug"
    }
  ],
  "url": "www.iplaysoft.com",
  "view": 0
}
```
