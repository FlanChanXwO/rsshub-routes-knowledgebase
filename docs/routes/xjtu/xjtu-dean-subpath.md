# 西安交通大学 - 教务处

## Coverage
`index-only`

## Route
- Namespace: `xjtu`
- Namespace Name: `西安交通大学`
- Route Path: `/xjtu/dean/:subpath{.+}`
- Route Name: `教务处`
- Example: `/xjtu/dean/jxxx/jxtz2`
- URL: `2yuan.xjtu.edu.cn`
- Language: `_None_`
- Categories: `university`
- Maintainers: `hoilc`
- Source Location: `dean.ts`
- Source Module: `_None_`

## Description
打开一个类似 <https://dean.xjtu.edu.cn/jxxx/jxtz2.htm> 的网址，在 `.cn` 后的内容就是 subpath，此例中是 `jxxx/jxtz2`

## Parameters
_None_


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "university"
  ],
  "description": "打开一个类似 <https://dean.xjtu.edu.cn/jxxx/jxtz2.htm> 的网址，在 `.cn` 后的内容就是 subpath，此例中是 `jxxx/jxtz2`",
  "example": "/xjtu/dean/jxxx/jxtz2",
  "heat": 8,
  "location": "dean.ts",
  "maintainers": [
    "hoilc"
  ],
  "name": "教务处",
  "path": "/dean/:subpath{.+}",
  "topFeeds": [
    {
      "description": "西安交大教务处 - 教学通知 - Powered by RSSHub",
      "errorAt": "2025-12-26T10:25:16.832Z",
      "errorMessage": "this route is empty, please check the original site or <a href=\"https://github.com/DIYgod/RSSHub/issues/new/choose\">create an issue</a>\n",
      "id": "41461870201364490",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "http://dean.xjtu.edu.cn/jxxx/jxtz2.htm",
      "title": "西安交大教务处 - 教学通知",
      "type": "feed",
      "url": "rsshub://xjtu/dean/jxxx/jxtz2"
    }
  ]
}
```
