---
layout: default
title: "songbird Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# songbird sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Songbird |
| Collection key | `songbird` |
| imdb_id | [tt12592252](https://www.imdb.com/title/tt12592252/) |
| wikipedia_url | [Songbird (2020 film)](https://en.wikipedia.org/wiki/Songbird_(2020_film)) |
| Sample dates | 2020-12-11-to-2021-02-04 |
| Sample days | 56 |
| BTIH count | 52 |
| Unique BTIH count | 35 |
| Downloaders total | 2,430,871 |
| Uploaders total | 645,618 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-04T03:20:38Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2020-12-11 to 2021-02-18 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 14

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![Songbird collection size histogram](figures/songbird-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/songbird-downloads-by-week-songbird-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![songbird downloads by day](figures/songbird-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2020/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2020/refs/heads/main/data/geojson.cumulative/songbird-cumulative-aggregate.geojson.gz" data-map-title="Songbird — songbird" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Songbird (songbird) cumulative data map in new window" title="Opens interactive map for Songbird (songbird) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 11.02 | 32.72 | 17.69 | 19.83 | 2.13 | 7.23 |

### Network infrastructure

[![Songbird cumulative map](figures/songbird-carto.png)](figures/songbird-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/songbird-data-ge-1080p.webp)](figures/songbird-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/songbird-data-lt-1080p.webp)](figures/songbird-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
