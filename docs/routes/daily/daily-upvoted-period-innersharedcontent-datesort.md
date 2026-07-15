# Daily.dev - Most upvoted

## Coverage
`index-only`

## Route
- Namespace: `daily`
- Namespace Name: `Daily.dev`
- Route Path: `/daily/upvoted/:period?/:innerSharedContent?/:dateSort?`
- Route Name: `Most upvoted`
- Example: `/daily/upvoted/7`
- URL: `app.daily.dev/upvoted`
- Language: `_None_`
- Categories: `social-media`
- Maintainers: `Rjnishant530`
- Source Location: `upvoted.ts`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `innerSharedContent`: {"default": "false", "description": "Where to Fetch inner Shared Posts instead of original", "options": [{"label": "False", "value": "false"}, {"label": "True", "value": "true"}]}
- `dateSort`: {"default": "true", "description": "Sort posts by publication date instead of popularity", "options": [{"label": "False", "value": "false"}, {"label": "True", "value": "true"}]}
- `period`: {"default": "7", "description": "Period of Lookup", "options": [{"label": "Last Week", "value": "7"}, {"label": "Last Month", "value": "30"}, {"label": "Last Year", "value": "365"}]}


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `app.daily.dev/upvoted`

## Raw JSON
```json
{
  "categories": [
    "social-media"
  ],
  "example": "/daily/upvoted/7",
  "heat": 21,
  "location": "upvoted.ts",
  "maintainers": [
    "Rjnishant530"
  ],
  "name": "Most upvoted",
  "parameters": {
    "dateSort": {
      "default": "true",
      "description": "Sort posts by publication date instead of popularity",
      "options": [
        {
          "label": "False",
          "value": "false"
        },
        {
          "label": "True",
          "value": "true"
        }
      ]
    },
    "innerSharedContent": {
      "default": "false",
      "description": "Where to Fetch inner Shared Posts instead of original",
      "options": [
        {
          "label": "False",
          "value": "false"
        },
        {
          "label": "True",
          "value": "true"
        }
      ]
    },
    "period": {
      "default": "7",
      "description": "Period of Lookup",
      "options": [
        {
          "label": "Last Week",
          "value": "7"
        },
        {
          "label": "Last Month",
          "value": "30"
        },
        {
          "label": "Last Year",
          "value": "365"
        }
      ]
    }
  },
  "path": "/upvoted/:period?/:innerSharedContent?/:dateSort?",
  "radar": [
    {
      "source": [
        "app.daily.dev/upvoted"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Find the most upvoted developer posts on daily.dev. Explore top-rated content in coding, tutorials, and tech news from the largest developer network in the world. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "81424438471419904",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://app.daily.dev/posts/upvoted",
      "title": "Most upvoted posts for developers | daily.dev",
      "type": "feed",
      "url": "rsshub://daily/upvoted"
    },
    {
      "description": "Find the most upvoted developer posts on daily.dev. Explore top-rated content in coding, tutorials, and tech news from the largest developer network in the world. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "129176238537455616",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://app.daily.dev/posts/upvoted",
      "title": "Most upvoted posts for developers | daily.dev",
      "type": "feed",
      "url": "rsshub://daily/upvoted/7"
    }
  ],
  "url": "app.daily.dev/upvoted",
  "view": 0
}
```
