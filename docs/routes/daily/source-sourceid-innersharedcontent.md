# Daily.dev - Source Posts

## Coverage
`index-only`

## Route
- Namespace: `daily`
- Namespace Name: `Daily.dev`
- Route Path: `/source/:sourceId/:innerSharedContent?`
- Route Name: `Source Posts`
- Example: `/daily/source/hn`
- URL: `app.daily.dev`
- Language: `en`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `source.ts`
- Source Module: `() => import('@/routes/daily/source.ts')`

## Description
_None_

## Parameters
- `sourceId`: The source id
- `innerSharedContent`: {"default": "false", "description": "Where to Fetch inner Shared Posts instead of original", "options": [{"label": "False", "value": "false"}, {"label": "True", "value": "true"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `app.daily.dev/sources/:sourceId`

## Raw JSON
```json
{
  "example": "/daily/source/hn",
  "location": "source.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/daily/source.ts')",
  "name": "Source Posts",
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
    },
    "sourceId": "The source id"
  },
  "path": "/source/:sourceId/:innerSharedContent?",
  "radar": [
    {
      "source": [
        "app.daily.dev/sources/:sourceId"
      ]
    }
  ],
  "url": "app.daily.dev"
}
```
