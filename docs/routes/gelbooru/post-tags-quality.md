# Gelbooru - 标签查询

## Coverage
`index-only`

## Route
- Namespace: `gelbooru`
- Namespace Name: `Gelbooru`
- Route Path: `/post/:tags?/:quality?`
- Route Name: `标签查询`
- Example: `/gelbooru/post/1girl rating:general`
- URL: `gelbooru.com`
- Language: `_None_`
- Categories: `picture`
- Maintainers: `magicFeirl`
- Source Location: `post.ts`
- Source Module: `() => import('@/routes/gelbooru/post.ts')`

## Description
- 默认查询: `/gelbooru/post` 功能等同查询 Gelbooru 网站最新的投稿
- 单标签查询: `/gelbooru/post/1girl` 查询 `1girl` 的最新投稿
- 多标签查询: `/gelbooru/post/1girl school_uniform rating:general`
- 指定为原图: `/gelbooru/post/1girl school_uniform rating:general/orig`
- 更多例子: 请参考 Gelbooru 官方 wiki https://gelbooru.com/index.php?page=wiki&s=&s=view&id=25921

**可选的 URL 参数**
- limit 页面返回数据量，默认 40，可选 1 ~ 100

e.g.: `/gelbooru/post?limit=20&`

## Parameters
- `tags`: 要搜索的标签，多个标签用 ` `（空格）隔开
- `quality`: {"default": "sample", "description": "图片质量，可选值为 `sample`（压缩后的图片，推荐值） 或 `orig`（原图），默认为 `sample`"}


## Features
- `requireConfig`: [{"description": "Gelbooru 偶尔会开启 API 认证，需配合 `GELBOORU_USER_ID`，从 `https://gelbooru.com/index.php?page=account&s=options` 获取", "name": "GELBOORU_API_KEY", "optional": true}, {"description": "参见 `GELBOORU_API_KEY`", "name": "GELBOORU_USER_ID", "optional": true}]
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
  - `gelbooru.com/index.php`

## Raw JSON
```json
{
  "categories": [
    "picture"
  ],
  "description": "\n- 默认查询: `/gelbooru/post` 功能等同查询 Gelbooru 网站最新的投稿\n- 单标签查询: `/gelbooru/post/1girl` 查询 `1girl` 的最新投稿\n- 多标签查询: `/gelbooru/post/1girl school_uniform rating:general`\n- 指定为原图: `/gelbooru/post/1girl school_uniform rating:general/orig`\n- 更多例子: 请参考 Gelbooru 官方 wiki https://gelbooru.com/index.php?page=wiki&s=&s=view&id=25921\n\n**可选的 URL 参数**\n- limit 页面返回数据量，默认 40，可选 1 ~ 100\n\ne.g.: `/gelbooru/post?limit=20&`\n",
  "example": "/gelbooru/post/1girl rating:general",
  "features": {
    "antiCrawler": false,
    "nsfw": true,
    "requireConfig": [
      {
        "description": "Gelbooru 偶尔会开启 API 认证，需配合 `GELBOORU_USER_ID`，从 `https://gelbooru.com/index.php?page=account&s=options` 获取",
        "name": "GELBOORU_API_KEY",
        "optional": true
      },
      {
        "description": "参见 `GELBOORU_API_KEY`",
        "name": "GELBOORU_USER_ID",
        "optional": true
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "post.ts",
  "maintainers": [
    "magicFeirl"
  ],
  "module": "() => import('@/routes/gelbooru/post.ts')",
  "name": "标签查询",
  "parameters": {
    "quality": {
      "default": "sample",
      "description": "图片质量，可选值为 `sample`（压缩后的图片，推荐值） 或 `orig`（原图），默认为 `sample`"
    },
    "tags": "要搜索的标签，多个标签用 ` `（空格）隔开"
  },
  "path": "/post/:tags?/:quality?",
  "radar": [
    {
      "source": [
        "gelbooru.com/index.php"
      ]
    }
  ],
  "view": 2
}
```
