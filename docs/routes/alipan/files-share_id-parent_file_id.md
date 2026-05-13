# 阿里云盘 - 文件列表

## Coverage
`index-only`

## Route
- Namespace: `alipan`
- Namespace Name: `阿里云盘`
- Route Path: `/files/:share_id/:parent_file_id?`
- Route Name: `文件列表`
- Example: `/alipan/files/jjtKEgXJAtC/64a957744876479ab17941b29d1289c6ebdd71ef`
- URL: `www.alipan.com/s`
- Language: `zh-CN`
- Categories: `multimedia`
- Maintainers: `DIYgod`
- Source Location: `files.ts`
- Source Module: `() => import('@/routes/alipan/files.ts')`

## Description
_None_

## Parameters
- `share_id`: 分享 id，可以从分享页面 URL 中找到
- `parent_file_id`: 文件夹 id，可以从文件夹页面 URL 中找到


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.alipan.com/s/:share_id/folder/:parent_file_id`
  - `www.alipan.com/s/:share_id`

## Raw JSON
```json
{
  "example": "/alipan/files/jjtKEgXJAtC/64a957744876479ab17941b29d1289c6ebdd71ef",
  "location": "files.ts",
  "maintainers": [
    "DIYgod"
  ],
  "module": "() => import('@/routes/alipan/files.ts')",
  "name": "文件列表",
  "parameters": {
    "parent_file_id": "文件夹 id，可以从文件夹页面 URL 中找到",
    "share_id": "分享 id，可以从分享页面 URL 中找到"
  },
  "path": "/files/:share_id/:parent_file_id?",
  "radar": [
    {
      "source": [
        "www.alipan.com/s/:share_id/folder/:parent_file_id",
        "www.alipan.com/s/:share_id"
      ]
    }
  ],
  "url": "www.alipan.com/s"
}
```
