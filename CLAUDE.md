# CLAUDE.md - AI Assistant Guide

This document provides guidance for AI assistants working with this repository.

## Repository Overview

**Purpose:** Bulk water infrastructure benchmarking study for Australian pipeline projects, focused on establishing cost benchmarks for large-diameter (≥300mm) bulk water supply pipelines.

**Domain:** Water infrastructure cost estimation, primarily supporting early-stage project scoping and business case development.

**Geographic Focus:** Queensland priority, with broader Australian coverage (VIC, NT, TAS).

**Timeframe:** Projects with construction completed or substantially commenced between 2019-2025.

## Repository Structure

```
water-benchmarked/
├── README.md                              # Project overview and key findings summary
├── CLAUDE.md                              # This file - AI assistant guidance
├── 01_project_research_summaries.md       # Index of individual project research
├── 02_benchmarking_database.md            # Structured dataset with normalised costs
├── 03_research_audit_log.md               # Phase 3: Research quality self-audit
├── 04_analysis_summary.md                 # Statistical analysis and benchmarking guidance
├── 05_analysis_audit_log.md               # Phase 6: Calculations and conclusions audit
├── 06_executive_slide_deck.md             # 8-slide executive presentation (markdown)
├── 07_additional_projects_assessment.md   # Assessment of potential new projects
├── 08_database_improvement_actions.md     # Action register for data quality improvements
└── Input projects/                        # Individual project research files
    ├── 01_fitzroy_to_gladstone_pipeline.md
    ├── 02_haughton_pipeline_stage_1.md
    ├── 03_haughton_pipeline_stage_2.md
    ├── 04_toowoomba_to_warwick_pipeline.md
    ├── 05_mareeba_dimbulah_efficiency.md
    └── 06_east_grampians_rural_pipeline.md
```

## File Naming Conventions

- **Numbered prefixes (01-08):** Sequential deliverables in order of creation/workflow
- **Input projects folder:** Individual project research files, numbered to match their position in the database
- **Lowercase with underscores:** All filenames use snake_case

## Document Types and Purposes

| Document Type | Purpose | Update Frequency |
|--------------|---------|------------------|
| Research summaries | Source-verified project data | When new data emerges |
| Benchmarking database | Normalised cost metrics | When projects added or costs updated |
| Audit logs | Quality assurance records | After each analysis phase |
| Analysis summary | Statistical outputs and guidance | When database changes significantly |
| Actions register | Track data gaps and improvements | Ongoing as work progresses |
| Executive deck | Stakeholder communication | When key findings change |

## Key Conventions

### Cost Data

- **Currency:** All normalised costs expressed in AUD 2024 (Real)
- **Nominal costs:** Original costs as stated, with cost year noted
- **Normalisation method:** ABS Producer Price Index for Heavy & Civil Engineering Construction
- **Cost metric:** Primary metric is $/km (cost per kilometre)

### Data Quality Ratings

| Rating | Definition |
|--------|------------|
| **A** | Verified from multiple authoritative sources |
| **B** | Single authoritative source |
| **C** | Estimated/inferred from available data |
| **D** | Significant uncertainty |

### Source Hierarchy

1. Government ministerial statements and budget papers (highest)
2. Infrastructure authority official project pages
3. Infrastructure Australia assessments
4. National Water Grid Authority database
5. Contractor case studies
6. Media reports (lowest - use for leads only)

### Project Classification

- **Core sample:** Large-diameter (≥600mm) municipal bulk supply - full weight in analysis
- **Supplementary sample:** Rural/irrigation projects - reference only, noted with asterisk

### Diameter Classes

| Class | Range | Notes |
|-------|-------|-------|
| Small | 300-450mm | Limited sample data |
| Medium | 450-750mm | Primary TWP reference |
| Large | 750-1200mm | FGP reference |
| Very Large | >1200mm | Haughton references |

## Workflow Phases

The study follows a structured methodology:

1. **Project Identification** - Identify projects meeting scope criteria
2. **Research** - Gather data from authoritative sources
3. **Research Audit** - Self-audit research quality (03_research_audit_log.md)
4. **Database Creation** - Structure and normalise data (02_benchmarking_database.md)
5. **Analysis** - Calculate metrics and identify drivers (04_analysis_summary.md)
6. **Analysis Audit** - Verify calculations and conclusions (05_analysis_audit_log.md)
7. **Reporting** - Prepare executive outputs (06_executive_slide_deck.md)
8. **Continuous Improvement** - Track actions and expansions (07, 08 files)

