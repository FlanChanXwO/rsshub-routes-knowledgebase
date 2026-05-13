# 华南理工大学 - 电子与信息学院 - 新闻速递

## Coverage
`index-only`

## Route
- Namespace: `scut`
- Namespace Name: `华南理工大学`
- Route Path: `/seie/news_center`
- Route Name: `电子与信息学院 - 新闻速递`
- Example: `/scut/seie/news_center`
- URL: `www2.scut.edu.cn/ee/16285/list.htm`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `auto-bot-ty`
- Source Location: `seie/news-ccenter.ts`
- Source Module: `() => import('@/routes/scut/seie/news-ccenter.ts')`

## Description
::: warning
由于学院官网对非大陆 IP 的访问存在限制，需自行部署。
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
  - `www2.scut.edu.cn/ee/16285/list.htm`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "::: warning\n由于学院官网对非大陆 IP 的访问存在限制，需自行部署。\n:::",
  "example": "/scut/seie/news_center",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "seie/news-ccenter.ts",
  "maintainers": [
    "auto-bot-ty"
  ],
  "module": "() => import('@/routes/scut/seie/news-ccenter.ts')",
  "name": "电子与信息学院 - 新闻速递",
  "parameters": {},
  "path": "/seie/news_center",
  "radar": [
    {
      "source": [
        "www2.scut.edu.cn/ee/16285/list.htm"
      ]
    }
  ],
  "url": "www2.scut.edu.cn/ee/16285/list.htm"
}
```
