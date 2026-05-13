# 太平洋科技 - 科技新闻

## Coverage
`index-only`

## Route
- Namespace: `pconline`
- Namespace Name: `太平洋科技`
- Route Path: `/focus/:category?`
- Route Name: `科技新闻`
- Example: `/pconline/focus`
- URL: `pconline.com.cn`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `CH563`
- Source Location: `focus.ts`
- Source Module: `() => import('@/routes/pconline/focus.ts')`

## Description
::: tip
| 全部 | 科技 | 财经 | 生活 | 公司 | 人物 |
| --- | --- | --- | --- | --- | --- |
| all | tech | finance | life | company | character |
:::

## Parameters
- `category`: {"default": "all", "description": "科技新闻的类别，获取最新的一页，分别：all, tech, finance, life, company, character"}


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
  - `pconline.com.cn/focus/`
  - `pconline.com.cn/`
- `target`: `/focus`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "::: tip\n| 全部 | 科技 | 财经 | 生活 | 公司 | 人物 |\n| --- | --- | --- | --- | --- | --- |\n| all | tech | finance | life | company | character |\n:::",
  "example": "/pconline/focus",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "focus.ts",
  "maintainers": [
    "CH563"
  ],
  "module": "() => import('@/routes/pconline/focus.ts')",
  "name": "科技新闻",
  "parameters": {
    "category": {
      "default": "all",
      "description": "科技新闻的类别，获取最新的一页，分别：all, tech, finance, life, company, character"
    }
  },
  "path": "/focus/:category?",
  "radar": [
    {
      "source": [
        "pconline.com.cn/focus/",
        "pconline.com.cn/"
      ],
      "target": "/focus"
    }
  ]
}
```
