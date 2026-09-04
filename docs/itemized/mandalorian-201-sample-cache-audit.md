---
layout: default
title: "mandalorian-201 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# mandalorian-201 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | The Mandalorian |
| Collection key | `mandalorian-201` |
| imdb_id | [tt8111088](https://www.imdb.com/title/tt8111088/) |
| wikipedia_url | [The Mandalorian](https://en.wikipedia.org/wiki/The_Mandalorian) |
| Sample dates | 2020-10-30-to-2020-12-17 |
| Sample days | 49 |
| BTIH count | 203 |
| Unique BTIH count | 160 |
| Downloaders total | 5,909,805 |
| Uploaders total | 2,331,843 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-04T03:20:38Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2020-10-30 to 2020-12-17 (49 days)
- Cache Day products: 49
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![The Mandalorian collection size histogram](figures/mandalorian-201-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/mandalorian-201-downloads-by-week-mandalorian-201-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![mandalorian-201 downloads by day](figures/mandalorian-201-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 3.10 | 29.52 | 13.26 | 39.42 | 3.15 | 1.25 |

### Cumulative network infrastructure

[![The Mandalorian cumulative map](figures/mandalorian-201-carto.png)](figures/mandalorian-201-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/mandalorian-201-data-ge-1080p.webp)](figures/mandalorian-201-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/mandalorian-201-data-lt-1080p.webp)](figures/mandalorian-201-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
