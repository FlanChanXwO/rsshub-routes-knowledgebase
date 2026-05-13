# 南京航空航天大学 - 研究生院

## Coverage
`index-only`

## Route
- Namespace: `nuaa`
- Namespace Name: `南京航空航天大学`
- Route Path: `/yjsy/:type/:getDescription?`
- Route Name: `研究生院`
- Example: `/nuaa/yjsy/tzgg/getDescription`
- URL: `aao.nuaa.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `junfengP, Seiry, Xm798`
- Source Location: `yjsy/yjsy.ts`
- Source Module: `() => import('@/routes/nuaa/yjsy/yjsy.ts')`

## Description
| 通知公告 | 新闻动态 | 学术信息 | 师生风采 |
| -------- | -------- | -------- | -------- |
| tzgg     | xwdt     | xsxx     | ssfc     |

## Parameters
- `type`: 分类名，见下表
- `getDescription`: 是否获取全文


## Features
- `requireConfig`: false
- `requirePuppeteer`: true
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
    "university"
  ],
  "description": "| 通知公告 | 新闻动态 | 学术信息 | 师生风采 |\n| -------- | -------- | -------- | -------- |\n| tzgg     | xwdt     | xsxx     | ssfc     |",
  "example": "/nuaa/yjsy/tzgg/getDescription",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": true,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "yjsy/yjsy.ts",
  "maintainers": [
    "junfengP",
    "Seiry",
    "Xm798"
  ],
  "module": "() => import('@/routes/nuaa/yjsy/yjsy.ts')",
  "name": "研究生院",
  "parameters": {
    "getDescription": "是否获取全文",
    "type": "分类名，见下表"
  },
  "path": "/yjsy/:type/:getDescription?"
}
```
