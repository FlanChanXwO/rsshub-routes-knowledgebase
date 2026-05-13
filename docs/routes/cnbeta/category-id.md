# cnBeta.COM - 分类

## Coverage
`index-only`

## Route
- Namespace: `cnbeta`
- Namespace Name: `cnBeta.COM`
- Route Path: `/category/:id`
- Route Name: `分类`
- Example: `/cnbeta/category/movie`
- URL: `cnbeta.com.tw`
- Language: `zh-TW`
- Categories: `new-media`
- Maintainers: `nczitzk`
- Source Location: `category.ts`
- Source Module: `() => import('@/routes/cnbeta/category.ts')`

## Description
| 影视  | 音乐  | 游戏 | 动漫  | 趣闻  | 科学    | 软件 |
| ----- | ----- | ---- | ----- | ----- | ------- | ---- |
| movie | music | game | comic | funny | science | soft |

## Parameters
- `id`: 分类 id，可在对应分类页的 URL 中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `cnbeta.com.tw/category/:id`

## Raw JSON
```json
{
  "description": "| 影视  | 音乐  | 游戏 | 动漫  | 趣闻  | 科学    | 软件 |\n| ----- | ----- | ---- | ----- | ----- | ------- | ---- |\n| movie | music | game | comic | funny | science | soft |",
  "example": "/cnbeta/category/movie",
  "location": "category.ts",
  "maintainers": [
    "nczitzk"
  ],
  "module": "() => import('@/routes/cnbeta/category.ts')",
  "name": "分类",
  "parameters": {
    "id": "分类 id，可在对应分类页的 URL 中找到"
  },
  "path": [
    "/category/:id"
  ],
  "radar": [
    {
      "source": [
        "cnbeta.com.tw/category/:id"
      ]
    }
  ],
  "url": "cnbeta.com.tw"
}
```
