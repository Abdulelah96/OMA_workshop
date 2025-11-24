# OMA Workshop

This repository contains materials for the Operational Modal Analysis (OMA) Workshop, focusing on signal processing and its application to offshore wind turbines.

Participants will learn how to:

- Preprocess and analyze structural acceleration signals

- Apply key signal-processing techniques (filtering, PSD, decimation, etc.)

- Perform Operational Modal Analysis (OMA)

- Interpret mode shapes and damping from real turbine data

The dataset includes measurements collected from offshore wind turbines under three operational states:

- Parked (idling)

- Rotor-stop

- Rated operation

These conditions provide a rich basis for comparing modal behavior under different aerodynamic and structural loading.

The workshop notebook can be opened on Binder 

## 🧩 Running on Binder

You can explore and run each notebook interactively using **Binder**, without installing anything locally.  
Each Binder link below will launch **classic Jupyter Notebook interface** in your browser and automatically open the corresponding notebook.

> 💡 It may take a few minutes for Binder to start the first time (it’s building the environment).  
> Once the environment is ready, notebooks will load instantly on subsequent launches.

---

### ** OMA Workshop**

This notebook introduces:

- Signal processing fundamentals
- Hands-on exercises using real turbine measurements
- OMA practical implementation
- Mode identification and comparison between operating states

<!-- [![OMA Notebook](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/OWI-Lab/FIRMEST_fatigue_assessment_workshop/main?filepath=Notebooks/1.Geometry_Resistance_OWIMetaDataBase.ipynb) -->

---

<!-- ### **2️⃣ Load Processing**

This notebook covers preprocessing and conditioning of SCADA or simulation load data for fatigue analysis.

[![Launch Load Processing Notebook](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/OWI-Lab/FIRMEST_fatigue_assessment_workshop/main?filepath=Notebooks/2.Load_Processing.ipynb)


---

### **3️⃣ Fatigue Assessment**

This notebook performs the fatigue analysis using processed load data and stress cycle counting.

[![Launch Fatigue Assessment Notebook](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/OWI-Lab/FIRMEST_fatigue_assessment_workshop/main?filepath=Notebooks/3.Fatigue_Assessment.ipynb)


---

### 🧠 Notes

- All three notebooks share the same environment defined in `.binder/environment.yml`.  
- Data files (`.pkl`, `.gz`, etc.) stored in the `Notebooks/` folder are automatically available when launched on Binder.  
- You can also download the notebooks and run them locally if you prefer.

---

### ✅ Quick Reference

| Notebook | Purpose | Binder Link |
|-----------|----------|--------------|
| 1️⃣ 1.Geometry_Resistance_OWIMetaDataBase.ipynb | Explore geometry & resistance metadata | [Open](https://mybinder.org/v2/gh/OWI-Lab/FIRMEST_fatigue_assessment_workshop/main?filepath=Notebooks/1.Geometry_Resistance_OWIMetaDataBase.ipynb) |
| 2️⃣ 2.Load_Processing.ipynb | Process SCADA/load data | [Open](https://mybinder.org/v2/gh/OWI-Lab/FIRMEST_fatigue_assessment_workshop/main?filepath=Notebooks/2.Load_Processing.ipynb) |
| 3️⃣ 3.Fatigue_Assessment.ipynb | Perform fatigue analysis | [Open](https://mybinder.org/v2/gh/OWI-Lab/FIRMEST_fatigue_assessment_workshop/main?filepath=Notebooks/3.Fatigue_Assessment.ipynb) |

--- -->