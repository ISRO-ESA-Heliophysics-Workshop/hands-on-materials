# Flare hands-on tutorial (workflow)

This repository is part of the **ISRO–ESA Workshop hands-on sessions** and is designed to be **informal and interactive**. Participants will work directly with real observations, with team leads available for support and discussion.

People can engage at different depths depending on their background and interest:
- some participants may explore a dataset in more detail and try extended analysis  
- others may focus on getting started and understanding the core tools and workflows  



## Event studied

**Flare:** **2025-01-19 ~03:30 UT** (M-class)

This flare was observed by both **Aditya-L1** and **Solar Orbiter**. In this session we will analyse this event using:

- **Solar Orbiter / STIX**
- **Solar Orbiter / EUI**
- **Aditya-L1 / HEL1OS**
- **Aditya-L1 / SoLEXS**
- **Aditya-L1 / SUIT**

This notebook is a **starting point** — please run with it and explore.

---

## Google Colab
You can open any notebook in this repository directly in **Google Colab**:
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/ISRO-ESA-Heliophysics-Workshop/hands-on-materials/blob/main/science-workflows/01_flares_multimission/flare_workflow.ipynb)

## Data access

This notebook includes steps for downloading data, however some parts may require files locally.

All data used in this notebook is available here:  
https://drive.google.com/drive/u/1/folders/1czUWf8y9TWfrYXVf4jA52ZFB8LzUaHlp

---



---
## Use what you’ve seen in the tutorial sessions

These hands-on workflows build on the tutorial notebooks from earlier in the week:

https://github.com/ISRO-ESA-Heliophysics-Workshop/hands-on-materials/

---

## Suggested tasks (things to try)

This is intentionally open-ended. Here are some suggested analysis tasks:

### 1) Spacecraft context / geometry
- Plot the locations of the spacecraft (e.g. Earth and Solar Orbiter)

### 2) Time series comparisons
- Plot the **STIX quicklook lightcurves**
- Estimate the **time delay** between STIX and Earth-view observations
- Plot the **SoLEXS** and **HEL1OS** lightcurves and compare timing and evolution

### 3) Imaging observations (EUI)
- Search for EUI data (or download it from the Google Drive link)
- Plot an EUI image as a **SunPy map**
- Create a **submap** over the region of interest

---

## Notes for participants

- You can run this notebook either:
  - locally on your laptop, or
  - in Google Colab (if provided for this session)
- This is a hands-on session: feel free to experiment, ask questions, and compare with other groups.
