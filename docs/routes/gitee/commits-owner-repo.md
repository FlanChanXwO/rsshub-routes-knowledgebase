# Gitee - 仓库提交

## Coverage
`index-only`

## Route
- Namespace: `gitee`
- Namespace Name: `Gitee`
- Route Path: `/commits/:owner/:repo`
- Route Name: `仓库提交`
- Example: `/gitee/commits/y_project/RuoYi`
- URL: `gitee.com`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `TonyRL`
- Source Location: `repos/commits.ts`
- Source Module: `() => import('@/routes/gitee/repos/commits.ts')`

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
  - `gitee.com/:owner/:repo/commits`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/gitee/commits/y_project/RuoYi",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "repos/commits.ts",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/gitee/repos/commits.ts')",
  "name": "仓库提交",
  "parameters": {
    "owner": "用户名",
    "repo": "仓库名"
  },
  "path": "/commits/:owner/:repo",
  "radar": [
    {
      "source": [
        "gitee.com/:owner/:repo/commits"
      ]
    }
  ]
}
```
