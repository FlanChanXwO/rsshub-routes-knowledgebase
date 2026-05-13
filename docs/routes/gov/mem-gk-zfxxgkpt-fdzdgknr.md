# 国家能源局 - 法定主动公开内容

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/mem/gk/zfxxgkpt/fdzdgknr`
- Route Name: `法定主动公开内容`
- Example: `/gov/mem/gk/zfxxgkpt/fdzdgknr`
- URL: `www.nea.gov.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `skeaven`
- Source Location: `mem/zfxxgkpt.ts`
- Source Module: `() => import('@/routes/gov/mem/zfxxgkpt.ts')`

## Description
应急管理部法定主动公开内容,包含通知、公告、督办、政策解读等，可供应急相关工作人员及时获取政策信息

## Parameters
_None_


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
  - `www.mem.gov.cn/gk/zfxxgkpt/fdzdgknr`
- `target`: `/mem/gk/zfxxgkpt/fdzdgknr`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "应急管理部法定主动公开内容,包含通知、公告、督办、政策解读等，可供应急相关工作人员及时获取政策信息",
  "example": "/gov/mem/gk/zfxxgkpt/fdzdgknr",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "mem/zfxxgkpt.ts",
  "maintainers": [
    "skeaven"
  ],
  "module": "() => import('@/routes/gov/mem/zfxxgkpt.ts')",
  "name": "法定主动公开内容",
  "parameters": {},
  "path": "/mem/gk/zfxxgkpt/fdzdgknr",
  "radar": [
    {
      "source": [
        "www.mem.gov.cn/gk/zfxxgkpt/fdzdgknr"
      ],
      "target": "/mem/gk/zfxxgkpt/fdzdgknr"
    }
  ]
}
```
