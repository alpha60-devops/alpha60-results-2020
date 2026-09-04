---
layout: default
title: "high-fidelity-01 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# high-fidelity-01 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | High Fidelity |
| Collection key | `high-fidelity-01` |
| imdb_id | [tt8577458](https://www.imdb.com/title/tt8577458/) |
| wikipedia_url | [High Fidelity (TV series)](https://en.wikipedia.org/wiki/High_Fidelity_(TV_series)) |
| Sample dates | 2020-02-14-to-2020-08-13 |
| Sample days | 182 |
| BTIH count | 206 |
| Unique BTIH count | 200 |
| Downloaders total | 9,477,456 |
| Uploaders total | 886,965 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-04T03:20:38Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2020-02-14 to 2020-08-13 (182 days)
- Cache Day products: 182
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![High Fidelity collection size histogram](figures/high-fidelity-01-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/high-fidelity-01-downloads-by-week-high-fidelity-01-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![high-fidelity-01 downloads by day](figures/high-fidelity-01-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 3.53 | 39.75 | 17.62 | 25.88 | 1.59 | 9.40 |

### Cumulative network infrastructure

[![High Fidelity cumulative map](figures/high-fidelity-01-carto.png)](figures/high-fidelity-01-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/high-fidelity-01-data-ge-1080p.webp)](figures/high-fidelity-01-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/high-fidelity-01-data-lt-1080p.webp)](figures/high-fidelity-01-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
