# 什么值得买 - 用户爆料

## Coverage
`index-only`

## Route
- Namespace: `smzdm`
- Namespace Name: `什么值得买`
- Route Path: `/baoliao/:uid`
- Route Name: `用户爆料`
- Example: `/smzdm/baoliao/7367111021`
- URL: `post.smzdm.com`
- Language: `zh-CN`
- Categories: `shopping`
- Maintainers: `nczitzk`
- Source Location: `baoliao.ts`
- Source Module: `() => import('@/routes/smzdm/baoliao.ts')`

## Description
_None_

## Parameters
- `uid`: 用户id，网址上直接可以看到


## Features
- `requireConfig`: [{"description": "什么值得买登录后的 Cookie 值", "name": "SMZDM_COOKIE"}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `zhiyou.smzdm.com/member/:uid/baoliao`

## Raw JSON
```json
{
  "categories": [
    "shopping"
  ],
  "example": "/smzdm/baoliao/7367111021",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "什么值得买登录后的 Cookie 值",
        "name": "SMZDM_COOKIE"
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "baoliao.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/smzdm/baoliao.ts')",
  "name": "用户爆料",
  "parameters": {
    "uid": "用户id，网址上直接可以看到"
  },
  "path": "/baoliao/:uid",
  "radar": [
    {
      "source": [
        "zhiyou.smzdm.com/member/:uid/baoliao"
      ]
    }
  ]
}
```
