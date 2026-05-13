# GitHub - Repo Stars

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/stars/:user/:repo`
- Route Name: `Repo Stars`
- Example: `/github/stars/DIYgod/RSSHub`
- URL: `github.com`
- Language: `en`
- Categories: `programming`
- Maintainers: `HenryQW`
- Source Location: `star.ts`
- Source Module: `() => import('@/routes/github/star.ts')`

## Description
_None_

## Parameters
- `user`: GitHub username
- `repo`: GitHub repo name


## Features
- `requireConfig`: [{"description": "GitHub Access Token", "name": "GITHUB_ACCESS_TOKEN"}]

## Radar
### Rule 1
- `source`:
  - `github.com/:user/:repo/stargazers`
  - `github.com/:user/:repo`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/github/stars/DIYgod/RSSHub",
  "features": {
    "requireConfig": [
      {
        "description": "GitHub Access Token",
        "name": "GITHUB_ACCESS_TOKEN"
      }
    ]
  },
  "location": "star.ts",
  "maintainers": [
    "HenryQW"
  ],
  "module": "() => import('@/routes/github/star.ts')",
  "name": "Repo Stars",
  "parameters": {
    "repo": "GitHub repo name",
    "user": "GitHub username"
  },
  "path": "/stars/:user/:repo",
  "radar": [
    {
      "source": [
        "github.com/:user/:repo/stargazers",
        "github.com/:user/:repo"
      ]
    }
  ],
  "view": 5
}
```
