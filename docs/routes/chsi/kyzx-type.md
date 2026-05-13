# 中国研究生招生信息网 - 考研资讯

## Coverage
`index-only`

## Route
- Namespace: `chsi`
- Namespace Name: `中国研究生招生信息网`
- Route Path: `/kyzx/:type`
- Route Name: `考研资讯`
- Example: `/chsi/kyzx/fstj`
- URL: `yz.chsi.com.cn`
- Language: `zh-CN`
- Categories: `study`
- Maintainers: `yanbot-team`
- Source Location: `kyzx.ts`
- Source Module: `() => import('@/routes/chsi/kyzx.ts')`

## Description
| `:type` | 专题名称 |
| ------- | -------- |
| fstj    | 复试调剂 |
| kydt    | 考研动态 |
| zcdh    | 政策导航 |
| kyrw    | 考研人物 |
| jyxd    | 经验心得 |

## Parameters
- `type`: type 见下表，亦可在网站 URL 找到


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
  - `yz.chsi.com.cn/kyzx/:type`

## Raw JSON
```json
{
  "categories": [
    "study"
  ],
  "description": "| `:type` | 专题名称 |\n| ------- | -------- |\n| fstj    | 复试调剂 |\n| kydt    | 考研动态 |\n| zcdh    | 政策导航 |\n| kyrw    | 考研人物 |\n| jyxd    | 经验心得 |",
  "example": "/chsi/kyzx/fstj",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "kyzx.ts",
  "maintainers": [
    "yanbot-team"
  ],
  "module": "() => import('@/routes/chsi/kyzx.ts')",
  "name": "考研资讯",
  "parameters": {
    "type": " type 见下表，亦可在网站 URL 找到"
  },
  "path": "/kyzx/:type",
  "radar": [
    {
      "source": [
        "yz.chsi.com.cn/kyzx/:type"
      ]
    }
  ]
}
```
