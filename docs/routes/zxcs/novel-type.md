# 知轩藏书 - 小说列表

## Coverage
`index-only`

## Route
- Namespace: `zxcs`
- Namespace Name: `知轩藏书`
- Route Path: `/novel/:type`
- Route Name: `小说列表`
- Example: `/zxcs/novel/jinqigengxin`
- URL: `zxcs.click`
- Language: `zh-CN`
- Categories: `reading`
- Maintainers: `liaochuan`
- Source Location: `novel.ts`
- Source Module: `() => import('@/routes/zxcs/novel.ts')`

## Description
支持小说类型：jinqigengxin-近期更新,dushi-都市,xianxia-仙侠,xuanhuan-玄幻,qihuan-奇幻,lishi-历史,youxi-游戏,wuxia-武侠,kehuan-科幻,tiyu-体育,lingyi-灵异,junshi-军事,erciyuan-轻小说

## Parameters
- `type`: 小说类型, 可在对应类型页 URL 中找到


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
  - `zxcs.click/:type`
- `target`: `/novel/:type`

## Raw JSON
```json
{
  "categories": [
    "reading"
  ],
  "description": "支持小说类型：jinqigengxin-近期更新,dushi-都市,xianxia-仙侠,xuanhuan-玄幻,qihuan-奇幻,lishi-历史,youxi-游戏,wuxia-武侠,kehuan-科幻,tiyu-体育,lingyi-灵异,junshi-军事,erciyuan-轻小说",
  "example": "/zxcs/novel/jinqigengxin",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "novel.ts",
  "maintainers": [
    "liaochuan"
  ],
  "module": "() => import('@/routes/zxcs/novel.ts')",
  "name": "小说列表",
  "parameters": {
    "type": "小说类型, 可在对应类型页 URL 中找到"
  },
  "path": "/novel/:type",
  "radar": [
    {
      "source": [
        "zxcs.click/:type"
      ],
      "target": "/novel/:type"
    }
  ],
  "url": "zxcs.click"
}
```
