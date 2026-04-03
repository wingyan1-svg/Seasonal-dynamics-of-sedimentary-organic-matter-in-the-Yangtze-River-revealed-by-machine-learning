# Seasonal-dynamics-of-sedimentary-organic-matter-in-the-Yangtze-River-revealed-by-machine-learning

### 1. `FT-ICR_MS_DATA.xlsx`
- **Description:** Raw Fourier Transform Ion Cyclotron Resonance Mass Spectrometry (FT-ICR MS) data of SOM.
- **Sheets:**
  1. **Intensity weighted parameter** – Sample-wise molecular parameters (e.g., H/C, O/C, DBE, NOSC, AImod) calculated using intensity-weighted averages for each sample.
  2. **M02_wet** – Detailed FT-ICR MS molecular formula dataset for sample M02 in the wet season.
  3. **M02_dry** – Detailed FT-ICR MS molecular formula dataset for sample M02 in the dry season.
- **Usage:** 

### 2. `Bulk_parameter.xlsx` (or .csv)
- **Description:** Bulk chemical and physical parameters measured for the samples.
- **Contents:**
  - Total Organic Carbon (TOC)
  - Dissolved Organic Carbon (DOC)
  - pH, conductivity, and other environmental variables
  - Sample IDs
- **Usage:** Provides context for interpreting FT-ICR MS results and correlating bulk parameters with molecular data.

### 3. `SHAP_data.xlsx` (or .csv)
- **Description:** SHAP (SHapley Additive exPlanations) values derived from the predictive models.
- **Contents:**
  - Features used in the model
  - SHAP values indicating feature importance per sample
  - Sample IDs
- **Usage:** Helps interpret the contributions of individual variables to model predictions.

## Notes
- All data are linked to sample IDs consistently across files.
- Please cite: `[Your Article Citation]` if you use this dataset.

## License
Specify your license here, e.g., CC BY 4.0, MIT, etc.
