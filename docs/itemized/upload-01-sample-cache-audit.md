---
layout: default
title: "upload-01 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# upload-01 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Upload |
| Collection key | `upload-01` |
| imdb_id | [tt7826376](https://www.imdb.com/title/tt7826376/) |
| wikipedia_url | [Upload (TV series)](https://en.wikipedia.org/wiki/Upload_(TV_series)) |
| Sample dates | 2020-05-01-to-2020-07-09 |
| Sample days | 70 |
| BTIH count | 171 |
| Unique BTIH count | 158 |
| Downloaders total | 2,513,711 |
| Uploaders total | 846,584 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-04T03:20:38Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2020-05-01 to 2020-07-09 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Upload collection size histogram](figures/upload-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/upload-01-downloads-by-week-upload-01-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![upload-01 downloads by day](figures/upload-01-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 4.31 | 28.82 | 22.68 | 29.05 | 3.59 | 1.12 |

### Cumulative network infrastructure

[![Upload cumulative map](figures/upload-01-carto.png)](figures/upload-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/upload-01-data-ge-1080p.webp)](figures/upload-01-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/upload-01-data-lt-1080p.webp)](figures/upload-01-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
