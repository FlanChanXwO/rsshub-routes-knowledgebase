# 豆瓣 - 豆瓣小组

## Coverage
`index-only`

## Route
- Namespace: `douban`
- Namespace Name: `豆瓣`
- Route Path: `/group/:groupid/:type?`
- Route Name: `豆瓣小组`
- Example: `/douban/group/648102`
- URL: `www.douban.com`
- Language: `zh-CN`
- Categories: `social-media`
- Maintainers: `DIYgod`
- Source Location: `other/group.ts`
- Source Module: `() => import('@/routes/douban/other/group.ts')`

## Description
_None_

## Parameters
- `groupid`: 豆瓣小组的 id
- `type`: {"default": "latest", "description": "类型", "options": [{"label": "最新", "value": "latest"}, {"label": "最热", "value": "essence"}, {"label": "精华", "value": "elite"}]}


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
  - `www.douban.com/group/:groupid`
- `target`: `/group/:groupid`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/douban/group/648102",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "other/group.ts",
  "maintainers": [
    "DIYgod"
  ],
  "module": "() => import('@/routes/douban/other/group.ts')",
  "name": "豆瓣小组",
  "parameters": {
    "groupid": "豆瓣小组的 id",
    "type": {
      "default": "latest",
      "description": "类型",
      "options": [
        {
          "label": "最新",
          "value": "latest"
        },
        {
          "label": "最热",
          "value": "essence"
        },
        {
          "label": "精华",
          "value": "elite"
        }
      ]
    }
  },
  "path": "/group/:groupid/:type?",
  "radar": [
    {
      "source": [
        "www.douban.com/group/:groupid"
      ],
      "target": "/group/:groupid"
    }
  ],
  "view": 1
}
```
