# A-Track Repository Structure and Notes

This document describes the proposed repository structure and supporting notes for structuring biodiversity and ecosystem data according to a **Nature Information Pathway (NIP)**, in line with A-Track Deliverables (notably D2.3).

---

## Repository-level folders

### 1. General NIP data structuring
Folder for **general data structuring according to a Nature Information Pathway (NIP)**.

**Purpose**
- User manual
- General use in workshops
- Deliverable tool
- Intended for future public use

---

### 2. Demo-specific material
Folder for **extra demo-specific scripts and example data**.

**Purpose**
- Replicability of deliverable and demo task results  
- Private or limited public use  

---

## Scripts and documentation by NIP step

The following is a **working list of scripts and documents** potentially needed for each step of structuring data according to a NIP (see *A-Track D2.3 outline*).  
These can be filtered into folders later.

---

### Pre-identifying scope
- ENCORE README, reference material, and example use
- Primary data collection notes
- Script to extract non-vegetation classes
- GBIF extraction script (TBD)
- Example datasets:
  - sPlotOpen data + derived features
  - Vegetation map data

---

### Transfer of data
- *Guidelines for habitat mapping reference data* (draft)
- Script for spatial filtering and basic processing of **Pl@ntBERT** output into a mapping-ready format
- Example of filtered output data
- Data inputs including secondary layers
- Example of a ready-to-use habitat map (e.g. GeoPlantNet)
- Links to reference viewers/databases (e.g. Natura 2000, BirdLife)

---

### Applying accounting principles
- Link to **WEED / habitat workflow**

---

### Application-focused transformation of data
- Script to:
  - Create buffers
  - Clip data
  - Extract area per habitat class
  - Link habitat classes to Red List status

---

### Compilation of the nature information set
- Split natural vs. semi-natural habitats
- Calculate change over time (TBD)
- Site condition assessment  
  - *Sibelco condition v2* (draft)
- FRAGSTATS data and scripts (or GUI reference)
- Cross-walking script
- Script to format output tables cleanly

---

## Internal (to be populated)

- *Guidelines for habitat mapping reference data* (draft)
- R scripts for older training data workflows
- R-PlantBERT scripts (internal SharePoint)
- Local WEED project directories (PyCharm / OneDrive)

> **Note**: Internal paths and draft documents should not be exposed in public repositories.
