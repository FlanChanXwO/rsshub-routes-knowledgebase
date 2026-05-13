# 北京大学 - 北大未名 BBS 全站十大

## Coverage
`index-only`

## Route
- Namespace: `pku`
- Namespace Name: `北京大学`
- Route Path: `/bbs/hot`
- Route Name: `北大未名 BBS 全站十大`
- Example: `/pku/bbs/hot`
- URL: `bbs.pku.edu.cn/v2/hot-topic.php`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `wooddance`
- Source Location: `bbs/hot.ts`
- Source Module: `() => import('@/routes/pku/bbs/hot.ts')`

## Description
::: warning
  论坛部分帖子正文内容的获取需要用户登录后的 Cookie 值，详情见部署页面的配置模块。
:::

## Parameters
_None_


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `bbs.pku.edu.cn/v2/hot-topic.php`
  - `bbs.pku.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "::: warning\n  论坛部分帖子正文内容的获取需要用户登录后的 Cookie 值，详情见部署页面的配置模块。\n:::",
  "example": "/pku/bbs/hot",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "bbs/hot.ts",
  "maintainers": [
    "wooddance"
  ],
  "module": "() => import('@/routes/pku/bbs/hot.ts')",
  "name": "北大未名 BBS 全站十大",
  "parameters": {},
  "path": "/bbs/hot",
  "radar": [
    {
      "source": [
        "bbs.pku.edu.cn/v2/hot-topic.php",
        "bbs.pku.edu.cn/"
      ]
    }
  ],
  "url": "bbs.pku.edu.cn/v2/hot-topic.php"
}
```
