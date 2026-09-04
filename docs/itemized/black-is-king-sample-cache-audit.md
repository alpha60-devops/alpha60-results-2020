---
layout: default
title: "black-is-king Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# black-is-king sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Black Is King |
| Collection key | `black-is-king` |
| imdb_id | [tt12607910](https://www.imdb.com/title/tt12607910/) |
| wikipedia_url | [Black Is King](https://en.wikipedia.org/wiki/Black_Is_King) |
| Sample dates | 2020-07-31-to-2021-01-28 |
| Sample days | 182 |
| BTIH count | 61 |
| Unique BTIH count | 38 |
| Downloaders total | 2,813,924 |
| Uploaders total | 991,768 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-04T03:20:38Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2020-07-31 to 2021-01-28 (182 days)
- Cache Day products: 182
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Black Is King collection size histogram](figures/black-is-king-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/black-is-king-downloads-by-week-black-is-king-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![black-is-king downloads by day](figures/black-is-king-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 20.59 | 40.16 | 11.90 | 15.82 | 1.31 | 0.88 |

### Cumulative network infrastructure

[![Black Is King cumulative map](figures/black-is-king-carto.png)](figures/black-is-king-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/black-is-king-data-ge-1080p.webp)](figures/black-is-king-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/black-is-king-data-lt-1080p.webp)](figures/black-is-king-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
