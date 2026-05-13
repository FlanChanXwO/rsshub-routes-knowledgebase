# Massachusetts Institute of Technology - Scratch User Comments

## Coverage
`index-only`

## Route
- Namespace: `mit`
- Namespace Name: `Massachusetts Institute of Technology`
- Route Path: `/scratch/user-comments/:username`
- Route Name: `Scratch User Comments`
- Example: `/mit/scratch/user-comments/skota11`
- URL: `mit.edu`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `Skota11`
- Source Location: `scratch/user-comments.ts`
- Source Module: `() => import('@/routes/mit/scratch/user-comments.ts')`

## Description
_None_

## Parameters
- `username`: Scratch username


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
  - `scratch.mit.edu/users/:username/`
- `target`: `/scratch/user-comments/:username`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/mit/scratch/user-comments/skota11",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "scratch/user-comments.ts",
  "maintainers": [
    "Skota11"
  ],
  "module": "() => import('@/routes/mit/scratch/user-comments.ts')",
  "name": "Scratch User Comments",
  "parameters": {
    "username": "Scratch username"
  },
  "path": "/scratch/user-comments/:username",
  "radar": [
    {
      "source": [
        "scratch.mit.edu/users/:username/"
      ],
      "target": "/scratch/user-comments/:username"
    }
  ]
}
```
