# NGA - 分区帖子

## Coverage
`index-only`

## Route
- Namespace: `nga`
- Namespace Name: `NGA`
- Route Path: `/forum/:fid/:recommend?`
- Route Name: `分区帖子`
- Example: `/nga/forum/489`
- URL: `bbs.nga.cn`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `xyqfer`
- Source Location: `forum.ts`
- Source Module: `() => import('@/routes/nga/forum.ts')`

## Description
_None_

## Parameters
- `fid`: 分区 id, 可在分区主页 URL 找到, 没有 fid 时 stid 同样适用
- `recommend`: 是否只显示精华主题, 留空为否, 任意值为是


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
    "bbs"
  ],
  "example": "/nga/forum/489",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "forum.ts",
  "maintainers": [
    "xyqfer"
  ],
  "module": "() => import('@/routes/nga/forum.ts')",
  "name": "分区帖子",
  "parameters": {
    "fid": "分区 id, 可在分区主页 URL 找到, 没有 fid 时 stid 同样适用",
    "recommend": "是否只显示精华主题, 留空为否, 任意值为是"
  },
  "path": "/forum/:fid/:recommend?",
  "view": 0
}
```
