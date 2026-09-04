---
layout: default
title: "vanguard Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# vanguard sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Vanguard |
| Collection key | `vanguard` |
| imdb_id | [tt9695722](https://www.imdb.com/title/tt9695722/) |
| wikipedia_url | [Vanguard (film)](https://en.wikipedia.org/wiki/Vanguard_(film)) |
| Sample dates | 2020-10-02-to-2021-04-01 |
| Sample days | 182 |
| BTIH count | 153 |
| Unique BTIH count | 117 |
| Downloaders total | 8,284,330 |
| Uploaders total | 1,281,127 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-04T03:20:38Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2020-10-02 to 2021-04-01 (182 days)
- Cache Day products: 182
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Vanguard collection size histogram](figures/vanguard-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/vanguard-downloads-by-week-vanguard-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![vanguard downloads by day](figures/vanguard-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 5.93 | 27.83 | 29.92 | 22.63 | 1.25 | 7.65 |

### Cumulative network infrastructure

[![Vanguard cumulative map](figures/vanguard-carto.png)](figures/vanguard-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/vanguard-data-ge-1080p.webp)](figures/vanguard-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/vanguard-data-lt-1080p.webp)](figures/vanguard-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
