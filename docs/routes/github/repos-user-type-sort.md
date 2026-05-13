# GitHub - User Repo

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/repos/:user/:type?/:sort?`
- Route Name: `User Repo`
- Example: `/github/repos/DIYgod`
- URL: `github.com`
- Language: `en`
- Categories: `programming`
- Maintainers: `DIYgod`
- Source Location: `repos.ts`
- Source Module: `() => import('@/routes/github/repos.ts')`

## Description
_None_

## Parameters
- `user`: GitHub username
- `type`: Type of repository, can be `all`, `owner`, `member`, `public`, `private`, `forks`, `sources`
- `sort`: Sort by `created`, `updated`, `pushed`, `full_name`


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
  "example": "/github/repos/DIYgod",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "repos.ts",
  "maintainers": [
    "DIYgod"
  ],
  "module": "() => import('@/routes/github/repos.ts')",
  "name": "User Repo",
  "parameters": {
    "sort": "Sort by `created`, `updated`, `pushed`, `full_name`",
    "type": "Type of repository, can be `all`, `owner`, `member`, `public`, `private`, `forks`, `sources`",
    "user": "GitHub username"
  },
  "path": "/repos/:user/:type?/:sort?",
  "radar": [
    {
      "source": [
        "github.com/:user"
      ]
    }
  ]
}
```
