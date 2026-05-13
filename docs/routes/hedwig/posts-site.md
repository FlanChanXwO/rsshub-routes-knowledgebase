# Hedwig - Posts

## Coverage
`index-only`

## Route
- Namespace: `hedwig`
- Namespace Name: `Hedwig`
- Route Path: `/posts/:site`
- Route Name: `Posts`
- Example: `/posts/walnut`
- URL: `hedwig.pub`
- Language: `zh-CN`
- Categories: `blog`
- Maintainers: `zwithz, GetToSet`
- Source Location: `posts.ts`
- Source Module: `() => import('@/routes/hedwig/posts.ts')`

## Description
_None_

## Parameters
- `site`: 站点名，原则上只要是 `{site}.hedwig.pub` 都可以匹配


## Features
- `supportRadar`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "example": "/posts/walnut",
  "features": {
    "supportRadar": false
  },
  "location": "posts.ts",
  "maintainers": [
    "zwithz",
    "GetToSet"
  ],
  "module": "() => import('@/routes/hedwig/posts.ts')",
  "name": "Posts",
  "parameters": {
    "site": "站点名，原则上只要是 `{site}.hedwig.pub` 都可以匹配"
  },
  "path": "/posts/:site",
  "url": "hedwig.pub",
  "view": 0
}
```
