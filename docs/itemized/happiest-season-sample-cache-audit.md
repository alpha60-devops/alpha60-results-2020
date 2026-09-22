---
layout: default
title: "happiest-season Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# happiest-season sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Happiest Season |
| Collection key | `happiest-season` |
| imdb_id | [tt8522006](https://www.imdb.com/title/tt8522006/) |
| wikipedia_url | [Happiest Season](https://en.wikipedia.org/wiki/Happiest_Season) |
| Sample dates | 2020-11-25-to-2021-02-02 |
| Sample days | 70 |
| BTIH count | 103 |
| Unique BTIH count | 64 |
| Downloaders total | 2,426,050 |
| Uploaders total | 889,369 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-04T03:20:38Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2020-11-25 to 2021-02-02 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![Happiest Season collection size histogram](figures/happiest-season-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/happiest-season-downloads-by-week-happiest-season-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![happiest-season downloads by day](figures/happiest-season-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2020/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2020/refs/heads/main/data/geojson.cumulative/happiest-season-cumulative-aggregate.geojson.gz" data-map-title="Happiest Season — happiest-season" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Happiest Season (happiest-season) cumulative data map in new window" title="Opens interactive map for Happiest Season (happiest-season) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 11.10 | 25.54 | 22.05 | 28.65 | 3.46 | 0.70 |

### Network infrastructure

[![Happiest Season cumulative map](figures/happiest-season-carto.png)](figures/happiest-season-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/happiest-season-data-ge-1080p.webp)](figures/happiest-season-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/happiest-season-data-lt-1080p.webp)](figures/happiest-season-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
