# 国家能源局 - 政府新闻

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/cn/news/:uid`
- Route Name: `政府新闻`
- Example: `/gov/cn/news/bm`
- URL: `www.nea.gov.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `EsuRt, howfool`
- Source Location: `cn/news/index.ts`
- Source Module: `() => import('@/routes/gov/cn/news/index.ts')`

## Description
| 政务部门 | 滚动新闻 | 新闻要闻 | 国务院新闻 | 国务院工作会议 | 政策文件 |
| :------: | :------: | :------: | :--------: | :------------: | :------: |
|    bm    |    gd    |    yw    |     gwy    |     gwyzzjg    |  zhengce |

## Parameters
- `uid`: 分类名


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
    "government"
  ],
  "description": "| 政务部门 | 滚动新闻 | 新闻要闻 | 国务院新闻 | 国务院工作会议 | 政策文件 |\n| :------: | :------: | :------: | :--------: | :------------: | :------: |\n|    bm    |    gd    |    yw    |     gwy    |     gwyzzjg    |  zhengce |",
  "example": "/gov/cn/news/bm",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "cn/news/index.ts",
  "maintainers": [
    "EsuRt",
    "howfool"
  ],
  "module": "() => import('@/routes/gov/cn/news/index.ts')",
  "name": "政府新闻",
  "parameters": {
    "uid": "分类名"
  },
  "path": "/cn/news/:uid"
}
```