## Working with the Database

### Adding a New Project

1. Create individual research file in `Input projects/` folder
2. Follow existing file structure (Project Identification, Technical Specs, Costs, Sources, Data Quality)
3. Update `01_project_research_summaries.md` index
4. Add to `02_benchmarking_database.md` tables with normalised costs
5. Update `04_analysis_summary.md` if statistics change significantly
6. Add to `08_database_improvement_actions.md` if data gaps exist

### Updating Cost Data

1. Document source and date of new information
2. Update nominal cost in research file
3. Recalculate normalised cost using current indices
4. Update $/km metrics in database
5. Verify internal consistency (audit log methodology)

### Cost Normalisation Formula

```
Normalised Cost = Nominal Cost × (Target Index / Source Year Index)

Where: Target Index = 132.5 (2024 base)
       Source Year Index from Table 1 in 02_benchmarking_database.md
```

## Key Metrics Reference

### Current Benchmarking Ranges (AUD 2024)

| Diameter Class | Low $/km | Mid $/km | High $/km |
|----------------|----------|----------|-----------|
| Medium (450-750mm) | $4.0M | $5.5M | $7.5M |
| Large (750-1200mm) | $7.0M | $9.0M | $12.0M |
| Very Large (>1200mm) | $8.0M | $10.0M | $15.0M |

### Common Adjustment Factors

| Factor | Adjustment |
|--------|------------|
| Greenfield terrain | +20-40% |
| Hilly terrain | +15-30% |
| Treatment plant inclusion | +5-15% |
| Remote location | +10-25% |

## Important Limitations to Communicate

When generating outputs or answering questions, always acknowledge:

1. **Small sample size** (n=4-6 projects)
2. **Geographic concentration** (QLD/VIC only in core sample)
3. **Time period volatility** (2020-2024 saw 25%+ cost escalation)
4. **Scope variation** (some projects include WTP, reservoirs; others pipeline-only)
5. **Appropriate use cases** - early scoping yes, tender evaluation no

## Common Tasks

### Answering benchmarking questions

1. Identify relevant diameter class
2. Cite specific comparable projects from database
3. Apply appropriate adjustment factors
4. State confidence level and limitations
5. Reference data quality ratings

### Updating the action register

1. Assign priority (P1-P4) based on definitions in 08 file
2. Identify contact and source documents needed
3. Link to relevant database entries
4. Track status (Open/In Progress/Complete)

### Preparing stakeholder communications

1. Use executive deck (06) as template
2. Keep messaging consistent with stated confidence levels
3. Always include limitations and appropriate use guidance
4. Cite sources from research files

## Technical Notes

### File Format

- All documents are Markdown (.md)
- Tables use GitHub-flavored markdown pipe syntax
- ASCII diagrams used for visualisations in executive deck
- CSV export format provided in database file

### Project IDs

| ID | Project |
|----|---------|
| FGP | Fitzroy to Gladstone Pipeline |
| HP1 | Haughton Pipeline Stage 1 |
| HP2 | Haughton Pipeline Stage 2 |
| TWP | Toowoomba to Warwick Pipeline |
| MDW | Mareeba-Dimbulah WSS Efficiency |
| EGR | East Grampians Rural Pipeline |

### Index Values (Base 2019 = 100)

| Year | Index | Factor to 2024 |
|------|-------|----------------|
| 2017 | 96.0* | 1.380 |
| 2019 | 100.0 | 1.325 |
| 2020 | 101.5 | 1.305 |
| 2021 | 105.7 | 1.254 |
| 2022 | 114.5 | 1.157 |
| 2023 | 124.0 | 1.069 |
| 2024 | 132.5 | 1.000 |

*Extrapolated

## Contact and Attribution

- **Study:** Water Infrastructure Benchmarking Study
- **Date:** January 2026
- **Version:** 1.0

When referencing this study, attribute as: "Water Infrastructure Benchmarking Study, January 2026"
