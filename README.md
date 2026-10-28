# Geospatial Tile Server

Vector tile service that turns PostGIS tables into Mapbox Vector Tiles on the
fly, with caching, zoom-level simplification and per-layer access control.

**Planned stack:** Go · PostGIS · MVT · Redis

> **Status: design phase.** This repository holds the technical
> documentation; implementation has not started yet.

## Documentation

All documentation lives in [`1—Documentation/`](1—Documentation/README.md):
[Technical documentation (PDF)](1—Documentation/Geospatial-Tile-Server-Technical-Docs.pdf).

## What the documentation covers

1. Introduction
2. Architecture
3. Request lifecycle
4. Tile addressing
5. MVT generation
6. Zoom-level simplification
7. Caching
8. Access control
9. Configuration
10. HTTP API
11. Data preparation
12. Deployment
13. Performance tuning
14. Observability
15. Testing
16. Security considerations
17. Troubleshooting
