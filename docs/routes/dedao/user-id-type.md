# 得到 - 用户主页

## Coverage
`index-only`

## Route
- Namespace: `dedao`
- Namespace Name: `得到`
- Route Path: `/user/:id/:type?`
- Route Name: `用户主页`
- Example: `/dedao/user/VkA5OqLX4RyGxmZRNBMlwBrDaJQ9og`
- URL: `dedao.cn`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `user.tsx`
- Source Module: `() => import('@/routes/dedao/user.tsx')`

## Description
| 动态 | 书评 | 视频 |
| ---- | ---- | ---- |
| 0    | 7    | 12   |

## Parameters
- `id`: 用户 id，可在对应用户主页 URL 中找到
- `type`: 类型，见下表，默认为`0`，即动态


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
    "new-media"
  ],
  "description": "| 动态 | 书评 | 视频 |\n| ---- | ---- | ---- |\n| 0    | 7    | 12   |",
  "example": "/dedao/user/VkA5OqLX4RyGxmZRNBMlwBrDaJQ9og",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "user.tsx",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/dedao/user.tsx')",
  "name": "用户主页",
  "parameters": {
    "id": "用户 id，可在对应用户主页 URL 中找到",
    "type": "类型，见下表，默认为`0`，即动态"
  },
  "path": "/user/:id/:type?"
}
```
