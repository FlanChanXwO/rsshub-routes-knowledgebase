# Daily.dev - Most Discussed

## Coverage
`index-only`

## Route
- Namespace: `daily`
- Namespace Name: `Daily.dev`
- Route Path: `/discussed/:period?/:innerSharedContent?/:dateSort?`
- Route Name: `Most Discussed`
- Example: `/daily/discussed/30`
- URL: `app.daily.dev/discussed`
- Language: `en`
- Categories: `social-media`
- Maintainers: `Rjnishant530`
- Source Location: `discussed.ts`
- Source Module: `() => import('@/routes/daily/discussed.ts')`

## Description
_None_

## Parameters
- `innerSharedContent`: {"default": "false", "description": "Where to Fetch inner Shared Posts instead of original", "options": [{"label": "False", "value": "false"}, {"label": "True", "value": "true"}]}
- `dateSort`: {"default": "true", "description": "Sort posts by publication date instead of popularity", "options": [{"label": "False", "value": "false"}, {"label": "True", "value": "true"}]}
- `period`: {"default": "7", "description": "Period of Lookup", "options": [{"label": "Last Week", "value": "7"}, {"label": "Last Month", "value": "30"}, {"label": "Last Year", "value": "365"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `app.daily.dev/discussed`

## Raw JSON
```json
{
  "example": "/daily/discussed/30",
  "location": "discussed.ts",
  "maintainers": [
    "Rjnishant530"
  ],
  "module": "() => import('@/routes/daily/discussed.ts')",
  "name": "Most Discussed",
  "parameters": {
    "dateSort": {
      "default": "true",
      "description": "Sort posts by publication date instead of popularity",
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
    },
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
    },
    "period": {
      "default": "7",
      "description": "Period of Lookup",
      "options": [
        {
          "label": "Last Week",
          "value": "7"
        },
        {
          "label": "Last Month",
          "value": "30"
        },
        {
          "label": "Last Year",
          "value": "365"
        }
      ]
    }
  },
  "path": "/discussed/:period?/:innerSharedContent?/:dateSort?",
  "radar": [
    {
      "source": [
        "app.daily.dev/discussed"
      ]
    }
  ],
  "url": "app.daily.dev/discussed",
  "view": 0
}
```
