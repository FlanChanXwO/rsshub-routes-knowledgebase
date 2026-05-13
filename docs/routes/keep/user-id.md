# Keep - 运动日记

## Coverage
`index-only`

## Route
- Namespace: `keep`
- Namespace Name: `Keep`
- Route Path: `/user/:id`
- Route Name: `运动日记`
- Example: `/keep/user/556b02c1ab59390afea671ea`
- URL: `gotokeep.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `Dectinc, DIYgod`
- Source Location: `user.tsx`
- Source Module: `() => import('@/routes/keep/user.tsx')`

## Description
_None_

## Parameters
- `id`: Keep 用户 id


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
  - `gotokeep.com/users/:id`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/keep/user/556b02c1ab59390afea671ea",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "user.tsx",
  "maintainers": [
    "Dectinc",
    "DIYgod"
  ],
  "module": "() => import('@/routes/keep/user.tsx')",
  "name": "运动日记",
  "parameters": {
    "id": "Keep 用户 id"
  },
  "path": "/user/:id",
  "radar": [
    {
      "source": [
        "gotokeep.com/users/:id"
      ]
    }
  ]
}
```
