# ExifTool Cookbook

<!-- ZQM-START -->
<!-- markdownlint-disable MD033 -->
<p align="center">
  <strong>ZQM Computing — Geospatial Engineering & Scientific Computing</strong><br>
  <a href="https://github.com/ZQM-Computing">ZQM Computing</a>
</p>
<!-- markdownlint-enable MD033 -->
<!-- ZQM-END -->

![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

A **ExifTool cookbook** — metadata reading and writing from the command line. Second-tier OSINT tool in the wave-8 set. Patterns are planned from the design, not yet from fleet runs. It is intended for Practitioners who read, compare, and clean file metadata in bulk. Validate each pattern against your own data, software versions, and operating environment before adopting it.

## Repository role and status

**Status:** Active, public — seeding. Pattern passes land in follow-up work from fleet-verified setups; the tables below list what is planned, not what is already written.

**What this repository is:** ExifTool patterns — see the table below.

**What it contributes:** Part of the ZQM Computing geospatial portfolio. Intended to provide geospatial data feeds (satellite imagery, weather, routing, geocoding) for the ZQM game platform. The umbrella index for the series is [geospatial-cookbooks](https://github.com/ZQM-Computing/geospatial-cookbooks).

**Standing:** This repository is maintained independently. Automated checks cover only the paths and environments configured in its workflows; they do not establish production readiness or operational certification.

## Who this is for

Practitioners who read, compare, and clean file metadata in bulk.

## Prerequisites

- ExifTool
- Sample image and document files
- Bash or PowerShell

## Patterns (planned)

| # | Example | What it will demonstrate |
|---|---------|--------------------------|
| 01 | `01-read-metadata` | Reading metadata from images and documents |
| 02 | `02-batch-ops` | Batch reads across directories with JSON output |
| 03 | `03-write-strip` | Writing tags and stripping sensitive metadata |
| 04 | `04-geo-tags` | GPS tags: reading coordinates from photo metadata |

## Repository layout

```text
exiftool-cookbook/
├── examples/          # pattern passes, landing in follow-up work
├── README.md
└── LICENSE
```

## Roadmap

- First pattern pass: the first two table rows
- Second pass: the remaining rows, from fleet-verified setups

## Contributing

A contributing guide lands with the first pattern pass. Report security issues to <zqmcomputing@gmail.com> — please do not open a public issue for those.

## More from this series

- [scrapy-cookbook](https://github.com/ZQM-Computing/scrapy-cookbook) — Polite web scraping spiders, pipelines, and exports
- [waybackpy-cookbook](https://github.com/ZQM-Computing/waybackpy-cookbook) — Wayback Machine queries and archiving from Python
- [cog-cookbook](https://github.com/ZQM-Computing/cog-cookbook) — Cloud Optimized GeoTIFF creation, validation, TiTiler serving
