# 52hrtt 华人头条 - 专题

## Coverage
`index-only`

## Route
- Namespace: `52hrtt`
- Namespace Name: `52hrtt 华人头条`
- Route Path: `/52hrtt/symposium/:id?/:classId?`
- Route Name: `专题`
- Example: `/52hrtt/symposium/F1626082387819`
- URL: `52hrtt.com`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `symposium.ts`
- Source Module: `_None_`

## Description
专题 id 和 子分类 id 皆可在浏览器地址栏中找到，下面是一个例子。

访问 “邱毅看平潭” 专题，会跳转到 `https://www.52hrtt.com/global/n/w/symposium/F1626082387819`。其中 `F1626082387819` 即为 **专题 id** 对应的地区代码。

::: tip
更多的专题可以点击 [这里](https://www.52hrtt.com/global/n/w/symposium)
:::

## Parameters
- `id`: 专题 id
- `classId`: 子分类 id


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
  - `52hrtt.com/global/n/w/symposium/:id`
- `target`: `/symposium/:id`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "专题 id 和 子分类 id 皆可在浏览器地址栏中找到，下面是一个例子。\n\n访问 “邱毅看平潭” 专题，会跳转到 `https://www.52hrtt.com/global/n/w/symposium/F1626082387819`。其中 `F1626082387819` 即为 **专题 id** 对应的地区代码。\n\n::: tip\n更多的专题可以点击 [这里](https://www.52hrtt.com/global/n/w/symposium)\n:::",
  "example": "/52hrtt/symposium/F1626082387819",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 0,
  "location": "symposium.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "专题",
  "parameters": {
    "classId": "子分类 id",
    "id": "专题 id"
  },
  "path": "/symposium/:id?/:classId?",
  "radar": [
    {
      "source": [
        "52hrtt.com/global/n/w/symposium/:id"
      ],
      "target": "/symposium/:id"
    }
  ],
  "topFeeds": []
}
```
