# 慢雾科技 - 动态

## Coverage
`index-only`

## Route
- Namespace: `slowmist`
- Namespace Name: `慢雾科技`
- Route Path: `/:type?`
- Route Name: `动态`
- Example: `/slowmist/research`
- URL: `slowmist.com/zh/news.html`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `AtlasQuan`
- Source Location: `slowmist.ts`
- Source Module: `() => import('@/routes/slowmist/slowmist.ts')`

## Description
| 公司新闻 | 漏洞披露 | 技术研究 |
| -------- | -------- | -------- |
| news     | vul      | research |

## Parameters
- `type`: 分类，见下表，默认为公司新闻


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
  - `slowmist.com/zh/news.html`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 公司新闻 | 漏洞披露 | 技术研究 |\n| -------- | -------- | -------- |\n| news     | vul      | research |",
  "example": "/slowmist/research",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "slowmist.ts",
  "maintainers": [
    "AtlasQuan"
  ],
  "module": "() => import('@/routes/slowmist/slowmist.ts')",
  "name": "动态",
  "parameters": {
    "type": "分类，见下表，默认为公司新闻"
  },
  "path": "/:type?",
  "radar": [
    {
      "source": [
        "slowmist.com/zh/news.html"
      ]
    }
  ],
  "url": "slowmist.com/zh/news.html"
}
```
