# HelloGitHub - 文章

## Coverage
`index-only`

## Route
- Namespace: `hellogithub`
- Namespace Name: `HelloGitHub`
- Route Path: `/article/:sort?`
- Route Name: `文章`
- Example: `/hellogithub/article`
- URL: `hellogithub.com`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `moke8, nczitzk, CaoMeiYouRen`
- Source Location: `article.ts`
- Source Module: `() => import('@/routes/hellogithub/article.ts')`

## Description
| 热门 | 最近 |
| ---- | ---- |
| hot  | last |

## Parameters
- `sort`: 排序方式，见下表，默认为 `last`，即最近


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
    "programming"
  ],
  "description": "| 热门 | 最近 |\n| ---- | ---- |\n| hot  | last |",
  "example": "/hellogithub/article",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "article.ts",
  "maintainers": [
    "moke8",
    "nczitzk",
    "CaoMeiYouRen"
  ],
  "module": "() => import('@/routes/hellogithub/article.ts')",
  "name": "文章",
  "parameters": {
    "sort": "排序方式，见下表，默认为 `last`，即最近"
  },
  "path": "/article/:sort?"
}
```
