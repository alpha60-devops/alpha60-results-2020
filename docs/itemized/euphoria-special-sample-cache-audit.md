---
layout: default
title: "euphoria-special Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# euphoria-special sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Euphoria Special |
| Collection key | `euphoria-special` |
| imdb_id | [tt8772296](https://www.imdb.com/title/tt8772296/) |
| wikipedia_url | [Euphoria (American TV series)](https://en.wikipedia.org/wiki/Euphoria_(American_TV_series)) |
| Sample dates | 2020-12-05-to-2021-03-19 |
| Sample days | 105 |
| BTIH count | 127 |
| Unique BTIH count | 94 |
| Downloaders total | 1,619,637 |
| Uploaders total | 638,922 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-04T03:20:38Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2020-12-05 to 2021-03-19 (105 days)
- Cache Day products: 105
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Euphoria Special collection size histogram](figures/euphoria-special-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/euphoria-special-downloads-by-week-euphoria-special-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![euphoria-special downloads by day](figures/euphoria-special-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 8.26 | 37.21 | 13.33 | 30.42 | 1.84 | 0.80 |

### Cumulative network infrastructure

[![Euphoria Special cumulative map](figures/euphoria-special-carto.png)](figures/euphoria-special-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/euphoria-special-data-ge-1080p.webp)](figures/euphoria-special-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/euphoria-special-data-lt-1080p.webp)](figures/euphoria-special-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
