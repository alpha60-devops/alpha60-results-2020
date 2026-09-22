---
layout: default
title: "japan-sinks Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# japan-sinks sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Japan Sinks |
| Collection key | `japan-sinks` |
| imdb_id | [tt12031040](https://www.imdb.com/title/tt12031040/) |
| wikipedia_url | [Japan Sinks: 2020](https://en.wikipedia.org/wiki/Japan_Sinks:_2020) |
| Sample dates | 2020-07-09-to-2020-09-23 |
| Sample days | 77 |
| BTIH count | 169 |
| Unique BTIH count | 138 |
| Downloaders total | 916,282 |
| Uploaders total | 181,382 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-04T03:20:38Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2020-07-09 to 2020-09-23 (77 days)
- Cache Day products: 77
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![Japan Sinks collection size histogram](figures/japan-sinks-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/japan-sinks-downloads-by-week-japan-sinks-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![japan-sinks downloads by day](figures/japan-sinks-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2020/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2020/refs/heads/main/data/geojson.cumulative/japan-sinks-cumulative-aggregate.geojson.gz" data-map-title="Japan Sinks — japan-sinks" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Japan Sinks (japan-sinks) cumulative data map in new window" title="Opens interactive map for Japan Sinks (japan-sinks) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 1.44 | 48.79 | 18.98 | 23.39 | 1.01 | 3.34 |

### Network infrastructure

[![Japan Sinks cumulative map](figures/japan-sinks-carto.png)](figures/japan-sinks-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/japan-sinks-data-ge-1080p.webp)](figures/japan-sinks-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/japan-sinks-data-lt-1080p.webp)](figures/japan-sinks-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
