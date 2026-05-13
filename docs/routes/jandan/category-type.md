# 煎蛋 - Section

## Coverage
`index-only`

## Route
- Namespace: `jandan`
- Namespace Name: `煎蛋`
- Route Path: `/:category/:type?`
- Route Name: `Section`
- Example: `/jandan/top`
- URL: `jandan.net`
- Language: `zh-CN`
- Categories: `None`
- Maintainers: `nczitzk, pseudoyu`
- Source Location: `section.ts`
- Source Module: `() => import('@/routes/jandan/section.ts')`

## Description
_None_

## Parameters
- `category`: {"description": "板块", "options": [{"label": "热榜", "value": "top"}, {"label": "问答", "value": "qa"}, {"label": "树洞", "value": "treehole"}, {"label": "随手拍", "value": "ooxx"}, {"label": "无聊图", "value": "pic"}, {"label": "鱼塘", "value": "bbs"}]}
- `type`: {"default": "4hr", "description": "热榜类型，仅当 category 选择 `top` 时有效", "options": [{"label": "4小时热门", "value": "4hr"}, {"label": "3天内无聊图", "value": "pic3days"}, {"label": "7天内无聊图", "value": "pic7days"}]}


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
  - `i.jandan.net/:category`
- `target`: `/jandan/:category?`

## Raw JSON
```json
{
  "example": "/jandan/top",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "section.ts",
  "maintainers": [
    "nczitzk",
    "pseudoyu"
  ],
  "module": "() => import('@/routes/jandan/section.ts')",
  "name": "Section",
  "parameters": {
    "category": {
      "description": "板块",
      "options": [
        {
          "label": "热榜",
          "value": "top"
        },
        {
          "label": "问答",
          "value": "qa"
        },
        {
          "label": "树洞",
          "value": "treehole"
        },
        {
          "label": "随手拍",
          "value": "ooxx"
        },
        {
          "label": "无聊图",
          "value": "pic"
        },
        {
          "label": "鱼塘",
          "value": "bbs"
        }
      ]
    },
    "type": {
      "default": "4hr",
      "description": "热榜类型，仅当 category 选择 `top` 时有效",
      "options": [
        {
          "label": "4小时热门",
          "value": "4hr"
        },
        {
          "label": "3天内无聊图",
          "value": "pic3days"
        },
        {
          "label": "7天内无聊图",
          "value": "pic7days"
        }
      ]
    }
  },
  "path": "/:category/:type?",
  "radar": [
    {
      "source": [
        "i.jandan.net/:category"
      ],
      "target": "/jandan/:category?"
    }
  ]
}
```
