# Follow - User subscriptions

## Coverage
`index-only`

## Route
- Namespace: `follow`
- Namespace Name: `Follow`
- Route Path: `/profile/:uid`
- Route Name: `User subscriptions`
- Example: `/follow/profile/41279032429549568`
- URL: `app.follow.is`
- Language: `en`
- Categories: `social-media`
- Maintainers: `KarasuShin, DIYgod, DFobain`
- Source Location: `profile.ts`
- Source Module: `() => import('@/routes/follow/profile.ts')`

## Description
_None_

## Parameters
- `uid`: User ID or user handle


## Features
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `app.follow.is/profile/:uid`
- `target`: `/profile/:uid`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/follow/profile/41279032429549568",
  "features": {
    "supportRadar": true
  },
  "location": "profile.ts",
  "maintainers": [
    "KarasuShin",
    "DIYgod",
    "DFobain"
  ],
  "module": "() => import('@/routes/follow/profile.ts')",
  "name": "User subscriptions",
  "parameters": {
    "uid": "User ID or user handle"
  },
  "path": "/profile/:uid",
  "radar": [
    {
      "source": [
        "app.follow.is/profile/:uid"
      ],
      "target": "/profile/:uid"
    }
  ],
  "view": 5
}
```
