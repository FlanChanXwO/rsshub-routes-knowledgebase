# GitHub - Issue / Pull Request comments

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/comments/:user/:repo/:number?`
- Route Name: `Issue / Pull Request comments`
- Example: `/github/comments/DIYgod/RSSHub/8116`
- URL: `github.com`
- Language: `en`
- Categories: `programming`
- Maintainers: `TonyRL, FliegendeWurst`
- Source Location: `comments.ts`
- Source Module: `() => import('@/routes/github/comments.ts')`

## Description
_None_

## Parameters
- `user`: User / Org name
- `repo`: Repo name
- `number`: Issue or pull number (if omitted: all)


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `github.com/:user/:repo/:type`
  - `github.com/:user/:repo/:type/:number`
- `target`: `/comments/:user/:repo/:number?`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/github/comments/DIYgod/RSSHub/8116",
  "location": "comments.ts",
  "maintainers": [
    "TonyRL",
    "FliegendeWurst"
  ],
  "module": "() => import('@/routes/github/comments.ts')",
  "name": "Issue / Pull Request comments",
  "parameters": {
    "number": "Issue or pull number (if omitted: all)",
    "repo": "Repo name",
    "user": "User / Org name"
  },
  "path": "/comments/:user/:repo/:number?",
  "radar": [
    {
      "source": [
        "github.com/:user/:repo/:type",
        "github.com/:user/:repo/:type/:number"
      ],
      "target": "/comments/:user/:repo/:number?"
    }
  ]
}
```
