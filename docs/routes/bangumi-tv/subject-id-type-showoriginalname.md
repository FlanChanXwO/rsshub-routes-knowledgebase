# Bangumi 番组计划 - 条目的通用路由格式

## Coverage
`index-only`

## Route
- Namespace: `bangumi.tv`
- Namespace Name: `Bangumi 番组计划`
- Route Path: `/subject/:id/:type?/:showOriginalName?`
- Route Name: `条目的通用路由格式`
- Example: `/bangumi.tv/subject/328609/ep/true`
- URL: `bangumi.tv`
- Language: `zh-CN`
- Categories: `anime`
- Maintainers: `JimenezLi`
- Source Location: `subject/index.ts`
- Source Module: `() => import('@/routes/bangumi.tv/subject/index.ts')`

## Description
::: warning
  此通用路由仅用于对路由参数的描述，具体信息请查看下方与条目相关的路由
:::

## Parameters
- `id`: 条目 id, 在条目页面的地址栏查看
- `type`: 条目类型，可选值为 `ep`, `comments`, `blogs`, `topics`，默认为 `ep`
- `showOriginalName`: 显示番剧标题原名，可选值 0/1/false/true，默认为 false


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
  - `bgm.tv/subject/:id`
- `target`: `/tv/subject/:id`

## Raw JSON
```json
{
  "categories": [
    "anime"
  ],
  "description": "::: warning\n  此通用路由仅用于对路由参数的描述，具体信息请查看下方与条目相关的路由\n:::",
  "example": "/bangumi.tv/subject/328609/ep/true",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "subject/index.ts",
  "maintainers": [
    "JimenezLi"
  ],
  "module": "() => import('@/routes/bangumi.tv/subject/index.ts')",
  "name": "条目的通用路由格式",
  "parameters": {
    "id": "条目 id, 在条目页面的地址栏查看",
    "showOriginalName": "显示番剧标题原名，可选值 0/1/false/true，默认为 false",
    "type": "条目类型，可选值为 `ep`, `comments`, `blogs`, `topics`，默认为 `ep`"
  },
  "path": "/subject/:id/:type?/:showOriginalName?",
  "radar": [
    {
      "source": [
        "bgm.tv/subject/:id"
      ],
      "target": "/tv/subject/:id"
    }
  ]
}
```
