# HelloGitHub - 开源项目

## Coverage
`index-only`

## Route
- Namespace: `hellogithub`
- Namespace Name: `HelloGitHub`
- Route Path: `/home/:sort?/:id?`
- Route Name: `开源项目`
- Example: `/hellogithub/home`
- URL: `hellogithub.com`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `moke8, nczitzk, CaoMeiYouRen`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/hellogithub/index.ts')`

## Description
| 精选 | 全部 |
| ---- | ---- |
| featured  | all |

## Parameters
- `sort`: 排序方式，见下表，默认为 `featured`，即精选
- `id`: 标签 id，可在对应标签页 URL 中找到，默认为全部标签


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
  "description": "| 精选 | 全部 |\n| ---- | ---- |\n| featured  | all |",
  "example": "/hellogithub/home",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [
    "moke8",
    "nczitzk",
    "CaoMeiYouRen"
  ],
  "module": "() => import('@/routes/hellogithub/index.ts')",
  "name": "开源项目",
  "parameters": {
    "id": "标签 id，可在对应标签页 URL 中找到，默认为全部标签",
    "sort": "排序方式，见下表，默认为 `featured`，即精选"
  },
  "path": "/home/:sort?/:id?"
}
```
