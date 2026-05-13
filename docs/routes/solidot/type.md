# Solidot - 最新消息

## Coverage
`index-only`

## Route
- Namespace: `solidot`
- Namespace Name: `Solidot`
- Route Path: `/:type?`
- Route Name: `最新消息`
- Example: `/solidot/linux`
- URL: `www.solidot.org`
- Language: `zh-CN`
- Categories: `traditional-media`
- Maintainers: `sgqy, hang333, TonyRL`
- Source Location: `main.ts`
- Source Module: `() => import('@/routes/solidot/main.ts')`

## Description
_None_

## Parameters
- `type`: {"default": "www", "description": "消息类型，在网站上方选择后复制子域名或参见 [https://www.solidot.org/index.rss](https://www.solidot.org/index.rss) 即可", "options": [{"label": "全部", "value": "www"}, {"label": "创业", "value": "startup"}, {"label": "Linux", "value": "linux"}, {"label": "科学", "value": "science"}, {"label": "科技", "value": "technology"}, {"label": "移动", "value": "mobile"}, {"label": "苹果", "value": "apple"}, {"label": "硬件", "value": "hardware"}, {"label": "软件", "value": "software"}, {"label": "安全", "value": "security"}, {"label": "游戏", "value": "games"}, {"label": "书籍", "value": "books"}, {"label": "ask", "value": "ask"}, {"label": "idle", "value": "idle"}, {"label": "博客", "value": "blog"}, {"label": "云计算", "value": "cloud"}, {"label": "奇客故事", "value": "story"}]}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "example": "/solidot/linux",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "main.ts",
  "maintainers": [
    "sgqy",
    "hang333",
    "TonyRL"
  ],
  "module": "() => import('@/routes/solidot/main.ts')",
  "name": "最新消息",
  "parameters": {
    "type": {
      "default": "www",
      "description": "消息类型，在网站上方选择后复制子域名或参见 [https://www.solidot.org/index.rss](https://www.solidot.org/index.rss) 即可",
      "options": [
        {
          "label": "全部",
          "value": "www"
        },
        {
          "label": "创业",
          "value": "startup"
        },
        {
          "label": "Linux",
          "value": "linux"
        },
        {
          "label": "科学",
          "value": "science"
        },
        {
          "label": "科技",
          "value": "technology"
        },
        {
          "label": "移动",
          "value": "mobile"
        },
        {
          "label": "苹果",
          "value": "apple"
        },
        {
          "label": "硬件",
          "value": "hardware"
        },
        {
          "label": "软件",
          "value": "software"
        },
        {
          "label": "安全",
          "value": "security"
        },
        {
          "label": "游戏",
          "value": "games"
        },
        {
          "label": "书籍",
          "value": "books"
        },
        {
          "label": "ask",
          "value": "ask"
        },
        {
          "label": "idle",
          "value": "idle"
        },
        {
          "label": "博客",
          "value": "blog"
        },
        {
          "label": "云计算",
          "value": "cloud"
        },
        {
          "label": "奇客故事",
          "value": "story"
        }
      ]
    }
  },
  "path": "/:type?",
  "view": 0
}
```
