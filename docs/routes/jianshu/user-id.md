# 简书 - 作者

## Coverage
`index-only`

## Route
- Namespace: `jianshu`
- Namespace Name: `简书`
- Route Path: `/user/:id`
- Route Name: `作者`
- Example: `/jianshu/user/yZq3ZV`
- URL: `www.jianshu.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `DIYgod, HenryQW, JimenezLi`
- Source Location: `user.ts`
- Source Module: `() => import('@/routes/jianshu/user.ts')`

## Description
_None_

## Parameters
- `id`: 作者 id, 可在作者主页 URL 中找到


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
  - `www.jianshu.com/u/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/jianshu/user/yZq3ZV",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "user.ts",
  "maintainers": [
    "DIYgod",
    "HenryQW",
    "JimenezLi"
  ],
  "module": "() => import('@/routes/jianshu/user.ts')",
  "name": "作者",
  "parameters": {
    "id": "作者 id, 可在作者主页 URL 中找到"
  },
  "path": "/user/:id",
  "radar": [
    {
      "source": [
        "www.jianshu.com/u/:id"
      ]
    }
  ],
  "view": 0
}
```
