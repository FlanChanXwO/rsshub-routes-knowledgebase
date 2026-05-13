# 趣集 - 盐选故事专栏

## Coverage
`index-only`

## Route
- Namespace: `ifun`
- Namespace Name: `趣集`
- Route Path: `/n/tag/:name`
- Route Name: `盐选故事专栏`
- Example: `/ifun/n/tag/zhihu`
- URL: `n.ifun.cool`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `n/tag.ts`
- Source Module: `() => import('@/routes/ifun/n/tag.ts')`

## Description
::: tip
若订阅 [zhihu](https://n.ifun.cool/article-list/2?tagName=zhihu)，网址为 `https://n.ifun.cool/article-list/2?tagName=zhihu`，请截取 `tagName` 的值 `zhihu` 作为 `name` 参数填入，此时目标路由为 [`/ifun/n/tag/zhihu`](https://rsshub.app/ifun/n/tag/zhihu)。

更多专栏请见 [盐选故事专栏](https://n.ifun.cool/tags)。
:::

## Parameters
- `name`: 专栏 id，可在对应专栏页 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `n.ifun.cool/article-list/1`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n若订阅 [zhihu](https://n.ifun.cool/article-list/2?tagName=zhihu)，网址为 `https://n.ifun.cool/article-list/2?tagName=zhihu`，请截取 `tagName` 的值 `zhihu` 作为 `name` 参数填入，此时目标路由为 [`/ifun/n/tag/zhihu`](https://rsshub.app/ifun/n/tag/zhihu)。\n\n更多专栏请见 [盐选故事专栏](https://n.ifun.cool/tags)。\n:::\n    ",
  "example": "/ifun/n/tag/zhihu",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "n/tag.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/ifun/n/tag.ts')",
  "name": "盐选故事专栏",
  "parameters": {
    "name": "专栏 id，可在对应专栏页 URL 中找到"
  },
  "path": "/n/tag/:name",
  "radar": [
    {
      "source": [
        "n.ifun.cool/article-list/1"
      ]
    }
  ],
  "url": "n.ifun.cool",
  "view": 0
}
```
