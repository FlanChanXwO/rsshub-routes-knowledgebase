# 观察者网 - 个人主页文章

## Coverage
`index-only`

## Route
- Namespace: `guancha`
- Namespace Name: `观察者网`
- Route Path: `/personalpage/:uid`
- Route Name: `个人主页文章`
- Example: `/guancha/personalpage/243983`
- URL: `guancha.cn`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `Jeason0228`
- Source Location: `personalpage.ts`
- Source Module: `() => import('@/routes/guancha/personalpage.ts')`

## Description
_None_

## Parameters
- `uid`: 用户id， 可在URL中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/guancha/personalpage/243983",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "personalpage.ts",
  "maintainers": [
    "Jeason0228"
  ],
  "module": "() => import('@/routes/guancha/personalpage.ts')",
  "name": "个人主页文章",
  "parameters": {
    "uid": "用户id， 可在URL中找到"
  },
  "path": "/personalpage/:uid"
}
```
