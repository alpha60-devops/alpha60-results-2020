---
layout: default
title: "bojack-horseman-06 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# bojack-horseman-06 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | BoJack Horseman |
| Collection key | `bojack-horseman-06` |
| imdb_id | [tt3398228](https://www.imdb.com/title/tt3398228/) |
| wikipedia_url | [BoJack Horseman](https://en.wikipedia.org/wiki/BoJack_Horseman) |
| Sample dates | 2020-01-31-to-2020-04-09 |
| Sample days | 70 |
| BTIH count | 142 |
| Unique BTIH count | 134 |
| Downloaders total | 3,952,222 |
| Uploaders total | 220,893 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-04T03:20:38Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2020-01-31 to 2020-04-09 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![BoJack Horseman collection size histogram](figures/bojack-horseman-06-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/bojack-horseman-06-downloads-by-week-bojack-horseman-06-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![bojack-horseman-06 downloads by day](figures/bojack-horseman-06-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 2.29 | 35.90 | 19.84 | 26.76 | 1.43 | 10.72 |

### Cumulative network infrastructure

[![BoJack Horseman cumulative map](figures/bojack-horseman-06-carto.png)](figures/bojack-horseman-06-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/bojack-horseman-06-data-ge-1080p.webp)](figures/bojack-horseman-06-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/bojack-horseman-06-data-lt-1080p.webp)](figures/bojack-horseman-06-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
