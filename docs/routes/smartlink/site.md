# SmartLink - Posts

## Coverage
`index-only`

## Route
- Namespace: `smartlink`
- Namespace Name: `SmartLink`
- Route Path: `/:site`
- Route Name: `Posts`
- Example: `/smartlink/bloombergpursuits`
- URL: `smartlink.bio`
- Language: `en`
- Categories: `social-media`
- Maintainers: `nickyfoto`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/smartlink/index.ts')`

## Description
smartlink.bio link in bio takes your audience from Instagram and TikTok to your website in one easy step.

## Parameters
- `site`: the site attached to smartlink.bio/


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
  - `smartlink.bio/`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "description": "smartlink.bio link in bio takes your audience from Instagram and TikTok to your website in one easy step.",
  "example": "/smartlink/bloombergpursuits",
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
  "module": "() => import('@/routes/smartlink/index.ts')",
  "name": "Posts",
  "parameters": {
    "site": "the site attached to smartlink.bio/"
  },
  "path": "/:site",
  "radar": [
    {
      "source": [
        "smartlink.bio/"
      ]
    }
  ]
}
```
