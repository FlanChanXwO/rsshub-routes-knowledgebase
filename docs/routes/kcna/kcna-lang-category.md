# Korean Central News Agency (KCNA) 朝鲜中央通讯社 - News

## Coverage
`index-only`

## Route
- Namespace: `kcna`
- Namespace Name: `Korean Central News Agency (KCNA) 朝鲜中央通讯社`
- Route Path: `/kcna/:lang/:category?`
- Route Name: `News`
- Example: `/kcna/en`
- URL: `www.kcna.kp`
- Language: `_None_`
- Categories: `traditional-media`
- Maintainers: `Rongronggg9`
- Source Location: `news.tsx`
- Source Module: `_None_`

## Description
| Language | 조선어 | English | 中国语 | Русский | Español | 日本語 |
| -------- | ------ | ------- | ------ | ------- | ------- | ------ |
| `:lang`  | `kp`   | `en`    | `cn`   | `ru`    | `es`    | `jp`   |

| Category                                                         | `:category`                        |
| ---------------------------------------------------------------- | ---------------------------------- |
| WPK General Secretary **Kim Jong Un**'s Revolutionary Activities | `54c0ca4ca013a92cc9cf95bd4004c61a` |
| Latest News (default)                                            | `1ee9bdb7186944f765208f34ecfb5407` |
| Top News                                                         | `5394b80bdae203fadef02522cfb578c0` |
| Home News                                                        | `b2b3bcc1b0a4406ab0c36e45d5db58db` |
| Documents                                                        | `a8754921399857ebdbb97a98a1e741f5` |
| World                                                            | `593143484cf15d48ce85c26139582395` |
| Society-Life                                                     | `93102e5a735d03979bc58a3a7aefb75a` |
| External                                                         | `0f98b4623a3ef82aeea78df45c423fd0` |
| News Commentary                                                  | `12c03a49f7dbe829bceea8ac77088c21` |

## Parameters
- `lang`: Language, refer to the table below
- `category`: Category, refer to the table below


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: true
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
### Rule 1
- `source`:
  - `www.kcna.kp/:lang`
  - `www.kcna.kp/:lang/category/articles/q/1ee9bdb7186944f765208f34ecfb5407.kcmsf`
  - `www.kcna.kp/:lang/category/articles.kcmsf`
- `target`: `/:lang`

## Raw JSON
```json
{
  "categories": [
    "traditional-media"
  ],
  "description": "| Language | 조선어 | English | 中国语 | Русский | Español | 日本語 |\n| -------- | ------ | ------- | ------ | ------- | ------- | ------ |\n| `:lang`  | `kp`   | `en`    | `cn`   | `ru`    | `es`    | `jp`   |\n\n| Category                                                         | `:category`                        |\n| ---------------------------------------------------------------- | ---------------------------------- |\n| WPK General Secretary **Kim Jong Un**'s Revolutionary Activities | `54c0ca4ca013a92cc9cf95bd4004c61a` |\n| Latest News (default)                                            | `1ee9bdb7186944f765208f34ecfb5407` |\n| Top News                                                         | `5394b80bdae203fadef02522cfb578c0` |\n| Home News                                                        | `b2b3bcc1b0a4406ab0c36e45d5db58db` |\n| Documents                                                        | `a8754921399857ebdbb97a98a1e741f5` |\n| World                                                            | `593143484cf15d48ce85c26139582395` |\n| Society-Life                                                     | `93102e5a735d03979bc58a3a7aefb75a` |\n| External                                                         | `0f98b4623a3ef82aeea78df45c423fd0` |\n| News Commentary                                                  | `12c03a49f7dbe829bceea8ac77088c21` |",
  "example": "/kcna/en",
  "features": {
    "antiCrawler": true,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 9,
  "location": "news.tsx",
  "maintainers": [
    "Rongronggg9"
  ],
  "name": "News",
  "parameters": {
    "category": "Category, refer to the table below",
    "lang": "Language, refer to the table below"
  },
  "path": "/:lang/:category?",
  "radar": [
    {
      "source": [
        "www.kcna.kp/:lang",
        "www.kcna.kp/:lang/category/articles/q/1ee9bdb7186944f765208f34ecfb5407.kcmsf",
        "www.kcna.kp/:lang/category/articles.kcmsf"
      ],
      "target": "/:lang"
    }
  ],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:105:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "朝鲜中央通讯 | 新闻 | 最新新闻 - Powered by RSSHub",
      "errorAt": "2026-07-01T13:42:05.311Z",
      "errorMessage": "[GET] \"http://www.kcna.kp/cn/category/articles/q/1ee9bdb7186944f765208f34ecfb5407.kcmsf\": 404 Not Found\n[GET] \"http://www.kcna.kp/cn/category/articles/q/1ee9bdb7186944f765208f34ecfb5407.kcmsf\": 404 Not Found\n[GET] \"http://www.kcna.kp/cn/category/articles/q/1ee9bdb7186944f765208f34ecfb5407.kcmsf\": 404 Not Found\n",
      "id": "213406943351213061",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.kcna.kp/cn/category/articles/q/1ee9bdb7186944f765208f34ecfb5407.kcmsf",
      "title": "朝鲜中央通讯 | 新闻 | 最新新闻",
      "type": "feed",
      "url": "rsshub://kcna/cn"
    },
    {
      "description": "KCNA | Article | Latest News - Powered by RSSHub",
      "errorAt": "2026-05-27T10:15:40.792Z",
      "errorMessage": "Failed to fetch\n",
      "id": "185526378093555750",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://www.kcna.kp/en/category/articles/q/1ee9bdb7186944f765208f34ecfb5407.kcmsf",
      "title": "KCNA | Article | Latest News",
      "type": "feed",
      "url": "rsshub://kcna/en"
    }
  ]
}
```
