# Sketis | Website of Dr. Makarius Wenzel - Isabelle Development Blogs

## Coverage
`index-only`

## Route
- Namespace: `sketis`
- Namespace Name: `Sketis | Website of Dr. Makarius Wenzel`
- Route Path: `/isabelle-dev/blog/:blog`
- Route Name: `Isabelle Development Blogs`
- Example: `/sketis/isabelle-dev/blog/1`
- URL: `isabelle-dev.sketis.net`
- Language: `en`
- Categories: `programming`
- Maintainers: `Ritsuka314`
- Source Location: `isabelle-dev/blog/index.ts`
- Source Module: `() => import('@/routes/sketis/isabelle-dev/blog/index.ts')`

## Description
- Isabelle News: `https://isabelle-dev.sketis.net/phame/blog/view/1/`
- Isabelle Release: `https://isabelle-dev.sketis.net/phame/blog/view/2/`

## Parameters
- `blog`: name of blog (1 for NEWS; 2 for Release)


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
  - `isabelle-dev.sketis.net/phame/`
  - `isabelle-dev.sketis.net/phame/blog/`
  - `isabelle-dev.sketis.net/phame/blog/view/:blog/`
  - `isabelle-dev.sketis.net/phame/post/`
  - `isabelle-dev.sketis.net/phame/post/view/:post_id/:post_title/`
- `target`: `/isabelle-dev/blog/1`
### Rule 2
- `source`:
  - `isabelle-dev.sketis.net/phame/`
  - `isabelle-dev.sketis.net/phame/blog/`
  - `isabelle-dev.sketis.net/phame/blog/view/:blog/`
  - `isabelle-dev.sketis.net/phame/post/`
  - `isabelle-dev.sketis.net/phame/post/view/:post_id/:post_title/`
- `target`: `/isabelle-dev/blog/2`

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "\n- Isabelle News: `https://isabelle-dev.sketis.net/phame/blog/view/1/`\n- Isabelle Release: `https://isabelle-dev.sketis.net/phame/blog/view/2/`\n",
  "example": "/sketis/isabelle-dev/blog/1",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "isabelle-dev/blog/index.ts",
  "maintainers": [
    "Ritsuka314"
  ],
  "module": "() => import('@/routes/sketis/isabelle-dev/blog/index.ts')",
  "name": "Isabelle Development Blogs",
  "parameters": {
    "blog": "name of blog (1 for NEWS; 2 for Release)"
  },
  "path": "/isabelle-dev/blog/:blog",
  "radar": [
    {
      "source": [
        "isabelle-dev.sketis.net/phame/",
        "isabelle-dev.sketis.net/phame/blog/",
        "isabelle-dev.sketis.net/phame/blog/view/:blog/",
        "isabelle-dev.sketis.net/phame/post/",
        "isabelle-dev.sketis.net/phame/post/view/:post_id/:post_title/"
      ],
      "target": "/isabelle-dev/blog/1"
    },
    {
      "source": [
        "isabelle-dev.sketis.net/phame/",
        "isabelle-dev.sketis.net/phame/blog/",
        "isabelle-dev.sketis.net/phame/blog/view/:blog/",
        "isabelle-dev.sketis.net/phame/post/",
        "isabelle-dev.sketis.net/phame/post/view/:post_id/:post_title/"
      ],
      "target": "/isabelle-dev/blog/2"
    }
  ],
  "url": "isabelle-dev.sketis.net"
}
```
