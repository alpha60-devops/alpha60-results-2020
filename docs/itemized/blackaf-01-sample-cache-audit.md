---
layout: default
title: "blackaf-01 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# blackaf-01 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | #blackAF |
| Collection key | `blackaf-01` |
| imdb_id | [tt10311562](https://www.imdb.com/title/tt10311562/) |
| wikipedia_url | [BlackAF](https://en.wikipedia.org/wiki/BlackAF) |
| Sample dates | 2020-04-18-to-2020-05-29 |
| Sample days | 42 |
| BTIH count | 82 |
| Unique BTIH count | 76 |
| Downloaders total | 974,160 |
| Uploaders total | 57,593 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-04T03:20:38Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2020-04-18 to 2020-05-29 (42 days)
- Cache Day products: 42
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![#blackAF collection size histogram](figures/blackaf-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/blackaf-01-downloads-by-week-blackaf-01-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![blackaf-01 downloads by day](figures/blackaf-01-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2020/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2020/refs/heads/main/data/geojson.cumulative/blackaf-01-cumulative-aggregate.geojson.gz" data-map-title="#blackAF — blackaf-01" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open #blackAF (blackaf-01) cumulative data map in new window" title="Opens interactive map for #blackAF (blackaf-01) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 7.33 | 38.48 | 16.70 | 19.90 | 1.31 | 10.50 |

### Network infrastructure

[![#blackAF cumulative map](figures/blackaf-01-carto.png)](figures/blackaf-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/blackaf-01-data-ge-1080p.webp)](figures/blackaf-01-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/blackaf-01-data-lt-1080p.webp)](figures/blackaf-01-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
