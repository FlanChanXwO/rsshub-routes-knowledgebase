# 中国科学院 - 成果转化

## Coverage
`index-only`

## Route
- Namespace: `cas`
- Namespace Name: `中国科学院`
- Route Path: `/cg/:caty?`
- Route Name: `成果转化`
- Example: `/cas/cg/cgzhld`
- URL: `www.cas.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `nczitzk`
- Source Location: `cg/index.ts`
- Source Module: `() => import('@/routes/cas/cg/index.ts')`

## Description
| 工作动态 | 科技成果转移转化亮点工作 |
| -------- | ------------------------ |
| zh       | cgzhld                   |

## Parameters
- `caty`: 分类，见下表，默认为工作动态


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
  - `www.cas.cn/cg/:caty?`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 工作动态 | 科技成果转移转化亮点工作 |\n| -------- | ------------------------ |\n| zh       | cgzhld                   |",
  "example": "/cas/cg/cgzhld",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "cg/index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/cas/cg/index.ts')",
  "name": "成果转化",
  "parameters": {
    "caty": "分类，见下表，默认为工作动态"
  },
  "path": "/cg/:caty?",
  "radar": [
    {
      "source": [
        "www.cas.cn/cg/:caty?"
      ]
    }
  ]
}
```
