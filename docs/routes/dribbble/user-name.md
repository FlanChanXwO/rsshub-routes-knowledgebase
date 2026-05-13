# Dribbble - User (or team)

## Coverage
`index-only`

## Route
- Namespace: `dribbble`
- Namespace Name: `Dribbble`
- Route Path: `/user/:name`
- Route Name: `User (or team)`
- Example: `/dribbble/user/google`
- URL: `dribbble.com`
- Language: `en`
- Categories: `design`
- Maintainers: `DIYgod, loganrockmore`
- Source Location: `user.ts`
- Source Module: `() => import('@/routes/dribbble/user.ts')`

## Description
_None_

## Parameters
- `name`: username, available in user's homepage URL


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
  - `dribbble.com/:name`

## Raw JSON
```json
{
  "categories": [
    "design"
  ],
  "example": "/dribbble/user/google",
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
    "loganrockmore"
  ],
  "module": "() => import('@/routes/dribbble/user.ts')",
  "name": "User (or team)",
  "parameters": {
    "name": "username, available in user's homepage URL"
  },
  "path": "/user/:name",
  "radar": [
    {
      "source": [
        "dribbble.com/:name"
      ]
    }
  ]
}
```
