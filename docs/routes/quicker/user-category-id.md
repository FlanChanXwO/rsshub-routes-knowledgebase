# Quicker - 用户更新

## Coverage
`index-only`

## Route
- Namespace: `quicker`
- Namespace Name: `Quicker`
- Route Path: `/user/:category/:id`
- Route Name: `用户更新`
- Example: `/quicker/user/Actions/3-CL`
- URL: `getquicker.net`
- Language: `zh-CN`
- Categories: `programming`
- Maintainers: `Cesaryuan, nczitzk`
- Source Location: `user.ts`
- Source Module: `() => import('@/routes/quicker/user.ts')`

## Description
| 动作    | 子程序      | 动作单      |
| ------- | ----------- | ----------- |
| Actions | SubPrograms | ActionLists |

## Parameters
- `category`: 分类，见下表
- `id`: 用户 id，可在对应用户页 URL 中找到


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
    "programming"
  ],
  "description": "| 动作    | 子程序      | 动作单      |\n| ------- | ----------- | ----------- |\n| Actions | SubPrograms | ActionLists |",
  "example": "/quicker/user/Actions/3-CL",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "user.ts",
  "maintainers": [
    "Cesaryuan",
    "nczitzk"
  ],
  "module": "() => import('@/routes/quicker/user.ts')",
  "name": "用户更新",
  "parameters": {
    "category": "分类，见下表",
    "id": "用户 id，可在对应用户页 URL 中找到"
  },
  "path": "/user/:category/:id"
}
```
