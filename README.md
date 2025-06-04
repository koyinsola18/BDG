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


