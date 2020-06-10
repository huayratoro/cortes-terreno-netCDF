# cortes-terreno-netCDF

Extraido de : Smith & Sandwell v. 8.2: 1/30-degree topography and bathymetry
    Conventions: COARDS
    GFDL_NCIR_VER_NO: 1.0beta4
    unpacked_missing_value: -32767.0
    institution: University of California San Diego
    source: Uses satellite-measured gravity anomalies constrained by ship soundings to predict water depth.
    history: 26 Sep 2003: Dataset SS_2min_topo_8.2.nc FTPed from NOAA/GFDL by E. D. Cokelet, NOAA/PMEL.  Variable Z_ELEVATION name changed to ROSE, Relief of Surface of the Earth.  Documentation added to global attributes.  Data file name changed to smith_sandwell_topo_v8.2 to parallel Smith & Sandwell v. 6.2 dataset used by Ferret.  Sometime earlier GFDL had converted this dataset to netcdf.  See GFDL website http://www.gfdl.noaa.gov/~hnv/SS_topography.html.

#### references: Smith, W. H. F. and D. T. Sandwell, Global Seafloor Topography from Satellite Altimetry and Ship Depth Soundings, Science, v. 277, p. 1956-1962, 26 September, 1997.

#### comment: Read accompanying smith_sandwell_COPYRIGHT and smith_sandwell_README_V8.2 files for details.

#### Contiene las variables de X (longitudes), Y (latitudes) y terreno (msnm)
#### El mar y el terreno por debajo está enmascarado con NaN

El corte de Sudamerica es: lat_n = 5; lat_s = -60; lon_w = -90; lon_e = -30

El corte de Cordillera es: lat_n = -5; lat_s = -40; lon_w = -75; lon_e = -55
