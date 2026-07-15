# The Palace Museum - Current Exhibitions

## Coverage
`index-only`

## Route
- Namespace: `dpm`
- Namespace Name: `The Palace Museum`
- Route Path: `/dpm/exhibitions/:type?`
- Route Name: `Current Exhibitions`
- Example: `/dpm/exhibitions/temporary_exhibitions`
- URL: `www.dpm.org.cn`
- Language: `_None_`
- Categories: `travel`
- Maintainers: `magazian`
- Source Location: `exhibitions.tsx`
- Source Module: `_None_`

## Description
_None_

## Parameters
- `type`: Exhibition type, supported values: temporary_exhibitions（特展）、galleries（专馆）、longterm_exhibitions（常设展览）、period_halls（原状陈列）. Default: Current Exhibitions.


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.dpm.org.cn/classify/exhibition.html`
- `target`: `/exhibitions`

## Raw JSON
```json
{
  "categories": [
    "travel"
  ],
  "example": "/dpm/exhibitions/temporary_exhibitions",
  "heat": 0,
  "location": "exhibitions.tsx",
  "maintainers": [
    "magazian"
  ],
  "name": "Current Exhibitions",
  "parameters": {
    "type": "Exhibition type, supported values: temporary_exhibitions（特展）、galleries（专馆）、longterm_exhibitions（常设展览）、period_halls（原状陈列）. Default: Current Exhibitions."
  },
  "path": "/exhibitions/:type?",
  "radar": [
    {
      "source": [
        "www.dpm.org.cn/classify/exhibition.html"
      ],
      "target": "/exhibitions"
    }
  ],
  "test": {
    "code": 1,
    "message": "Error: STACK_TRACE_ERROR\n    at task (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1784:27)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1817:16)\n    at Object.<anonymous> (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1563:28)\n    at chain (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:599:14)\n    at /home/runner/work/RSSHub/RSSHub/lib/app.test.ts:98:12\n    at file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:40\n    at runWithSuite (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:2258:8)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1889:10)\n    at Object.collect (file:///home/runner/work/RSSHub/RSSHub/node_modules/.pnpm/@vitest+runner@4.1.10/node_modules/@vitest/runner/dist/chunk-artifact.js:1893:54)\n    at processTicksAndRejections (node:internal/process/task_queues:104:5)"
  },
  "topFeeds": []
}
```
