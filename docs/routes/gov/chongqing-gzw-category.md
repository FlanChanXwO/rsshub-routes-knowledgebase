# 国家能源局 - 重庆市人民政府 国有资产监督管理委员会

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/chongqing/gzw/:category{.+}?`
- Route Name: `重庆市人民政府 国有资产监督管理委员会`
- Example: `_None_`
- URL: `gzw.cq.gov.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `chongqing/gzw.ts`
- Source Module: `() => import('@/routes/gov/chongqing/gzw.ts')`

## Description
| 通知公告  | 国企资讯 | 国企简介 | 国企招聘 |
| --------- | -------- | -------- | -------- |
| tzgg_191 | gqdj     | gqjj     | gqzp     |

## Parameters
- `category`: 分类，见下表，默认为通知公告


## Features
_None_

## Radar
### Rule 1
- `source`: `gzw.cq.gov.cn/*category`
- `target`: `/chongqing/gzw/*category`

## Raw JSON
```json
{
  "description": "| 通知公告  | 国企资讯 | 国企简介 | 国企招聘 |\n| --------- | -------- | -------- | -------- |\n| tzgg_191 | gqdj     | gqjj     | gqzp     |",
  "location": "chongqing/gzw.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/gov/chongqing/gzw.ts')",
  "name": "重庆市人民政府 国有资产监督管理委员会",
  "parameters": {
    "category": "分类，见下表，默认为通知公告"
  },
  "path": "/chongqing/gzw/:category{.+}?",
  "radar": [
    {
      "source": "gzw.cq.gov.cn/*category",
      "target": "/chongqing/gzw/*category"
    }
  ],
  "url": "gzw.cq.gov.cn"
}
```
