# Hydrological modeling: Monkey River watershed, Belize
[![Update](https://img.shields.io/github/last-commit/bzgeo/bz_monkey_river_hydrological_modeling?label=repo%20last%20updated&style=flat-square)](https://github.com/BzGEO/bz_monkey_river_hydrological_modeling)

[bit.ly/bz_hydro](https://bit.ly/bz_hydro)

**Description**: *Files and links related to hydrological modeling of the Monkey River watershed in Belize*

**Workshop [agenda](https://docs.google.com/document/d/1tLAI79wB3mt5phLMQgXYLCnv0hGTdHAUnG4LiGdU5H0/edit?tab=t.0)**

![](https://github.com/BzGEO/bz_monkey_river_hydrological_modeling/blob/main/_graphics/workshop_agenda_2025-09-09a.png)

## Hydrological modeling using the Non-point Source Pollution & Erosion Comparison Tool for QGIS (QNSPECT)
1. Download QGIS (e.g., version 3.40 LTR): https://qgis.org/download/
2. Download the QNSPECT plugin: https://plugins.qgis.org/plugins/QNSPECT/version/1.0/download/. (Also see the plugin page: https://plugins.qgis.org/plugins/QNSPECT/.)
3. Download the test data for the Monkey River watershed: https://github.com/BzGEO/bz_monkey_river_hydrological_modeling/blob/main/data/bz_monkey_river_qnspect_030m.zip
4. See the QNSPECT Technical Guide (Eslinger et al., 2022): https://coast.noaa.gov/data/digitalcoast/pdf/qnspect-technical-guide.pdf.
5. There is an overview article of the QNSPECT plugin: https://ar-siddiqui.medium.com/introducing-qnspect-76f4dc8e0fed. There is also a defunct NOAA tutorial for QNSPECT: https://coast.noaa.gov/digitalcoast/training/qnspect.html.

![](https://github.com/BzGEO/bz_monkey_river_hydrological_modeling/blob/main/_graphics/workflow_rusle_new2.png)

## Hydrological modeling using the Soil & Water Assessment Tool (SWAT)

* Download SWAT Check: https://swat.tamu.edu/media/4cwbo1wf/swatcheck-standalone-201.zip (more [info](https://swat.tamu.edu/software/swat-check/))
* Download Belize River watershed SWAT outputs: [uncalibrated](https://github.com/BzGEO/bz_monkey_river_hydrological_modeling/blob/main/data/bz_river_1991_2010_uncalibrated.zip) and [calibrated](https://github.com/BzGEO/bz_monkey_river_hydrological_modeling/blob/main/data/bz_river_1990_2020_calibrated.zip), the latter from [Copeland et al. (2025)](https://www.mdpi.com/2073-4441/17/13/1915)
* ArcSWAT plugins: https://swat.tamu.edu/software/arcswat/
* QSWAT plugins: https://swat.tamu.edu/software/qswat/
* SWAT global + other data: https://swat.tamu.edu/data/
* SWAT website: https://swat.tamu.edu/

![](https://github.com/BzGEO/bz_monkey_river_hydrological_modeling/blob/main/_graphics/swatcheck_bzr_erosion.png)
![](https://github.com/BzGEO/bz_monkey_river_hydrological_modeling/blob/main/_graphics/swatcheck_bzr_hydro.png)
