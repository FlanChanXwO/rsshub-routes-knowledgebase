# WordPress - WordPress

## Coverage
`index-only`

## Route
- Namespace: `wordpress`
- Namespace Name: `WordPress`
- Route Path: `/wordpress/:url?/:filter{.+}?`
- Route Name: `WordPress`
- Example: `/wordpress/https%3A%2F%2Fwordpress.org%2Fnews/category/Podcast`
- URL: `wordpress.org`
- Language: `_None_`
- Categories: `blog`
- Maintainers: `nczitzk`
- Source Location: `index.ts`
- Source Module: `_None_`

## Description
If you subscribe to [WordPress News](https://wordpress.org/news/)，where the URL is `https://wordpress.org/news/`, Encode the URL using `encodeURIComponent()` and then use it as the parameter. Therefore, the route will be [`/wordpress/https%3A%2F%2Fwordpress.org%2Fnews`](https://rsshub.app/wordpress/https%3A%2F%2Fwordpress.org%2Fnews).

::: tip
If you wish to subscribe to specific categories or tags, you can fill in the "filter" parameter in the route. `/category/Podcast` to subscribe to the Podcast category. In this case, the route would be [`/wordpress/https%3A%2F%2Fwordpress.org%2Fnews/category/Podcast`](https://rsshub.app/wordpress/https%3A%2F%2Fwordpress.org%2Fnews/category/Podcast).

You can also subscribe to multiple categories. `/category/Podcast,Community` to subscribe to both the Podcast and Community categories. In this case, the route would be [`/wordpress/https%3A%2F%2Fwordpress.org%2Fnews/category/Podcast,Community`](https://rsshub.app/wordpress/https%3A%2F%2Fwordpress.org%2Fnews/category/Podcast,Community).

Categories and tags can be combined as well. `/category/Releases/tag/tagging` to subscribe to the Releases category and the tagging tag. In this case, the route would be [`/wordpress/https%3A%2F%2Fwordpress.org%2Fnews/category/Releases/tag/tagging`](https://rsshub.app/wordpress/https%3A%2F%2Fwordpress.org%2Fnews/category/Releases/tag/tagging).

You can also search for keywords. `/search/Blog` to search for the keyword "Blog". In this case, the route would be [`/wordpress/https%3A%2F%2Fwordpress.org%2Fnews/search/Blog`](https://rsshub.app/wordpress/https%3A%2F%2Fwordpress.org%2Fnews/search/Blog).
:::

## Parameters
- `url`: URL, <https://wordpress.org/news> by default
- `filter`: Filter, see below


## Features
- `requireConfig`: [{"description": "This RSS is disabled unless 'ALLOW_USER_SUPPLY_UNSAFE_DOMAIN' is set to 'true'.", "name": "ALLOW_USER_SUPPLY_UNSAFE_DOMAIN", "optional": false}]
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportRadar`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "blog"
  ],
  "description": "If you subscribe to [WordPress News](https://wordpress.org/news/)，where the URL is `https://wordpress.org/news/`, Encode the URL using `encodeURIComponent()` and then use it as the parameter. Therefore, the route will be [`/wordpress/https%3A%2F%2Fwordpress.org%2Fnews`](https://rsshub.app/wordpress/https%3A%2F%2Fwordpress.org%2Fnews).\n\n::: tip\nIf you wish to subscribe to specific categories or tags, you can fill in the \"filter\" parameter in the route. `/category/Podcast` to subscribe to the Podcast category. In this case, the route would be [`/wordpress/https%3A%2F%2Fwordpress.org%2Fnews/category/Podcast`](https://rsshub.app/wordpress/https%3A%2F%2Fwordpress.org%2Fnews/category/Podcast).\n\nYou can also subscribe to multiple categories. `/category/Podcast,Community` to subscribe to both the Podcast and Community categories. In this case, the route would be [`/wordpress/https%3A%2F%2Fwordpress.org%2Fnews/category/Podcast,Community`](https://rsshub.app/wordpress/https%3A%2F%2Fwordpress.org%2Fnews/category/Podcast,Community).\n\nCategories and tags can be combined as well. `/category/Releases/tag/tagging` to subscribe to the Releases category and the tagging tag. In this case, the route would be [`/wordpress/https%3A%2F%2Fwordpress.org%2Fnews/category/Releases/tag/tagging`](https://rsshub.app/wordpress/https%3A%2F%2Fwordpress.org%2Fnews/category/Releases/tag/tagging).\n\nYou can also search for keywords. `/search/Blog` to search for the keyword \"Blog\". In this case, the route would be [`/wordpress/https%3A%2F%2Fwordpress.org%2Fnews/search/Blog`](https://rsshub.app/wordpress/https%3A%2F%2Fwordpress.org%2Fnews/search/Blog).\n:::",
  "example": "/wordpress/https%3A%2F%2Fwordpress.org%2Fnews/category/Podcast",
  "features": {
    "antiCrawler": false,
    "requireConfig": [
      {
        "description": "This RSS is disabled unless 'ALLOW_USER_SUPPLY_UNSAFE_DOMAIN' is set to 'true'.",
        "name": "ALLOW_USER_SUPPLY_UNSAFE_DOMAIN",
        "optional": false
      }
    ],
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": false,
    "supportScihub": false
  },
  "heat": 76,
  "location": "index.ts",
  "maintainers": [
    "nczitzk"
  ],
  "name": "WordPress",
  "parameters": {
    "filter": "Filter, see below",
    "url": "URL, <https://wordpress.org/news> by default"
  },
  "path": "/:url?/:filter{.+}?",
  "radar": [],
  "test": {
    "code": 1,
    "message": "AssertionError: expected 503 to be 200 // Object.is equality\n    at /home/runner/work/RSSHub/RSSHub/lib/routes.test.ts:81:41\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.6/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20"
  },
  "topFeeds": [
    {
      "description": "switch游戏下载-PC游戏下载-switch破解游戏下载-PC破解游戏下载-Switch520-gamer520 - Powered by RSSHub",
      "errorAt": "2025-10-29T12:00:50.099Z",
      "errorMessage": "This RSS is disabled unless 'ALLOW_USER_SUPPLY_UNSAFE_DOMAIN' is set to 'true'.\n",
      "id": "76290647520065536",
      "image": "https://ig.freer.blog/2023/10/25/d67adcffb89dd.jpg",
      "ownerUserId": null,
      "siteUrl": "https://www.gamer520.com//",
      "title": "Switch520",
      "type": "feed",
      "url": "rsshub://wordpress/https%3A%2F%2Fwww.gamer520.com%2F"
    },
    {
      "description": " - Powered by RSSHub",
      "errorAt": "2026-01-19T18:36:43.282Z",
      "errorMessage": "This RSS is disabled unless 'ALLOW_USER_SUPPLY_UNSAFE_DOMAIN' is set to 'true'.\n",
      "id": "168574790345884672",
      "image": "https://s.w.org/images/wmark.png",
      "ownerUserId": null,
      "siteUrl": "https://docs.rsshub.app/",
      "title": "RSSHub",
      "type": "feed",
      "url": "rsshub://wordpress"
    }
  ],
  "url": "wordpress.org"
}
```
