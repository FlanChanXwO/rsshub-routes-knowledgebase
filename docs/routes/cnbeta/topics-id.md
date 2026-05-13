# cnBeta.COM - 主题

## Coverage
`index-only`

## Route
- Namespace: `cnbeta`
- Namespace Name: `cnBeta.COM`
- Route Path: `/topics/:id`
- Route Name: `主题`
- Example: `/cnbeta/topics/453`
- URL: `cnbeta.com.tw`
- Language: `zh-TW`
- Categories: `new-media`
- Maintainers: `cczhong11, nczitzk`
- Source Location: `topics.ts`
- Source Module: `() => import('@/routes/cnbeta/topics.ts')`

## Description
::: tip
完整的主题列表参见 [主题列表](https://www.cnbeta.com.tw/topics.htm)
:::

## Parameters
- `id`: 主题 id，可在对应主题页的 URL 中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `cnbeta.com.tw/topics/:id`

## Raw JSON
```json
{
  "description": "::: tip\n完整的主题列表参见 [主题列表](https://www.cnbeta.com.tw/topics.htm)\n:::",
  "example": "/cnbeta/topics/453",
  "location": "topics.ts",
  "maintainers": [
    "cczhong11",
    "nczitzk"
  ],
  "module": "() => import('@/routes/cnbeta/topics.ts')",
  "name": "主题",
  "parameters": {
    "id": "主题 id，可在对应主题页的 URL 中找到"
  },
  "path": [
    "/topics/:id"
  ],
  "radar": [
    {
      "source": [
        "cnbeta.com.tw/topics/:id"
      ]
    }
  ],
  "url": "cnbeta.com.tw"
}
```
