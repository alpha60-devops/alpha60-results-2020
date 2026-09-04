---
layout: default
title: "hamilton Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# hamilton sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Hamilton |
| Collection key | `hamilton` |
| imdb_id | [tt8503618](https://www.imdb.com/title/tt8503618/) |
| wikipedia_url | [Hamilton (2020 film)](https://en.wikipedia.org/wiki/Hamilton_(2020_film)) |
| Sample dates | 2020-07-03-to-2020-12-31 |
| Sample days | 182 |
| BTIH count | 80 |
| Unique BTIH count | 49 |
| Downloaders total | 6,886,446 |
| Uploaders total | 3,082,728 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-04T03:20:38Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2020-07-03 to 2020-12-31 (182 days)
- Cache Day products: 182
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Hamilton collection size histogram](figures/hamilton-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/hamilton-downloads-by-week-hamilton-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![hamilton downloads by day](figures/hamilton-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 5.88 | 31.41 | 26.20 | 20.47 | 2.51 | 0.89 |

### Cumulative network infrastructure

[![Hamilton cumulative map](figures/hamilton-carto.png)](figures/hamilton-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/hamilton-data-ge-1080p.webp)](figures/hamilton-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/hamilton-data-lt-1080p.webp)](figures/hamilton-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
