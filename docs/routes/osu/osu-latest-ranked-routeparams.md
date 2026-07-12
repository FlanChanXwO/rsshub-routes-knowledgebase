# osu! - Latest Ranked Beatmap

## Coverage
`index-only`

## Route
- Namespace: `osu`
- Namespace Name: `osu!`
- Route Path: `/osu/latest-ranked/:routeParams?`
- Route Name: `Latest Ranked Beatmap`
- Example: `/osu/latest-ranked/includeMode=osu&difficultyLimit=L3&difficultyLimit=U7`
- URL: `osu.ppy.sh`
- Language: `_None_`
- Categories: `game`
- Maintainers: `nfnfgo`
- Source Location: `beatmaps/latest-ranked.tsx`
- Source Module: `_None_`

## Description
Subscribe to the new beatmaps on https://osu.ppy.sh/beatmapsets.

#### Parameter Description

Parameters allows you to:

- Filter game mode
- Limit beatmap difficulty
- Show/hide game mode in feed title

Below is a table of all allowed parameters passed to `routeParams`


| Name              | Default  | Description                                                                                                                                                                                                                                          |
| ----------------- | -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `includeMode`     | All mode | Could be `osu`, `mania`, `fruits` or `taiko`. Specify included game mode of beatmaps. Including this paramseter multiple times to specify multiple game modes, e.g.: `includeMode=osu&includeMode=mania`. Subscribe to all game modes if not specified |
| `difficultyLimit` | None     | Lower/upper limit of star rating of the beatmaps in the beatmapset item, e.g.:`difficultyLimit=U6`. Checkout tips in descriptions for detailed explaination and examples.                                                                            |
| `modeInTitle`     | `true`   | `true` or `false` Add mode info into feed title.


This actual parameters should be passed as `routeParams` in URL Query String format without `?`, e.g.:

    /osu/latest-ranked/modeInTitle=true&includeMode=osu

::: tip
You could make use of `difficultyLimit` paramters to create a "high difficulty/low difficulty only" only feed.

For example, if you only wants to play low star rating beatmap like 1 or 2 star, you could subscribe to:

    /osu/latest-ranked/difficultyLimit=U2

This will filter out all beatmapsets that do not provide at least one beatmap with star rating<=`2.00`.

Similarly, you could use lower bound to filter out beatmapsets which don't have at least one beatmap
with star rating higher than a certain threshold.

    /osu/latest-ranked/difficultyLimit=L6

Now all beatmapsets that don't provided at least one beatmap with star rating higher than `6.00` will be filtered.
:::

## Parameters
- `routeParams`: {"default": "null", "description": "Used to pass route parameters in Query String format. Check out route description for more info."}


## Features
- `requireConfig`: false
- `requirePuppeteer`: false
- `antiCrawler`: false
- `supportBT`: false
- `supportPodcast`: false
- `supportScihub`: false
- `supportRadar`: true

## Radar
### Rule 1
- `source`:
  - `osu.ppy.sh/beatmapsets`

## Raw JSON
```json
{
  "categories": [
    "game"
  ],
  "description": "\nSubscribe to the new beatmaps on https://osu.ppy.sh/beatmapsets.\n\n#### Parameter Description\n\nParameters allows you to:\n\n- Filter game mode\n- Limit beatmap difficulty\n- Show/hide game mode in feed title\n\nBelow is a table of all allowed parameters passed to `routeParams`\n\n\n| Name              | Default  | Description                                                                                                                                                                                                                                          |\n| ----------------- | -------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |\n| `includeMode`     | All mode | Could be `osu`, `mania`, `fruits` or `taiko`. Specify included game mode of beatmaps. Including this paramseter multiple times to specify multiple game modes, e.g.: `includeMode=osu&includeMode=mania`. Subscribe to all game modes if not specified |\n| `difficultyLimit` | None     | Lower/upper limit of star rating of the beatmaps in the beatmapset item, e.g.:`difficultyLimit=U6`. Checkout tips in descriptions for detailed explaination and examples.                                                                            |\n| `modeInTitle`     | `true`   | `true` or `false` Add mode info into feed title.\n\n\nThis actual parameters should be passed as `routeParams` in URL Query String format without `?`, e.g.:\n\n    /osu/latest-ranked/modeInTitle=true&includeMode=osu\n\n::: tip\nYou could make use of `difficultyLimit` paramters to create a \"high difficulty/low difficulty only\" only feed.\n\nFor example, if you only wants to play low star rating beatmap like 1 or 2 star, you could subscribe to:\n\n    /osu/latest-ranked/difficultyLimit=U2\n\nThis will filter out all beatmapsets that do not provide at least one beatmap with star rating<=`2.00`.\n\nSimilarly, you could use lower bound to filter out beatmapsets which don't have at least one beatmap\nwith star rating higher than a certain threshold.\n\n    /osu/latest-ranked/difficultyLimit=L6\n\nNow all beatmapsets that don't provided at least one beatmap with star rating higher than `6.00` will be filtered.\n:::",
  "example": "/osu/latest-ranked/includeMode=osu&difficultyLimit=L3&difficultyLimit=U7",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportRadar": true,
    "supportScihub": false
  },
  "heat": 1,
  "location": "beatmaps/latest-ranked.tsx",
  "maintainers": [
    "nfnfgo"
  ],
  "name": "Latest Ranked Beatmap",
  "parameters": {
    "routeParams": {
      "default": "null",
      "description": "Used to pass route parameters in Query String format. Check out route description for more info."
    }
  },
  "path": "/latest-ranked/:routeParams?",
  "radar": [
    {
      "source": [
        "osu.ppy.sh/beatmapsets"
      ]
    }
  ],
  "test": {
    "code": 0
  },
  "topFeeds": [
    {
      "description": "Newly ranked beatmaps at https://osu.ppy.sh/beatmapsets. - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "173104715305606144",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://osu.ppy.sh/beatmapsets",
      "title": "Osu! Latest Ranked Map",
      "type": "feed",
      "url": "rsshub://osu/latest-ranked"
    }
  ]
}
```
