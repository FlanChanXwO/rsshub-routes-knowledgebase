# 北京社科网 - 基金项目管理平台

## Coverage
`index-only`

## Route
- Namespace: `bjsk`
- Namespace Name: `北京社科网`
- Route Path: `/keti/:id?`
- Route Name: `基金项目管理平台`
- Example: `/bjsk/keti`
- URL: `keti.bjsk.org.cn/indexAction!to_index.action`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `keti.ts`
- Source Module: `() => import('@/routes/bjsk/keti.ts')`

## Description
| 通知公告                         | 资料下载                         |
| -------------------------------- | -------------------------------- |
| 402881027cbb8c6f017cbb8e17710002 | 2c908aee818e04f401818e08645c0002 |

## Parameters
- `id`: 分类 id，见下表，默认为通知公告


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
  - `keti.bjsk.org.cn/indexAction!to_index.action`
  - `keti.bjsk.org.cn/`
- `target`: `/keti/:id`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "| 通知公告                         | 资料下载                         |\n| -------------------------------- | -------------------------------- |\n| 402881027cbb8c6f017cbb8e17710002 | 2c908aee818e04f401818e08645c0002 |",
  "example": "/bjsk/keti",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "keti.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/bjsk/keti.ts')",
  "name": "基金项目管理平台",
  "parameters": {
    "id": "分类 id，见下表，默认为通知公告"
  },
  "path": "/keti/:id?",
  "radar": [
    {
      "source": [
        "keti.bjsk.org.cn/indexAction!to_index.action",
        "keti.bjsk.org.cn/"
      ],
      "target": "/keti/:id"
    }
  ],
  "url": "keti.bjsk.org.cn/indexAction!to_index.action"
}
```
