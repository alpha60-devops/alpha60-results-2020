---
layout: default
title: "da-5-bloods Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# da-5-bloods sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Da 5 Bloods |
| Collection key | `da-5-bloods` |
| imdb_id | [tt9777644](https://www.imdb.com/title/tt9777644/) |
| wikipedia_url | [Da 5 Bloods](https://en.wikipedia.org/wiki/Da_5_Bloods) |
| Sample dates | 2020-06-12-to-2020-08-20 |
| Sample days | 70 |
| BTIH count | 109 |
| Unique BTIH count | 79 |
| Downloaders total | 4,666,627 |
| Uploaders total | 961,442 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-04T03:20:38Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2020-06-12 to 2020-08-20 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Da 5 Bloods collection size histogram](figures/da-5-bloods-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/da-5-bloods-downloads-by-week-da-5-bloods-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![da-5-bloods downloads by day](figures/da-5-bloods-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 8.29 | 35.28 | 18.98 | 22.09 | 1.78 | 6.38 |

### Cumulative network infrastructure

[![Da 5 Bloods cumulative map](figures/da-5-bloods-carto.png)](figures/da-5-bloods-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/da-5-bloods-data-ge-1080p.webp)](figures/da-5-bloods-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/da-5-bloods-data-lt-1080p.webp)](figures/da-5-bloods-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
