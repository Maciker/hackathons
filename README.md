# Hackathon Projects

An index of my geospatial projects for hackathons and technical experiments. Each project has its own repository, which is the source of truth for its code, roadmap, evaluation, and current status.

## Projects

### Spatial ML Benchmark

A TypeScript-first benchmark for comparing a majority baseline with a JavaScript Random Forest under random and spatial evaluation.

**Current state:** The balanced-accuracy kernel and a known-result test are in place. Dataset, features, folds, model adapter, experiment runner, and map remain on the roadmap.

[Open the Spatial ML Benchmark repository](https://github.com/Maciker/spatial-ml-benchmark)

### Geospatial Quality Explorer

A TypeScript application for validating a bounded vector dataset and reviewing traceable findings through CLI, API, browser, and QGIS workflows.

**Current state:** The repository includes a licensed GeoJSON fixture and documentation for its vector contracts, demo, CLI, API, and QGIS review.

[Open the Geospatial Quality Explorer repository](https://github.com/Maciker/geospatial-quality-explorer)

### Territorial Change Monitor

An offline TypeScript MVP that compares a bounded pair of Sentinel-2 observations, masks invalid pixels, and reports candidate spectral change with provenance.

**Current state:** It runs against recorded fixtures and provides a local map report. It does not infer the cause of a detected change.

[Open the Territorial Change Monitor repository](https://github.com/Maciker/territorial-change-monitor)

## Approach

I use TypeScript across the application, CLI, and API wherever practical. Each project keeps its own requirements, workflow, and evaluation. The reusable development workflow is maintained in [agent-workflow-code-ts](https://github.com/Maciker/agent-workflow-code-ts).
