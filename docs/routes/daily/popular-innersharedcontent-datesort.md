# Daily.dev - Popular

## Coverage
`index-only`

## Route
- Namespace: `daily`
- Namespace Name: `Daily.dev`
- Route Path: `/popular/:innerSharedContent?/:dateSort?`
- Route Name: `Popular`
- Example: `/daily/popular`
- URL: `app.daily.dev/popular`
- Language: `en`
- Categories: `social-media`
- Maintainers: `Rjnishant530`
- Source Location: `popular.ts`
- Source Module: `() => import('@/routes/daily/popular.ts')`

## Description
_None_

## Parameters
- `innerSharedContent`: {"default": "false", "description": "Where to Fetch inner Shared Posts instead of original", "options": [{"label": "False", "value": "false"}, {"label": "True", "value": "true"}]}
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
  "example": "/daily/popular",
  "location": "popular.ts",
  "maintainers": [
    "Rjnishant530"
  ],
  "module": "() => import('@/routes/daily/popular.ts')",
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
    }
  },
  "path": "/popular/:innerSharedContent?/:dateSort?",
  "radar": [
    {
      "source": [
        "app.daily.dev/popular"
      ]
    }
  ],
  "url": "app.daily.dev/popular",
  "view": 0
}
```
