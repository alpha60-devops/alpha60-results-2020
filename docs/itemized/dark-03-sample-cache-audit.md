---
layout: default
title: "dark-03 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# dark-03 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Dark |
| Collection key | `dark-03` |
| imdb_id | [tt5753856](https://www.imdb.com/title/tt5753856/) |
| wikipedia_url | [Dark (TV series)](https://en.wikipedia.org/wiki/Dark_(TV_series)) |
| Sample dates | 2020-06-27-to-2020-08-28 |
| Sample days | 63 |
| BTIH count | 162 |
| Unique BTIH count | 148 |
| Downloaders total | 4,496,919 |
| Uploaders total | 798,503 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-04T03:20:38Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2020-06-27 to 2020-09-04 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 7

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![Dark collection size histogram](figures/dark-03-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/dark-03-downloads-by-week-dark-03-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![dark-03 downloads by day](figures/dark-03-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2020/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2020/refs/heads/main/data/geojson.cumulative/dark-03-cumulative-aggregate.geojson.gz" data-map-title="Dark — dark-03" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Dark (dark-03) cumulative data map in new window" title="Opens interactive map for Dark (dark-03) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.72 | 38.23 | 21.94 | 23.69 | 1.22 | 8.74 |

### Network infrastructure

[![Dark cumulative map](figures/dark-03-carto.png)](figures/dark-03-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/dark-03-data-ge-1080p.webp)](figures/dark-03-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/dark-03-data-lt-1080p.webp)](figures/dark-03-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
