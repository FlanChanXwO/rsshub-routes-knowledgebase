# 开源中国 - 资讯

## Coverage
`index-only`

## Route
- Namespace: `oschina`
- Namespace Name: `开源中国`
- Route Path: `/news/:category?`
- Route Name: `资讯`
- Example: `/oschina/news`
- URL: `oschina.net`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `tgly307, zengxs`
- Source Location: `news.ts`
- Source Module: `() => import('@/routes/oschina/news.ts')`

## Description
_None_

## Parameters
- `category`: {"default": "0", "description": "板块名", "options": [{"label": "全部", "value": "0"}, {"label": "开源治理", "value": "1"}, {"label": "区块链 & Web3 & 元宇宙", "value": "2"}, {"label": "云原生", "value": "3"}, {"label": "AI & 大模型", "value": "4"}, {"label": "数据库", "value": "5"}, {"label": "硬件 & IoT", "value": "6"}, {"label": "信息安全", "value": "7"}, {"label": "程序人生", "value": "8"}, {"label": "DevOps", "value": "9"}, {"label": "软件架构", "value": "10"}, {"label": "开发技能", "value": "11"}, {"label": "大前端", "value": "12"}, {"label": "信息安全", "value": "13"}, {"label": "软件测试 & 运维", "value": "14"}, {"label": "网络技术", "value": "15"}, {"label": "游戏开发", "value": "16"}, {"label": "多媒体处理", "value": "17"}, {"label": "操作系统", "value": "19"}, {"label": "开源资讯", "value": "9998"}, {"label": "软件资讯", "value": "9999"}]}


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
  - `oschina.net`
- `target`: `/news`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/oschina/news",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "news.ts",
  "maintainers": [
    "tgly307",
    "zengxs"
  ],
  "module": "() => import('@/routes/oschina/news.ts')",
  "name": "资讯",
  "parameters": {
    "category": {
      "default": "0",
      "description": "板块名",
      "options": [
        {
          "label": "全部",
          "value": "0"
        },
        {
          "label": "开源治理",
          "value": "1"
        },
        {
          "label": "区块链 & Web3 & 元宇宙",
          "value": "2"
        },
        {
          "label": "云原生",
          "value": "3"
        },
        {
          "label": "AI & 大模型",
          "value": "4"
        },
        {
          "label": "数据库",
          "value": "5"
        },
        {
          "label": "硬件 & IoT",
          "value": "6"
        },
        {
          "label": "信息安全",
          "value": "7"
        },
        {
          "label": "程序人生",
          "value": "8"
        },
        {
          "label": "DevOps",
          "value": "9"
        },
        {
          "label": "软件架构",
          "value": "10"
        },
        {
          "label": "开发技能",
          "value": "11"
        },
        {
          "label": "大前端",
          "value": "12"
        },
        {
          "label": "信息安全",
          "value": "13"
        },
        {
          "label": "软件测试 & 运维",
          "value": "14"
        },
        {
          "label": "网络技术",
          "value": "15"
        },
        {
          "label": "游戏开发",
          "value": "16"
        },
        {
          "label": "多媒体处理",
          "value": "17"
        },
        {
          "label": "操作系统",
          "value": "19"
        },
        {
          "label": "开源资讯",
          "value": "9998"
        },
        {
          "label": "软件资讯",
          "value": "9999"
        }
      ]
    }
  },
  "path": "/news/:category?",
  "radar": [
    {
      "source": [
        "oschina.net"
      ],
      "target": "/news"
    }
  ]
}
```
