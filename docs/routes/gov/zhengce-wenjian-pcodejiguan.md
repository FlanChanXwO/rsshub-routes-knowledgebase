# 国家能源局 - 最新文件

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/zhengce/wenjian/:pcodeJiguan?`
- Route Name: `最新文件`
- Example: `/gov/zhengce/wenjian`
- URL: `www.gov.cn/`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `ciaranchen`
- Source Location: `zhengce/wenjian.ts`
- Source Module: `() => import('@/routes/gov/zhengce/wenjian.ts')`

## Description
_None_

## Parameters
- `pcodeJiguan`: 文种分类。国令、国发、国函、国发明电、国办发、国办函、国办发明电、其他


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
  - `www.gov.cn/`
- `target`: `/zhengce/wenjian`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "example": "/gov/zhengce/wenjian",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "zhengce/wenjian.ts",
  "maintainers": [
    "ciaranchen"
  ],
  "module": "() => import('@/routes/gov/zhengce/wenjian.ts')",
  "name": "最新文件",
  "parameters": {
    "pcodeJiguan": "文种分类。国令、国发、国函、国发明电、国办发、国办函、国办发明电、其他"
  },
  "path": "/zhengce/wenjian/:pcodeJiguan?",
  "radar": [
    {
      "source": [
        "www.gov.cn/"
      ],
      "target": "/zhengce/wenjian"
    }
  ],
  "url": "www.gov.cn/"
}
```
