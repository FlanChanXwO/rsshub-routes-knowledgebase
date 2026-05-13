# X (Twitter) - User timeline - Sotwe

## Coverage
`index-only`

## Route
- Namespace: `sotwe`
- Namespace Name: `X (Twitter)`
- Route Path: `/user/:id`
- Route Name: `User timeline - Sotwe`
- Example: `/sotwe/user/_RSSHub`
- URL: `x.com`
- Language: `en`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `user.ts`
- Source Module: `() => import('@/routes/sotwe/user.ts')`

## Description
_None_

## Parameters
- `id`: Twitter username


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.sotwe.com/:id`
- `target`: `/user/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/sotwe/user/_RSSHub",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "user.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/sotwe/user.ts')",
  "name": "User timeline - Sotwe",
  "parameters": {
    "id": "Twitter username"
  },
  "path": "/user/:id",
  "radar": [
    {
      "source": [
        "www.sotwe.com/:id"
      ],
      "target": "/user/:id"
    }
  ],
  "view": 2
}
```
