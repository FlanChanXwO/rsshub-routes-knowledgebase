# 禁漫天堂 - 文庫

## Coverage
`index-only`

## Route
- Namespace: `18comic`
- Namespace Name: `禁漫天堂`
- Route Path: `/blogs/:category?`
- Route Name: `文庫`
- Example: `/18comic/blogs`
- URL: `jmcomic.group/`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `nczitzk, pseudoyu`
- Source Location: `blogs.ts`
- Source Module: `() => import('@/routes/18comic/blogs.ts')`

## Description
分类

| 全部 | 紳夜食堂 | 遊戲文庫 | JG GAMES | 模型山下 |
| ---- | -------- | -------- | -------- | -------- |
|      | dinner   | raiders  | jg       | figure   |

## Parameters
- `category`: 分类，见下表，默认为空即全部


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `nsfw`: true

## Radar
### Rule 1
- `source`:
  - `jmcomic.group/`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "分类\n\n| 全部 | 紳夜食堂 | 遊戲文庫 | JG GAMES | 模型山下 |\n| ---- | -------- | -------- | -------- | -------- |\n|      | dinner   | raiders  | jg       | figure   |",
  "example": "/18comic/blogs",
  "features": {
    "antiCrawler": true,
    "nsfw": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "blogs.ts",
  "maintainers": [
    "nczitzk",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/18comic/blogs.ts')",
  "name": "文庫",
  "parameters": {
    "category": "分类，见下表，默认为空即全部"
  },
  "path": "/blogs/:category?",
  "radar": [
    {
      "source": [
        "jmcomic.group/"
      ]
    }
  ],
  "url": "jmcomic.group/"
}
```
