# Instagram - User Profile - Picnob

## Coverage
`index-only`

## Route
- Namespace: `picnob.info`
- Namespace Name: `Instagram`
- Route Path: `/user/:id/:type?`
- Route Name: `User Profile - Picnob`
- Example: `/picnob.info/user/xlisa_olivex`
- URL: `picnob.info`
- Language: `en`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `user.ts`
- Source Module: `() => import('@/routes/picnob.info/user.ts')`

## Description
_None_

## Parameters
- `id`: Instagram id
- `type`: {"default": "posts", "description": "Type of profile page", "options": [{"label": "Posts", "value": "posts"}, {"label": "Stories", "value": "stories"}]}


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
    "social-media"
  ],
  "example": "/picnob.info/user/xlisa_olivex",
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
    "TonyRL"
  ],
  "module": "() => import('@/routes/picnob.info/user.ts')",
  "name": "User Profile - Picnob",
  "parameters": {
    "id": "Instagram id",
    "type": {
      "default": "posts",
      "description": "Type of profile page",
      "options": [
        {
          "label": "Posts",
          "value": "posts"
        },
        {
          "label": "Stories",
          "value": "stories"
        }
      ]
    }
  },
  "path": "/user/:id/:type?",
  "url": "picnob.info",
  "view": 2
}
```
