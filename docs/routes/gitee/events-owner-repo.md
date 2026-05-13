# Gitee - 仓库动态

## Coverage
`index-only`

## Route
- Namespace: `gitee`
- Namespace Name: `Gitee`
- Route Path: `/events/:owner/:repo`
- Route Name: `仓库动态`
- Example: `/gitee/events/y_project/RuoYi`
- URL: `gitee.com`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `TonyRL`
- Source Location: `repos/events.ts`
- Source Module: `() => import('@/routes/gitee/repos/events.ts')`

## Description
_None_

## Parameters
- `owner`: 用户名
- `repo`: 仓库名


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
  - `gitee.com/:owner/:repo`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/gitee/events/y_project/RuoYi",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "repos/events.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/gitee/repos/events.ts')",
  "name": "仓库动态",
  "parameters": {
    "owner": "用户名",
    "repo": "仓库名"
  },
  "path": "/events/:owner/:repo",
  "radar": [
    {
      "source": [
        "gitee.com/:owner/:repo"
      ]
    }
  ]
}
```
