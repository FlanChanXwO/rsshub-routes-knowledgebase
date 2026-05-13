# GitHub - Repo Issues

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/issue/:user/:repo/:state?/:labels?`
- Route Name: `Repo Issues`
- Example: `/github/issue/DIYgod/RSSHub/open`
- URL: `github.com`
- Language: `en`
- Categories: `programming`
- Maintainers: `HenryQW, AndreyMZ`
- Source Location: `issue.ts`
- Source Module: `() => import('@/routes/github/issue.ts')`

## Description
_None_

## Parameters
- `user`: GitHub username
- `repo`: GitHub repo name
- `state`: {"default": "open", "description": "the state of the issues.", "options": [{"label": "Open", "value": "open"}, {"label": "Closed", "value": "closed"}, {"label": "All", "value": "all"}]}
- `labels`: a list of comma separated label names


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `github.com/:user/:repo/issues`
  - `github.com/:user/:repo/issues/:id`
  - `github.com/:user/:repo`
- `target`: `/issue/:user/:repo`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/github/issue/DIYgod/RSSHub/open",
  "location": "issue.ts",
  "maintainers": [
    "HenryQW",
    "AndreyMZ"
  ],
  "module": "() => import('@/routes/github/issue.ts')",
  "name": "Repo Issues",
  "parameters": {
    "labels": "a list of comma separated label names",
    "repo": "GitHub repo name",
    "state": {
      "default": "open",
      "description": "the state of the issues.",
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
          "label": "All",
          "value": "all"
        }
      ]
    },
    "user": "GitHub username"
  },
  "path": "/issue/:user/:repo/:state?/:labels?",
  "radar": [
    {
      "source": [
        "github.com/:user/:repo/issues",
        "github.com/:user/:repo/issues/:id",
        "github.com/:user/:repo"
      ],
      "target": "/issue/:user/:repo"
    }
  ],
  "view": 5
}
```
