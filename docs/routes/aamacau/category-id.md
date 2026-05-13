# 論盡媒體 AllAboutMacau Media - 话题

## Coverage
`index-only`

## Route
- Namespace: `aamacau`
- Namespace Name: `論盡媒體 AllAboutMacau Media`
- Route Path: `/:category?/:id?`
- Route Name: `话题`
- Example: `/aamacau`
- URL: `aamacau.com/`
- Language: `zh-HK`
- Categories: `new-media`
- Maintainers: `None`
- Source Location: `index.ts`
- Source Module: `() => import('@/routes/aamacau/index.ts')`

## Description
| 即時報道     | 每週專題    | 藝文爛鬼樓 | 論盡紙本 | 新聞事件 | 特別企劃 |
| ------------ | ----------- | ---------- | -------- | -------- | -------- |
| breakingnews | weeklytopic | culture    | press    | case     | special  |

::: tip
  除了直接订阅分类全部文章（如 [每週專題](https://aamacau.com/topics/weeklytopic) 的对应路由为 [/aamacau/weeklytopic](https://rsshub.app/aamacau/weeklytopic)），你也可以订阅特定的专题，如 [【9-12】2021 澳門立法會選舉](https://aamacau.com/topics/【9-12】2021澳門立法會選舉) 的对应路由为 [/【9-12】2021 澳門立法會選舉](https://rsshub.app/aamacau/【9-12】2021澳門立法會選舉)。

  分类中的专题也可以单独订阅，如 [新聞事件](https://aamacau.com/topics/case) 中的 [「武漢肺炎」新聞檔案](https://aamacau.com/topics/case/「武漢肺炎」新聞檔案) 对应路由为 [/case/「武漢肺炎」新聞檔案](https://rsshub.app/aamacau/case/「武漢肺炎」新聞檔案)。

  同理，其他分类同上例子也可以订阅特定的单独专题。
:::

## Parameters
- `category`: 分类，见下表，默认为即時報道
- `id`: id，可在对应页面 URL 中找到，默认为空


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
  - `aamacau.com/`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "description": "| 即時報道     | 每週專題    | 藝文爛鬼樓 | 論盡紙本 | 新聞事件 | 特別企劃 |\n| ------------ | ----------- | ---------- | -------- | -------- | -------- |\n| breakingnews | weeklytopic | culture    | press    | case     | special  |\n\n::: tip\n  除了直接订阅分类全部文章（如 [每週專題](https://aamacau.com/topics/weeklytopic) 的对应路由为 [/aamacau/weeklytopic](https://rsshub.app/aamacau/weeklytopic)），你也可以订阅特定的专题，如 [【9-12】2021 澳門立法會選舉](https://aamacau.com/topics/【9-12】2021澳門立法會選舉) 的对应路由为 [/【9-12】2021 澳門立法會選舉](https://rsshub.app/aamacau/【9-12】2021澳門立法會選舉)。\n\n  分类中的专题也可以单独订阅，如 [新聞事件](https://aamacau.com/topics/case) 中的 [「武漢肺炎」新聞檔案](https://aamacau.com/topics/case/「武漢肺炎」新聞檔案) 对应路由为 [/case/「武漢肺炎」新聞檔案](https://rsshub.app/aamacau/case/「武漢肺炎」新聞檔案)。\n\n  同理，其他分类同上例子也可以订阅特定的单独专题。\n:::",
  "example": "/aamacau",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "index.ts",
  "maintainers": [],
  "module": "() => import('@/routes/aamacau/index.ts')",
  "name": "话题",
  "parameters": {
    "category": "分类，见下表，默认为即時報道",
    "id": "id，可在对应页面 URL 中找到，默认为空"
  },
  "path": "/:category?/:id?",
  "radar": [
    {
      "source": [
        "aamacau.com/"
      ]
    }
  ],
  "url": "aamacau.com/"
}
```
