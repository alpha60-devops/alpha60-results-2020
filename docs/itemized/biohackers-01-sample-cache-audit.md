---
layout: default
title: "biohackers-01 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# biohackers-01 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Biohackers |
| Collection key | `biohackers-01` |
| imdb_id | [tt9849210](https://www.imdb.com/title/tt9849210/) |
| wikipedia_url | [Biohackers](https://en.wikipedia.org/wiki/Biohackers) |
| Sample dates | 2020-08-20-to-2020-10-29 |
| Sample days | 71 |
| BTIH count | 85 |
| Unique BTIH count | 74 |
| Downloaders total | 1,380,122 |
| Uploaders total | 144,745 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-04T03:20:38Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2020-08-20 to 2020-10-29 (71 days)
- Cache Day products: 71
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Biohackers collection size histogram](figures/biohackers-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/biohackers-01-downloads-by-week-biohackers-01-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![biohackers-01 downloads by day](figures/biohackers-01-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 3.07 | 38.37 | 17.94 | 23.07 | 1.39 | 10.34 |

### Cumulative network infrastructure

[![Biohackers cumulative map](figures/biohackers-01-carto.png)](figures/biohackers-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/biohackers-01-data-ge-1080p.webp)](figures/biohackers-01-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/biohackers-01-data-lt-1080p.webp)](figures/biohackers-01-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
