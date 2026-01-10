# Bulk Water Pipeline Benchmarking Database

**Version:** 1.0
**Date:** January 2026
**Currency Base:** AUD 2024 (Real)

---

## Cost Normalisation Methodology

### Construction Cost Escalation Index
Based on ABS Producer Price Index for Heavy and Civil Engineering Construction and Infrastructure Australia methodology:

| Period | Index (Base 2019 = 100) | Cumulative Change |
|--------|------------------------|-------------------|
| 2019 | 100.0 | - |
| 2020 | 101.5 | +1.5% |
| 2021 | 105.7 | +5.7% |
| 2022 | 114.5 | +14.5% |
| 2023 | 124.0 | +24.0% |
| 2024 | 132.5 | +32.5% |

**Note:** Civil/engineering construction costs increased approximately 21.3% between December 2019 and March 2024 per ABS data. Index above includes full year estimates.

### Adjustment Factors Applied
- Costs stated in pre-2024 dollars adjusted using index above
- All normalised costs expressed in AUD 2024 (real)

---

## Benchmarking Database - Core Projects

### Table 1: Project Identification

| ID | Project Name | State | Delivery Authority | Construction Contractor | Delivery Model |
|----|--------------|-------|-------------------|------------------------|----------------|
| FGP | Fitzroy to Gladstone Pipeline | QLD | GAWB | McConnell Dowell BMD JV | ECI + D&C |
| HP1 | Haughton Pipeline Stage 1 | QLD | Townsville City Council | Various | Traditional |
| HP2 | Haughton Pipeline Stage 2 | QLD | Townsville City Council | BMD (main), Iplex (pipe) | Traditional |
| TWP | Toowoomba to Warwick Pipeline | QLD | Seqwater | TBA (procurement 2025) | Head Contractor |
| MDW | Mareeba-Dimbulah WSS Efficiency | QLD | Sunwater | Sunwater delivery | Direct Delivery |
| EGR | East Grampians Rural Pipeline | VIC | GWMWater | Mitchell Water | Traditional |

---

### Table 2: Technical Specifications

| ID | Length (km) | Diameter (mm) | Diameter Class | Pipe Material | Capacity (ML/day) | Annual Capacity (ML) |
|----|-------------|---------------|----------------|---------------|-------------------|---------------------|
| FGP | 117.0 | 1,000 | Large (≥900mm) | Steel/Concrete | 82 | 30,000 |
| HP1 | 36.0 | 1,800 | Very Large (≥1500mm) | GRP | 119* | 43,000* |
| HP2 | 28.2 | 1,800 | Very Large (≥1500mm) | GRP | 356** | 130,000** |
| TWP | 111.0 | 350-600 | Medium (300-600mm) | Various | 7-10 | 2,500-3,700 |
| MDW | 14.0 | <300*** | Small (<300mm) | Various | N/A | N/A |
| EGR | 130.0**** | 100-450 | Small-Medium | Various | N/A | 1,400 |

*Combined system capacity
**Combined Stage 1+2 system capacity
***Irrigation pipeline, diameter not specified
****Trunk mains only; excludes 470km distribution

---

### Table 3: Cost Data - Nominal

| ID | Total Cost (Nominal $M) | Cost Year | Development Cost ($M) | Construction Cost ($M) | Contingency ($M) |
|----|------------------------|-----------|----------------------|----------------------|------------------|
| FGP | $983.0 | 2023 | Est. $50-80* | Est. $850-900* | Included |
| HP1 | $215.0 | 2017 | Included | Included | Included |
| HP2 | $274.0 (revised) | 2021 | Est. $15-20* | Est. $235-250* | Included |
| HP2 | $420.0 (outturn est.) | 2025 | - | - | - |
| TWP | $370.0 (mid-est.) | 2023 | $19.3 (feasibility) | Est. $330-350* | Included |
| TWP | $467.0 (revised) | 2024 | - | - | - |
| MDW | $32.5 | 2021 | Included | Included | Included |
| EGR | $64.0 (total funding) | 2024 | Included | Included | Included |

*Estimated breakdown based on typical industry proportions; not verified

---

### Table 4: Cost Data - Normalised to AUD 2024

| ID | Nominal Cost ($M) | Cost Year | Escalation Factor | Normalised Cost ($M AUD 2024) |
|----|------------------|-----------|-------------------|------------------------------|
| FGP | $983.0 | 2023 | 1.069 | $1,050.8 |
| HP1 | $215.0 | 2017 | 1.380* | $296.7 |
| HP2 | $274.0 | 2021 | 1.254 | $343.6 |
| HP2 (outturn) | $420.0 | 2025 | 0.962** | $404.0 |
| TWP (mid) | $370.0 | 2023 | 1.069 | $395.5 |
| TWP (revised) | $467.0 | 2024 | 1.000 | $467.0 |
| MDW | $32.5 | 2021 | 1.254 | $40.8 |
| EGR | $64.0 | 2024 | 1.000 | $64.0 |

*Extrapolated from 2019 base
**Deflated from 2025 estimate

---

### Table 5: Unit Cost Metrics - Normalised (AUD 2024)

