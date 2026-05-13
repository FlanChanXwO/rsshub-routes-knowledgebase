# Lens - Lens Profile

## Coverage
`index-only`

## Route
- Namespace: `lens`
- Namespace Name: `Lens`
- Route Path: `/profile/:handle`
- Route Name: `Lens Profile`
- Example: `/lens/profile/stani`
- URL: `www.lens.xyz`
- Language: `en`
- Categories: `social-media`
- Maintainers: `DIYgod`
- Source Location: `profile.ts`
- Source Module: `() => import('@/routes/lens/profile.ts')`

## Description
_None_

## Parameters
- `handle`: Lens handle


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
  - `hey.xyz/u/:handle`
- `target`: `/profile/:handle`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/lens/profile/stani",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "profile.ts",
  "maintainers": [
    "DIYgod"
  ],
  "module": "() => import('@/routes/lens/profile.ts')",
  "name": "Lens Profile",
  "parameters": {
    "handle": "Lens handle"
  },
  "path": "/profile/:handle",
  "radar": [
    {
      "source": [
        "hey.xyz/u/:handle"
      ],
      "target": "/profile/:handle"
    }
  ]
}
```
