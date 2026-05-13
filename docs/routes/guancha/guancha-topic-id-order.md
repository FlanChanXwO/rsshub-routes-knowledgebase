# 观察者网 - Unknown

## Coverage
`index-only`

## Route
- Namespace: `guancha`
- Namespace Name: `观察者网`
- Route Path: `/guancha/topic/:id/:order?`
- Route Name: `Unknown`
- Example: `_None_`
- URL: `guancha.cn/`
- Language: `_None_`
- Categories: `new-media`
- Maintainers: `occupy5, nczitzk`
- Source Location: `topic.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `guancha.cn/`
- `target`: `/:category?`

## Raw JSON
```json
{
  "categories": [
    "new-media"
  ],
  "heat": 3,
  "location": "topic.ts",
  "maintainers": [
    "occupy5",
    "nczitzk"
  ],
  "name": "Unknown",
  "path": "/topic/:id/:order?",
  "radar": [
    {
      "source": [
        "guancha.cn/"
      ],
      "target": "/:category?"
    }
  ],
  "topFeeds": [
    {
      "description": "观察者网 - 国际 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "113028454025389056",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://user.guancha.cn/topic/post-list?topic_id=110&page=1&order=1",
      "title": "观察者网 - 国际",
      "type": "feed",
      "url": "rsshub://guancha/topic/110/1"
    },
    {
      "description": "观察者网 - 风闻 - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "150456296214658048",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://user.guancha.cn/main/index-list.json?&page=1&order=6",
      "title": "观察者网 - 风闻",
      "type": "feed",
      "url": "rsshub://guancha/topic/0/6"
    }
  ],
  "url": "guancha.cn/"
}
```
