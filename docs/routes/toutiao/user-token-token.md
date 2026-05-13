# 今日头条 - 头条主页

## Coverage
`index-only`

## Route
- Namespace: `toutiao`
- Namespace Name: `今日头条`
- Route Path: `/user/token/:token`
- Route Name: `头条主页`
- Example: `/toutiao/user/token/MS4wLjABAAAAEmbqJP2CmC8XXv1BpMvQ3sQHKAxFsq8wHxj8XVIQWja6tMcB-QEbFkzkRNgMl12M`
- URL: `www.toutiao.com`
- Language: `zh-CN`
- Categories: `new-media`
- Maintainers: `TonyRL`
- Source Location: `user.tsx`
- Source Module: `() => import('@/routes/toutiao/user.tsx')`

## Description
_None_

## Parameters
- `token`: 用户 token，可在用户主页 URL 找到


## Features
- `antiCrawler`: true

## Radar
### Rule 1
- `source`:
  - `www.toutiao.com/c/user/token/:token`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "example": "/toutiao/user/token/MS4wLjABAAAAEmbqJP2CmC8XXv1BpMvQ3sQHKAxFsq8wHxj8XVIQWja6tMcB-QEbFkzkRNgMl12M",
  "features": {
    "antiCrawler": true
  },
  "location": "user.tsx",
  "maintainers": [
    "TonyRL"
  ],
  "module": "() => import('@/routes/toutiao/user.tsx')",
  "name": "头条主页",
  "parameters": {
    "token": "用户 token，可在用户主页 URL 找到"
  },
  "path": "/user/token/:token",
  "radar": [
    {
      "source": [
        "www.toutiao.com/c/user/token/:token"
      ]
    }
  ]
}
```
