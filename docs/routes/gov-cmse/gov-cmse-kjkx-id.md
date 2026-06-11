# 中国载人航天工程 - 空间科学

## Coverage
`index-only`

## Route
- Namespace: `gov/cmse`
- Namespace Name: `中国载人航天工程`
- Route Path: `/gov/cmse/kjkx/:id`
- Route Name: `空间科学`
- Example: `/gov/cmse/kjkx/kjkxyjyyy`
- URL: `www.cmse.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `kjkx.ts`
- Source Module: `_None_`

## Description
| 空间科学研究与应用 | 航天技术试验 | 航天医学实验 |
| ------------------ | ------------ | ------------ |
| kjkxyjyyy          | htjssy       | htyxsy       |

## Parameters
- `id`: 分类 id，见下表，可在对应分类页 URL 中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.cmse.gov.cn/kjkx/:id`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 空间科学研究与应用 | 航天技术试验 | 航天医学实验 |\n| ------------------ | ------------ | ------------ |\n| kjkxyjyyy          | htjssy       | htyxsy       |",
  "example": "/gov/cmse/kjkx/kjkxyjyyy",
  "heat": 0,
  "location": "kjkx.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "空间科学",
  "parameters": {
    "id": "分类 id，见下表，可在对应分类页 URL 中找到"
  },
  "path": "/kjkx/:id",
  "radar": [
    {
      "source": [
        "www.cmse.gov.cn/kjkx/:id"
      ]
    }
  ],
  "topFeeds": []
}
```
