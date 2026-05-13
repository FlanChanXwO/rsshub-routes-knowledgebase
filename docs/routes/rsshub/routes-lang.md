# RSSHub - New routes

## Coverage
`index-only`

## Route
- Namespace: `rsshub`
- Namespace Name: `RSSHub`
- Route Path: `/routes/:lang?`
- Route Name: `New routes`
- Example: `/rsshub/routes/en`
- URL: `docs.rsshub.app/*`
- Language: `en`
- Categories: `program-update`
- Maintainers: `DIYgod`
- Source Location: `routes.ts`
- Source Module: `() => import('@/routes/rsshub/routes.ts')`

## Description
_None_

## Parameters
- `lang`: {"default": "en", "description": "Language", "options": [{"label": "Chinese", "value": "zh"}, {"label": "English", "value": "en"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `docs.rsshub.app/*`
- `target`: `/routes`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "example": "/rsshub/routes/en",
  "location": "routes.ts",
  "maintainers": [
    "DIYgod"
  ],
  "module": "() => import('@/routes/rsshub/routes.ts')",
  "name": "New routes",
  "parameters": {
    "lang": {
      "default": "en",
      "description": "Language",
      "options": [
        {
          "label": "Chinese",
          "value": "zh"
        },
        {
          "label": "English",
          "value": "en"
        }
      ]
    }
  },
  "path": "/routes/:lang?",
  "radar": [
    {
      "source": [
        "docs.rsshub.app/*"
      ],
      "target": "/routes"
    }
  ],
  "url": "docs.rsshub.app/*",
  "view": 5
}
```
