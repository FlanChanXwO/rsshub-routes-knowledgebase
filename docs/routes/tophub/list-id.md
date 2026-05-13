# 今日热榜 - 榜单列表

## Coverage
`index-only`

## Route
- Namespace: `tophub`
- Namespace Name: `今日热榜`
- Route Path: `/list/:id`
- Route Name: `榜单列表`
- Example: `/tophub/list/Om4ejxvxEN`
- URL: `tophub.today`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `akynazh`
- Source Location: `list.tsx`
- Source Module: `() => import('@/routes/tophub/list.tsx')`

## Description
::: tip
将榜单条目集合到一个列表中，且有热度排序，可避免推送大量条目。
:::

## Parameters
- `id`: 榜单id，可在 URL 中找到


## Features
- `requireConfig`: [{"description": "", "name": "TOPHUB_COOKIE", "optional": true}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `tophub.today/n/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n将榜单条目集合到一个列表中，且有热度排序，可避免推送大量条目。\n:::",
  "example": "/tophub/list/Om4ejxvxEN",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "",
        "name": "TOPHUB_COOKIE",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "list.tsx",
  "maintainers": [
    "akynazh"
  ],
  "module": "() => import('@/routes/tophub/list.tsx')",
  "name": "榜单列表",
  "parameters": {
    "id": "榜单id，可在 URL 中找到"
  },
  "path": "/list/:id",
  "radar": [
    {
      "source": [
        "tophub.today/n/:id"
      ]
    }
  ]
}
```
