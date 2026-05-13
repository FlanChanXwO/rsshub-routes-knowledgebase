# Chinese Academy of Geological Sciences - 研究生院

## Coverage
`index-only`

## Route
- Namespace: `cags`
- Namespace Name: `Chinese Academy of Geological Sciences`
- Route Path: `/edu/:category`
- Route Name: `研究生院`
- Example: `/cags/edu/tzgg`
- URL: `cags.cgs.gov.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `Chikit-L`
- Source Location: `edu/index.ts`
- Source Module: `() => import('@/routes/cags/edu/index.ts')`

## Description
| 通知公告 | 要闻简讯 | 博士生招生 | 硕士生招生 | 大学生夏令营 |
| -------- | -------- | ---------- | ---------- | ------------ |
| tzgg     | ywjx     | zs_bss     | zs_sss     | zs_dxsxly    |

## Parameters
- `category`: 通知频道，可选 tzgg/ywjx/zs_bss/zs_sss/zs_dxsxly


## Features
- `antiCrawler`: false
- `requireConfig`: false
- `requirePuppeteer`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `edu.cags.ac.cn/`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "\n| 通知公告 | 要闻简讯 | 博士生招生 | 硕士生招生 | 大学生夏令营 |\n| -------- | -------- | ---------- | ---------- | ------------ |\n| tzgg     | ywjx     | zs_bss     | zs_sss     | zs_dxsxly    |\n",
  "example": "/cags/edu/tzgg",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "edu/index.ts",
  "maintainers": [
    "Chikit-L"
  ],
  "module": "() => import('@/routes/cags/edu/index.ts')",
  "name": "研究生院",
  "parameters": {
    "category": "通知频道，可选 tzgg/ywjx/zs_bss/zs_sss/zs_dxsxly"
  },
  "path": "/edu/:category",
  "radar": [
    {
      "source": [
        "edu.cags.ac.cn/"
      ]
    }
  ]
}
```
