# Daily.dev - Squads

## Coverage
`index-only`

## Route
- Namespace: `daily`
- Namespace Name: `Daily.dev`
- Route Path: `/squads/:squads/:innerSharedContent?`
- Route Name: `Squads`
- Example: `/daily/squads/watercooler`
- URL: `app.daily.dev/squads/discover`
- Language: `en`
- Categories: `social-media`
- Maintainers: `Rjnishant530`
- Source Location: `squads.ts`
- Source Module: `() => import('@/routes/daily/squads.ts')`

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
  "example": "/daily/squads/watercooler",
  "location": "squads.ts",
  "maintainers": [
    "Rjnishant530"
  ],
  "module": "() => import('@/routes/daily/squads.ts')",
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
  "url": "app.daily.dev/squads/discover",
  "view": 0
}
```
