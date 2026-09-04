---
layout: default
title: "control-z-01 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# control-z-01 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Control Z |
| Collection key | `control-z-01` |
| imdb_id | [tt11937662](https://www.imdb.com/title/tt11937662/) |
| wikipedia_url | [Control Z](https://en.wikipedia.org/wiki/Control_Z) |
| Sample dates | 2020-05-22-to-2020-07-30 |
| Sample days | 70 |
| BTIH count | 93 |
| Unique BTIH count | 78 |
| Downloaders total | 531,926 |
| Uploaders total | 152,184 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-04T03:20:38Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2020-05-22 to 2020-07-30 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Control Z collection size histogram](figures/control-z-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/control-z-01-downloads-by-week-control-z-01-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![control-z-01 downloads by day](figures/control-z-01-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 8.17 | 43.34 | 15.80 | 24.14 | 0.88 | 1.17 |

### Cumulative network infrastructure

[![Control Z cumulative map](figures/control-z-01-carto.png)](figures/control-z-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/control-z-01-data-ge-1080p.webp)](figures/control-z-01-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/control-z-01-data-lt-1080p.webp)](figures/control-z-01-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
