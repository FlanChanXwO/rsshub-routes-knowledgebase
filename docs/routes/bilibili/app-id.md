# 哔哩哔哩 bilibili - 更新情报

## Coverage
`index-only`

## Route
- Namespace: `bilibili`
- Namespace Name: `哔哩哔哩 bilibili`
- Route Path: `/app/:id?`
- Route Name: `更新情报`
- Example: `/bilibili/app/android`
- URL: `www.bilibili.com`
- Language: `zh-CN`
- Categories: `program-update`
- Maintainers: `nczitzk`
- Source Location: `app.ts`
- Source Module: `() => import('@/routes/bilibili/app.ts')`

## Description
| 安卓版  | iPhone 版 | iPad HD 版 | UWP 版 | TV 版            |
| ------- | --------- | ---------- | ------ | ---------------- |
| android | iphone    | ipad       | win    | android_tv_yst |

## Parameters
- `id`: 客户端 id，见下表，默认为安卓版


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
    "program-update"
  ],
  "description": "| 安卓版  | iPhone 版 | iPad HD 版 | UWP 版 | TV 版            |\n| ------- | --------- | ---------- | ------ | ---------------- |\n| android | iphone    | ipad       | win    | android_tv_yst |",
  "example": "/bilibili/app/android",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "app.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/bilibili/app.ts')",
  "name": "更新情报",
  "parameters": {
    "id": "客户端 id，见下表，默认为安卓版"
  },
  "path": "/app/:id?"
}
```
