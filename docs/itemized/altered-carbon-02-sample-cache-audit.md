---
layout: default
title: "altered-carbon-02 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# altered-carbon-02 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Altered Carbon |
| Collection key | `altered-carbon-02` |
| imdb_id | [tt2261227](https://www.imdb.com/title/tt2261227/) |
| wikipedia_url | [Altered Carbon (TV series)](https://en.wikipedia.org/wiki/Altered_Carbon_(TV_series)) |
| Sample dates | 2020-02-28-to-2020-08-27 |
| Sample days | 182 |
| BTIH count | 254 |
| Unique BTIH count | 242 |
| Downloaders total | 13,366,349 |
| Uploaders total | 1,760,330 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-04T03:20:38Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2020-02-28 to 2020-08-27 (182 days)
- Cache Day products: 182
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![Altered Carbon collection size histogram](figures/altered-carbon-02-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/altered-carbon-02-downloads-by-week-altered-carbon-02-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![altered-carbon-02 downloads by day](figures/altered-carbon-02-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2020/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2020/refs/heads/main/data/geojson.cumulative/altered-carbon-02-cumulative-aggregate.geojson.gz" data-map-title="Altered Carbon — altered-carbon-02" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Altered Carbon (altered-carbon-02) cumulative data map in new window" title="Opens interactive map for Altered Carbon (altered-carbon-02) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 4.13 | 36.54 | 18.75 | 27.50 | 1.69 | 8.62 |

### Network infrastructure

[![Altered Carbon cumulative map](figures/altered-carbon-02-carto.png)](figures/altered-carbon-02-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/altered-carbon-02-data-ge-1080p.webp)](figures/altered-carbon-02-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/altered-carbon-02-data-lt-1080p.webp)](figures/altered-carbon-02-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
