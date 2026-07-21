# Hudson River Trading - Tech Blog

## Coverage
`index-only`

## Route
- Namespace: `hudsonrivertrading`
- Namespace Name: `Hudson River Trading`
- Route Path: `/hudsonrivertrading/blog/:section?`
- Route Name: `Tech Blog`
- Example: `/hudsonrivertrading/blog`
- URL: `hudsonrivertrading.com`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `johan456789`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
HRT (Hudson River Trading) Tech Blog

| Route | Section |
| ----- | ------- |
| /hudsonrivertrading/blog | All Posts |
| /hudsonrivertrading/blog/algo | Algorithm |
| /hudsonrivertrading/blog/engineers | Engineering |
| /hudsonrivertrading/blog/interns | Intern Spotlight |
| /hudsonrivertrading/blog/more | Hardware, Systems & More |

## Parameters
- `section`: {"description": "Optional section filter", "options": [{"label": "Algorithm", "value": "algo"}, {"label": "Engineering", "value": "engineers"}, {"label": "Intern Spotlight", "value": "interns"}, {"label": "Hardware, Systems & More", "value": "more"}]}


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
  - `www.hudsonrivertrading.com/hrtbeat/`

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "description": "HRT (Hudson River Trading) Tech Blog\n\n| Route | Section |\n| ----- | ------- |\n| /hudsonrivertrading/blog | All Posts |\n| /hudsonrivertrading/blog/algo | Algorithm |\n| /hudsonrivertrading/blog/engineers | Engineering |\n| /hudsonrivertrading/blog/interns | Intern Spotlight |\n| /hudsonrivertrading/blog/more | Hardware, Systems & More |",
  "example": "/hudsonrivertrading/blog",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "heat": 2,
  "location": "index.ts",
  "maintainers": [
    "johan456789"
  ],
  "name": "Tech Blog",
  "parameters": {
    "section": {
      "description": "Optional section filter",
      "options": [
        {
          "label": "Algorithm",
          "value": "algo"
        },
        {
          "label": "Engineering",
          "value": "engineers"
        },
        {
          "label": "Intern Spotlight",
          "value": "interns"
        },
        {
          "label": "Hardware, Systems & More",
          "value": "more"
        }
      ]
    }
  },
  "path": "/blog/:section?",
  "radar": [
    {
      "source": [
        "www.hudsonrivertrading.com/hrtbeat/"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Hudson River Trading - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "181667751333892096",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://www.hudsonrivertrading.com/hrtbeat/#",
      "title": "Hudson River Trading",
      "type": "feed",
      "url": "rsshub://hudsonrivertrading/blog"
    }
  ]
}
```
