---
layout: default
title: "devs-108 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# devs-108 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Devs |
| Collection key | `devs-108` |
| imdb_id | [tt8134186](https://www.imdb.com/title/tt8134186/) |
| wikipedia_url | [Devs (TV series)](https://en.wikipedia.org/wiki/Devs_(TV_series)) |
| Sample dates | 2020-04-16-to-2020-06-24 |
| Sample days | 70 |
| BTIH count | 56 |
| Unique BTIH count | 45 |
| Downloaders total | 1,769,813 |
| Uploaders total | 385,457 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-04T03:20:38Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2020-04-16 to 2020-06-24 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![Devs collection size histogram](figures/devs-108-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/devs-108-downloads-by-week-devs-108-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![devs-108 downloads by day](figures/devs-108-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2020/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2020/refs/heads/main/data/geojson.cumulative/devs-108-cumulative-aggregate.geojson.gz" data-map-title="Devs — devs-108" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Devs (devs-108) cumulative data map in new window" title="Opens interactive map for Devs (devs-108) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.76 | 35.37 | 14.70 | 31.97 | 2.59 | 6.72 |

### Network infrastructure

[![Devs cumulative map](figures/devs-108-carto.png)](figures/devs-108-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/devs-108-data-ge-1080p.webp)](figures/devs-108-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/devs-108-data-lt-1080p.webp)](figures/devs-108-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
