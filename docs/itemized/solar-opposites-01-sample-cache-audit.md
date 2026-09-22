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

## 2. Coverage report

- Generated: 2026-09-04T03:20:38Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2020-05-08 to 2020-07-16 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![Solar Opposites collection size histogram](figures/solar-opposites-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

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

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2020/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2020/refs/heads/main/data/geojson.cumulative/solar-opposites-01-cumulative-aggregate.geojson.gz" data-map-title="Solar Opposites — solar-opposites-01" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Solar Opposites (solar-opposites-01) cumulative data map in new window" title="Opens interactive map for Solar Opposites (solar-opposites-01) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 4.55 | 38.62 | 12.92 | 30.38 | 3.58 | 2.50 |

### Network infrastructure

[![Solar Opposites cumulative map](figures/solar-opposites-01-carto.png)](figures/solar-opposites-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/solar-opposites-01-data-ge-1080p.webp)](figures/solar-opposites-01-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/solar-opposites-01-data-lt-1080p.webp)](figures/solar-opposites-01-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
