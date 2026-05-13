# Pinterest - User

## Coverage
`index-only`

## Route
- Namespace: `pinterest`
- Namespace Name: `Pinterest`
- Route Path: `/user/:username/:type?`
- Route Name: `User`
- Example: `/pinterest/user/howieserious`
- URL: `www.pinterest.com`
- Language: `en`
- Categories: `picture`
- Maintainers: `TonyRL`
- Source Location: `user.ts`
- Source Module: `() => import('@/routes/pinterest/user.ts')`

## Description
_None_

## Parameters
- `username`: Username
- `type`: {"default": "_created", "description": "Type, default to `_created`", "options": [{"label": "Created", "value": "_created"}, {"label": "Saved", "value": "_saved"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.pinterest.com/:id/:type?`
  - `www.pinterest.com/:id`
- `target`: `/user/:id/:type?`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "example": "/pinterest/user/howieserious",
  "location": "user.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/pinterest/user.ts')",
  "name": "User",
  "parameters": {
    "type": {
      "default": "_created",
      "description": "Type, default to `_created`",
      "options": [
        {
          "label": "Created",
          "value": "_created"
        },
        {
          "label": "Saved",
          "value": "_saved"
        }
      ]
    },
    "username": "Username"
  },
  "path": "/user/:username/:type?",
  "radar": [
    {
      "source": [
        "www.pinterest.com/:id/:type?",
        "www.pinterest.com/:id"
      ],
      "target": "/user/:id/:type?"
    }
  ]
}
```
