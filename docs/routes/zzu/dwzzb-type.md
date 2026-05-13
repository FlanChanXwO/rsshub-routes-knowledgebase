# 郑州大学 - 郑大党委组织部

## Coverage
`index-only`

## Route
- Namespace: `zzu`
- Namespace Name: `郑州大学`
- Route Path: `/dwzzb/:type`
- Route Name: `郑大党委组织部`
- Example: `/zzu/dwzzb/djgz`
- URL: `www.zzu.edu.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `amandus1990`
- Source Location: `dwzzb.ts`
- Source Module: `() => import('@/routes/zzu/dwzzb.ts')`

## Description
| 党建工作 | 干部工作 | 人才工作 | 乡村振兴工作 |
| -------- | -------- | -------- | -------- |
| djgz     | gbgz     | rcgz     | fpgz     |

## Parameters
- `type`: 分类名


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
  - `dwzzb.v.zzu.edu.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 党建工作 | 干部工作 | 人才工作 | 乡村振兴工作 |\n| -------- | -------- | -------- | -------- |\n| djgz     | gbgz     | rcgz     | fpgz     |",
  "example": "/zzu/dwzzb/djgz",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "dwzzb.ts",
  "maintainers": [
    "amandus1990"
  ],
  "module": "() => import('@/routes/zzu/dwzzb.ts')",
  "name": "郑大党委组织部",
  "parameters": {
    "type": "分类名"
  },
  "path": "/dwzzb/:type",
  "radar": [
    {
      "source": [
        "dwzzb.v.zzu.edu.cn/"
      ]
    }
  ]
}
```
