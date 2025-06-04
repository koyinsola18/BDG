# BDG

# Cost–Access Trade-offs for Newcomers in Canada  
### Spatial analysis of health, recreation & post-secondary service gaps

---

## 👋 What is our project?
We merge lived-experience stories with Statistics Canada Spatial Access Measures to show **where refugees, economic immigrants and international students can actually live and study once rent, transit time and service deserts are mapped together**.

---

**Research question:** *How does the cost–access trade-off reshape newcomer geography, and where should planners intervene first?*

## 🔬 Methodology snapshot
1. **Spatial join** dual-gravity SAM scores → Aggregate Dissemination Areas (ADAs).  
2. **Min–max scaling** per service (0 = worst in Canada; 1 = best).  
3. **Migrant-dominance flag** `Refugees≥Econ` when `refugeeF ≥ econF`.  
4. **Non-parametric tests** Mann–Whitney U + BCa bootstrap CIs.  
5. **Cartography**  
   * Per-CMA colourbars (prevents “all-purple Edmonton”).  
   * White halo + cyan outline on refugee-dominant ADAs for legibility.

---
## 📊 Key findings

| Figure | Insight |
|-------|---------|
| **Fig A** | **Toronto** – refugee-dominant ADAs cluster in the downtown core; post-secondary access index is **2× higher** than in surrounding suburbs (<em>p</em> = 0.03). |
| **Fig B** | **Alberta** – 93 % of ADAs score **0.00** for post-secondary access, creating service deserts outside Calgary and Edmonton. |
| **Heat-map** | Across the four CMAs, access peaks strongly track the **highest rents** (Spearman ρ = 0.71). |

@misc{JPK2025,
  title  = {Cost–Access Trade-offs for Newcomers in Canada},
  author = {Justina M., Precious A., Koyinsola T.},
  year   = 2025,
  url    = {https://github.com/<YOUR-ORG>/cost-access-tradeoffs}
}

