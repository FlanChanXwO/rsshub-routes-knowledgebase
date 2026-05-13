# LikeShop - Posts

## Coverage
`index-only`

## Route
- Namespace: `likeshop`
- Namespace Name: `LikeShop`
- Route Path: `/:site`
- Route Name: `Posts`
- Example: `/likeshop/nytimes`
- URL: `likeshop.me`
- Language: `en`
- Categories: `social-media`
- Maintainers: `nickyfoto`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/likeshop/index.ts')`

## Description
LikeShop link in bio takes your audience from Instagram and TikTok to your website in one easy step.

## Parameters
- `site`: the site attached to likeshop.me/


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
  - `likeshop.me/`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "LikeShop link in bio takes your audience from Instagram and TikTok to your website in one easy step.",
  "example": "/likeshop/nytimes",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "nickyfoto"
  ],
  "module": "() => import('@/routes/likeshop/index.ts')",
  "name": "Posts",
  "parameters": {
    "site": "the site attached to likeshop.me/"
  },
  "path": "/:site",
  "radar": [
    {
      "source": [
        "likeshop.me/"
      ]
    }
  ]
}
```
