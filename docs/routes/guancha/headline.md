# 观察者网 - 头条

## Coverage
`index-only`

## Route
- Namespace: `guancha`
- Namespace Name: `观察者网`
- Route Path: `/headline`
- Route Name: `头条`
- Example: `/guancha/headline`
- URL: `guancha.cn/GuanChaZheTouTiao`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `headline.ts`
- Source Module: `() => import('@/routes/guancha/headline.ts')`

## Description
_None_

## Parameters
_None_


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
  - `guancha.cn/GuanChaZheTouTiao`
  - `guancha.cn/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/guancha/headline",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "headline.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/guancha/headline.ts')",
  "name": "头条",
  "parameters": {},
  "path": "/headline",
  "radar": [
    {
      "source": [
        "guancha.cn/GuanChaZheTouTiao",
        "guancha.cn/"
      ]
    }
  ],
  "url": "guancha.cn/GuanChaZheTouTiao"
}
```
