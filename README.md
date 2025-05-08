# Pharmacy Expansion Location Analysis

**Data-driven strategy to identify optimal new drug store outlets in the U.S.**

---

## Problem Statement

Hospitals often lack nearby, easily accessible pharmacies, creating friction for patients and lost revenue opportunities for drug store brands. Our goal: **recommend the best brand and specific locations** for opening a new outlet that maximizes market potential and minimizes competitive risk.

## Business Problem & Impact

- **Business Problem:** Mid‑sized pharmacy brands struggle to find expansion sites with high foot traffic and underserved demographics.  
- **Impact:** Guiding brand expansion can boost revenue, improve patient convenience, and strengthen community healthcare access.

## Approach / Methodology

1. **Brand Selection:**  
   - Filtered NAICS 446110 brands with 50–500 outlets  
   - Ranked by average monthly footfall per location  

2. **Geographic Analysis:**  
   - Aggregated hospital visit counts and county demographics  
   - Ranked counties above median hospital foot traffic and below median brand saturation  

3. **Site-Level Selection:**  
   - Pinpointed streets & postal codes in top county (King County, WA)  
   - Prioritized locations near high-traffic hospitals and older adult populations  

## Data Sources

- SafeGraph Places & Visits (NAICS 446110, 622110)  
- Census Block Group Demographics  

## Key Findings & Solution

- **Brand:** Safeway Pharmacy emerged as the optimal partner  
- **County:** King County, Washington, offers high hospital footfall & strong older-adult density  
- **Specific Sites:** Renton (98055) street addresses (e.g., 4033 Talbot Rd S Ste 530) ranked highest for traffic  

## Conclusion & Recommendations

- **Launch Safeway Pharmacy** in King County, WA, focusing on Renton locations  
- **Monitor** competitor presence and update demographic data regularly  
- **Extend analysis** to other states once additional population data are secured  

### Future Work

- Integrate real‑time footfall feeds for dynamic site scoring  
- Model competitor cannibalization effects  
- Explore supply‑chain logistics via wholesaler proximity  

#### Team : Chhaya, Avanti, Jayesh
 
