# 央视新闻 - 栏目

## Coverage
`index-only`

## Route
- Namespace: `cctv`
- Namespace Name: `央视新闻`
- Route Path: `/lm/:id?`
- Route Name: `栏目`
- Example: `/cctv/lm/xwzk`
- URL: `news.cctv.com`
- Language: `zh-CN`
- Categories: `traditional-media`
- Maintainers: `nczitzk`
- Source Location: `lm.ts`
- Source Module: `() => import('@/routes/cctv/lm.ts')`

## Description
| 焦点访谈 | 等着我 | 今日说法 | 开讲啦 |
| -------- | ------ | -------- | ------ |
| jdft     | dzw    | jrsf     | kjl    |

| 正大综艺 | 经济半小时 | 第一动画乐园 |
| -------- | ---------- | ------------ |
| zdzy     | jjbxs      | dydhly       |

::: tip
  更多栏目请看 [这里](https://tv.cctv.com/lm)
:::

## Parameters
- `id`: 栏目 id，可在对应栏目页 URL 中找到，默认为 `xwzk` 即 新闻周刊


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `news.cctv.com/:category`
- `target`: `/:category`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| 焦点访谈 | 等着我 | 今日说法 | 开讲啦 |\n| -------- | ------ | -------- | ------ |\n| jdft     | dzw    | jrsf     | kjl    |\n\n| 正大综艺 | 经济半小时 | 第一动画乐园 |\n| -------- | ---------- | ------------ |\n| zdzy     | jjbxs      | dydhly       |\n\n::: tip\n  更多栏目请看 [这里](https://tv.cctv.com/lm)\n:::",
  "example": "/cctv/lm/xwzk",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "lm.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/cctv/lm.ts')",
  "name": "栏目",
  "parameters": {
    "id": "栏目 id，可在对应栏目页 URL 中找到，默认为 `xwzk` 即 新闻周刊"
  },
  "path": "/lm/:id?",
  "radar": [
    {
      "source": [
        "news.cctv.com/:category"
      ],
      "target": "/:category"
    }
  ]
}
```
