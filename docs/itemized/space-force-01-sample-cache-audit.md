---
layout: default
title: "space-force-01 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# space-force-01 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Space Force |
| Collection key | `space-force-01` |
| imdb_id | [tt9612516](https://www.imdb.com/title/tt9612516/) |
| wikipedia_url | [Space Force (TV series)](https://en.wikipedia.org/wiki/Space_Force_(TV_series)) |
| Sample dates | 2020-05-29-to-2020-07-02 |
| Sample days | 35 |
| BTIH count | 181 |
| Unique BTIH count | 178 |
| Downloaders total | 1,587,181 |
| Uploaders total | 635,936 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-04T03:20:38Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2020-05-29 to 2020-07-02 (35 days)
- Cache Day products: 34
- Sparse Day indices: 1
- Post-release Day products: 0

### Sample archive discontinuities

- missing Day index 8: `2020-06-05`

## 3. Media objects file size histogram

![Space Force collection size histogram](figures/space-force-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/space-force-01-downloads-by-week-space-force-01-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![space-force-01 downloads by day](figures/space-force-01-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 7.65 | 26.33 | 17.24 | 28.04 | 3.38 | 0.71 |

### Cumulative network infrastructure

[![Space Force cumulative map](figures/space-force-01-carto.png)](figures/space-force-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/space-force-01-data-ge-1080p.webp)](figures/space-force-01-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/space-force-01-data-lt-1080p.webp)](figures/space-force-01-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
