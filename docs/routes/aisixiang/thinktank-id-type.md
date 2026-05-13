# 爱思想 - 思想库（专栏）

## Coverage
`index-only`

## Route
- Namespace: `aisixiang`
- Namespace Name: `爱思想`
- Route Path: `/thinktank/:id/:type?`
- Route Name: `思想库（专栏）`
- Example: `/aisixiang/thinktank/WuQine/论文`
- URL: `aisixiang.com`
- Language: `zh-CN`
- Categories: `reading`
- Maintainers: `hoilc, nczitzk`
- Source Location: `thinktank.ts`
- Source Module: `() => import('@/routes/aisixiang/thinktank.ts')`

## Description
| 论文 | 时评 | 随笔 | 演讲 | 访谈 | 著作 | 读书 | 史论 | 译作 | 诗歌 | 书信 | 科学 |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |

## Parameters
- `id`: 专栏 ID，一般为作者拼音，可在URL中找到
- `type`: 栏目类型，参考下表，默认为全部


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "description": "| 论文 | 时评 | 随笔 | 演讲 | 访谈 | 著作 | 读书 | 史论 | 译作 | 诗歌 | 书信 | 科学 |\n| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |",
  "example": "/aisixiang/thinktank/WuQine/论文",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "thinktank.ts",
  "maintainers": [
    "hoilc",
    "nczitzk"
  ],
  "module": "() => import('@/routes/aisixiang/thinktank.ts')",
  "name": "思想库（专栏）",
  "parameters": {
    "id": "专栏 ID，一般为作者拼音，可在URL中找到",
    "type": "栏目类型，参考下表，默认为全部"
  },
  "path": "/thinktank/:id/:type?"
}
```
