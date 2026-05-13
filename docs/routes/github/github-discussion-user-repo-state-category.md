# GitHub - Repo Discussions

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/github/discussion/:user/:repo/:state?/:category?`
- Route Name: `Repo Discussions`
- Example: `/github/discussion/DIYgod/RSSHub`
- URL: `github.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `waynzh`
- Source Location: `discussions.ts`
- Source Module: `_None_`

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
  "heat": 43,
  "location": "discussions.ts",
  "maintainers": [
    "waynzh"
  ],
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
  ],
  "topFeeds": [
    {
      "description": "DIYgod/RSSHub Discussions - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "65680104647425024",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://github.com/DIYgod/RSSHub/discussions",
      "title": "DIYgod/RSSHub Discussions",
      "type": "feed",
      "url": "rsshub://github/discussion/DIYgod/RSSHub"
    },
    {
      "description": "noncegeek/indiehacker-handbook Discussions - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "65940238359013376",
      "image": null,
      "ownerUserId": "55822446012235776",
      "siteUrl": "https://github.com/noncegeek/indiehacker-handbook/discussions",
      "title": "noncegeek/indiehacker-handbook Discussions",
      "type": "feed",
      "url": "rsshub://github/discussion/noncegeek/indiehacker-handbook"
    }
  ]
}
```
