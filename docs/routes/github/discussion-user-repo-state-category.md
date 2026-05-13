# GitHub - Repo Discussions

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/discussion/:user/:repo/:state?/:category?`
- Route Name: `Repo Discussions`
- Example: `/github/discussion/DIYgod/RSSHub`
- URL: `github.com`
- Language: `en`
- Categories: `programming`
- Maintainers: `waynzh`
- Source Location: `discussions.ts`
- Source Module: `() => import('@/routes/github/discussions.ts')`

## Description
_None_

## Parameters
- `user`: User name
- `repo`: Repo name
- `state`: {"default": "open", "description": "The state of discussions", "options": [{"label": "Open", "value": "open"}, {"label": "Closed", "value": "closed"}, {"label": "Answered", "value": "answered"}, {"label": "Unanswered", "value": "unanswered"}, {"label": "Locked", "value": "locked"}, {"label": "Unlocked", "value": "unlocked"}, {"label": "All", "value": "all"}]}
- `category`: Category Name (case-sensitive). Default: `null`.


## Features
- `requireConfig`: [{"description": "GitHub Access Token", "name": "GITHUB_ACCESS_TOKEN"}]

## Radar
### Rule 1
- `source`:
  - `github.com/:user/:repo/discussions`
  - `github.com/:user/:repo/discussions/:id`
  - `github.com/:user/:repo`
- `target`: `/discussion/:user/:repo`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/github/discussion/DIYgod/RSSHub",
  "features": {
    "requireConfig": [
      {
        "description": "GitHub Access Token",
        "name": "GITHUB_ACCESS_TOKEN"
      }
    ]
  },
  "location": "discussions.ts",
  "maintainers": [
    "waynzh"
  ],
  "module": "() => import('@/routes/github/discussions.ts')",
  "name": "Repo Discussions",
  "parameters": {
    "category": "Category Name (case-sensitive). Default: `null`.",
    "repo": "Repo name",
    "state": {
      "default": "open",
      "description": "The state of discussions",
      "options": [
        {
          "label": "Open",
          "value": "open"
        },
        {
          "label": "Closed",
          "value": "closed"
        },
        {
          "label": "Answered",
          "value": "answered"
        },
        {
          "label": "Unanswered",
          "value": "unanswered"
        },
        {
          "label": "Locked",
          "value": "locked"
        },
        {
          "label": "Unlocked",
          "value": "unlocked"
        },
        {
          "label": "All",
          "value": "all"
        }
      ]
    },
    "user": "User name"
  },
  "path": "/discussion/:user/:repo/:state?/:category?",
  "radar": [
    {
      "source": [
        "github.com/:user/:repo/discussions",
        "github.com/:user/:repo/discussions/:id",
        "github.com/:user/:repo"
      ],
      "target": "/discussion/:user/:repo"
    }
  ]
}
```
