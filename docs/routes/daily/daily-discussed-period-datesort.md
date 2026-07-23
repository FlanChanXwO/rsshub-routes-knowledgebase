# Daily.dev - Most Discussed

## Coverage
`index-only`

## Route
- Namespace: `daily`
- Namespace Name: `Daily.dev`
- Route Path: `/daily/discussed/:period?/:dateSort?`
- Route Name: `Most Discussed`
- Example: `/daily/discussed/30`
- URL: `app.daily.dev/discussed`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `Rjnishant530`
- Source Location: `discussed.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
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
  "categories": [
    "social-media"
  ],
  "example": "/daily/discussed/30",
  "heat": 0,
  "location": "discussed.ts",
  "maintainers": [
    "Rjnishant530"
  ],
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
  "path": "/discussed/:period?/:dateSort?",
  "radar": [
    {
      "source": [
        "app.daily.dev/discussed"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "app.daily.dev/discussed",
  "view": 0
}
```
