---
layout: dataset
date: 2016-10-01 10:46:43
publicationyear: 2014
lastupdate:

authorlist: "A. Newman, K. Sampson, M.P. Clark, A. Bock, and R.J. Viger, and D. Blodgett"
fulltitle: "A large-sample watershed-scale hydrometeorological dataset for the contiguous USA"
location: "Boulder, CO"
publisher: "UCAR/NCAR"
download: http://ral.ucar.edu/projects/hap/flowpredict/hydromet_data
versions: 1.0
lastestversion: 
status: available
doi: "10.5065/D6MW2F4D"

title: "CAMELS: Large-Sample Hydrometeorological Dataset"
shortblurb: "This dataset includes basin scale hydrometeorological forcing data for 671 basins in the U.S. Geological Survey's Hydro-Climatic Data Network using retrospective model forcings from three different datasets: Daymet (1980-2014), NLDAS (1980-2014), and Maurer et al. (1980-2008)."

format: "ascii files, X MB"
coverage: 671 watersheds across contiguous USA
access: freely available at http://ral.ucar.edu/projects/hap/flowpredict/hydromet_data
paperdescribe: Newman et al., HESS, 2015
paperlink: http://dx.doi.org/10.5194/hess-19-209-2015

teamline1: "NCAR: Martyn Clark (PI), Andrew Newman, Kevin Sampson"
teamline2: "USGS: A. Bock, R.J. Viger, D. Blodgett"
contacts: "Andrew Newman | anewman@ucar.edu"
sponsors: "Bureau of Reclamation, U.S. Army Corps of Engineers"

modellink:
projectlink:
datasetlink: CAMELS_attributes

ref: CAMELS_timeseries 
filename: CAMELS_timeseries

tags: [datasets,dataset_params,dataset_streamforecast,dataset_CAMELS_timeseries]
categories:
- datasets
---

This project developed basin scale hydrometeorological forcing data for 671 basins in the United States Geological Survey's Hydro-Climatic Data Network 2009 (HCDN-2009, Lins 2012) conterminous U.S. basin subset. Retrospective model forcings are derived from Daymet, NLDAS, and Maurer et al. (2002) Daymet forcing data run from 1 Jan 1980 to 31 Dec 2012, NLDAS and Maurer run from 1 January 1980 to 31 December 2008. USGS streamflow data are provided for all basins for all dates available in the 1 Jan to 31 Dec 2012 period. Daymet, NLDAS forcing and USGS streamflow data will be extended through 31 December 2014 by the end of 2015.
Figure 1 displays the location of each basin with the mean annual precipitation (mm) colored. State boundaries are in gray and the USGS HUC level 02 regions are in red.

<img src="{{ "/assets/img/datasets/671basins_fig1.png" | prepend: site.baseurl }}" class="img-responsive" height="100%" width="100%">

 Following generation of the forcign data, we initially implemented the hydrologic model and calibration routine traditionally used by the NWS, the SNOW-17 and Sacramento soil moisture accounting (SAC-SMA) based hydrologic modeling system and the shuffled complex evolution (SCE) optimization approach (Duan et al. 1993).

Results indicate that the SNOW-17/SAC-SMA optimized model parameters perform quite well overall (Figures 2 and 3), with arid basins and basins along the high plains of the US generally having worse model performance (Fig 2).

Finally, we have packaged all the basin metadata (shapefiles, locations, etc), hydrometeorological forcing data, streamflow data, model summary statistics, raw model output and model parameters in a large-sample basin scale hydrometeorolgical dataset. See below for the download link and more information

<img src="{{ "/assets/img/datasets/671basins_fig2.png" | prepend: site.baseurl }}" class="img-responsive" height="100%" width="100%">

<img src="{{ "/assets/img/datasets/671basins_fig3.png" | prepend: site.baseurl }}" class="img-responsive" height="100%" width="100%">
