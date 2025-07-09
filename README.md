This code is part of a publication by Leonard Arning and Heather Kaths (in press). Further, Steeper, Greener: Implications from an Electric Bicycle Mode Choice Model. International Journal of Sustainable Transportation.

01_spatial_type.ipynb

Python code which writes one of four RegioStaR spatial typologies to 1km-grid cells.

02_elevation_change.ipynb

Python code which computes the gradient attribute for 1km-Gridcells. Uses the GeoGitter Inspire (https://gdz.bkg.bund.de/index.php/default/geographische-gitter-fur-deutschland-in-lambert-projektion-geogitter-inspire.html), a dataset provided exclusively by Burgdorf M, Pütz T. Dokumentation der Raumvariablen des BBSR im Regionalfile. Annex 5 to the user manual for the MiD 2017. 2019., and the list of target grid cells created by 01_Cells spatial typology.

03_pt_quality.ipynb

Python code that counts the number of departures per transit stop and writes it to a csv file. These stops and the centers of the grid cells are then read into QGIS where the number of departures in an area 2 km around each grid cell center is computed. This value is then written back onto the grid cell csv file.

04_Infra_quality.ipynb

Python code that extracts the total road network length and the bicycle infrastructure length for each of the 400 German Landkreise/kreisfreie Städte/Stadtkreise/city states and computes the ratio of both for each region.

10_data_processing_mode_choice.ipynb

Python code that processes the MiD data for Biogeme and adds the four aforementioned datasets.

21_NL_car.ipynb

Python code using the Biogeme 3.2.14 package by Bierlaire, M. (2023). A short introduction to Biogeme: Technical report transpo-or 230620. Retrieved fromhttps://transp-or.epfl.ch/documents/technicalReports/Bier23.pdf. This code is for the model variant nesting car (driver) and car (passenger). Other nesting variants were tested but discarded. For more details, please refer to the publication.

30_Analysis_Validation.ipynb

Python code used to validate and analyse model results.
