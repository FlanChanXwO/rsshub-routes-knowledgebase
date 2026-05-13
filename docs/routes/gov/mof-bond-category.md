# 国家能源局 - 专题

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/mof/bond/:category?`
- Route Name: `专题`
- Example: `/gov/mof/bond`
- URL: `www.nea.gov.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `la3rence`
- Source Location: `mof/bond.ts`
- Source Module: `() => import('@/routes/gov/mof/bond.ts')`

## Description
#### 政府债券管理

| 国债管理工作动态 | 记账式国债 (含特别国债) 发行 | 储蓄国债发行 | 地方政府债券管理      |
| ---------------- | ---------------------------- | ------------ | --------------------- |
| gzfxgzdt         | gzfxzjs                      | gzfxdzs      | difangzhengfuzhaiquan |

## Parameters
- `category`: 专题，见下表，默认为国债管理工作动态


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
    "government"
  ],
  "description": "#### 政府债券管理\n\n| 国债管理工作动态 | 记账式国债 (含特别国债) 发行 | 储蓄国债发行 | 地方政府债券管理      |\n| ---------------- | ---------------------------- | ------------ | --------------------- |\n| gzfxgzdt         | gzfxzjs                      | gzfxdzs      | difangzhengfuzhaiquan |",
  "example": "/gov/mof/bond",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "mof/bond.ts",
  "maintainers": [
    "la3rence"
  ],
  "module": "() => import('@/routes/gov/mof/bond.ts')",
  "name": "专题",
  "parameters": {
    "category": "专题，见下表，默认为国债管理工作动态"
  },
  "path": "/mof/bond/:category?"
}
```
