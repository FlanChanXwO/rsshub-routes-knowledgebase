# 国家能源局 - 中华人民共和国国家发展和改革委员会价格监测中心

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/jgjcndrc/:columnId?/:subColumnId?`
- Route Name: `中华人民共和国国家发展和改革委员会价格监测中心`
- Example: `/gov/jgjcndrc/1832739866673426433`
- URL: `www.jgjcndrc.org.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `jgjcndrc/index.ts`
- Source Module: `() => import('@/routes/gov/jgjcndrc/index.ts')`

## Description
::: tip
  若订阅 [通知公告](https://www.jgjcndrc.org.cn/list?clmId=1832739866673426433)，网址为 `https://www.jgjcndrc.org.cn/list?clmId=1832739866673426433`。截取 `clmId` 的参数部分 `1832739866673426433` 作为参数填入，此时路由为 [`/gov/jgjcndrc/1832739866673426433`](https://rsshub.app/gov/jgjcndrc/1832739866673426433)。

  若订阅 [国内外市场价格监测情况周报](https://www.jgjcndrc.org.cn/list?clmId=1832298113994649601&sclmId=1832751799531220993)，网址为 `https://www.jgjcndrc.org.cn/list?clmId=1832298113994649601&sclmId=1832751799531220993`。截取 `clmId` 和 `sclmId` 的参数部分 `1832298113994649601` 和 `1832751799531220993` 作为参数填入，此时路由为 [`/gov/jgjcndrc/1832298113994649601/1832751799531220993`](https://rsshub.app/gov/jgjcndrc/1832298113994649601/1832751799531220993)。
:::

## Parameters
- `columnId`: 栏目 id，默认为 `1832739866673426433`，即通知公告，可在对应栏目页 URL 中找到
- `subColumnId`: 子栏目 id，默认为空，可在对应子栏目页 URL 中找到


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.jgjcndrc.org.cn/list`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "::: tip\n  若订阅 [通知公告](https://www.jgjcndrc.org.cn/list?clmId=1832739866673426433)，网址为 `https://www.jgjcndrc.org.cn/list?clmId=1832739866673426433`。截取 `clmId` 的参数部分 `1832739866673426433` 作为参数填入，此时路由为 [`/gov/jgjcndrc/1832739866673426433`](https://rsshub.app/gov/jgjcndrc/1832739866673426433)。\n\n  若订阅 [国内外市场价格监测情况周报](https://www.jgjcndrc.org.cn/list?clmId=1832298113994649601&sclmId=1832751799531220993)，网址为 `https://www.jgjcndrc.org.cn/list?clmId=1832298113994649601&sclmId=1832751799531220993`。截取 `clmId` 和 `sclmId` 的参数部分 `1832298113994649601` 和 `1832751799531220993` 作为参数填入，此时路由为 [`/gov/jgjcndrc/1832298113994649601/1832751799531220993`](https://rsshub.app/gov/jgjcndrc/1832298113994649601/1832751799531220993)。\n:::",
  "example": "/gov/jgjcndrc/1832739866673426433",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "location": "jgjcndrc/index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/gov/jgjcndrc/index.ts')",
  "name": "中华人民共和国国家发展和改革委员会价格监测中心",
  "parameters": {
    "columnId": "栏目 id，默认为 `1832739866673426433`，即通知公告，可在对应栏目页 URL 中找到",
    "subColumnId": "子栏目 id，默认为空，可在对应子栏目页 URL 中找到"
  },
  "path": "/jgjcndrc/:columnId?/:subColumnId?",
  "radar": [
    {
      "source": [
        "www.jgjcndrc.org.cn/list"
      ]
    }
  ],
  "url": "www.jgjcndrc.org.cn"
}
```
