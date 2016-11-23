---
layout: page
title: Science Traceability Matrix (STM)
permalink: /design/
---

Below is an example STM for one of the 12 HiMAT projects. We will populate STMs for all 12 projects prior to the workshop.

<hr>

<hr>
# NASA Earth System Science

To develop a scientific understanding of Earth's system and its response to natural or human-induced changes, and to improve prediction of climate, weather, and natural hazards.

## NASA High Mountain Asia Team (HiMAT)

* __Objective #1__: To determine the physical processes driving changes in water resources in the HMA region.
* __Objective #2__: To predict impacts of changing HMA water resources on human and biogeophysical systems.  

<hr>
<hr>

### PI Arendt
 Validating a Glacier Melt Toolbox For High Mountain Asia Using a Remote-Sensing-Driven Data Integration Framework

| Science Objectives | Approach | Data Needed  | Data/output generated | Expected Outcomes |
|:-------------|:----------------------|:-------------|:-------------|:-------------|
| To quantify the mass variations of the entire HMA region with a focus on isolating mass changes due to hydrology and cryosphere. | Forward modeling of GRACE Level 1B data together with all available observed/modeled hydrological information. | Best estimates of cryosphere and hydrology variations in the region along with associated uncertainties, up to daily resolution, up to 1 km spatial.	| Residuals of mass not currently captured by existing cryosphere/hydrology observations and models @ 1x1 degree mascon spatial and monthly temporal resolution across entire HMA.	| Information on deficiencies in existing models /datasets; Formal mechanism for using GRACE to validate model output; iterative procedure can be implemented. |
| To assess HMA glacier mass balance on ~50-year, decadal, annual and seasonal timescales.	| Generate high-resolution DEMs from DigitalGlobe imagery and integrate with other available DEMs for elevation change analysis.|<ul><li>DigitalGlobe imagery from Polar Geospatial Center (Morin, Osmanoglu/Montesano/Neigh)</li><li> SNODAS snowcover data for DEM co-registration (Painter) </li><li>Historical DEMs from declassified ~1970s imagery (Rupper/Maurer)</li><li> SRTM, ICESat-1, ICESat-2</li></ul> | <ul><li>2, 8, 32-m DEMs</li><li>0.5-m orthoimages</li><li>DEM time series and regional mosaics</li><li>Volume/mass change estimates</li></ul>|  <ul><li>Regional glacier mass balance estimates</li><li>Cal/val for GMELT models</li><li>New capacity for high-resolution geomorphological analyses (lakes, debris cover, landslides, etc)</li></ul>| 
| To quantify groundwater contributions to terrestrial water storage change in HMA| Collect and analyze available groundwater observations and conduct baseflow recession analysis from available stream gauges | Observation wells and longterm streamflow records, ideally a few points within major sub-basins | Monthly groundwater storage changes (spatial resolution partially dependent on data availability) | Improved groundwater data to contribute to GRACE forward modeling efforts | 
| To assess downstream impacts of changing water availability on agricultural systems | <ul><li>Estimate demand for groundwater and surface water</li><li>develop future demand scenarios from projected water availablity</li><li>crop modeling to assess management strategies</li></ul> | Projections of changes in streamflow, landcover maps, population projects, historical crop yields (if doing crop modeling) | Maps of land use scenarios as a function of changes in water availability | <ul><li>mechanism to translate the impacts of scientific findings to societal applications</li><li>improved understanding of future water availability, and the changing dependence between surface water and groundwater</li></ul> |
<br>
<br>
### PI Sarah Kapnick
Quantifying the Role of Dust on Precipitation, Snow, and Runoff in High Mountain Asia

| Science Objectives | Approach | Data Needed  | Data/output generated | Expected Outcomes |
|:-------------|:-------------|:-------------|:-------------|:-------------|
| To identify the sources of aerosols globally | Collect and analyze remote sensing products following Ginoux et al. Rev. Geophys., 2012 | MODIS, SeaWiFS, TOMS, OMI, CALIOP, MODIS LAI,  MODIS snow, AMSRE soil moisture, HYDE3.2 land use, GMTED2010 topography | Global 0.1 x 0.1 deg resolution dust source inventory |<ul><li>Provides a common gridded inventory of dust sources at high resolution (cf. Ginoux et al., 2012)</li><li>•	Will provide natural and anthropogenic attribution based on land use datasets</li><li>•	Can be used as sources for emission parameterization and validation of dust</li></ul> |
| To identify the frequency and strength of deposition and origins of aerosols | Run a nudged global GCM from 1980-2015 to generate meteorological conditions and separately with tagging techniques to track the origin of aerosols (cf. Li et al., JGR-Atmos, 2010) | NCEP reanalysis, monthly/daily aerosol optical depth (MODIS, SeaWiFS, CALIOP, AERONET) | Global climate model output for HMA region at 50 km resolution for meteorological data and aerosols from 1980-2015 | <ul><li>Statistics of HMA dust deposition events to determine 'major' events</li><li>•	Contribution of each major sources to aerosol deposition over the Himalaya</li><li> Can be used to calibrate and implement a surface albedo change parameterization in the land surface model component of our global modeling work</li></ul> |
| Validate snowcover and snowpack in GCM model | compare GCM output with available snow data sets | MODIS, output from other HiMAT teams, Rutgers snow product | Regional biases in snowpack simulations will be quantified | <ul><li>Pinpoint regions of simulation issues for future improvement</li><li>Allows for calculations of error bars and bias correction for future climate projections</li></ul> |
| To quantify how aerosols interact with the HMA hydroclimate | Run the global climate model with and without aerosol deposition events affecting surface albedo at fixed global radiative forcing | Parameterization from previous objective outcome, global climate model simulations | Global climate model output for HMA region at 50 km resolution for meteorological data and aerosols for a control simulation with and without aerosol deposition (cf. Kapnick et al., Nat. Geo., 2014) | <ul><li>Improves our understanding of how surface albedo changes from aerosols affect hydroclimate</li><li>Improved understanding of the role of dust in altering snowpack and HMA water availability</li></ul> |
| To assess future HMA hydroclimate | Run global climate model with and without deposition events from present to 2100 | Parameterization from previous objective outcome, global climate model simulations | Global climate model output for HMA region at 50 km resolution for meteorological data and aerosols for a climate change simulation with and without aerosol deposition |<ul><li>Improves our understanding of how surface albedo changes from aerosols will affect hydroclimate and regional climate sensitivity in the future</li><li>Quantify the role of dust in future HMA water availability</li></ul> |
<br>
<br>
### PI Dalia Kirschbaum
Multi-sensor impact analysis of cascading hazards and transportation corridors in Nepal

