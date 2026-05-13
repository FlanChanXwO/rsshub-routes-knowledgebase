# The Nikkei 日本経済新聞 - 中文版新闻

## Coverage
`index-only`

## Route
- Namespace: `nikkei`
- Namespace Name: `The Nikkei 日本経済新聞`
- Route Path: `/cn/*`
- Route Name: `中文版新闻`
- Example: `/nikkei/cn`
- URL: `nikkei.com`
- Language: `ja`
- Categories: `None`
- Maintainers: `nczitzk`
- Source Location: `cn/index.ts`
- Source Module: `() => import('@/routes/nikkei/cn/index.ts')`

## Description
::: tip
  如 [中国 经济 日经中文网](https://cn.nikkei.com/china/ceconomy.html) 的 URL 为 `https://cn.nikkei.com/china/ceconomy.html` 对应路由为 [`/nikkei/cn/cn/china/ceconomy`](https://rsshub.app/nikkei/cn/cn/china/ceconomy)

  如 [中國 經濟 日經中文網](https://zh.cn.nikkei.com/china/ceconomy.html) 的 URL 为 `https://zh.cn.nikkei.com/china/ceconomy.html` 对应路由为 [`/nikkei/cn/zh/china/ceconomy`](https://rsshub.app/nikkei/cn/zh/china/ceconomy)

  特别地，当 `path` 填入 `rss` 后（如路由为 [`/nikkei/cn/cn/rss`](https://rsshub.app/nikkei/cn/cn/rss)），此时返回的是 [官方 RSS 的内容](https://cn.nikkei.com/rss.html)
:::

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `title`: `中文版新闻`
- `source`:
  - `cn.nikkei.com/:category/:type`
  - `cn.nikkei.com/:category`
  - `cn.nikkei.com/`
### Rule 2
- `title`: `中文版新聞`
- `source`:
  - `zh.cn.nikkei.com/:category/:type`
  - `zh.cn.nikkei.com/:category`
  - `zh.cn.nikkei.com/`

## Raw JSON
```json
{
  "description": "::: tip\n  如 [中国 经济 日经中文网](https://cn.nikkei.com/china/ceconomy.html) 的 URL 为 `https://cn.nikkei.com/china/ceconomy.html` 对应路由为 [`/nikkei/cn/cn/china/ceconomy`](https://rsshub.app/nikkei/cn/cn/china/ceconomy)\n\n  如 [中國 經濟 日經中文網](https://zh.cn.nikkei.com/china/ceconomy.html) 的 URL 为 `https://zh.cn.nikkei.com/china/ceconomy.html` 对应路由为 [`/nikkei/cn/zh/china/ceconomy`](https://rsshub.app/nikkei/cn/zh/china/ceconomy)\n\n  特别地，当 `path` 填入 `rss` 后（如路由为 [`/nikkei/cn/cn/rss`](https://rsshub.app/nikkei/cn/cn/rss)），此时返回的是 [官方 RSS 的内容](https://cn.nikkei.com/rss.html)\n:::",
  "example": "/nikkei/cn",
  "location": "cn/index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/nikkei/cn/index.ts')",
  "name": "中文版新闻",
  "path": "/cn/*",
  "radar": [
    {
      "source": [
        "cn.nikkei.com/:category/:type",
        "cn.nikkei.com/:category",
        "cn.nikkei.com/"
      ],
      "title": "中文版新闻"
    },
    {
      "source": [
        "zh.cn.nikkei.com/:category/:type",
        "zh.cn.nikkei.com/:category",
        "zh.cn.nikkei.com/"
      ],
      "title": "中文版新聞"
    }
  ]
}
```
