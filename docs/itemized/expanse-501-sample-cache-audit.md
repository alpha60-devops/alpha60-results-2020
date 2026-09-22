---
layout: default
title: "expanse-501 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# expanse-501 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | The Expanse |
| Collection key | `expanse-501` |
| imdb_id | [tt3230854](https://www.imdb.com/title/tt3230854/) |
| wikipedia_url | [The Expanse (TV series)](https://en.wikipedia.org/wiki/The_Expanse_(TV_series)) |
| Sample dates | 2020-12-16-to-2021-02-14 |
| Sample days | 61 |
| BTIH count | 221 |
| Unique BTIH count | 187 |
| Downloaders total | 3,035,036 |
| Uploaders total | 1,234,663 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-04T03:20:38Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2020-12-16 to 2021-02-23 (70 days)
- Cache Day products: 68
- Sparse Day indices: 2
- Post-release Day products: 7

### Sample archive discontinuities

- missing Day index 62: `2021-02-15`
- missing Day index 63: `2021-02-16`

## 3. File sizes histogram *median[lowest, highest]*

![The Expanse collection size histogram](figures/expanse-501-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/expanse-501-downloads-by-week-expanse-501-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![expanse-501 downloads by day](figures/expanse-501-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2020/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2020/refs/heads/main/data/geojson.cumulative/expanse-501-cumulative-aggregate.geojson.gz" data-map-title="The Expanse — expanse-501" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open The Expanse (expanse-501) cumulative data map in new window" title="Opens interactive map for The Expanse (expanse-501) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 5.15 | 27.69 | 14.32 | 41.80 | 5.21 | 1.17 |

### Network infrastructure

[![The Expanse cumulative map](figures/expanse-501-carto.png)](figures/expanse-501-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/expanse-501-data-ge-1080p.webp)](figures/expanse-501-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/expanse-501-data-lt-1080p.webp)](figures/expanse-501-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
