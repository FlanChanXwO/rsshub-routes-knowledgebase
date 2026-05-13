# Daily.dev - Most upvoted

## Coverage
`index-only`

## Route
- Namespace: `daily`
- Namespace Name: `Daily.dev`
- Route Path: `/upvoted/:period?/:innerSharedContent?/:dateSort?`
- Route Name: `Most upvoted`
- Example: `/daily/upvoted/7`
- URL: `app.daily.dev/upvoted`
- Language: `en`
- Categories: `social-media`
- Maintainers: `Rjnishant530`
- Source Location: `upvoted.ts`
- Source Module: `() => import('@/routes/daily/upvoted.ts')`

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
  - `app.daily.dev/upvoted`

## Raw JSON
```json
{
  "example": "/daily/upvoted/7",
  "location": "upvoted.ts",
  "maintainers": [
    "Rjnishant530"
  ],
  "module": "() => import('@/routes/daily/upvoted.ts')",
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
  "path": "/upvoted/:period?/:innerSharedContent?/:dateSort?",
  "radar": [
    {
      "source": [
        "app.daily.dev/upvoted"
      ]
    }
  ],
  "url": "app.daily.dev/upvoted",
  "view": 0
}
```
