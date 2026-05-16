# 数字尾巴 - 标签

## Coverage
`index-only`

## Route
- Namespace: `dgtle`
- Namespace Name: `数字尾巴`
- Route Path: `/dgtle/tag/:id`
- Route Name: `标签`
- Example: `/dgtle/tag/394`
- URL: `www.dgtle.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `tag.ts`
- Source Module: `_None_`

## Description
::: tip
订阅 [#手机讨论区](https://www.dgtle.com/tag-394-1.html)，其源网址为 `https://www.dgtle.com/tag-394-1.html`，请参考该 URL 指定部分构成参数，此时路由为 [`/dgtle/tag/394`](https://rsshub.app/dgtle/tag/394)。
:::

## Parameters
- `id`: {"description": "标签 ID，可在对应标签页 URL 中找到"}


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
  - `www.dgtle.com/$tag-:id-\d+.html`
- `target`: `/tag/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n订阅 [#手机讨论区](https://www.dgtle.com/tag-394-1.html)，其源网址为 `https://www.dgtle.com/tag-394-1.html`，请参考该 URL 指定部分构成参数，此时路由为 [`/dgtle/tag/394`](https://rsshub.app/dgtle/tag/394)。\n:::",
  "example": "/dgtle/tag/394",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 0,
  "location": "tag.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "标签",
  "parameters": {
    "id": {
      "description": "标签 ID，可在对应标签页 URL 中找到"
    }
  },
  "path": "/tag/:id",
  "radar": [
    {
      "source": [
        "www.dgtle.com/$tag-:id-\\d+.html"
      ],
      "target": "/tag/:id"
    }
  ],
  "topFeeds": [],
  "url": "www.dgtle.com",
  "view": 0
}
```
