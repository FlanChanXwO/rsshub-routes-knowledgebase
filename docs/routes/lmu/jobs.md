# Ludwig Maximilian University of Munich - Job Openings

## Coverage
`index-only`

## Route
- Namespace: `lmu`
- Namespace Name: `Ludwig Maximilian University of Munich`
- Route Path: `/jobs`
- Route Name: `Job Openings`
- Example: `/lmu/jobs`
- URL: `lmu.de`
- Language: `de`
- Categories: `university, study`
- Maintainers: `StarDxxx`
- Source Location: `jobs.tsx`
- Source Module: `() => import('@/routes/lmu/jobs.tsx')`

## Description
RSS feed for LMU academic staff job openings.

## Parameters
_None_


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.lmu.de/en/about-lmu/working-at-lmu/job-portal/academic-staff/`
- `target`: `/lmu/jobs`

## Raw JSON
```json
{
  "categories": [
    "university",
    "study"
  ],
  "description": "RSS feed for LMU academic staff job openings.",
  "example": "/lmu/jobs",
  "location": "jobs.tsx",
  "maintainers": [
    "StarDxxx"
  ],
  "module": "() => import('@/routes/lmu/jobs.tsx')",
  "name": "Job Openings",
  "path": "/jobs",
  "radar": [
    {
      "source": [
        "www.lmu.de/en/about-lmu/working-at-lmu/job-portal/academic-staff/"
      ],
      "target": "/lmu/jobs"
    }
  ],
  "url": "lmu.de"
}
```
