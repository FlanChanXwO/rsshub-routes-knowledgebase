# Daily.dev - Squads

## Coverage
`index-only`

## Route
- Namespace: `daily`
- Namespace Name: `Daily.dev`
- Route Path: `/daily/squads/:squads/:innerSharedContent?`
- Route Name: `Squads`
- Example: `/daily/squads/watercooler`
- URL: `app.daily.dev/squads/discover`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `Rjnishant530`
- Source Location: `squads.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `innerSharedContent`: {"default": "false", "description": "Where to Fetch inner Shared Posts instead of original", "options": [{"label": "False", "value": "false"}, {"label": "True", "value": "true"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `app.daily.dev/squads/:squads`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/daily/squads/watercooler",
  "heat": 0,
  "location": "squads.ts",
  "maintainers": [
    "Rjnishant530"
  ],
  "name": "Squads",
  "parameters": {
    "innerSharedContent": {
      "default": "false",
      "description": "Where to Fetch inner Shared Posts instead of original",
      "options": [
        {
          "label": "False",
          "value": "false"
        },
        {
          "label": "True",
          "value": "true"
        }
      ]
    }
  },
  "path": "/squads/:squads/:innerSharedContent?",
  "radar": [
    {
      "source": [
        "app.daily.dev/squads/:squads"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "app.daily.dev/squads/discover",
  "view": 0
}
```
