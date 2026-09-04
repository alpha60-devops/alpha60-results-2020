---
layout: default
title: "avenue-5-101 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# avenue-5-101 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Avenue 5 |
| Collection key | `avenue-5-101` |
| imdb_id | [tt10234362](https://www.imdb.com/title/tt10234362/) |
| wikipedia_url | [Avenue 5](https://en.wikipedia.org/wiki/Avenue_5) |
| Sample dates | 2020-01-20-to-2020-02-16 |
| Sample days | 28 |
| BTIH count | 37 |
| Unique BTIH count | 33 |
| Downloaders total | 844,878 |
| Uploaders total | 118,440 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-04T03:20:38Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2020-01-20 to 2020-02-16 (28 days)
- Cache Day products: 28
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Avenue 5 collection size histogram](figures/avenue-5-101-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/avenue-5-101-downloads-by-week-avenue-5-101-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![avenue-5-101 downloads by day](figures/avenue-5-101-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.83 | 33.53 | 16.64 | 27.20 | 3.04 | 8.74 |

### Cumulative network infrastructure

[![Avenue 5 cumulative map](figures/avenue-5-101-carto.png)](figures/avenue-5-101-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/avenue-5-101-data-ge-1080p.webp)](figures/avenue-5-101-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/avenue-5-101-data-lt-1080p.webp)](figures/avenue-5-101-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
