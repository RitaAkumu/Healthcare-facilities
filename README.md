# Healthcare Facilities Dataset Kenya — EDA

**Author:** Rita Akumu  
**Tools:** SPSS • Python • Microsoft Excel  
**Source:** Open Africa / eHealth Kenya Facilities Dataset  
**Last Updated:** 30 Nov 2024
**Status:** Completed ✅  

---

## 📌 Overview
This project explores Kenya’s healthcare facilities dataset to understand facility distribution, ownership, service availability, and resource capacity (beds/cots). The goal is to identify healthcare access gaps across counties and provide actionable recommendations for improvements.

---

## 🎯 Objectives
- Analyze facility distribution across Kenya’s 47 counties  
- Explore common facility types and ownership (public vs private)  
- Assess healthcare resources (beds and baby cots)  
- Evaluate availability of key services: **ART, C-IMCI, FP, HBC, IPD**  
- Highlight underserved counties and provide recommendations  

---

## 🗂️ Dataset Summary
- **Records:** 10,505 facilities  
- **Columns:** 49 (empty/unusable columns removed)  
- **Continuous variables:** Beds, Cots  

**Descriptive Statistics**
| Variable | Min | Max | Mean |
|---------|-----|-----|------|
| Beds | 0 | 1455 | 5.39 |
| Cots | 0 | 1000 | 0.74 |

---

## 🔍 Key Findings
- **Nairobi** has the most facilities (**900+**)  
- **Lamu** has the fewest facilities (**<50**) and also ranks lowest in bed availability  
- The most common facility type is **Dispensary (4,820 facilities)**  
- The **Ministry of Health** is the largest single owner (**4,687 facilities**)  
- Only a small share of facilities offer specialized services:
  - **ART:** ~9%  
  - **C-IMCI:** ~11%  
  - **Family Planning:** ~41%  
  - **HBC:** ~27%  
  - **IPD:** ~38%  
- **Public facilities provide more services and higher bed/cot capacity** compared to private facilities  
- Service availability is lowest in several underserved counties, especially in rural areas  

---

## ✅ Recommendations
- Prioritize investment in counties with low facility coverage:  
  **Lamu, Isiolo, Tana River, Mandera, Taita Taveta**
- Increase bed/cot capacity in low-resource counties  
- Expand emergency and inpatient services in underserved regions  
- Increase incentives for more **24-hour facilities** and weekend operations  
- Fast-track opening of pending facilities and reduce closures  

---

## ⚠️ Limitations
- Missing values were filled where necessary (“N/A” or 0 depending on context)  
- County-level analysis may hide inequalities within sub-counties  
- Results depend on completeness and accuracy of facility reporting  

---

