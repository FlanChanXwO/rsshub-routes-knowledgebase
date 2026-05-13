# メロンブックス - 搜索结果

## Coverage
`index-only`

## Route
- Namespace: `melonbooks`
- Namespace Name: `メロンブックス`
- Route Path: `/search/:query?`
- Route Name: `搜索结果`
- Example: `/melonbooks/search/name=けいおん`
- URL: `www.melonbooks.co.jp`
- Language: `ja`
- Categories: `anime`
- Maintainers: `cokemine`
- Source Location: `search.ts`
- Source Module: `() => import('@/routes/melonbooks/search.ts')`

## Description
::: tip
如果你期望获取限制级内容，可以添加`&adult_view=1`参数
:::

## Parameters
- `category`: 链接参数，对应网址问号后的内容，不携带问号


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "::: tip\n如果你期望获取限制级内容，可以添加`&adult_view=1`参数\n:::",
  "example": "/melonbooks/search/name=けいおん",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "search.ts",
  "maintainers": [
    "cokemine"
  ],
  "module": "() => import('@/routes/melonbooks/search.ts')",
  "name": "搜索结果",
  "parameters": {
    "category": "链接参数，对应网址问号后的内容，不携带问号"
  },
  "path": "/search/:query?"
}
```
