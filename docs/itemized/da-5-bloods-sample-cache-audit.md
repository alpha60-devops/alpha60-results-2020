---
layout: default
title: "da-5-bloods Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# da-5-bloods sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Da 5 Bloods |
| Collection key | `da-5-bloods` |
| imdb_id | [tt9777644](https://www.imdb.com/title/tt9777644/) |
| wikipedia_url | [Da 5 Bloods](https://en.wikipedia.org/wiki/Da_5_Bloods) |
| Sample dates | 2020-06-12-to-2020-08-20 |
| Sample days | 70 |
| BTIH count | 109 |
| Unique BTIH count | 79 |
| Downloaders total | 4,666,627 |
| Uploaders total | 961,442 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-04T03:20:38Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2020-06-12 to 2020-08-20 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![Da 5 Bloods collection size histogram](figures/da-5-bloods-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/da-5-bloods-downloads-by-week-da-5-bloods-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![da-5-bloods downloads by day](figures/da-5-bloods-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2020/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2020/refs/heads/main/data/geojson.cumulative/da-5-bloods-cumulative-aggregate.geojson.gz" data-map-title="Da 5 Bloods — da-5-bloods" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Da 5 Bloods (da-5-bloods) cumulative data map in new window" title="Opens interactive map for Da 5 Bloods (da-5-bloods) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 8.29 | 35.28 | 18.98 | 22.09 | 1.78 | 6.38 |

### Network infrastructure

[![Da 5 Bloods cumulative map](figures/da-5-bloods-carto.png)](figures/da-5-bloods-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/da-5-bloods-data-ge-1080p.webp)](figures/da-5-bloods-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/da-5-bloods-data-lt-1080p.webp)](figures/da-5-bloods-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
