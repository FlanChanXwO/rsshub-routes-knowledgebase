# 国家能源局 - 国家统计局 通用

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `国家能源局`
- Route Path: `/stats/*`
- Route Name: `国家统计局 通用`
- Example: `/gov/stats/sj/zxfb`
- URL: `www.stats.gov.cn`
- Language: `zh-CN`
- Categories: `government`
- Maintainers: `bigfei, nczitzk, reply2future`
- Source Location: `stats/index.tsx`
- Source Module: `() => import('@/routes/gov/stats/index.tsx')`

## Description
::: tip
路径处填写对应页面 URL 中 `http://www.stats.gov.cn/` 后的字段。下面是一个例子。

若订阅 [数据 > 数据解读](http://www.stats.gov.cn/sj/sjjd/)
则将对应页面 URL `http://www.stats.gov.cn/sj/sjjd/` 中 `http://www.stats.gov.cn/` 后的字段 `sj/sjjd` 作为路径填入。
此时路由为 [`/gov/stats/sj/sjjd`](https://rsshub.app/gov/stats/sj/sjjd)

若订阅 [新闻 > 时政要闻 > 中央精神](http://www.stats.gov.cn/xw/szyw/zyjs/)
则将对应页面 URL `http://www.stats.gov.cn/xw/szyw/zyjs/` 中 `http://www.stats.gov.cn/`
后的字段 `xw/szyw/zyjs` 作为路径填入。此时路由为 [`/gov/stats/xw/szyw/zyjs`](https://rsshub.app/gov/stats/xw/szyw/zyjs)
:::

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `title`: `国家统计局 通用`
- `source`:
  - `www.stats.gov.cn/*path`
- `target`: `/gov/stats/*path`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "::: tip\n路径处填写对应页面 URL 中 `http://www.stats.gov.cn/` 后的字段。下面是一个例子。\n\n若订阅 [数据 > 数据解读](http://www.stats.gov.cn/sj/sjjd/)\n则将对应页面 URL `http://www.stats.gov.cn/sj/sjjd/` 中 `http://www.stats.gov.cn/` 后的字段 `sj/sjjd` 作为路径填入。\n此时路由为 [`/gov/stats/sj/sjjd`](https://rsshub.app/gov/stats/sj/sjjd)\n\n若订阅 [新闻 > 时政要闻 > 中央精神](http://www.stats.gov.cn/xw/szyw/zyjs/)\n则将对应页面 URL `http://www.stats.gov.cn/xw/szyw/zyjs/` 中 `http://www.stats.gov.cn/`\n后的字段 `xw/szyw/zyjs` 作为路径填入。此时路由为 [`/gov/stats/xw/szyw/zyjs`](https://rsshub.app/gov/stats/xw/szyw/zyjs)\n:::",
  "example": "/gov/stats/sj/zxfb",
  "location": "stats/index.tsx",
  "maintainers": [
    "bigfei",
    "nczitzk",
    "reply2future"
  ],
  "module": "() => import('@/routes/gov/stats/index.tsx')",
  "name": "国家统计局 通用",
  "path": "/stats/*",
  "radar": [
    {
      "source": [
        "www.stats.gov.cn/*path"
      ],
      "target": "/gov/stats/*path",
      "title": "国家统计局 通用"
    }
  ],
  "url": "www.stats.gov.cn"
}
```
