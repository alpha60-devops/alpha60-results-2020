---
layout: default
title: "lovecraft-country-101 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# lovecraft-country-101 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Lovecraft Country |
| Collection key | `lovecraft-country-101` |
| imdb_id | [tt6905686](https://www.imdb.com/title/tt6905686/) |
| wikipedia_url | [Lovecraft Country (TV series)](https://en.wikipedia.org/wiki/Lovecraft_Country_(TV_series)) |
| Sample dates | 2020-08-17-to-2020-10-25 |
| Sample days | 70 |
| BTIH count | 71 |
| Unique BTIH count | 57 |
| Downloaders total | 3,737,859 |
| Uploaders total | 711,972 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Coverage report

- Generated: 2026-09-04T03:20:38Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2020-08-17 to 2020-10-25 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. File sizes histogram *median[lowest, highest]*

![Lovecraft Country collection size histogram](figures/lovecraft-country-101-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/lovecraft-country-101-downloads-by-week-lovecraft-country-101-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![lovecraft-country-101 downloads by day](figures/lovecraft-country-101-downloads-by-day-day.svg)

## 5. Cumulative Maps

<script defer type="text/javascript" crossorigin="anonymous" id="geojson-map"
        src="../../resources/izzi-map-leaflet-geojson-v7.8.js"></script>

<!-- https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2020/refs/heads/main/data/ -->

### <a href="https://raw.githubusercontent.com/alpha60-devops/alpha60-results-2020/refs/heads/main/data/geojson.cumulative/lovecraft-country-101-cumulative-aggregate.geojson.gz" data-map-title="Lovecraft Country — lovecraft-country-101" onclick="leaflet_map_open_window(this.href, this.dataset.mapTitle); return false;" class="table-link" aria-label="Open Lovecraft Country (lovecraft-country-101) cumulative data map in new window" title="Opens interactive map for Lovecraft Country (lovecraft-country-101) data">Swarm Detail</a>

### Geographic Regions

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 4.31 | 40.28 | 15.58 | 23.88 | 2.46 | 7.50 |

### Network infrastructure

[![Lovecraft Country cumulative map](figures/lovecraft-country-101-carto.png)](figures/lovecraft-country-101-carto-4k.webp){:target="_blank" rel="noopener"}

### Resolution >= 1080p

[![Cumulative >= 1080p](figures/lovecraft-country-101-data-ge-1080p.webp)](figures/lovecraft-country-101-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

### Resolution < 1080p

[![Cumulative < 1080p](figures/lovecraft-country-101-data-lt-1080p.webp)](figures/lovecraft-country-101-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
