---
layout: default
title: "mandalorian-208 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# mandalorian-208 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | The Mandalorian |
| Collection key | `mandalorian-208` |
| imdb_id | [tt8111088](https://www.imdb.com/title/tt8111088/) |
| wikipedia_url | [The Mandalorian](https://en.wikipedia.org/wiki/The_Mandalorian) |
| Sample dates | 2020-12-18-to-2021-06-17 |
| Sample days | 182 |
| BTIH count | 229 |
| Unique BTIH count | 177 |
| Downloaders total | 29,561,399 |
| Uploaders total | 7,121,985 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-04T03:20:38Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2020-12-18 to 2021-06-17 (182 days)
- Cache Day products: 181
- Sparse Day indices: 1
- Post-release Day products: 0

### Sample archive discontinuities

- missing Day index 63: `2021-02-18`

## 3. Media objects file size histogram

![The Mandalorian collection size histogram](figures/mandalorian-208-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/mandalorian-208-downloads-by-week-mandalorian-208-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![mandalorian-208 downloads by day](figures/mandalorian-208-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 3.74 | 33.40 | 18.85 | 31.59 | 2.48 | 6.90 |

### Cumulative network infrastructure

[![The Mandalorian cumulative map](figures/mandalorian-208-carto.png)](figures/mandalorian-208-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/mandalorian-208-data-ge-1080p.webp)](figures/mandalorian-208-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/mandalorian-208-data-lt-1080p.webp)](figures/mandalorian-208-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
