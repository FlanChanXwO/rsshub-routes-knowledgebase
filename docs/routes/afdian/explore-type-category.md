# 爱发电 - 发现用户

## Coverage
`index-only`

## Route
- Namespace: `afdian`
- Namespace Name: `爱发电`
- Route Path: `/explore/:type/:category?`
- Route Name: `发现用户`
- Example: `/afdian/explore/hot/所有`
- URL: `afdian.net`
- Language: `zh-CN`
- Categories: `other`
- Maintainers: `sanmmm`
- Source Location: `explore.ts`
- Source Module: `() => import('@/routes/afdian/explore.ts')`

## Description
分类

| 推荐 | 最热 |
| ---- | ---- |
| rec  | hot  |

  目录类型

| 所有 | 绘画 | 视频 | 写作 | 游戏 | 音乐 | 播客 | 摄影 | 技术 | Vtuber | 舞蹈 | 体育 | 旅游 | 美食 | 时尚 | 数码 | 动画 | 其他 |
| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ------ | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |
| 所有 | 绘画 | 视频 | 写作 | 游戏 | 音乐 | 播客 | 摄影 | 技术 | Vtuber | 舞蹈 | 体育 | 旅游 | 美食 | 时尚 | 数码 | 动画 | 其他 |

## Parameters
- `type`: 分类
- `category`: 目录类型，默认为 `所有`


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "other"
  ],
  "description": "分类\n\n| 推荐 | 最热 |\n| ---- | ---- |\n| rec  | hot  |\n\n  目录类型\n\n| 所有 | 绘画 | 视频 | 写作 | 游戏 | 音乐 | 播客 | 摄影 | 技术 | Vtuber | 舞蹈 | 体育 | 旅游 | 美食 | 时尚 | 数码 | 动画 | 其他 |\n| ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ------ | ---- | ---- | ---- | ---- | ---- | ---- | ---- | ---- |\n| 所有 | 绘画 | 视频 | 写作 | 游戏 | 音乐 | 播客 | 摄影 | 技术 | Vtuber | 舞蹈 | 体育 | 旅游 | 美食 | 时尚 | 数码 | 动画 | 其他 |",
  "example": "/afdian/explore/hot/所有",
  "location": "explore.ts",
  "maintainers": [
    "sanmmm"
  ],
  "module": "() => import('@/routes/afdian/explore.ts')",
  "name": "发现用户",
  "parameters": {
    "category": "目录类型，默认为 `所有`",
    "type": "分类"
  },
  "path": "/explore/:type/:category?"
}
```
