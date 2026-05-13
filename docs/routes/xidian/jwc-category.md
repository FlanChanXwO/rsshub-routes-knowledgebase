# 西安电子科技大学 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `xidian`
- Namespace Name: `西安电子科技大学`
- Route Path: `/jwc/:category?`
- Route Name: `教务处`
- Example: `/xidian/jwc/tzgg`
- URL: `jwc.xidian.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `ShadowySpirits`
- Source Location: `jwc.ts`
- Source Module: `() => import('@/routes/xidian/jwc.ts')`

## Description
| 教学信息 | 教学研究 | 实践教学 | 质量监控 | 通知公告 |
| :------: | :------: | :------: | :------: | :------: |
|   jxxx   |   jxyj   |   sjjx   |   zljk   |   tzgg   |

## Parameters
- `category`: 通知类别，默认为通知公告


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
    "university"
  ],
  "description": "| 教学信息 | 教学研究 | 实践教学 | 质量监控 | 通知公告 |\n| :------: | :------: | :------: | :------: | :------: |\n|   jxxx   |   jxyj   |   sjjx   |   zljk   |   tzgg   |",
  "example": "/xidian/jwc/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "jwc.ts",
  "maintainers": [
    "ShadowySpirits"
  ],
  "module": "() => import('@/routes/xidian/jwc.ts')",
  "name": "教务处",
  "parameters": {
    "category": "通知类别，默认为通知公告"
  },
  "path": "/jwc/:category?",
  "url": "jwc.xidian.edu.cn"
}
```