| Science Objectives | Approach | Data Needed  | Data/output generated | Expected Outcomes |
|:-------------|:-------------|:-------------|:-------------|:-------------|
| To map landslides along key road corridors (main highways and new road construction) | Fusion of remote sensing data to catalog recent landslides, merge with existing records of landslide activity | Optical imagery, SAR data, and high-resolution digital elevation models | Landslide inventories | Better understanding of where, when, and how many landslides are occurring | 
| To model landslide susceptibility | Determine terrain's susceptibility to landslide initiation with locally calibrated empirical models, then generate runout simulations  | DEM, Land cover, Soils, Geology, landslide volume (or range of volumes) to delineate runout  | Susceptibility map of each study area | Better infrastructure planning, due to ranking of road segments by probability of disruption | 
| To incorporate landslide triggering events into a real-time dynamic model | Establish triggering relationships for hydrometeorological and seismic variables | Locally calibrated datasets for rain (including forecasts), snow, snowmelt, and seismicity | Nowcast that shows the current landslide hazard | Broad situational awareness of landslide hazard in real-time for multiple stakeholders | 
| To characterize risk and vulnerability related to landslides and identify potential economic impacts in the transportation network due to the disruptions from landslides | Combine spatial data on hazard and exposure with economic analyses to assess road networks at risk to cascading landslide hazards | Population, Road networks (OSM), economic data (if available) from the World Bank | Indicators of Exposure, Vulnerability, and Risk | Better understanding of the geography of risk along road networks within Nepal | 
<br>
<br>
### PI Summer Rupper
Precipitation and Glacier Change in High Mountain Asia Over the Modern Era

| Science Objectives | Approach | Data Needed  | Data/output generated | Expected Outcomes |
|:-------------|:-------------|:-------------|:-------------|:-------------|
| To quantify the temporal and spatial variability in precipitation over HMA, and impacts of this variability on glacier mass balance over the modern era (1980-present) | Model precipitation using WRF and Bayesian statistical models; model glacier surface energy and mass balance; generate DEMs from historical satellite imagery; validate climate and glacier model output | Precipitation products (station, reanalysis, remote sensing), glacier areas over time, gridded climate data, glacier debris thickness and aerial extent, glacier/snow albedo | High-res gridded weather and climate products over modern era, glacier mass balance change (modeled and observed) over modern era, glacier energy balance terms, glacier meltwater flux | Improved understanding of precipitation variability/trends and processes, robust estimates of glacier sensitivity to climate variability and change, contribution of glaciers to water resources and sea level rise |
<br>
<br>

### PI Si-Chee Tsay
Radiation, Aerosol Joint Observation-Modeling Exploration over Glaciers in Himalayan Asia

| Science Objectives | Approach | Data Needed  | Data/output generated | Expected Outcomes |
|:-------------|:-------------|:-------------|:-------------|:-------------|
|To provide better understanding of aerosol/snow/ice properties over the HMA region using satellite products | Performing satellite retrievals by employing the state-of-the-art _enhanced-Deep Blue_ algorithm | Satellite L1B reflectance from MODIS/VIIRS (as input) and ground-based measurements of aerosol and snow impurity (below, as validation) | MODIS/VIIRS RGB imagery, retrievals of AOD, Angstrom Exponent, snow effective grain size, impurity equivalent (dust, soot), and surface radiative forcing at 1 km resolution over HMA |Large-scale information to help constrain the model simulations of changes in HMA region due to the presence of light-absorbing aerosols | 
| To conduct field deployment in spring 2018 for providing initialization and validation data in retrieval and modeling studies | Deploying, in collaboration with regional groups, a network of sunphotometer, spectrometer, radiometer at selected sites | Laboratory analysis of snow impurity and grain size (critically needed) | Retrieved aerosol/ cirrus properties, surface bidirectional reflectance and irradiance fields over a network of selected sites | Critical ground-truth data over a network of aerosol inflow, transport and deposition sites for validation/ initialization studies |
| To assess the roles of aerosol, snow impurity and radiation interactions in regional climate and to provide predictions for guiding field experiment, as well as the post-mission mini-reanalysis | Conducting simulations of GEOS-5, with and without aerosol radiative and snow impurity effects, and conducting a post-mission reanalysis including field observations | Satellite and ground-based measurements of AOD, snow impurity and albedo, and irradiance fields as the model constraints and validations | Simulated and assimilated AOD, atmospheric state parameters, snow impurity (dust, EC/OC), surface albedo, solar and terrestrial heat fluxes, snowmelt flux and precipitation | Knowledge of the impact of snow impurity and aerosol radiative effects on snowmelt, land surface temperature and wetness, and subsequent development of Indian summer monsoon.|  
