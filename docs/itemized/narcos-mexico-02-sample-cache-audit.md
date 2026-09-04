---
layout: default
title: "narcos-mexico-02 Sample Cache Audit"
author: "Benjamin De Kosnik <bkoz@gnu.org>"
description: "Cache coverage and visualization audit for one media object."
---

# narcos-mexico-02 sample cache audit

## 1. Media object

| Field | Value |
| --- | --- |
| Media object | Narcos Mexico |
| Collection key | `narcos-mexico-02` |
| imdb_id | [tt8714904](https://www.imdb.com/title/tt8714904/) |
| wikipedia_url | [Narcos: Mexico](https://en.wikipedia.org/wiki/Narcos:_Mexico) |
| Sample dates | 2020-02-13-to-2020-04-22 |
| Sample days | 70 |
| BTIH count | 272 |
| Unique BTIH count | 250 |
| Downloaders total | 4,338,569 |
| Uploaders total | 1,296,853 |
| Data version | `2026-08-05` |
| IP geolocation version | `6:1777968300` |

## 2. Sample coverage report

- Generated: 2026-09-04T03:20:38Z
- Evidence: read-only Day-member stream of the selected cache archive; no raw sample contents were opened
- Required sample span: 2020-02-13 to 2020-04-22 (70 days)
- Cache Day products: 70
- Sparse Day indices: 0
- Post-release Day products: 0

### Sample archive discontinuities

None detected.

## 3. Media objects file size histogram

![Narcos Mexico collection size histogram](figures/narcos-mexico-02-cumulative-detail-btiha-itemized-by-bytes.svg)

## 4. Visualization pass — graphs

### Downloads by week cumulative (normalized start)

<script type="text/javascript" crossorigin="anonymous" id="graph-hover"
	src="../../resources/izzi-graph-hover-txt-polyline-red.js">
</script>

<div class="media-object-audit-week-graph" style="max-width: 100%;">
{% include_relative figures/narcos-mexico-02-downloads-by-week-narcos-mexico-02-week.svg %}
</div>
<style>
.media-object-audit-week-graph svg {
  display: block;
  width: 100%;
  height: auto;
}
</style>

### Downloads by day, Saturday and Sunday in gray

![narcos-mexico-02 downloads by day](figures/narcos-mexico-02-downloads-by-day-day.svg)

## 5. Visualization pass — maps

### Cumulative geographic slices

| Africa | Americas | Asia | Europe | Oceania | Unknown |
| --- | --- | --- | --- | --- | --- |
| 8.16 | 16.28 | 25.36 | 38.81 | 1.33 | 1.47 |

### Cumulative network infrastructure

[![Narcos Mexico cumulative map](figures/narcos-mexico-02-carto.png)](figures/narcos-mexico-02-carto-4k.webp){:target="_blank" rel="noopener"}

### Cumulative data maps

**Cumulative >= 1080p**

[![Cumulative >= 1080p](figures/narcos-mexico-02-data-ge-1080p.webp)](figures/narcos-mexico-02-data-ge-1080p-4k.webp){:target="_blank" rel="noopener"}

**Cumulative < 1080p**

[![Cumulative < 1080p](figures/narcos-mexico-02-data-lt-1080p.webp)](figures/narcos-mexico-02-data-lt-1080p-4k.webp){:target="_blank" rel="noopener"}
