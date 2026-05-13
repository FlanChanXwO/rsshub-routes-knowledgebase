# GitHub - User Starred Repositories

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/starred_repos/:user`
- Route Name: `User Starred Repositories`
- Example: `/github/starred_repos/DIYgod`
- URL: `github.com`
- Language: `en`
- Categories: `programming`
- Maintainers: `LanceZhu`
- Source Location: `starred-repos.ts`
- Source Module: `() => import('@/routes/github/starred-repos.ts')`

## Description
_None_

## Parameters
- `user`: User name


## Features
- `requireConfig`: [{"description": "To get more requests", "name": "GITHUB_ACCESS_TOKEN", "optional": true}]

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
  "example": "/github/starred_repos/DIYgod",
  "features": {
    "requireConfig": [
      {
        "description": "To get more requests",
        "name": "GITHUB_ACCESS_TOKEN",
        "optional": true
      }
    ]
  },
  "location": "starred-repos.ts",
  "maintainers": [
    "LanceZhu"
  ],
  "module": "() => import('@/routes/github/starred-repos.ts')",
  "name": "User Starred Repositories",
  "parameters": {
    "user": "User name"
  },
  "path": "/starred_repos/:user",
  "radar": [
    {
      "source": [
        "github.com/:user"
      ]
    }
  ]
}
```
