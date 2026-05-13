# 知乎 - 用户想法

## Coverage
`index-only`

## Route
- Namespace: `zhihu`
- Namespace Name: `知乎`
- Route Path: `/people/pins/:id`
- Route Name: `用户想法`
- Example: `/zhihu/people/pins/kan-dan-45`
- URL: `www.zhihu.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `xyqfer`
- Source Location: `pin/people.ts`
- Source Module: `() => import('@/routes/zhihu/pin/people.ts')`

## Description
_None_

## Parameters
- `id`: 作者 id，可在用户主页 URL 中找到


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
  - `www.zhihu.com/people/:id/pins`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/zhihu/people/pins/kan-dan-45",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "pin/people.ts",
  "maintainers": [
    "xyqfer"
  ],
  "module": "() => import('@/routes/zhihu/pin/people.ts')",
  "name": "用户想法",
  "parameters": {
    "id": "作者 id，可在用户主页 URL 中找到"
  },
  "path": "/people/pins/:id",
  "radar": [
    {
      "source": [
        "www.zhihu.com/people/:id/pins"
      ]
    }
  ]
}
```
