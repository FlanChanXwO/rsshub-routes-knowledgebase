# GitHub - Notifications

## Coverage
`index-only`

## Route
- Namespace: `github`
- Namespace Name: `GitHub`
- Route Path: `/github/notifications`
- Route Name: `Notifications`
- Example: `/github/notifications`
- URL: `github.com/notifications`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `zhzy0077`
- Source Location: `notifications.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
- `requireConfig`: [{"description": "", "name": "GITHUB_ACCESS_TOKEN"}]

## Radar
### Rule 1
- `source`:
  - `github.com/notifications`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/github/notifications",
  "features": {
    "requireConfig": [
      {
        "description": "",
        "name": "GITHUB_ACCESS_TOKEN"
      }
    ]
  },
  "heat": 5,
  "location": "notifications.ts",
  "maintainers": [
    "zhzy0077"
  ],
  "name": "Notifications",
  "path": "/notifications",
  "radar": [
    {
      "source": [
        "github.com/notifications"
      ]
    }
  ],
  "topFeeds": [
    {
      "description": "Github Notifications - Powered by RSSHub",
      "errorAt": "2024-11-14T01:50:35.024Z",
      "errorMessage": "[GET] \"https://api.github.com/notifications\": 403 Forbidden\n",
      "id": "79179425236069376",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://github.com/notifications",
      "title": "Github Notifications",
      "type": "feed",
      "url": "rsshub://github/notifications"
    }
  ],
  "url": "github.com/notifications"
}
```
