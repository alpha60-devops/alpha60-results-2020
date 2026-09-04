# Alpha60 results: year 2020 campaign

This directory holds the in-progress year-2020 Alpha60 results dataset. The
frozen campaign inventory contains 49 media objects at SHA-256
`22b2bcb1a13f83fa284584bd30c215741602b7f4e06371aaf1c7f99c2cb611ec`.

## Campaign inputs

- `txt/year-2020-0-media-objects.txt`: canonical ordered inventory.
- `txt/year-2020-cache-aliases.tsv`: empty alias receipt; every canonical
  key maps directly to its same-named gold cache directory and member key.
- `txt/year-2020-cache-archive-overrides.json`: explicitly reviewed archive
  endpoint selections, if any.
- `txt/year-2020-cache-archive-map.json`: exact archive paths, sizes,
  SHA-256 identities, canonical sample contracts, sparse intervals, and
  byte-balanced ord/eureka ownership.

Cache archives and raw samples are immutable external campaign inputs and are
never committed to this repository. Generated data, figures, audit pages, and
the final checksum/release manifests are added only by the verified campaign
pipeline.
