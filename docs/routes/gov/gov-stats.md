# 深圳市罗湖区人民政府 - 国家统计局 通用

## Coverage
`index-only`

## Route
- Namespace: `gov`
- Namespace Name: `深圳市罗湖区人民政府`
- Route Path: `/gov/stats/*`
- Route Name: `国家统计局 通用`
- Example: `/gov/stats/sj/zxfb`
- URL: `www.stats.gov.cn`
- Language: `_None_`
- Categories: `government, popular`
- Maintainers: `bigfei, nczitzk, reply2future`
- Source Location: `stats/index.tsx`
- Source Module: `_None_`

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
    "government",
    "popular"
  ],
  "description": "::: tip\n路径处填写对应页面 URL 中 `http://www.stats.gov.cn/` 后的字段。下面是一个例子。\n\n若订阅 [数据 > 数据解读](http://www.stats.gov.cn/sj/sjjd/)\n则将对应页面 URL `http://www.stats.gov.cn/sj/sjjd/` 中 `http://www.stats.gov.cn/` 后的字段 `sj/sjjd` 作为路径填入。\n此时路由为 [`/gov/stats/sj/sjjd`](https://rsshub.app/gov/stats/sj/sjjd)\n\n若订阅 [新闻 > 时政要闻 > 中央精神](http://www.stats.gov.cn/xw/szyw/zyjs/)\n则将对应页面 URL `http://www.stats.gov.cn/xw/szyw/zyjs/` 中 `http://www.stats.gov.cn/`\n后的字段 `xw/szyw/zyjs` 作为路径填入。此时路由为 [`/gov/stats/xw/szyw/zyjs`](https://rsshub.app/gov/stats/xw/szyw/zyjs)\n:::",
  "example": "/gov/stats/sj/zxfb",
  "heat": 1516,
  "location": "stats/index.tsx",
  "maintainers": [
    "bigfei",
    "nczitzk",
    "reply2future"
  ],
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
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "数据发布 - 国家统计局 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55877082660306949",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.stats.gov.cn/sj/zxfb/",
      "title": "数据发布 - 国家统计局",
      "type": "feed",
      "url": "rsshub://gov/stats/sj/zxfb"
    },
    {
      "description": "数据解读 - 国家统计局 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "55877082660306948",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.stats.gov.cn/sj/sjjd/",
      "title": "数据解读 - 国家统计局",
      "type": "feed",
      "url": "rsshub://gov/stats/sj/sjjd"
    }
  ],
  "url": "www.stats.gov.cn"
}
```
