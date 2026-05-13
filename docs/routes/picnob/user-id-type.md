# Instagram - User Profile - Pixnoy

## Coverage
`index-only`

## Route
- Namespace: `picnob`
- Namespace Name: `Instagram`
- Route Path: `/user/:id/:type?`
- Route Name: `User Profile - Pixnoy`
- Example: `/picnob/user/xlisa_olivex`
- URL: `www.instagram.com`
- Language: `en`
- Categories: `social-media`
- Maintainers: `TonyRL, micheal-death, AiraNadih, DIYgod, hyoban, Rongronggg9`
- Source Location: `user.ts`
- Source Module: `() => import('@/routes/picnob/user.ts')`

## Description
_None_

## Parameters
- `id`: Instagram id
- `type`: Type of profile page (profile or tagged)


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
  - `www.pixnoy.com/profile/:id`
- `target`: `/user/:id`
### Rule 2
- `source`:
  - `www.pixnoy.com/profile/:id/tagged`
- `target`: `/user/:id/tagged`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/picnob/user/xlisa_olivex",
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
    "TonyRL",
    "micheal-death",
    "AiraNadih",
    "DIYgod",
    "hyoban",
    "Rongronggg9"
  ],
  "module": "() => import('@/routes/picnob/user.ts')",
  "name": "User Profile - Pixnoy",
  "parameters": {
    "id": "Instagram id",
    "type": "Type of profile page (profile or tagged)"
  },
  "path": "/user/:id/:type?",
  "radar": [
    {
      "source": [
        "www.pixnoy.com/profile/:id"
      ],
      "target": "/user/:id"
    },
    {
      "source": [
        "www.pixnoy.com/profile/:id/tagged"
      ],
      "target": "/user/:id/tagged"
    }
  ],
  "view": 2
}
```
