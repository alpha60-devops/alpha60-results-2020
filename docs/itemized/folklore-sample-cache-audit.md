---
layout: default
title: "folklore Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# folklore sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Folklore |
| Collection key | `folklore` |
| imdb_id | [tt13524234](https://www.imdb.com/title/tt13524234/) |
| wikipedia_url | [Folklore: The Long Pond Studio Sessions](https://en.wikipedia.org/wiki/Folklore:_The_Long_Pond_Studio_Sessions) |
| Sample dates | 2020-07-24-to-2021-01-21 |
| Sample days | 182 |
| BTIH count | 93 |
| Unique BTIH count | 57 |
| Downloaders total | 2,534,211 |
| Uploaders total | 834,708 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-04T03:20:38Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2020-07-24 to 2021-01-21 (182 days)
- Cache Day products: 182
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Folklore collection size histogram](figures/folklore-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/folklore-downloads-by-week-folklore-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![folklore downloads by day](figures/folklore-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 5.12 | 35.87 | 18.37 | 24.28 | 1.51 | 2.04 |

### Cumulative network infrastructure

[![Folklore cumulative map](figures/folklore-carto.png)](figures/folklore-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/folklore-data-ge-1080p.webp)](figures/folklore-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/folklore-data-lt-1080p.webp)](figures/folklore-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
