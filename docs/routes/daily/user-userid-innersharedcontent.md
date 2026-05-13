# Daily.dev - User Posts

## Coverage
`index-only`

## Route
- Namespace: `daily`
- Namespace Name: `Daily.dev`
- Route Path: `/user/:userId/:innerSharedContent?`
- Route Name: `User Posts`
- Example: `/daily/user/kramer`
- URL: `app.daily.dev`
- Language: `en`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `user.ts`
- Source Module: `() => import('@/routes/daily/user.ts')`

## Description
_None_

## Parameters
- `innerSharedContent`: {"default": "false", "description": "Where to Fetch inner Shared Posts instead of original", "options": [{"label": "False", "value": "false"}, {"label": "True", "value": "true"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `app.daily.dev/:userId/posts`
  - `app.daily.dev/:userId`

## Raw JSON
```json
{
  "example": "/daily/user/kramer",
  "location": "user.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/daily/user.ts')",
  "name": "User Posts",
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
    }
  },
  "path": "/user/:userId/:innerSharedContent?",
  "radar": [
    {
      "source": [
        "app.daily.dev/:userId/posts",
        "app.daily.dev/:userId"
      ]
    }
  ],
  "url": "app.daily.dev"
}
```
