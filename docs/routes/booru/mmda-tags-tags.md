# Booru - MMDArchive 标签查询

## Coverage
`index-only`

## Route
- Namespace: `booru`
- Namespace Name: `Booru`
- Route Path: `/mmda/tags/:tags?`
- Route Name: `MMDArchive 标签查询`
- Example: `/booru/mmda/tags/full_body%20blue_eyes`
- URL: `mmda.booru.org`
- Language: `en`
- Categories: `picture`
- Maintainers: `N78Wy`
- Source Location: `mmda.ts`
- Source Module: `() => import('@/routes/booru/mmda.ts')`

## Description
For example:

  -   默认查询 (什么 tag 都不加)：`/booru/mmda/tags`
  -   默认查询单个 tag：`/booru/mmda/tags/full_body`
  -   默认查询多个 tag：`/booru/mmda/tags/full_body%20blue_eyes`
  -   默认查询根据作者查询：`/booru/mmda/tags/user:xxxx`

## Parameters
- `tags`: 标签，多个标签使用 `%20` 连接，如需根据作者查询则在 `user:` 后接上作者名，如：`user:xxxx`


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `mmda.booru.org/index.php`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "description": "For example:\n\n  -   默认查询 (什么 tag 都不加)：`/booru/mmda/tags`\n  -   默认查询单个 tag：`/booru/mmda/tags/full_body`\n  -   默认查询多个 tag：`/booru/mmda/tags/full_body%20blue_eyes`\n  -   默认查询根据作者查询：`/booru/mmda/tags/user:xxxx`",
  "example": "/booru/mmda/tags/full_body%20blue_eyes",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "mmda.ts",
  "maintainers": [
    "N78Wy"
  ],
  "module": "() => import('@/routes/booru/mmda.ts')",
  "name": "MMDArchive 标签查询",
  "parameters": {
    "tags": "标签，多个标签使用 `%20` 连接，如需根据作者查询则在 `user:` 后接上作者名，如：`user:xxxx`"
  },
  "path": "/mmda/tags/:tags?",
  "radar": [
    {
      "source": [
        "mmda.booru.org/index.php"
      ]
    }
  ]
}
```
