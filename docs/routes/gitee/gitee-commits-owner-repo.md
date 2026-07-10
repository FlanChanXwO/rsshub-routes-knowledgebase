# Gitee - 仓库提交

## Coverage
`index-only`

## Route
- Namespace: `gitee`
- Namespace Name: `Gitee`
- Route Path: `/gitee/commits/:owner/:repo`
- Route Name: `仓库提交`
- Example: `/gitee/commits/y_project/RuoYi`
- URL: `gitee.com`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `TonyRL`
- Source Location: `repos/commits.ts`
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
  "heat": 1,
  "location": "repos/commits.ts",
  "maintainers": [
    "TonyRL"
  ],
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
  ],
  "topFeeds": [
    {
      "description": "PublicGuan/qipaishi_server - 提交 - Powered by RSSHub",
      "errorAt": "2025-08-14T04:34:50.481Z",
      "errorMessage": "[GET] \"https://gitee.com/api/v5/repos/PublicGuan/qipaishi_server/commits?per_page=100&direction=desc\": 404 Not Found\n",
      "id": "86665639185398784",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://gitee.com/PublicGuan/qipaishi_server/commits",
      "title": "PublicGuan/qipaishi_server - 提交",
      "type": "feed",
      "url": "rsshub://gitee/commits/PublicGuan/qipaishi_server"
    }
  ]
}
```
