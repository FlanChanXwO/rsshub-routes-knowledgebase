# 国家能源局 - 新闻动态

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/ndrc/xwdt/:category{.+}?`
- Route Name: `新闻动态`
- Example: `/gov/ndrc/xwdt`
- URL: `www.nea.gov.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `ndrc/xwdt.ts`
- Source Module: `() => import('@/routes/gov/ndrc/xwdt.ts')`

## Description
| 新闻发布 | 通知通告 | 委领导动态 | 司局动态 | 地方动态 |
| -------- | -------- | ---------- | -------- | -------- |
| xwfb     | tzgg     | wlddt      | sjdt     | dfdt     |

## Parameters
- `category`: 分类，见下表，默认为新闻发布


## Features
_None_

## Radar
### Rule 1
- `title`: `中华人民共和国国家发展和改革委员会 - 新闻动态`
- `source`:
  - `ndrc.gov.cn/xwdt/:category*`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 新闻发布 | 通知通告 | 委领导动态 | 司局动态 | 地方动态 |\n| -------- | -------- | ---------- | -------- | -------- |\n| xwfb     | tzgg     | wlddt      | sjdt     | dfdt     |",
  "example": "/gov/ndrc/xwdt",
  "location": "ndrc/xwdt.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/gov/ndrc/xwdt.ts')",
  "name": "新闻动态",
  "parameters": {
    "category": "分类，见下表，默认为新闻发布"
  },
  "path": "/ndrc/xwdt/:category{.+}?",
  "radar": [
    {
      "source": [
        "ndrc.gov.cn/xwdt/:category*"
      ],
      "title": "中华人民共和国国家发展和改革委员会 - 新闻动态"
    }
  ]
}
```
