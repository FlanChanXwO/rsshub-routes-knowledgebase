# 阿里云 - 开发者社区 - 主题

## Coverage
`index-only`

## Route
- Namespace: `aliyun`
- Namespace Name: `阿里云`
- Route Path: `/developer/group/:type`
- Route Name: `开发者社区 - 主题`
- Example: `/aliyun/developer/group/alitech`
- URL: `developer.aliyun.com`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `umm233`
- Source Location: `developer/group.ts`
- Source Module: `() => import('@/routes/aliyun/developer/group.ts')`

## Description
_None_

## Parameters
- `type`: 对应技术领域分类


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
  - `developer.aliyun.com/group/:type`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "example": "/aliyun/developer/group/alitech",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "developer/group.ts",
  "maintainers": [
    "umm233"
  ],
  "module": "() => import('@/routes/aliyun/developer/group.ts')",
  "name": "开发者社区 - 主题",
  "parameters": {
    "type": "对应技术领域分类"
  },
  "path": "/developer/group/:type",
  "radar": [
    {
      "source": [
        "developer.aliyun.com/group/:type"
      ]
    }
  ]
}
```
