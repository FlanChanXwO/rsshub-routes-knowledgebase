# App Center - Release

## Coverage
`index-only`

## Route
- Namespace: `app-center`
- Namespace Name: `App Center`
- Route Path: `/release/:user/:app/:distribution_group`
- Route Name: `Release`
- Example: `/app-center/release/cloudflare/1.1.1.1-windows/beta`
- URL: `install.appcenter.ms`
- Language: `en`
- Categories: `program-update`
- Maintainers: `Rongronggg9`
- Source Location: `release.tsx`
- Source Module: `() => import('@/routes/app-center/release.tsx')`

## Description
::: tip
  The parameters can be extracted from the Release page URL: `https://install.appcenter.ms/users/:user/apps/:app/distribution_groups/:distribution_group`
:::

## Parameters
- `user`: User
- `app`: App name
- `distribution_group`: Distribution group


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
  - `install.appcenter.ms/users/:user/apps/:app/distribution_groups/:distribution_group`
  - `install.appcenter.ms/orgs/:user/apps/:app/distribution_groups/:distribution_group`

## Raw JSON
```json
{
  "categories": [
    "program-update"
  ],
  "description": "::: tip\n  The parameters can be extracted from the Release page URL: `https://install.appcenter.ms/users/:user/apps/:app/distribution_groups/:distribution_group`\n:::",
  "example": "/app-center/release/cloudflare/1.1.1.1-windows/beta",
  "features": {
    "antiCrawler": false,
    "requireConfig": false,
    "requirePuppeteer": false,
    "supportBT": false,
    "supportPodcast": false,
    "supportScihub": false
  },
  "location": "release.tsx",
  "maintainers": [
    "Rongronggg9"
  ],
  "module": "() => import('@/routes/app-center/release.tsx')",
  "name": "Release",
  "parameters": {
    "app": "App name",
    "distribution_group": "Distribution group",
    "user": "User"
  },
  "path": "/release/:user/:app/:distribution_group",
  "radar": [
    {
      "source": [
        "install.appcenter.ms/users/:user/apps/:app/distribution_groups/:distribution_group",
        "install.appcenter.ms/orgs/:user/apps/:app/distribution_groups/:distribution_group"
      ]
    }
  ]
}
```
