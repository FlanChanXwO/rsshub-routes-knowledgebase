# Bugzilla - bugs

## Coverage
`index-only`

## Route
- Namespace: `bugzilla`
- Namespace Name: `Bugzilla`
- Route Path: `/bugzilla/bug/:site/:bugId`
- Route Name: `bugs`
- Example: `/bugzilla/bug/webkit/251528`
- URL: `bugzilla.org`
- Language: `_None_`
- Categories: `programming`
- Maintainers: `FranklinYu`
- Source Location: `bug.ts`
- Source Module: `_None_`

## Description
Supported site identifiers: [`apache`](https://bz.apache.org/bugzilla), [`apache.ooo`](https://bz.apache.org/ooo), [`apache.SpamAssassin`](https://bz.apache.org/SpamAssassin), [`kernel`](https://bugzilla.kernel.org), [`mozilla`](https://bugzilla.mozilla.org), [`webkit`](https://bugs.webkit.org).

## Parameters
- `site`: site identifier
- `bugId`: numeric identifier of the bug in the site


## Features
_None_

## Radar
_None_

## Raw JSON
```json
{
  "categories": [
    "programming"
  ],
  "description": "Supported site identifiers: [`apache`](https://bz.apache.org/bugzilla), [`apache.ooo`](https://bz.apache.org/ooo), [`apache.SpamAssassin`](https://bz.apache.org/SpamAssassin), [`kernel`](https://bugzilla.kernel.org), [`mozilla`](https://bugzilla.mozilla.org), [`webkit`](https://bugs.webkit.org).",
  "example": "/bugzilla/bug/webkit/251528",
  "heat": 1,
  "location": "bug.ts",
  "maintainers": [
    "FranklinYu"
  ],
  "name": "bugs",
  "parameters": {
    "bugId": "numeric identifier of the bug in the site",
    "site": "site identifier"
  },
  "path": "/bug/:site/:bugId",
  "topFeeds": [
    {
      "description": "[GTK][WPE] EventSenderProxy::rawKeyDown|Up are not implemented - Powered by RSSHub",
      "errorAt": null,
      "errorMessage": null,
      "id": "74134408656516096",
      "image": null,
      "ownerUserId": null,
      "siteUrl": "https://bugs.webkit.org/show_bug.cgi?id=251528",
      "title": "[GTK][WPE] EventSenderProxy::rawKeyDown|Up are not implemented",
      "type": "feed",
      "url": "rsshub://bugzilla/bug/webkit/251528"
    }
  ],
  "zh": {
    "description": "支持的站点标识符：[`apache`](https://bz.apache.org/bugzilla)、[`apache.ooo`](https://bz.apache.org/ooo)、[`apache.SpamAssassin`](https://bz.apache.org/SpamAssassin)、[`kernel`](https://bugzilla.kernel.org)、[`mozilla`](https://bugzilla.mozilla.org)、[`webkit`](https://bugs.webkit.org)。",
    "name": "bugs"
  }
}
```
