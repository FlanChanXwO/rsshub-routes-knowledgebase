# Daily.dev - Most upvoted

## Coverage
`index-only`

## Route
- Namespace: `daily`
- Namespace Name: `Daily.dev`
- Route Path: `/daily/upvoted/:period?/:dateSort?`
- Route Name: `Most upvoted`
- Example: `/daily/upvoted/7`
- URL: `app.daily.dev/upvoted`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `Rjnishant530`
- Source Location: `upvoted.ts`
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
  - `app.daily.dev/upvoted`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/daily/upvoted/7",
  "heat": 0,
  "location": "upvoted.ts",
  "maintainers": [
    "Rjnishant530"
  ],
  "name": "Most upvoted",
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
  "path": "/upvoted/:period?/:dateSort?",
  "radar": [
    {
      "source": [
        "app.daily.dev/upvoted"
      ]
    }
  ],
  "topFeeds": [],
  "url": "app.daily.dev/upvoted",
  "view": 0
}
```
