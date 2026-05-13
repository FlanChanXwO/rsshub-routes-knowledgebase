# Gitee - 仓库 Releases

## Coverage
`index-only`

## Route
- Namespace: `gitee`
- Namespace Name: `Gitee`
- Route Path: `/gitee/releases/:owner/:repo`
- Route Name: `仓库 Releases`
- Example: `/gitee/releases/y_project/RuoYi`
- URL: `gitee.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `TonyRL`
- Source Location: `repos/releases.ts`
- Source Module: `_None_`

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
  "heat": 2,
  "location": "repos/releases.ts",
  "maintainers": [
    "TonyRL"
  ],
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
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "gurecn/YuyanIme - 发行版 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "121884655654946816",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://gitee.com/gurecn/YuyanIme/releases",
      "title": "gurecn/YuyanIme - 发行版",
      "type": "feed",
      "url": "rsshub://gitee/releases/gurecn/YuyanIme"
    },
    {
      "description": "cxasm/notepad-- - 发行版 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "82079478779730944",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://gitee.com/cxasm/notepad--/releases",
      "title": "cxasm/notepad-- - 发行版",
      "type": "feed",
      "url": "rsshub://gitee/releases/cxasm/notepad--"
    }
  ]
}
```
