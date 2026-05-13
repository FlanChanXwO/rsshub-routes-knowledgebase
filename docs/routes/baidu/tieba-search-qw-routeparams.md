# 百度 - 贴吧搜索

## Coverage
`index-only`

## Route
- Namespace: `baidu`
- Namespace Name: `百度`
- Route Path: `/tieba/search/:qw/:routeParams?`
- Route Name: `贴吧搜索`
- Example: `/baidu/tieba/search/neuro`
- URL: `www.baidu.com`
- Language: `zh-CN`
- Categories: `bbs`
- Maintainers: `JimenezLi`
- Source Location: `tieba/search.tsx`
- Source Module: `() => import('@/routes/baidu/tieba/search.tsx')`

## Description
| 键           | 含义                                                       | 接受的值      | 默认值 |
| ------------ | ---------------------------------------------------------- | ------------- | ------ |
| kw           | 在名为 kw 的贴吧中搜索                                     | 任意名称 / 无 | 无     |
| only_thread  | 只看主题帖，默认为 0 关闭                                  | 0/1           | 0      |
| rn           | 返回条目的数量                                             | 1-20          | 20     |
| sm           | 排序方式，0 为按时间顺序，1 为按时间倒序，2 为按相关性顺序 | 0/1/2         | 1      |

  用例：`/baidu/tieba/search/neuro/kw=neurosama&only_thread=1&sm=2`

## Parameters
- `qw`: 搜索关键词
- `routeParams`: 额外参数；请参阅以下说明和表格


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
    "bbs"
  ],
  "description": "| 键           | 含义                                                       | 接受的值      | 默认值 |\n| ------------ | ---------------------------------------------------------- | ------------- | ------ |\n| kw           | 在名为 kw 的贴吧中搜索                                     | 任意名称 / 无 | 无     |\n| only_thread  | 只看主题帖，默认为 0 关闭                                  | 0/1           | 0      |\n| rn           | 返回条目的数量                                             | 1-20          | 20     |\n| sm           | 排序方式，0 为按时间顺序，1 为按时间倒序，2 为按相关性顺序 | 0/1/2         | 1      |\n\n  用例：`/baidu/tieba/search/neuro/kw=neurosama&only_thread=1&sm=2`",
  "example": "/baidu/tieba/search/neuro",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "tieba/search.tsx",
  "maintainers": [
    "JimenezLi"
  ],
  "module": "() => import('@/routes/baidu/tieba/search.tsx')",
  "name": "贴吧搜索",
  "parameters": {
    "qw": "搜索关键词",
    "routeParams": "额外参数；请参阅以下说明和表格"
  },
  "path": "/tieba/search/:qw/:routeParams?"
}
```
