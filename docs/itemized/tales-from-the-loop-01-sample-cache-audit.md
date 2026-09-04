---
layout: default
title: "tales-from-the-loop-01 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# tales-from-the-loop-01 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Tales From The Loop |
| Collection key | `tales-from-the-loop-01` |
| imdb_id | [tt8741290](https://www.imdb.com/title/tt8741290/) |
| wikipedia_url | [Tales from the Loop](https://en.wikipedia.org/wiki/Tales_from_the_Loop) |
| Sample dates | 2020-04-03-to-2020-06-11 |
| Sample days | 70 |
| BTIH count | 145 |
| Unique BTIH count | 133 |
| Downloaders total | 4,595,568 |
| Uploaders total | 565,208 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-04T03:20:38Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2020-04-03 to 2020-06-11 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Tales From The Loop collection size histogram](figures/tales-from-the-loop-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/tales-from-the-loop-01-downloads-by-week-tales-from-the-loop-01-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![tales-from-the-loop-01 downloads by day](figures/tales-from-the-loop-01-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.82 | 38.00 | 17.82 | 27.89 | 1.90 | 9.31 |

### Cumulative network infrastructure

[![Tales From The Loop cumulative map](figures/tales-from-the-loop-01-carto.png)](figures/tales-from-the-loop-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/tales-from-the-loop-01-data-ge-1080p.webp)](figures/tales-from-the-loop-01-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/tales-from-the-loop-01-data-lt-1080p.webp)](figures/tales-from-the-loop-01-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
