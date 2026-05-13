# 上海社会科学院 - 研究生院

## Coverage
`index-only`

## Route
- Namespace: `sass`
- Namespace Name: `上海社会科学院`
- Route Path: `/gs/:type`
- Route Name: `研究生院`
- Example: `/sass/gs/1793`
- URL: `gs.sass.org.cn`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `yanbot-team`
- Source Location: `gs/index.ts`
- Source Module: `() => import('@/routes/sass/gs/index.ts')`

## Description
| 硕士统考招生 | 硕士推免招生 |
| ------------ | ------------ |
| 1793         | sstmzs       |

## Parameters
- `type`: 类别 ID，见下表，其他未列出的栏目参数可以从页面的 URL Path 中找到，例如：硕士统考招生的网址为 `https://gs.sass.org.cn/1793/list.htm`，则类别 ID 为`1793`


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
  - `gs.sass.org.cn/:type/list.htm`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "| 硕士统考招生 | 硕士推免招生 |\n| ------------ | ------------ |\n| 1793         | sstmzs       |",
  "example": "/sass/gs/1793",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "gs/index.ts",
  "maintainers": [
    "yanbot-team"
  ],
  "module": "() => import('@/routes/sass/gs/index.ts')",
  "name": "研究生院",
  "parameters": {
    "type": "类别 ID，见下表，其他未列出的栏目参数可以从页面的 URL Path 中找到，例如：硕士统考招生的网址为 `https://gs.sass.org.cn/1793/list.htm`，则类别 ID 为`1793`"
  },
  "path": "/gs/:type",
  "radar": [
    {
      "source": [
        "gs.sass.org.cn/:type/list.htm"
      ]
    }
  ]
}
```
