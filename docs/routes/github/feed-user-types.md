# GitHub - User's Feed

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/feed/:user/:types?`
- Route Name: `User's Feed`
- Example: `/github/feed/yihong0618/star,release,pr`
- URL: `github.com`
- Language: `en`
- Categories: `programming`
- Maintainers: `RtYkk`
- Source Location: `private-feed.ts`
- Source Module: `() => import('@/routes/github/private-feed.ts')`

## Description
_None_

## Parameters
- `user`: GitHub username
- `types`: {"default": "all", "description": "Event types to include, comma separated", "options": [{"label": "All events", "value": "all"}, {"label": "Create events", "value": "create"}, {"label": "Delete events", "value": "delete"}, {"label": "Fork events", "value": "fork"}, {"label": "Issue comment events", "value": "issuecomm"}, {"label": "Member events", "value": "member"}, {"label": "Pull request events", "value": "pr"}, {"label": "Pull request review comment events", "value": "prcomm"}, {"label": "Public events", "value": "public"}, {"label": "Push events", "value": "push"}, {"label": "Release events", "value": "release"}, {"label": "Watch events (stars)", "value": "star"}]}


## Features
- `requireConfig`: [{"description": "GitHub access token to access private events", "name": "GITHUB_ACCESS_TOKEN", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `github.com/:user`
- `target`: `/feed/:user`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/github/feed/yihong0618/star,release,pr",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "GitHub access token to access private events",
        "name": "GITHUB_ACCESS_TOKEN",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "private-feed.ts",
  "maintainers": [
    "RtYkk"
  ],
  "module": "() => import('@/routes/github/private-feed.ts')",
  "name": "User's Feed",
  "parameters": {
    "types": {
      "default": "all",
      "description": "Event types to include, comma separated",
      "options": [
        {
          "label": "All events",
          "value": "all"
        },
        {
          "label": "Create events",
          "value": "create"
        },
        {
          "label": "Delete events",
          "value": "delete"
        },
        {
          "label": "Fork events",
          "value": "fork"
        },
        {
          "label": "Issue comment events",
          "value": "issuecomm"
        },
        {
          "label": "Member events",
          "value": "member"
        },
        {
          "label": "Pull request events",
          "value": "pr"
        },
        {
          "label": "Pull request review comment events",
          "value": "prcomm"
        },
        {
          "label": "Public events",
          "value": "public"
        },
        {
          "label": "Push events",
          "value": "push"
        },
        {
          "label": "Release events",
          "value": "release"
        },
        {
          "label": "Watch events (stars)",
          "value": "star"
        }
      ]
    },
    "user": "GitHub username"
  },
  "path": "/feed/:user/:types?",
  "radar": [
    {
      "source": [
        "github.com/:user"
      ],
      "target": "/feed/:user"
    }
  ],
  "view": 5
}
```
