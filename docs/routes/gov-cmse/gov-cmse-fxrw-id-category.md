# 中国载人航天工程 - 任务动态

## Coverage
`index-only`

## Route
- Namespace: `gov/cmse`
- Namespace Name: `中国载人航天工程`
- Route Path: `/gov/cmse/fxrw/:id/:category`
- Route Name: `任务动态`
- Example: `/gov/cmse/fxrw/wtfx/rwdt`
- URL: `www.cmse.gov.cn`
- Language: `_None_`
- Categories: `government`
- Maintainers: `nczitzk`
- Source Location: `fxrw-category.ts`
- Source Module: `_None_`

## Description
::: tip

下表分类可能并不完整。请查看各飞行任务详情页获得完整分类。

:::

| 任务动态 | 综合新闻 | 视频 | 图片新闻 | 媒体聚焦 |
| -------- | -------- | ---- | -------- | -------- |
| rwdt     | zhxw     | sp   | tpxw     | mtjj     |

## Parameters
- `id`: 任务 id，可在对应任务页 URL 中找到
- `category`: 分类 id，见下表，可在对应任务页 URL 中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.cmse.gov.cn/fxrw/:id/:category`

## Raw JSON
```json
{
  "categories": [
    "government"
  ],
  "description": "::: tip\n\n下表分类可能并不完整。请查看各飞行任务详情页获得完整分类。\n\n:::\n\n| 任务动态 | 综合新闻 | 视频 | 图片新闻 | 媒体聚焦 |\n| -------- | -------- | ---- | -------- | -------- |\n| rwdt     | zhxw     | sp   | tpxw     | mtjj     |",
  "example": "/gov/cmse/fxrw/wtfx/rwdt",
  "heat": 0,
  "location": "fxrw-category.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "任务动态",
  "parameters": {
    "category": "分类 id，见下表，可在对应任务页 URL 中找到",
    "id": "任务 id，可在对应任务页 URL 中找到"
  },
  "path": "/fxrw/:id/:category",
  "radar": [
    {
      "source": [
        "www.cmse.gov.cn/fxrw/:id/:category"
      ]
    }
  ],
  "topFeeds": []
}
```
