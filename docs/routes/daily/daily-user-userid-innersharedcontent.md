# Daily.dev - User Posts

## Coverage
`index-only`

## Route
- Namespace: `daily`
- Namespace Name: `Daily.dev`
- Route Path: `/daily/user/:userId/:innerSharedContent?`
- Route Name: `User Posts`
- Example: `/daily/user/kramer`
- URL: `app.daily.dev`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `TonyRL`
- Source Location: `user.ts`
- Source Module: `_None_`

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
  "categories": [
    "social-media"
  ],
  "example": "/daily/user/kramer",
  "heat": 0,
  "location": "user.ts",
  "maintainers": [
    "TonyRL"
  ],
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
  "topFeeds": [],
  "url": "app.daily.dev"
}
```
