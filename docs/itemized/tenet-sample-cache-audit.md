---
layout: default
title: "tenet Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# tenet sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Tenet |
| Collection key | `tenet` |
| imdb_id | [tt6723592](https://www.imdb.com/title/tt6723592/) |
| wikipedia_url | [Tenet](https://en.wikipedia.org/wiki/Tenet) |
| Sample dates | 2020-08-30-to-2021-02-27 |
| Sample days | 182 |
| BTIH count | 326 |
| Unique BTIH count | 285 |
| Downloaders total | 26,108,321 |
| Uploaders total | 9,075,171 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-04T03:20:38Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2020-08-30 to 2021-02-27 (182 days)
- Cache Day products: 182
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![Tenet collection size histogram](figures/tenet-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/tenet-downloads-by-week-tenet-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![tenet downloads by day](figures/tenet-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2020/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2020/refs/heads/main/data/geojson.cumulative/tenet-cumulative-aggregate.geojson.gz" data-map-title="Tenet — tenet" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Tenet (tenet) cumulative data map in new window" title="Opens interactive map for Tenet (tenet) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 6.39 | 19.40 | 27.58 | 36.51 | 1.73 | 3.55 |

### Network infrastructure

[![Tenet cumulative map](figures/tenet-carto.png)](figures/tenet-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/tenet-data-ge-1080p.webp)](figures/tenet-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/tenet-data-lt-1080p.webp)](figures/tenet-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
