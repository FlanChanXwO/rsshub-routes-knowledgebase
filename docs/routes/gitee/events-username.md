# Gitee - 用户公开动态

## Coverage
`index-only`

## Route
- Namespace: `gitee`
- Namespace Name: `Gitee`
- Route Path: `/events/:username`
- Route Name: `用户公开动态`
- Example: `/gitee/events/y_project`
- URL: `gitee.com`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `TonyRL`
- Source Location: `users/events.ts`
- Source Module: `() => import('@/routes/gitee/users/events.ts')`

## Description
_None_

## Parameters
- `username`: 用户名


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `gitee.com/:username`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/gitee/events/y_project",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "users/events.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/gitee/users/events.ts')",
  "name": "用户公开动态",
  "parameters": {
    "username": "用户名"
  },
  "path": "/events/:username",
  "radar": [
    {
      "source": [
        "gitee.com/:username"
      ]
    }
  ]
}
```
