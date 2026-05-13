# GitHub - User Followers

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/user/followers/:user`
- Route Name: `User Followers`
- Example: `/github/user/followers/HenryQW`
- URL: `github.com`
- Language: `en`
- Categories: `programming`
- Maintainers: `HenryQW`
- Source Location: `follower.ts`
- Source Module: `() => import('@/routes/github/follower.ts')`

## Description
_None_

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

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/github/user/followers/HenryQW",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "follower.ts",
  "maintainers": [
    "HenryQW"
  ],
  "module": "() => import('@/routes/github/follower.ts')",
  "name": "User Followers",
  "parameters": {
    "user": "GitHub username"
  },
  "path": "/user/followers/:user",
  "radar": [
    {
      "source": [
        "github.com/:user"
      ]
    }
  ]
}
```
