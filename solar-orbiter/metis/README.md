# Metis Tutorial ISRO_ESA workshop January 2026, India

**Exploring Metis Data within the SunPy Ecosystem**

This Data Analysis Tutorial for Metis will guide you through the complete lifecycle of coronagraphic data: from discovery in the Solar Orbiter Archive (SOAR) to the creation of advanced multi-instrument composites.

---
**Run in COLAB**

This notebook can be run online in Colab without any local installation. It’s the fastest way to get started:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1V6uHdnDhPQRXjjh4FuLpWCSv_hYz3DF1?usp=sharing)
---

**Run locally:**
Prerequisites

The notebook relies on the standard Solar Physics Python stack. Python 3.9+ is recommended with the following packages:

- sunpy, sunpy-soar, astropy, matplotlib, numpy, drms, zeep, cmcrameri, scipy

**Installation & Setup**

1. Install via pip
You can install the necessary requirements using:
``` bash
pip install sunpy[all] sunpy-soar astropy matplotlib numpy drms zeep cmcrameri scipy jupyterlab
```   


2. Get the **MetisMap**
Clone the repository containing the Metis Map to your local machine:

``` bash
git clone https://github.com/gjerse/metisRepo.git

``` 

**How to Run**

- Open your terminal or Anaconda prompt.

- Navigate to the folder containing the file Exploring_Metis_Data.ipynb.

- Launch Jupyter Lab or Notebook:

``` bash
jupyter lab Exploring_Metis_Data.ipynb
``` 
<jupyter lab Exploring_Metis_Data.ipynb>

Run the cells sequentially to perform the data discovery, processing, and visualization.

**Notes & Troubleshooting**

METISMap: This tutorial uses a temporary implementation of METISMap. In the future, this class will be natively integrated into SunPy.

Units: You might see a SunpyMetadataWarning regarding the "MSB" unit (Mean Solar Brightness). This is expected as MSB is a non-standard FITS unit; the notebook handles this by setting a compliant dimensionless unit.

**Acknowledgements & Contact**
This tutorial is maintained by the Metis Python Working Group. 

Contact:  giovanna.jerse@inaf.it
          aleksandr.burtovoi@unifi.it
          alessandro.liberatore@inaf.it
          yara.deleo@inaf.it
          roberto.susino@inaf.it


Metis Page: https://metis.oato.inaf.it/


