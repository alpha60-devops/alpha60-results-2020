---
layout: default
title: "queer-eye-2018-05 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# queer-eye-2018-05 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Queer Eye 2018 |
| Collection key | `queer-eye-2018-05` |
| imdb_id | [tt7259746](https://www.imdb.com/title/tt7259746/) |
| wikipedia_url | [Queer Eye (2018 TV series)](https://en.wikipedia.org/wiki/Queer_Eye_(2018_TV_series)) |
| Sample dates | 2020-06-05-to-2020-08-13 |
| Sample days | 70 |
| BTIH count | 130 |
| Unique BTIH count | 115 |
| Downloaders total | 1,227,078 |
| Uploaders total | 109,033 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-04T03:20:38Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2020-06-05 to 2020-08-13 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Queer Eye 2018 collection size histogram](figures/queer-eye-2018-05-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/queer-eye-2018-05-downloads-by-week-queer-eye-2018-05-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![queer-eye-2018-05 downloads by day](figures/queer-eye-2018-05-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.02 | 45.39 | 16.71 | 20.57 | 1.35 | 9.39 |

### Cumulative network infrastructure

[![Queer Eye 2018 cumulative map](figures/queer-eye-2018-05-carto.png)](figures/queer-eye-2018-05-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/queer-eye-2018-05-data-ge-1080p.webp)](figures/queer-eye-2018-05-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/queer-eye-2018-05-data-lt-1080p.webp)](figures/queer-eye-2018-05-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
