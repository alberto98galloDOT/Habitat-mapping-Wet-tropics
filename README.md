# Wet Tropics — Habitat Mapping & Conservation Gap Analysis

Interactive web map published via GitHub Pages.

**Live map:** https://alberto98gallodot.github.io/Habitat-mapping/

## Overview
Habitat mapping and conservation gap analysis for Cairns Regional LGA (Queensland), focusing on the Southern Cassowary (*Casuarius casuarius johnsonii*) as an indicator species for the Wet Tropics rainforest ecosystem. Analysis assesses the proportion of Essential Habitat formally protected under Queensland legislation.

## Layers
- **Southern Cassowary Records (n=372)** — verified occurrence records from WildNet/GBIF 2024. 74.5% of records (277/372) fall outside formally protected areas
- **Essential Habitat (VMA 1999)** — habitat classified as Essential under the Vegetation Management Act 1999. Total area within LGA: 103,461 ha — only 8.7% within formally protected areas
- **Protected Areas** — Queensland protected areas (QPWS): National Parks, Conservation Parks and Nature Refuges
- **Wet Tropics World Heritage Area** — UNESCO World Heritage Area inscription 1988, 894,420 ha of tropical rainforest

## Key Findings
- 8.7% of Essential Habitat formally protected (8,990 ha inside protected areas out of 103,461 ha total)
- 74.5% of Southern Cassowary records outside formally protected areas (277 of 372)
- Coastal lowland corridor between Cairns and Innisfail identified as most vulnerable — highest cassowary density, lowest formal protection

## Methodology
Essential Habitat layer sourced from Queensland Spatial (Vegetation Management Act 1999 — MSES). Southern Cassowary occurrence records downloaded from GBIF (species: *Casuarius casuarius johnsonii*, bounding box: Wet Tropics region). Spatial selection in QGIS used to identify cassowary records outside protected area boundaries. Gap analysis compares Essential Habitat extent against Protected Areas and Wet Tropics WHA boundary.

## Data Sources
- Essential Habitat: Queensland Spatial — Vegetation Management Act 1999 (MSES)
- Protected Areas: Queensland Parks and Wildlife Service (QPWS)
- Southern Cassowary records: GBIF / WildNet 2024
- Wet Tropics World Heritage Area: UNESCO / DAFF
- LGA Boundary: Queensland Spatial — Local Government Area Boundaries

## Tools
QGIS 3.44 · QGIS2Web (Leaflet) · GitHub Pages

## Author
Alberto Gallo — GIS Analyst & Urban Planner
Graduate Member, Planning Institute of Australia (PIA)
