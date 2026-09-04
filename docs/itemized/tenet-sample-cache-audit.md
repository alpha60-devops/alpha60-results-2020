---
layout: default
title: "tenet Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# tenet sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Tenet |
| Collection key | `tenet` |
| imdb_id | [tt6723592](https://www.imdb.com/title/tt6723592/) |
| wikipedia_url | [Tenet](https://en.wikipedia.org/wiki/Tenet) |
| Sample dates | 2020-08-30-to-2021-02-27 |
| Sample days | 182 |
| BTIH count | 326 |
| Unique BTIH count | 285 |
| Downloaders total | 26,108,321 |
| Uploaders total | 9,075,171 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-04T03:20:38Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2020-08-30 to 2021-02-27 (182 days)
- Cache Day products: 182
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Tenet collection size histogram](figures/tenet-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/tenet-downloads-by-week-tenet-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![tenet downloads by day](figures/tenet-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 6.39 | 19.40 | 27.58 | 36.51 | 1.73 | 3.55 |

### Cumulative network infrastructure

[![Tenet cumulative map](figures/tenet-carto.png)](figures/tenet-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/tenet-data-ge-1080p.webp)](figures/tenet-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/tenet-data-lt-1080p.webp)](figures/tenet-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
