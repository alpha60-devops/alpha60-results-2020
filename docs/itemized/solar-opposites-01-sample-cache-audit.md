---
layout: default
title: "solar-opposites-01 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# solar-opposites-01 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Solar Opposites |
| Collection key | `solar-opposites-01` |
| imdb_id | [tt8910922](https://www.imdb.com/title/tt8910922/) |
| wikipedia_url | [Solar Opposites](https://en.wikipedia.org/wiki/Solar_Opposites) |
| Sample dates | 2020-05-08-to-2020-07-16 |
| Sample days | 70 |
| BTIH count | 166 |
| Unique BTIH count | 153 |
| Downloaders total | 2,613,121 |
| Uploaders total | 792,621 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-04T03:20:38Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2020-05-08 to 2020-07-16 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Solar Opposites collection size histogram](figures/solar-opposites-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/solar-opposites-01-downloads-by-week-solar-opposites-01-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![solar-opposites-01 downloads by day](figures/solar-opposites-01-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 4.55 | 38.62 | 12.92 | 30.38 | 3.58 | 2.50 |

### Cumulative network infrastructure

[![Solar Opposites cumulative map](figures/solar-opposites-01-carto.png)](figures/solar-opposites-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/solar-opposites-01-data-ge-1080p.webp)](figures/solar-opposites-01-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/solar-opposites-01-data-lt-1080p.webp)](figures/solar-opposites-01-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
