# Seasonal-dynamics-of-sedimentary-organic-matter-in-the-Yangtze-River-revealed-by-machine-learning

### 1. `FT-ICR_MS_DATA.xlsx`
- **Description:** Raw Fourier Transform Ion Cyclotron Resonance Mass Spectrometry (FT-ICR MS) data of SOM.
- **Sheets:**
  1. **Intensity weighted parameter** – Sample molecular parameters (e.g., H/C, O/C, DBE, NOSC, AImod) calculated using intensity weighted averages.
  2. **Wet season** – Detailed FT-ICR MS molecular formula dataset for sample M02 in the wet season.
  3. **Dry season** – Detailed FT-ICR MS molecular formula dataset for sample M02 in the dry season.

### 2. `Bulk_parameter.xlsx` 
- **Description:** Bulk chemicalparameters measured for the samples.
-**Sheets:**
   1. **Total Organic Carbon** (OC)
   2. **Dissolved Organic Carbon** (DOC)
   3. **Total nitrogen** (TN)
    
### 3. `SHAP_data.xlsx` (or .csv)
- **Description:** SHAP (SHapley Additive exPlanations) values derived from the SVM models.
- **Sheets:**
  1. **Wet-season-specific**: – SHAP values for Wet-season-specific molecule
  2. **Dry-season-specific** – SHAP values for Dry-season-specific molecule
  3. **seasonally shared** – SHAP values for Seasonally shared molecule
