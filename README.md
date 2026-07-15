# From Biomass to Biochemical Yield

## An open research framework for controlled-environment horticulture

**Project ID:** PF-VMB
**Version:** 0.1.0
**Status:** Public research concept and protocol-development repository
**Project lead:** Mathieu EMANE
**Initiative:** MORNYS
**Location:** France

## Project status

This repository documents an independent research initiative currently under protocol development.

No experimental result is claimed or reported at this stage.

This repository is:

* a public scientific overview;
* a versioned record of the research framework;
* a future entry point for protocols, data dictionaries, analysis notebooks and reproducibility materials.

It is not:

* a peer-reviewed publication;
* a completed experimental study;
* a clinical, medical or therapeutic claim;
* a formal preregistration;
* a repository for confidential or proprietary operational information.

## Research objective

The project develops a reproducible framework for evaluating plant production according to the quantity of targeted biochemical compounds produced, rather than according to harvested biomass alone.

The central question is:

> Can plant production in a controlled environment be measured and subsequently optimized according to targeted biochemical yield, while explicitly accounting for biomass, energy, water, uncertainty and physiological constraints?

## Core measurement model

For each target analyte *i*:

**Yᵢ = Bᴅᴡ × Cᵢ,ᴅᴡ**

Where:

* **Yᵢ** is the total biochemical yield of analyte *i*;
* **Bᴅᴡ** is harvested dry biomass;
* **Cᵢ,ᴅᴡ** is the concentration of analyte *i* expressed on a dry-weight basis.

Biomass, analyte concentration and biochemical yield will remain available as separate variables.

No composite score will replace the underlying measurements.

## Initial pilot scope

### Controlled-environment platform

* existing controlled-environment horticultural platform;
* experimental footprint: approximately 1.5 × 1.5 m;
* environmental sensing for climate, light, carbon dioxide and root-zone conditions;
* versioned actions, measurements and human interventions.

### Biological system

* species: *Lactuca sativa*;
* primary cultivar: ‘Rouxai’;
* validation cultivar considered for a later phase: ‘Red Salad Bowl’;
* primary harvested organ: whole edible aerial shoot, homogenized;
* harvest defined by a standardized phenological stage.

### Initial experimental contrast

The first pilot is designed around one bounded and attributable comparison:

* supplemental blue light;
* versus supplemental red light;
* using an explicitly matched photon-dose design.

The historical multi-phase horticultural programme is not treated as the lettuce protocol.

## Candidate analytical panel

### Primary endpoint

* total anthocyanins.

### Secondary endpoints

* total vitamin C;
* nitrate.

### Exploratory analytes

* chicoric acid;
* chlorogenic acid;
* lutein;
* beta-carotene.

The final analytical panel remains conditional on laboratory access, validated methods, quality controls and available budget.

## Environmental and resource variables

Candidate variables include:

* PPFD and DLI;
* air and leaf temperature;
* relative humidity and VPD;
* canopy carbon dioxide concentration;
* substrate water status;
* irrigation events and volumes;
* energy consumption;
* water consumption.

Installed, calibrated and proposed variables will be explicitly distinguished.

## Research roadmap

### Phase 1 — Measurement validity

Define sampling, dry biomass, analytical methods, uncertainty and quality control.

### Phase 2 — Biological pilot

Test whether bounded light treatments produce detectable differences in biomass, concentration and biochemical yield.

### Phase 3 — Predictive modelling

Model relationships between environmental trajectories, plant responses and biochemical outputs.

### Phase 4 — Constrained control

Evaluate rule-based control and model predictive control under a common safety envelope.

### Phase 5 — Safe RL–MPC research

Evaluate whether bounded reinforcement learning can adapt MPC parameters without overriding hard biological or physical constraints.

The superiority of RL–MPC is a research hypothesis, not an established result.

## Reproducibility principles

The project is designed around:

* immutable raw data;
* versioned protocols and configurations;
* explicit units and data dictionaries;
* calibrated sensors;
* traceable exclusions and transformations;
* tested analysis notebooks;
* separation of exploratory and confirmatory analyses;
* logging of AI prompts, outputs, tools and human validations;
* publication of negative or inconclusive findings when scientifically relevant.

## Experimental limitations

The current platform contains a single controlled environment.

Plants sharing the same environmental treatment are not automatically independent replications of that treatment.

Claims concerning causal effects, controller superiority, generalization or industrial scalability will therefore be limited to what the experimental unit and replication design support.

## Public disclosure boundary

This repository contains only non-confidential scientific framing.

It excludes:

* proprietary cultivation recipes;
* detailed substrate and fertigation formulations;
* security-sensitive automation configurations;
* private identities or contact details;
* unpublished partner information;
* unsupported performance claims.

See `PUBLIC_SCOPE.md`.

## Contributors

**Mathieu EMANE**
Project lead — scientific framing, controlled-environment horticulture, systems design and AI-assisted research methodology.

Additional contributors will be listed only after role confirmation and explicit consent.

## Contact

Contact: mornys@outlook.fr

## Citation

Citation metadata are provided in `CITATION.cff`.

## Current repository contents

* `README.md` — public project overview;
* `PUBLIC_SCOPE.md` — disclosure perimeter and exclusions;
* `CITATION.cff` — machine-readable citation metadata.

## Version notice

Version 0.1.0 records the public scientific framing of the project.

Definitions, hypotheses, endpoints and protocols may evolve through explicit version changes and documented revisions.