| ID | Normalised Cost ($M) | Length (km) | $/km ($M) | Diameter (mm) | $/km/100mm Dia ($M) |
|----|---------------------|-------------|-----------|---------------|---------------------|
| FGP | $1,050.8 | 117.0 | $8.98 | 1,000 | $0.898 |
| HP1 | $296.7 | 36.0 | $8.24 | 1,800 | $0.458 |
| HP2 (budget) | $343.6 | 28.2 | $12.18 | 1,800 | $0.677 |
| HP2 (outturn) | $404.0 | 28.2 | $14.33 | 1,800 | $0.796 |
| TWP (mid) | $395.5 | 111.0 | $3.56 | 475* | $0.750 |
| TWP (revised) | $467.0 | 111.0 | $4.21 | 475* | $0.886 |
| MDW | $40.8 | 14.0 | $2.91 | 200** | $1.457 |
| EGR | $64.0 | 130.0 | $0.49 | 275** | $0.179 |

*Average of 350-600mm range
**Estimated typical diameter

---

### Table 6: Complexity and Context Factors

| ID | Terrain | Remoteness | River Crossings | Tunnelling | Treatment Plant | Pump Stations | Special Features |
|----|---------|------------|-----------------|------------|-----------------|---------------|------------------|
| FGP | Rural/Agricultural | Regional | Yes | No | Yes | Yes | Reservoirs (2x50ML) |
| HP1 | Flat/Agricultural | Regional | Minor | No | No | Yes | Channel connection |
| HP2 | Greenfield | Regional | Minor | No | No | Yes | 6km access roads |
| TWP | Hilly/Agricultural | Regional | Multiple | No | Yes | Yes | Variable terrain |
| MDW | Existing corridor | Rural | Within scheme | No | No | No | Efficiency retrofit |
| EGR | Rural/Agricultural | Remote Rural | Minor | No | No | Yes (4) | Solar installations |

---

### Table 7: Data Quality Scores

**Quality Rating Scale:**
- **A:** Verified from multiple authoritative sources
- **B:** Single authoritative source
- **C:** Estimated/inferred from available data
- **D:** Significant uncertainty

| ID | Total Cost | Length | Diameter | Timeline | Breakdown | Overall |
|----|------------|--------|----------|----------|-----------|---------|
| FGP | A | A | A | A | C | A |
| HP1 | A | A | A | A | C | A |
| HP2 | B | A | A | B | C | B |
| TWP | C | A | B | C | C | C |
| MDW | A | A | C | A | C | B |
| EGR | B | B | B | B | C | B |

---

### Table 8: Source References

| ID | Primary Sources |
|----|-----------------|
| FGP | GAWB website; Qld Ministerial Statements; McConnell Dowell; DLGWV |
| HP1 | Townsville City Council; Infrastructure Australia |
| HP2 | Townsville City Council; Infrastructure Australia; Iplex; Federal Infrastructure Dept |
| TWP | Seqwater; DLGWV; Qld Ministerial Statements |
| MDW | National Water Grid Authority; Sunwater; Qld Ministerial Statements |
| EGR | GWMWater; National Water Grid Authority; Mitchell Water |

---

## Supplementary Metrics

### Table 9: Capacity-Based Metrics (where available)

| ID | Normalised Cost ($M) | Annual Capacity (ML) | $/ML Capacity |
|----|---------------------|---------------------|---------------|
| FGP | $1,050.8 | 30,000 | $35,027 |
| HP1 | $296.7 | 43,000* | $6,900* |
| HP2 | $404.0 | 130,000** | $3,108** |
| TWP | $467.0 | 3,650*** | $127,945 |
| EGR | $64.0 | 1,400 | $45,714 |

*Estimated based on pump/pipe capacity
**Combined Stage 1+2 system capacity
***Mid-range of 2,500-3,700 ML estimate

**Note:** $/ML capacity varies dramatically based on whether pipeline is primary supply or drought contingency.

---

### Table 10: Development Cost Analysis (where available)

| ID | Total Cost ($M) | Development/Pre-construction ($M) | Dev Cost % | Notes |
|----|-----------------|-----------------------------------|------------|-------|
| FGP | $983.0 | Est. $50-80 | 5-8% | Estimate based on typical |
| TWP | $370.0 | $19.3 | 5.2% | Feasibility phase confirmed |

**Industry Benchmark:** Development costs typically 5-12% of total project cost for water infrastructure.

---

## Database Export Format (CSV-Compatible)

```
ID,Project_Name,State,Length_km,Diameter_mm,Diameter_Class,Nominal_Cost_M,Cost_Year,Normalised_Cost_M_2024,Cost_per_km_M,Terrain,Remoteness,Data_Quality,Status
FGP,Fitzroy to Gladstone Pipeline,QLD,117.0,1000,Large,983.0,2023,1050.8,8.98,Rural,Regional,A,Construction
HP1,Haughton Pipeline Stage 1,QLD,36.0,1800,Very Large,215.0,2017,296.7,8.24,Flat,Regional,A,Completed
HP2,Haughton Pipeline Stage 2,QLD,28.2,1800,Very Large,274.0,2021,343.6,12.18,Greenfield,Regional,B,Construction
TWP,Toowoomba to Warwick Pipeline,QLD,111.0,475,Medium,370.0,2023,395.5,3.56,Hilly,Regional,C,Pre-construction
MDW,Mareeba-Dimbulah WSS,QLD,14.0,200,Small,32.5,2021,40.8,2.91,Existing,Rural,B,Completed
EGR,East Grampians Rural Pipeline,VIC,130.0,275,Small,64.0,2024,64.0,0.49,Rural,Remote,B,Construction
```

---

**Database Version:** 1.0
**Last Updated:** January 2026
