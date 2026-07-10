# Daily.dev - Source Posts

## Coverage
`index-only`

## Route
- Namespace: `daily`
- Namespace Name: `Daily.dev`
- Route Path: `/daily/source/:sourceId/:innerSharedContent?`
- Route Name: `Source Posts`
- Example: `/daily/source/hn`
- URL: `app.daily.dev`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `source.ts`
- Source Module: `_None_`

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
  "categories": [
    "social-media"
  ],
  "example": "/daily/source/hn",
  "heat": 0,
  "location": "source.ts",
  "maintainers": [
    "TonyRL"
  ],
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
  "topFeeds": [],
  "url": "app.daily.dev"
}
```
