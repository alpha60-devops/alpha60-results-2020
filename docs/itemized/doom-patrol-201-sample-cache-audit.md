---
layout: default
title: "doom-patrol-201 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# doom-patrol-201 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Doom Patrol |
| Collection key | `doom-patrol-201` |
| imdb_id | [tt8416494](https://www.imdb.com/title/tt8416494/) |
| wikipedia_url | [Doom Patrol (TV series)](https://en.wikipedia.org/wiki/Doom_Patrol_(TV_series)) |
| Sample dates | 2020-06-25-to-2020-09-02 |
| Sample days | 70 |
| BTIH count | 150 |
| Unique BTIH count | 134 |
| Downloaders total | 5,096,379 |
| Uploaders total | 653,236 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-04T03:20:38Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2020-06-25 to 2020-09-02 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![Doom Patrol collection size histogram](figures/doom-patrol-201-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/doom-patrol-201-downloads-by-week-doom-patrol-201-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![doom-patrol-201 downloads by day](figures/doom-patrol-201-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2020/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2020/refs/heads/main/data/geojson.cumulative/doom-patrol-201-cumulative-aggregate.geojson.gz" data-map-title="Doom Patrol — doom-patrol-201" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Doom Patrol (doom-patrol-201) cumulative data map in new window" title="Opens interactive map for Doom Patrol (doom-patrol-201) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 3.06 | 42.15 | 17.24 | 23.96 | 2.12 | 9.31 |

### Network infrastructure

[![Doom Patrol cumulative map](figures/doom-patrol-201-carto.png)](figures/doom-patrol-201-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/doom-patrol-201-data-ge-1080p.webp)](figures/doom-patrol-201-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/doom-patrol-201-data-lt-1080p.webp)](figures/doom-patrol-201-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
