---
layout: default
title: "mulan Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# mulan sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Mulan 2020 |
| Collection key | `mulan` |
| imdb_id | [tt4566758](https://www.imdb.com/title/tt4566758/) |
| wikipedia_url | [Mulan (2020 film)](https://en.wikipedia.org/wiki/Mulan_(2020_film)) |
| Sample dates | 2020-09-04-to-2021-03-04 |
| Sample days | 182 |
| BTIH count | 259 |
| Unique BTIH count | 223 |
| Downloaders total | 32,989,670 |
| Uploaders total | 8,286,285 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-04T03:20:38Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2020-09-04 to 2021-03-04 (182 days)
- Cache Day products: 180
- Sparse Day indices: 2
- Post-release Day products: 0

### Sample archive discontinuities

- missing Day index 165: `2021-02-15`
- missing Day index 166: `2021-02-16`

## 3. Media objects file size histogram

![Mulan 2020 collection size histogram](figures/mulan-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/mulan-downloads-by-week-mulan-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![mulan downloads by day](figures/mulan-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 5.35 | 33.41 | 23.32 | 24.96 | 1.68 | 4.87 |

### Cumulative network infrastructure

[![Mulan 2020 cumulative map](figures/mulan-carto.png)](figures/mulan-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/mulan-data-ge-1080p.webp)](figures/mulan-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/mulan-data-lt-1080p.webp)](figures/mulan-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
