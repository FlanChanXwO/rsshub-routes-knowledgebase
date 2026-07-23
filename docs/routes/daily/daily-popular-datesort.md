# Daily.dev - Popular

## Coverage
`index-only`

## Route
- Namespace: `daily`
- Namespace Name: `Daily.dev`
- Route Path: `/daily/popular/:dateSort?`
- Route Name: `Popular`
- Example: `/daily/popular`
- URL: `app.daily.dev/popular`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `Rjnishant530`
- Source Location: `popular.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `dateSort`: {"default": "true", "description": "Sort posts by publication date instead of popularity", "options": [{"label": "False", "value": "false"}, {"label": "True", "value": "true"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `app.daily.dev/popular`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/daily/popular",
  "heat": 0,
  "location": "popular.ts",
  "maintainers": [
    "Rjnishant530"
  ],
  "name": "Popular",
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
    }
  },
  "path": "/popular/:dateSort?",
  "radar": [
    {
      "source": [
        "app.daily.dev/popular"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [],
  "url": "app.daily.dev/popular",
  "view": 0
}
```
