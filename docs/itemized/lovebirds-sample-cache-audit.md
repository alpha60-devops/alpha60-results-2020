---
layout: default
title: "lovebirds Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# lovebirds sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | The Lovebirds |
| Collection key | `lovebirds` |
| imdb_id | [tt8851668](https://www.imdb.com/title/tt8851668/) |
| wikipedia_url | [The Lovebirds (2020 film)](https://en.wikipedia.org/wiki/The_Lovebirds_(2020_film)) |
| Sample dates | 2020-05-22-to-2020-07-30 |
| Sample days | 70 |
| BTIH count | 92 |
| Unique BTIH count | 64 |
| Downloaders total | 2,382,093 |
| Uploaders total | 895,996 |
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

![The Lovebirds collection size histogram](figures/lovebirds-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/lovebirds-downloads-by-week-lovebirds-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![lovebirds downloads by day](figures/lovebirds-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 25.45 | 24.37 | 17.06 | 21.64 | 1.99 | 0.52 |

### Cumulative network infrastructure

[![The Lovebirds cumulative map](figures/lovebirds-carto.png)](figures/lovebirds-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/lovebirds-data-ge-1080p.webp)](figures/lovebirds-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/lovebirds-data-lt-1080p.webp)](figures/lovebirds-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
