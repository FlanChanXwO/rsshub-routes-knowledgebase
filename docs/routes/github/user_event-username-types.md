# GitHub - User Event

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/user_event/:username/:types?`
- Route Name: `User Event`
- Example: `/github/user_event/mslxl`
- URL: `github.com`
- Language: `en`
- Categories: `programming`
- Maintainers: `mslxl`
- Source Location: `user-event.ts`
- Source Module: `() => import('@/routes/github/user-event.ts')`

## Description
_None_

## Parameters
- `username`: Username
- `types`: {"default": "all", "description": "Event types to include, comma separated", "options": [{"label": "All events", "value": "all"}, {"label": "Create events", "value": "create"}, {"label": "Delete events", "value": "delete"}, {"label": "Fork events", "value": "fork"}, {"label": "Issue create events", "value": "issue"}, {"label": "Issue comment events", "value": "issuecomm"}, {"label": "Member events", "value": "member"}, {"label": "Pull request events", "value": "pr"}, {"label": "Pull request review comment events", "value": "prcomm"}, {"label": "Pull request review events", "value": "prrev"}, {"label": "Public events", "value": "public"}, {"label": "Push events", "value": "push"}, {"label": "Release events", "value": "release"}, {"label": "Watch events (stars)", "value": "star"}, {"label": "Wiki item create or update events", "value": "wiki"}, {"label": "Commit comment events", "value": "cmcomm"}, {"label": "Discussion events", "value": "discussion"}]}


## Features
- `requireConfig`: [{"description": "GitHub access token to access private repository events", "name": "GITHUB_ACCESS_TOKEN", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `github.com/:username`
- `target`: `/user_event/:username`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/github/user_event/mslxl",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "GitHub access token to access private repository events",
        "name": "GITHUB_ACCESS_TOKEN",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "user-event.ts",
  "maintainers": [
    "mslxl"
  ],
  "module": "() => import('@/routes/github/user-event.ts')",
  "name": "User Event",
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
          "label": "Issue create events",
          "value": "issue"
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
          "label": "Pull request review events",
          "value": "prrev"
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
        },
        {
          "label": "Wiki item create or update events",
          "value": "wiki"
        },
        {
          "label": "Commit comment events",
          "value": "cmcomm"
        },
        {
          "label": "Discussion events",
          "value": "discussion"
        }
      ]
    },
    "username": "Username"
  },
  "path": "/user_event/:username/:types?",
  "radar": [
    {
      "source": [
        "github.com/:username"
      ],
      "target": "/user_event/:username"
    }
  ],
  "view": 5
}
```
