# GitHub - Repo Pull Requests

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/pull/:user/:repo/:state?/:labels?`
- Route Name: `Repo Pull Requests`
- Example: `/github/pull/DIYgod/RSSHub`
- URL: `github.com`
- Language: `en`
- Categories: `programming`
- Maintainers: `hashman, TonyRL`
- Source Location: `pulls.ts`
- Source Module: `() => import('@/routes/github/pulls.ts')`

## Description
_None_

## Parameters
- `user`: User name
- `repo`: Repo name
- `state`: the state of pull requests. Can be either `open`, `closed`, or `all`. Default: `open`.
- `labels`: a list of comma separated label names


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
  - `github.com/:user/:repo/pulls`
  - `github.com/:user/:repo/pulls/:id`
  - `github.com/:user/:repo`
- `target`: `/pull/:user/:repo`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/github/pull/DIYgod/RSSHub",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "pulls.ts",
  "maintainers": [
    "hashman",
    "TonyRL"
  ],
  "module": "() => import('@/routes/github/pulls.ts')",
  "name": "Repo Pull Requests",
  "parameters": {
    "labels": "a list of comma separated label names",
    "repo": "Repo name",
    "state": "the state of pull requests. Can be either `open`, `closed`, or `all`. Default: `open`.",
    "user": "User name"
  },
  "path": "/pull/:user/:repo/:state?/:labels?",
  "radar": [
    {
      "source": [
        "github.com/:user/:repo/pulls",
        "github.com/:user/:repo/pulls/:id",
        "github.com/:user/:repo"
      ],
      "target": "/pull/:user/:repo"
    }
  ]
}
```
