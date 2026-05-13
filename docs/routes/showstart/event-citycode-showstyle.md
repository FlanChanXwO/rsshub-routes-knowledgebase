# 秀动网 - 按城市 - 演出更新

## Coverage
`index-only`

## Route
- Namespace: `showstart`
- Namespace Name: `秀动网`
- Route Path: `/event/:cityCode/:showStyle?`
- Route Name: `按城市 - 演出更新`
- Example: `/showstart/event/571/3`
- URL: `www.showstart.com`
- Language: `zh-CN`
- Categories: `shopping`
- Maintainers: `lchtao26`
- Source Location: `event.ts`
- Source Module: `() => import('@/routes/showstart/event.ts')`

## Description
::: tip
-   演出城市 `cityCode` 查询: `/showstart/search/city/:keyword`, 如: [https://rsshub.app/showstart/search/city/杭州](https://rsshub.app/showstart/search/city/杭州)

-   演出风格 `showStyle` 查询: `/showstart/search/style/:keyword`，如: [https://rsshub.app/showstart/search/style/摇滚](https://rsshub.app/showstart/search/style/摇滚)
:::

## Parameters
- `cityCode`: 演出城市 (编号)
- `showStyle`: 演出风格 (编号)


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
    "shopping"
  ],
  "description": "::: tip\n-   演出城市 `cityCode` 查询: `/showstart/search/city/:keyword`, 如: [https://rsshub.app/showstart/search/city/杭州](https://rsshub.app/showstart/search/city/杭州)\n\n-   演出风格 `showStyle` 查询: `/showstart/search/style/:keyword`，如: [https://rsshub.app/showstart/search/style/摇滚](https://rsshub.app/showstart/search/style/摇滚)\n:::",
  "example": "/showstart/event/571/3",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "event.ts",
  "maintainers": [
    "lchtao26"
  ],
  "module": "() => import('@/routes/showstart/event.ts')",
  "name": "按城市 - 演出更新",
  "parameters": {
    "cityCode": "演出城市 (编号)",
    "showStyle": "演出风格 (编号)"
  },
  "path": "/event/:cityCode/:showStyle?"
}
```
