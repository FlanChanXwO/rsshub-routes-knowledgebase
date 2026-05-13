# 国家能源局 - 天津港保税区-公告

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/tianjin/tjftz-notice/:channelId`
- Route Name: `天津港保税区-公告`
- Example: `/gov/tianjin/tjftz-notice/6302`
- URL: `tjftz.gov.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `HaoyuLee`
- Source Location: `tianjin/tjftz.ts`
- Source Module: `() => import('@/routes/gov/tianjin/tjftz.ts')`

## Description
| 公告类别         | channelId |
| ------------ | -- |
| 首页>新闻>保税区要闻>区域聚焦     | 6302  |

## Parameters
- `channelId`: 公告分类id、详细信息点击源网站https://www.tjftz.gov.cn/请求中寻找


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `tjftz.gov.cn/channels/:channelId.html`
- `target`: `/tianjin/tjftz-notice/:channelId`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "\n| 公告类别         | channelId |\n| ------------ | -- |\n| 首页>新闻>保税区要闻>区域聚焦     | 6302  |\n    ",
  "example": "/gov/tianjin/tjftz-notice/6302",
  "location": "tianjin/tjftz.ts",
  "maintainers": [
    "HaoyuLee"
  ],
  "module": "() => import('@/routes/gov/tianjin/tjftz.ts')",
  "name": "天津港保税区-公告",
  "parameters": {
    "channelId": "公告分类id、详细信息点击源网站https://www.tjftz.gov.cn/请求中寻找"
  },
  "path": "/tianjin/tjftz-notice/:channelId",
  "radar": [
    {
      "source": [
        "tjftz.gov.cn/channels/:channelId.html"
      ],
      "target": "/tianjin/tjftz-notice/:channelId"
    }
  ],
  "url": "tjftz.gov.cn"
}
```
