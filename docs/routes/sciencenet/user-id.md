# 科学网 - 用户博客

## Coverage
`index-only`

## Route
- Namespace: `sciencenet`
- Namespace Name: `科学网`
- Route Path: `/user/:id`
- Route Name: `用户博客`
- Example: `/sciencenet/user/tony8310`
- URL: `blog.sciencenet.cn`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `user.ts`
- Source Module: `() => import('@/routes/sciencenet/user.ts')`

## Description
_None_

## Parameters
- `id`: 用户 id，可在对用户博客页 URL 中找到


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
  - `blog.sciencenet.cn/u/:id`
  - `blog.sciencenet.cn/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/sciencenet/user/tony8310",
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
    "nczitzk"
  ],
  "module": "() => import('@/routes/sciencenet/user.ts')",
  "name": "用户博客",
  "parameters": {
    "id": "用户 id，可在对用户博客页 URL 中找到"
  },
  "path": "/user/:id",
  "radar": [
    {
      "source": [
        "blog.sciencenet.cn/u/:id",
        "blog.sciencenet.cn/"
      ]
    }
  ]
}
```
