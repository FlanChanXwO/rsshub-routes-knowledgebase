# 中国载人航天工程 - 科普教育

## Coverage
`index-only`

## Route
- Namespace: `gov/cmse`
- Namespace Name: `中国载人航天工程`
- Route Path: `/gov/cmse/kpjy/:id`
- Route Name: `科普教育`
- Example: `/gov/cmse/kpjy/kphd`
- URL: `www.cmse.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `kpjy.ts`
- Source Module: `_None_`

## Description
| 科普活动 | 太空课堂 | 航天知识 |
| -------- | -------- | -------- |
| kphd     | tkkt     | ttzs     |

## Parameters
- `id`: 分类 id，见下表，可在对应分类页 URL 中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.cmse.gov.cn/kpjy/:id`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 科普活动 | 太空课堂 | 航天知识 |\n| -------- | -------- | -------- |\n| kphd     | tkkt     | ttzs     |",
  "example": "/gov/cmse/kpjy/kphd",
  "heat": 0,
  "location": "kpjy.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "科普教育",
  "parameters": {
    "id": "分类 id，见下表，可在对应分类页 URL 中找到"
  },
  "path": "/kpjy/:id",
  "radar": [
    {
      "source": [
        "www.cmse.gov.cn/kpjy/:id"
      ]
    }
  ],
  "test": {
    "code": 1
  },
  "topFeeds": []
}
```
