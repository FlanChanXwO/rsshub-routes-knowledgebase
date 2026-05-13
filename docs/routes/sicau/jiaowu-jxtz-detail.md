# 四川农业大学 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `sicau`
- Namespace Name: `四川农业大学`
- Route Path: `/jiaowu/jxtz/:detail?`
- Route Name: `教务处`
- Example: `/sicau/jiaowu/jxtz/detail`
- URL: `jiaowu.sicau.edu.cn/`
- Language: `zh-CN`
- Categories: `university`
- Maintainers: `hualiong`
- Source Location: `jiaowu.ts`
- Source Module: `() => import('@/routes/sicau/jiaowu.ts')`

## Description
::: tip
抓取全文返回会导致更长的响应时间，可以尝试使用 `/sicau/jiaowu/jxtz` 路径，这将只返回标题，然后再在应用内抓取全文内容。
:::

## Parameters
- `detail`: 是否抓取全文，该值只要不为空就抓取全文返回，否则只返回标题


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
  - `jiaowu.sicau.edu.cn/web/web/web/index.asp`
- `target`: `/jiaowu/jxtz`

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "\n::: tip\n抓取全文返回会导致更长的响应时间，可以尝试使用 `/sicau/jiaowu/jxtz` 路径，这将只返回标题，然后再在应用内抓取全文内容。\n:::\n",
  "example": "/sicau/jiaowu/jxtz/detail",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "jiaowu.ts",
  "maintainers": [
    "hualiong"
  ],
  "module": "() => import('@/routes/sicau/jiaowu.ts')",
  "name": "教务处",
  "parameters": {
    "detail": "是否抓取全文，该值只要不为空就抓取全文返回，否则只返回标题"
  },
  "path": "/jiaowu/jxtz/:detail?",
  "radar": [
    {
      "source": [
        "jiaowu.sicau.edu.cn/web/web/web/index.asp"
      ],
      "target": "/jiaowu/jxtz"
    }
  ],
  "url": "jiaowu.sicau.edu.cn/"
}
```
