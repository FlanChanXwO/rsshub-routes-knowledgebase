# GitHub - User Activities

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/activity/:user`
- Route Name: `User Activities`
- Example: `/github/activity/DIYgod`
- URL: `github.com`
- Language: `en`
- Categories: `programming`
- Maintainers: `hyoban`
- Source Location: `activity.ts`
- Source Module: `() => import('@/routes/github/activity.ts')`

## Description
Get the activities of a user on GitHub, based on the GitHub official RSS feed

## Parameters
- `user`: GitHub username


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
  - `github.com/:user`
- `target`: `/activity/:user`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "Get the activities of a user on GitHub, based on the GitHub official RSS feed",
  "example": "/github/activity/DIYgod",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "activity.ts",
  "maintainers": [
    "hyoban"
  ],
  "module": "() => import('@/routes/github/activity.ts')",
  "name": "User Activities",
  "parameters": {
    "user": "GitHub username"
  },
  "path": "/activity/:user",
  "radar": [
    {
      "source": [
        "github.com/:user"
      ],
      "target": "/activity/:user"
    }
  ],
  "view": 5
}
```
