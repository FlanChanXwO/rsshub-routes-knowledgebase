# Gitee - 仓库 Releases

## Coverage
`index-only`

## Route
- Namespace: `gitee`
- Namespace Name: `Gitee`
- Route Path: `/releases/:owner/:repo`
- Route Name: `仓库 Releases`
- Example: `/gitee/releases/y_project/RuoYi`
- URL: `gitee.com`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `TonyRL`
- Source Location: `repos/releases.ts`
- Source Module: `() => import('@/routes/gitee/repos/releases.ts')`

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
  - `gitee.com/:owner/:repo/releases`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/gitee/releases/y_project/RuoYi",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "repos/releases.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/gitee/repos/releases.ts')",
  "name": "仓库 Releases",
  "parameters": {
    "owner": "用户名",
    "repo": "仓库名"
  },
  "path": "/releases/:owner/:repo",
  "radar": [
    {
      "source": [
        "gitee.com/:owner/:repo/releases"
      ]
    }
  ]
}
```
