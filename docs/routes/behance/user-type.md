# Behance - User Works

## Coverage
`index-only`

## Route
- Namespace: `behance`
- Namespace Name: `Behance`
- Route Path: `/:user/:type?`
- Route Name: `User Works`
- Example: `/behance/mishapetrick`
- URL: `www.behance.net`
- Language: `en`
- Categories: `design`
- Maintainers: `MisteryMonster`
- Source Location: `user.tsx`
- Source Module: `() => import('@/routes/behance/user.tsx')`

## Description
Behance user's profile URL, like [https://www.behance.net/mishapetrick](https://www.behance.net/mishapetrick) the username will be `mishapetrick`。

## Parameters
- `user`: username
- `type`: {"default": "projects", "description": "type", "options": [{"label": "projects", "value": "projects"}, {"label": "appreciated", "value": "appreciated"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "design"
  ],
  "description": "Behance user's profile URL, like [https://www.behance.net/mishapetrick](https://www.behance.net/mishapetrick) the username will be `mishapetrick`。",
  "example": "/behance/mishapetrick",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "user.tsx",
  "maintainers": [
    "MisteryMonster"
  ],
  "module": "() => import('@/routes/behance/user.tsx')",
  "name": "User Works",
  "parameters": {
    "type": {
      "default": "projects",
      "description": "type",
      "options": [
        {
          "label": "projects",
          "value": "projects"
        },
        {
          "label": "appreciated",
          "value": "appreciated"
        }
      ]
    },
    "user": "username"
  },
  "path": "/:user/:type?",
  "view": 2
}
```
