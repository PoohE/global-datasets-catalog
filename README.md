# Каталог глобальных геопространственных покрытий природных факторов

**Global Geospatial Dataset Catalog of Natural Factors**

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22730919.svg)](https://doi.org/10.5281/zenodo.22730919)

---

## О каталоге / About

**RU.** Систематизированный каталог открытых глобальных геопространственных покрытий по природным факторам, динамике ландшафтов, биоразнообразию и охране природы. Охватывает рельеф, растительность, землепользование, климат, гидрологию, почвы, антропогенную нагрузку, пожарный мониторинг и охраняемые территории.

Составлен в Институте географии РАН. Предназначен для исследователей, работающих над задачами оценки динамики ландшафтов, угроз лесам и биоразнообразию, природоохранного планирования.
Каждая запись содержит: название продукта, тематическую группу, год выпуска, пространственное разрешение, наличие в Google Earth Engine, ссылку на источник и DOI для цитирования.

**EN.** A curated catalog of open global geospatial datasets covering natural factors, landscape dynamics, biodiversity, and nature conservation. Includes terrain, vegetation, land cover, climate, hydrology, soils, anthropogenic factors, fire monitoring, and protected areas.

Compiled at the Institute of Geography RAS. Designed for researchers working on landscape dynamics assessment, forest and biodiversity threat analysis, and conservation planning.
Each entry includes: product name, thematic group, release year, spatial resolution, Google Earth Engine availability, source URL, and citation DOI.

---

## Авторы / Authors

- **Пуреховский Андрей Жоржевич** — Институт географии РАН, Москва
- **Институт географии РАН** (ИГ РАН / Institute of Geography RAS), Москва

---

## Структура полей / Field description

| Поле / Field | Описание / Description |
|---|---|
| Название источника | Полное название датасета / Full dataset name |
| GEE Catalog | Asset ID или ссылка в GEE Community Catalog |
| Год данных | Год выпуска / Release year |
| Актуальные | Статус актуальности: Актуальный / — / ⚡ |
| Группа факторов | Тематическая группа |
| Фактор | Тематический фактор |
| Дата/Актуальность | Период охвата / Coverage period |
| Есть в GEE | Доступность в Google Earth Engine |
| Пространственное разрешение | Разрешение пикселя / Spatial resolution |
| Ссылка для цитирования | DOI статьи или датасета |
| Ссылка на источник | URL портала / Portal URL |

---

## Каталог / Catalog


### 1. Базовые физико-географические условия

| Название | Год | Разрешение | В GEE | Период | Цитирование | Источник |
|----------|-----|-----------|-------|--------|-------------|---------|
| [GRIT](https://gee-community-catalog.org/projects/grit) | 2024 | ~50 м (вектор) | Да (Community Catalog) | 2024 | [DOI](Allen, G.H. et al. (2024). Global River Topology (GRIT). ESS Open Archive. https://doi.org/10.22541/essoar.172108645.52746193/v1) | — |
| [Global River Widths (GRWL)](water.usgs.gov/cat…fd2b4/) | 2018 | 30 м | Да (через Community Catalog) | 2018 | [DOI](Allen, G.H., and Pavelsky, T.M., 2018, Global River Widths from Landsat (GRWL) Database (V01.01) [insert dataset name], Zenodo, https://doi.org/10.5281/zenodo.1297434) | — |
| [HydroBASINS](https://www.hydrosheds.org/products/hydrobasins) | 2024 | Варьируется (от ~100 м до ~5 км) | Да (через Community Catalog) | — | — | — |
| [HydroRIVERS](hydrosheds.org/pro…rivers) | 2024 | ~500 м | Да | — | — | — |
| [HydroSHEDS](https://developers.google.com/earth-engine/datasets/catalog/WWF_HydroSHEDS_03VFD) | 2006 | 3 arc-sec (~90 м) | Да | 2006 | [DOI](Lehner, B., Verdin, K., Jarvis, A. (2008). HydroSHEDS. https://doi.org/10.1594/PANGAEA.788872) | — |
| [Global Soil bioclimatic variables](https://gee-community-catalog.org/projects/soil_bioclim/) | 2022 | 1 км | Да (через Community Catalog) | 2022 | [DOI](Lembrechts, Jonas J., Johan van den Hoogen, Juha Aalto, Michael B. Ashcroft, Pieter De Frenne, Julia Kemppinen, Martin Kopecký et al. "Global maps of soil temperature." Global Change Biology 28, no. 9 (2022): 3110-3144.) | — |
| [Harmonized World Soil Database v 1.2](fao.org/soi…12/en/) | 2008 | 30 arc-second raster database | Да | 2008 | [DOI](Fischer, G., F. Nachtergaele, S. Prieler, H.T. van Velthuizen, L. Verelst, D. Wiberg, 2008. Global Agro-ecological Zones Assessment for Agriculture (GAEZ 2008). IIASA, Laxenburg, Austria and FAO, Rome, Italy.) | — |
| [HiHydroSoil v1.2](futurewater.eu/pro…osoil/) | 2016 | 1 км | Да (через Community Catalog) | 2016 | [DOI](Simons, G.W.H., R. Koster, P. Droogers. 2020. HiHydroSoil v2.0 - A high resolution soil map of global hydraulic properties. FutureWater Report 213.) | — |
| [OpenLandMap Soils](https://gee-community-catalog.org/projects/openlandmap) | 2018 | 250 м | Да (Community Catalog) | 2018 | [DOI](Hengl, T. et al. (2018). OpenLandMap. https://doi.org/10.5281/zenodo.1475459) | — |
| [SMAP L4 9 km EASE-Grid Surface and Root Zone Soil Moisture Geophysical Data, V3](nsidc.org/dat…ions/8) | 2024 | 9 км | Да (через Community Catalog) | Актуальный, оперативный | [DOI](Reichle, R., De Lannoy, G., Koster, R. D., Crow, W. T., Kimball, J. S., Liu, Q. & Bechtold, M. (2025). SMAP L4 Global 3-hourly 9 km EASE-Grid Surface and Root Zone Soil Moisture Geophysical Data. (SPL4SMGP, Version 8). [Data Set]. Boulder, Colorado USA. NASA National Snow and Ice Data Center Distributed Active Archive Center. doi:10.5067/T5RUATAQREF8) | — |
| [SoilGrids 250m v2.0](https://gee-community-catalog.org/projects/isric) | 2020 | 250 м | Да (Community Catalog) | 2020 | [DOI](Poggio, L. et al. (2021). SoilGrids 2.0. SOIL, 7, 317-333. https://doi.org/10.5194/soil-7-317-2021) | — |
| [ALOS DSM: Global 30m v3.2](developers.google.com/ear…0_V4_1) | 2014 | 30 м | Да | 2014 | [DOI](T. Tadono, H. Ishida, F. Oda, S. Naito, K. Minakawa, H. Iwamoto
Precise Global DEM Generation By ALOS PRISM, ISPRS Annals of the Photogrammetry, Remote Sensing and Spatial Information Sciences, Vol.II-4, pp.71-76, 2014) | — |
| [ASTER GDEM](asterweb.jpl.nasa.gov/gdem.asp) | 2019 | 30 м | Да | 2019 | — | — |
| [ArcticDEM](pgc.umn.edu/dat…icdem/) | 2023 | 2 м | Да | 2023 | [DOI](Porter, Claire, et al., 2023, “ArcticDEM, Version 4.1”, https://doi.org/10.7910/DVN/3VDC4W, Harvard Dataverse, V1, [Date Accessed]) | — |
| [FABDEM V1-2](data.bris.ac.uk/dat…4ew3sn) | 2023 | 1 угловая секунда (~30 м у экватора) | Да | 2023 | [DOI](Jeffrey Neal, Laurence Hawker (2023): FABDEM V1-2. https://doi.org/10.5523/bris.s5hqmjcdj8yo2ibzi9b4ew3sn) | — |
| [Geomorpho90m](portal.opentopography.org/dat…4326.1) | 2020 | 3 угловые секунды (~90 м) и 7,5 угловых секунд (~250 м) в геодезической системе координат WGS84, 100 м в проекции Equi7. | Да | 2020 | [DOI](Amatulli, G., McInerney, D., Sethi, T., Strobl, P., Domisch, S. (2020). Geomorpho90m - Global High-Resolution Geomorphometry Layers. Distributed by OpenTopography. https://doi.org/10.5069/G91R6NPX. Accessed: 2025-10-18) | — |
| [Global Terrain Slope and Aspect Data](fao.org/soi…12/en/) | 2008 | 30 arc-second raster database, 30 arc-sec and 5 min latitude/longitude grid cells | Нет | 2008 | [DOI](Fischer, G., F. Nachtergaele, S. Prieler, H.T. van Velthuizen, L. Verelst, D. Wiberg, 2008. Global Agro-ecological Zones Assessment for Agriculture (GAEZ 2008). IIASA, Laxenburg, Austria and FAO, Rome, Italy) | — |
| [Copernicus DEM GLO-30](https://developers.google.com/earth-engine/datasets/catalog/COPERNICUS_DEM_GLO30) | 2021 | 30 м | Да | 2019-2021, Актуальный | [DOI](European Space Agency (2022). Copernicus DEM GLO-30. https://doi.org/10.5270/ESA-c5d3d65) | — |
| [NASADEM](https://developers.google.com/earth-engine/datasets/catalog/NASA_NASADEM_HGT_001) | 2020 | 30 м | Да | 2000 (обработка 2020) | [DOI](NASA JPL (2020). NASADEM: A Global Elevation Model. https://doi.org/10.5067/MEaSUREs/NASADEM/NASADEM_HGT.001) | — |
| [SRTM](https://developers.google.com/earth-engine/datasets/catalog/USGS_SRTMGL1_003) | 2000 | 30 м | Да | 2000 | [DOI](Farr, T.G. et al. (2007). The Shuttle Radar Topography Mission. Reviews of Geophysics, 45, RG2004.) | — |
| [GEDTM30 bare-earth (Global Ensemble Digital Terrain Model, OpenTopography)](https://portal.opentopography.org/datasetMetadata?otCollectionID=OT.082025.4326.1) | 2025 | 30 м | Нет | 2025 | [DOI](https://doi.org/10.5069/G9BV7DT1) | — |

### 2. Растительность и горючие материалы

| Название | Год | Разрешение | В GEE | Период | Цитирование | Источник |
|----------|-----|-----------|-------|--------|-------------|---------|
| [GEM-Forest](doi.org/10.…921586) | 2025 | 10 м | Да (GEE Community Catalog) | 2025 | [DOI](Paluba, D., Marsocci, V., Onačillová, K., Puerta Quintana, Y. T., and Hastie, A.: GEM-Forest: A Global satellite EMbedding–based map of forests and tree crops for 2020, EGUsphere [preprint], https://doi.org/10.5194/egusphere-2026-1401, 2026.) | — |
| [Global Aboveground Biomass (GEDI L4)](https://developers.google.com/earth-engine/datasets/catalog/LARSE_GEDI_GEDI04_A_002) | 2023 | 1 км (грид) | Да | Актуальный, до 2023 | [DOI](Dubayah, R. et al. (2022). GEDI L4A Footprint Level Aboveground Biomass. ORNL DAAC. https://doi.org/10.3334/ORNLDAAC/2056) | — |
| [MODIS MOD13Q1 Vegetation Indices](https://developers.google.com/earth-engine/datasets/catalog/MODIS_061_MOD13Q1) | 2024 | 250 м | Да | Актуальный, каждые 16 дней | [DOI](Didan, K. (2015). MOD13Q1 MODIS/Terra Vegetation Indices 16-Day L3 Global 250m. NASA LP DAAC. https://doi.org/10.5067/MODIS/MOD13Q1.006) | — |
| [MODIS MYD13Q1 Vegetation Indices](https://developers.google.com/earth-engine/datasets/catalog/MODIS_061_MYD13Q1) | 2024 | 250 м | Да | Актуальный, каждые 16 дней | [DOI](Didan, K. (2015). MYD13Q1 MODIS/Aqua Vegetation Indices 16-Day L3 Global 250m. NASA LP DAAC. https://doi.org/10.5067/MODIS/MYD13Q1.006) | — |
| [Global Fuel Moisture Content (MODIS)](https://www.sciencedirect.com/science/article/pii/S0303243421000611) | 2021 | 500 м | Нет (Asset) | 2021 | [DOI](Yebra, M. et al. (2021). Global fuel moisture content mapping from MODIS. Int. J. Wildland Fire, 30(2), 81-93.) | — |
| [Global Forest Canopy Height 2019](https://glad.earthengine.app/view/global-forest-canopy-height-2019) | 2019 | 30 м | Да (Community Catalog) | 2019 | [DOI](Potapov, P. et al. (2021). Mapping global forest canopy height through integration of GEDI and Landsat. RSE, 253, 112165. https://doi.org/10.1016/j.rse.2020.112165) | — |
| [Global Daily 9 km VOD](https://essd.copernicus.org/articles/17/2849/2025) | 2025 | 9 км | Нет | 2025 | [DOI](Hu, T. et al. (2025). A global daily seamless 9 km VOD dataset. ESSD, 17, 2849-2866. https://doi.org/10.5281/zenodo.13334757) | — |
| [Global Fuelbed Dataset](https://doi.pangaea.de/10.1594/PANGAEA.849808) | 2016 | 1 км | Нет (Asset) | 2016 | [DOI](Pettinari, M.L. & Chuvieco, E. (2016). Generation of a global fuel data set using FCCS. Biogeosciences, 13, 2061-2076. https://doi.org/10.1594/PANGAEA.849808) | — |
| [ESA WorldCover 10m v200](esa-worldcover.org/en) | 2021 | 10 м | Да | 2021 | [DOI](WorldCover 2020 v100
Zanaga, D., Van De Kerchove, R., De Keersmaecker, W., Souverijns, N., Brockmann, C., Quast, R., Wevers, J., Grosu, A., Paccini, A., Vergnaud, S., Cartus, O., Santoro, M., Fritz, S., Georgieva, I., Lesiv, M., Carter, S., Herold, M., Li, Linlin, Tsendbazar, N.E., Ramoino, F., Arino, O., 2021. ESA WorldCover 10 m 2020 v100. https://doi.org/10.5281/zenodo.5571936 
 
WorldCover 2021 v200
Zanaga, D., Van De Kerchove, R., Daems, D., De Keersmaecker, W., Brockmann, C., Kirches, G., Wevers, J., Cartus, O., Santoro, M., Fritz, S., Lesiv, M., Herold, M., Tsendbazar, N.E., Xu, P., Ramoino, F., Arino, O., 2022. ESA WorldCover 10 m 2021 v200. https://doi.org/10.5281/zenodo.7254221) | — |
| [2020 Global vegetation height in 10m resolution. Produced by EcoVision Lab in the ETH Zurich Department of Civil, Environmental and Geomatic Engineering.](https://www.earthdata.nasa.gov/data/catalog/ornl-cloud-gedi-icesat2-global-veg-height-2294-1) | 2021 | 1 км | Да (Community Catalog) | 2019-2022 | [DOI](Dubayah, R. et al. (2022). GEDI L2A Height Metrics. NASA ORNL DAAC. https://doi.org/10.3334/ORNLDAAC/1953) | — |
| [Copernicus CGLS-LC100](land.copernicus.eu/en/…-globe) | 2019 | 100 м | Да | 2019 | [DOI](Buchhorn, M. ; Lesiv, M. ; Tsendbazar, N. - E. ; Herold, M. ; Bertels, L. ; Smets, B. Copernicus Global Land Cover Layers-Collection 2. Remote Sensing 2020, 12Volume 108, 1044. doi:10.3390/rs12061044
Buchhorn, M., Smets, B., Bertels, L., Roo, B. D., Lesiv, M., Tsendbazar, N.-E., Herold, M., & Fritz, S. (2020). Copernicus Global Land Service: Land Cover 100m: collection 3: epoch 2017: Globe (Version V3.0.1) [Data set]. Zenodo.
Buchhorn, M., Smets, B., Bertels, L., Roo, B. D., Lesiv, M., Tsendbazar, N.-E., Herold, M., & Fritz, S. (2020). Copernicus Global Land Service: Land Cover 100m: collection 3: epoch 2018: Globe (Version V3.0.1) [Data set]. Zenodo.
Buchhorn, M., Smets, B., Bertels, L., Roo, B. D., Lesiv, M., Tsendbazar, N.-E., Herold, M., & Fritz, S. (2020). Copernicus Global Land Service: Land Cover 100m: collection 3: epoch 2015: Globe (Version V3.0.1) [Data set]. Zenodo.
Buchhorn, M., Smets, B., Bertels, L., Roo, B. D., Lesiv, M., Tsendbazar, N.-E., Herold, M., & Fritz, S. (2020). Copernicus Global Land Service: Land Cover 100m: collection 3: epoch 2019: Globe (Version V3.0.1) [Data set]. Zenodo.) | — |
| [Dynamic World](dynamicworld.app/) | 2024 | 10 м | Да | Актуальный, в near-real-time | [DOI](недоступна) | — |
| [ESRI 10m Annual Land Cover](livingatlas.arcgis.com/landcover/) | 2023 | 10 м | Да (через Community Catalog) | Ежегодно, до 2023 | — | — |
| [GLC NMO: Global Land Cover by National Mapping Organisations](globalmaps.github.io/glcnmo.html) | 2017 | 500 м | Нет | 2017 | [DOI](Tateishi, R., Bayaer, U., Al-Bilbisi, H., Aboel Ghar, M., Tsend-Ayush, J., Kobayashi, T., Kasimuf, A., Thanh Hoan, N., Shalaby, A., Alsaaideh, B., Enkhzaya, T., Gegentana, Sato, H. P. (2011). Production of global land cover data - GLCNMO, International Journal of Digital Earth, 4(1), 22-49, http://dx.doi.org/10.1080/17538941003777521

Tateishi, R., Thanh Hoan, N., Kobayashi, T., Alsaaideh, B., Tana, G., Xuan Phong, D. (2014). Production of Global Land Cover Data - GLCNMO2008, Journal of Geography and Geology, Vol. 6, No. 3, 99-122, 2014, http://dx.doi.org/10.5539/jgg.v6n3p99

Kobayashi, T., Tateishi, R., Alsaaideh, B., Sharma, R.C., Wakaizumi, T., Miyamoto, D., Bai, X., Long, B.D., Gegentana, G., Maitiniyazi, A. (2017). Production of Global Land Cover Data - GLCNMO2013. Journal of Geography and Geology, Vol. 9, No. 3, 1-15, 2017, http://dx.doi.org/10.5539/jgg.v9n3p1) | — |
| [GlobCover: Global Land Cover Map](https://developers.google.com/earth-engine/datasets/catalog/ESA_GLOBCOVER_L4_200901_200912_V2_3) | 2009 | 300 м | Да | 2009 | [DOI](Arino, O. et al. (2012). Global Land Cover Map for 2009 (GlobCover 2009). https://doi.org/10.1594/PANGAEA.787668) | — |
| [Global Land Cover - SHARE (GLC-SHARE)](https://www.fao.org/land-water/land/land-governance/land-resources-planning-toolbox/category/details/en/c/1036355) | 2013 | 1 км | Нет | 2013 | [DOI](FAO (2014). Global Land Cover - SHARE (GLC-SHARE). Beta-Release v1.0. https://www.fao.org/land-water/land/land-governance/land-resources-planning-toolbox/category/details/en/c/1036355) | — |
| [Global Land Cover and Land Use Change, 2000-2020](https://glad.earthengine.app/view/glcluc-2000-2020) | 2020 | 30 м | Да (Community Catalog) | 2000-2020 | [DOI](Potapov, P. et al. (2022). Global land cover and land use change 2000-2020. Frontiers in Remote Sensing, 3, 856903. https://doi.org/10.3389/frsen.2022.856903) | — |
| [Global Natural and Planted Forests (2024)](https://gee-community-catalog.org/projects/global_ftype) | 2024 | 30 м | Да (Community Catalog) | 2024 | [DOI](FAO (2024). Global planted forest data for timber species. Scientific Data, 11, 4125. https://doi.org/10.46830/writn.23.00073) | — |
| [Global PALSAR-2/PALSAR/JERS-1 Mosaic and Forest/Non-Forest map](https://developers.google.com/earth-engine/datasets/catalog/JAXA_ALOS_PALSAR_YEARLY_FNF) | 2024 | 25 м | Да | 2024 | [DOI](Shimada, M. et al. (2014). New global forest/non-forest maps from ALOS PALSAR data. RSE, 155, 13-31. https://doi.org/10.1016/j.rse.2014.04.014) | — |
| [Global Vegetation Height Metrics from GEDI and ICESat2](https://www.earthdata.nasa.gov/data/catalog/ornl-cloud-gedi-icesat2-global-veg-height-2294-1) | 2021 | 1 км | Да (Community Catalog) | 2019-2022 | [DOI](Dubayah, R. et al. (2022). GEDI L2A Height Metrics. NASA ORNL DAAC. https://doi.org/10.3334/ORNLDAAC/1953) | — |
| [Global land cover and land use 2019, v1.0](https://glad.earthengine.app/view/global-land-cover-land-use-v1) | 2019 | 30 м | Да (Community Catalog) | 2019 | [DOI](Potapov, P. et al. (2022). The global 2019 land cover and land use map. Frontiers in Remote Sensing, 3, 856903. https://doi.org/10.3389/frsen.2022.856903) | — |
| [Tree Species SDM](https://www.nature.com/articles/s41597-024-04125-y) | 2024 | ~1 км | Нет (Asset) | 2024 | [DOI](Kindt, R. et al. (2023). TreeGOER. Global Change Biology, 29, 3919-3931. https://doi.org/10.5281/zenodo.7922927) | — |
| [Global Peatlands (GFW)](https://www.globalforestwatch.org) | 2023 | Вектор | Да (Community Catalog) | 2023, Актуальный | [DOI](Global Forest Watch / WRI (2023). Global Peatlands. https://www.globalforestwatch.org) | — |
| [The Global Peatland Database](https://greifswaldmoor.de/global-peatland-database-en.html) | 2024 | Вектор | Нет (по запросу) | 2024 | [DOI](Greifswald Mire Centre (2024). Global Peatland Database. https://greifswaldmoor.de/global-peatland-database-en.html) | — |
| [Global Safety Net (GSN)](https://www.globalsafetynet.app/) | 2020 | ~1 км | Нет | 2020 | [DOI](https://doi.org/10.1126/sciadv.aaw2869) | — |
| [GLASS-GLC (Global Land Surface Satellite Land Cover)](https://essd.copernicus.org/articles/12/1217/2020/) | 2015 | 5 км | Нет | 1982–2015 | [DOI](https://doi.org/10.5194/essd-12-1217-2020) | — |

### 3. Климатические и погодные условия

| Название | Год | Разрешение | В GEE | Период | Цитирование | Источник |
|----------|-----|-----------|-------|--------|-------------|---------|
| [ESA CCI Soil Moisture](https://gee-community-catalog.org/projects/esa_soil_moisture) | 2023 | 25 км | Да (Community Catalog) | 1978-2023, долговременный ряд | [DOI](Dorigo, W. et al. (2017). ESA CCI Soil Moisture. RSE, 201, 189-204.) | — |
| [SMAP L3 Soil Moisture](https://developers.google.com/earth-engine/datasets/catalog/NASA_SMAP_SPL3SMP_E_006) | 2025 | 9 км | Да | Актуальный, ежедневно | [DOI](O'Neill, P. et al. (2024). SMAP L3 Radiometer Global Daily Soil Moisture. NASA NSIDC DAAC. https://doi.org/10.5067/E5P3TNLV2SZG) | — |
| [Global Fire WEather Database (GFWED)](https://gee-community-catalog.org/projects/gfwed) | 2023 | 0.25° | Да (Community Catalog) | Актуальный | [DOI](Field, R.D. et al. (2015). Development of a Global Fire Weather Database. NHESS, 15, 1409-1423.) | — |
| [TerraClimate](https://developers.google.com/earth-engine/datasets/catalog/IDAHO_EPSCOR_TERRACLIMATE) | 2025 | ~4 км | Да | Актуальный, ежемесячно | [DOI](Abatzoglou, J.T. et al. (2018). TerraClimate. Scientific Data, 5, 170191. https://doi.org/10.1038/sdata.2017.191) | — |
| [WWLLN Global Lightning](https://wwlln.net) | 2025 | ~10 км | Нет | Актуальный, непрерывно | [DOI](Holzworth, R.H. et al. (2022). WWLLN Global Lightning. ESSD, 14, 5665-5682.) | — |
| [CHIRPS Daily](https://developers.google.com/earth-engine/datasets/catalog/UCSB-CHG_CHIRPS_DAILY) | 2025 | 0.05° (~5 км) | Да | Актуальный, с задержкой | [DOI](Funk, C. et al. (2015). The climate hazards infrared precipitation with stations. Scientific Data, 2, 150066. https://doi.org/10.1038/sdata201566) | — |
| [GSMaP Precipitation](https://developers.google.com/earth-engine/datasets/catalog/JAXA_GPM_L3_GSMaP_v8_operational) | 2025 | 0.1° (~10 км) | Да | Актуальный, оперативный | [DOI](Kubota, T. et al. (2020). GSMaP. JAXA. https://sharaku.eorc.jaxa.jp/GSMaP/) | — |
| [AgERA5](https://www.climateengine.org) | 2025 | ~10 км | Нет (CDS) | Актуальный | [DOI](ECMWF / Copernicus (2023). Agrometeorological indicators from 1979 to present. https://doi.org/10.24381/cds.6c68c9bb) | — |
| [SPEIbase](https://developers.google.com/earth-engine/datasets/catalog/CSIC_SPEI_2_10) | 2023 | 0.5° | Да | 2023 | [DOI](Begueria, S. et al. (2017). SPEIbase. https://spei.csic.es/database.html) | — |
| [ERA5-Land Daily](https://developers.google.com/earth-engine/datasets/catalog/ECMWF_ERA5_LAND_DAILY_AGGR) | 2025 | ~9 км | Да | Актуальный, с задержкой | [DOI](Munoz Sabater, J. (2021). ERA5-Land. ESSD, 13, 4349-4383. https://doi.org/10.5194/essd-13-4349-2021) | — |
| [ERA5-based Global Meteorological Wildfire Danger Maps](https://www.nature.com/articles/s41597-020-0554-z) | 2020 | 0.25° | Нет (CDS) | 2020 | [DOI](Vitolo, C. et al. (2020). ERA5-based global meteorological wildfire danger maps. Scientific Data, 7, 216. https://doi.org/10.1038/s41597-020-0554-z) | — |
| [GFS](https://developers.google.com/earth-engine/datasets/catalog/NOAA_GFS0P25) | 2025 | 0.25° (~25 км) | Да | Актуальный, оперативный прогноз | [DOI](NCEP / NOAA (2023). Global Forecast System. https://www.ncei.noaa.gov/products/weather-climate-models/global-forecast) | — |
| [MERRA-2](https://developers.google.com/earth-engine/datasets/catalog/NASA_GSFC_MERRA_slv_2) | 2025 | 0.5° x 0.625° | Да | Актуальный, с задержкой | [DOI](Gelaro, R. et al. (2017). MERRA-2. J. Climate, 30, 5419-5454. https://doi.org/10.1175/JCLI-D-16-0758.1) | — |
| [ERA5 Hourly Wind Data](https://developers.google.com/earth-engine/datasets/catalog/ECMWF_ERA5_LAND_HOURLY) | 2025 | ~9 км | Да | Актуальный, ежечасно | [DOI](Munoz Sabater, J. (2019). ERA5-Land. Copernicus C3S. https://doi.org/10.24381/cds.e2161bac) | — |
| [MODIS LST](https://developers.google.com/earth-engine/datasets/catalog/MODIS_061_MOD11A2) | 2025 | 1 км | Да | Актуальный, каждые 8 дней | [DOI](Wan, Z. (2021). MOD11A2 V6.1. NASA LP DAAC. https://doi.org/10.5067/MODIS/MOD11A2.061) | — |
| [VIIRS LST](https://developers.google.com/earth-engine/datasets/catalog/NASA_VIIRS_002_VNP21A1D) | 2025 | 1 км | Да | Актуальный, ежедневно | [DOI](NASA (2023). VNP21 LST. https://doi.org/10.5067/VIIRS/VNP21.001) | — |

### 4. Лесоизменения

| Название | Год | Разрешение | В GEE | Период | Цитирование | Источник |
|----------|-----|-----------|-------|--------|-------------|---------|
| [Global Forest Change](https://storage.googleapis.com/earthenginepartners-hansen/GFC-2024-v1.12/download.html) | 2024 | 30 м | Да | 2024 | [DOI](Hansen, M.C. et al. (2013). High-Resolution Global Maps of 21st-Century Forest Cover Change. Science, 342, 850-853. https://doi.org/10.1126/science.1244693) | — |
| [FireCCI51 Burned Area](https://developers.google.com/earth-engine/datasets/catalog/ESA_CCI_FireCCI_5_1) | 2020 | ~250 м | Да | До 2020 | [DOI](Chuvieco, E. et al. (2018). Generation and analysis of a new global burned area product based on MODIS 250m. Int. J. Digital Earth, 11, 889-910. https://doi.org/10.1080/17538947.2018.1424256) | — |
| [GlobMap FFP v1.0](https://essd.copernicus.org/preprints/essd-2025-733) | 2025 | 30 м | Нет (ожидается) | 2025 | [DOI](Chen, Y. et al. (2025). GlobMap FFP v1.0. ESSD Preprint. https://doi.org/10.5194/essd-2025-733) | — |
| [Global Forest Disturbance Type](https://essd.copernicus.org/articles/18/1601/2026) | 2025 | 30 м | Нет (ожидается) | 2025 | [DOI](Wang, L. et al. (2026). Global high-resolution forest disturbance type dataset. ESSD, 18, 1601. https://doi.org/10.5194/essd-18-1601-2026) | — |
| [Global forest loss due to fire](https://glad.earthengine.app/view/global-forest-loss-due-to-fire) | 2024 | 30 м | Да (Community Catalog) | До 2024 | [DOI](Tyukavina, A. et al. (2022). Global trends of forest loss due to fire. Frontiers in Remote Sensing, 3, 825190. https://doi.org/10.3389/frsen.2022.825190) | — |
| [MCD64A1 Burned Area](https://developers.google.com/earth-engine/datasets/catalog/MODIS_061_MCD64A1) | 2022 | 500 м | Да | Ежегодно, до 2022 | [DOI](Giglio, L. et al. (2018). The Collection 6 MODIS burned area mapping algorithm and product. RSE, 217, 72-85. https://doi.org/10.1016/j.rse.2018.08.005) | — |
| [GFW GLAD Alerts](https://developers.google.com/earth-engine/datasets/catalog/UMD_GLAD_GLAD_ALERT) | 2025 | 30 м | Да | Актуальный, оперативно | [DOI](Hansen, M.C. et al. (2016). Humid tropical forest disturbance alerts using Landsat data. Environmental Research Letters, 11(3).) | — |
| [MTBS Burn Severity (США)](https://gee-community-catalog.org/projects/mtbs) | 2024 | 30 м | Да (Community Catalog) | Актуальный, до 2024 | [DOI](Eidenshink, J. et al. (2007). MTBS Project. https://www.mtbs.gov) | — |
| [Global Fire Atlas (2003-2016)](https://gee-community-catalog.org/projects/gfa) | 2019 | 500 м | Да (Community Catalog) | 2003-2016 | [DOI](Andela, N. et al. (2019). The Global Fire Atlas. ESSD, 11, 529-550. https://doi.org/10.5194/essd-11-529-2019) | — |

### 5. Антропогенное влияние

| Название | Год | Разрешение | В GEE | Период | Цитирование | Источник |
|----------|-----|-----------|-------|--------|-------------|---------|
| [Global Roads (GRID3)](https://gee-community-catalog.org/projects/grid3) | 2023 | Вектор | Да (Community Catalog) | 2023, Актуальный | [DOI](CIESIN (2023). GRID3 Global Roads.) | — |
| [Global Human Settlement Layer (GHSL)](https://developers.google.com/earth-engine/datasets/catalog/JRC_GHSL_P2023A_GHS_BUILT_S) | 2023 | 10-100 м | Да | 2023, Актуальный | [DOI](Pesaresi, M. et al. (2023). GHS-BUILT-C R2023A. European Commission, JRC. https://doi.org/10.2905/3C60DDF6-0586-4190-854B-F6AA0EDC2A30) | — |
| [OpenStreetMap (OSM)](https://developers.google.com/earth-engine/datasets/catalog/sat-io_open-datasets_OSM) | 2025 | Вектор | Да (Community Catalog) | Постоянно обновляется | [DOI](OpenStreetMap contributors (2024). OpenStreetMap. https://doi.org/10.6084/m9.figshare.10048412.v1) | — |
| [World Settlement Footprint](https://developers.google.com/earth-engine/datasets/catalog/DLR_WSF_WSF2015_v1) | 2015 | 10 м | Да | 2015 | [DOI](Marconcini, M. et al. (2020). World Settlement Footprint 2015. Scientific Data, 7, 119. https://doi.org/10.1038/s41597-020-00580-5) | — |
| [OPERA Disturbance Alert](https://www.earthdata.nasa.gov/data/catalog/lpcloud-opera-l3-dist-alert-hls-v1-1) | 2025 | 30 м | Да | Актуальный, оперативный | [DOI](NASA JPL (2024). OPERA Land Surface Disturbance Alert. https://doi.org/10.5067/OPERA/dist-alert-hls-v1.1) | — |
| [WorldPop](https://developers.google.com/earth-engine/datasets/catalog/WorldPop_GP_100m_pop) | 2025 | 100 м | Да | Ежегодно, актуальный | [DOI](Tatem, A.J. (2017). WorldPop, open data for spatial demography. Scientific Data, 4, 170004. https://doi.org/10.1038/sdata2017.4) | — |
| [WDPA — World Database on Protected Areas](https://gee-community-catalog.org/projects/wdpa) | 2024 | Вектор | Да (Community Catalog) | 2024, Актуальный | [DOI](UNEP-WCMC & IUCN (2024). Protected Planet: WDPA.) | — |
| [Gridded Livestock of the World (GLW)](https://gee-community-catalog.org/projects/glw) | 2022 | ~10 км | Да (Community Catalog) | 2022 | [DOI](Gilbert, M. et al. (2022). Global distribution of cattle, sheep, goats, pigs and poultry. Scientific Data, 9, 189.) | — |
| [Global Cropland Extent (GFSAD)](https://developers.google.com/earth-engine/datasets/catalog/USGS_GFSAD_LC_CroplandExtent_2015) | 2015 | 30 м | Да | 2015 | [DOI](Thenkabail, P.S. et al. (2016). NASA MEaSUREs GFSAD. NASA LP DAAC.) | — |
| [Global forest management data for 2015 at a 100 m resolution](https://www.nature.com/articles/s41597-022-01332-3) | 2015 | 100 м | Да (Community Catalog) | 2015 | [DOI](Lesiv, M. et al. (2022). Global forest management data for 2015 at a 100 m resolution. Scientific Data, 9, 199. https://doi.org/10.1038/s41597-022-01332-3) | — |

### 6. Пожарный мониторинг

| Название | Год | Разрешение | В GEE | Период | Цитирование | Источник |
|----------|-----|-----------|-------|--------|-------------|---------|
| [FIRMS Global Vector Data (MODIS + VIIRS)](https://gee-community-catalog.org/projects/firms_vector) | 2025 | 375 м - 1 км | Да (Community Catalog) | Актуальный, NRT | [DOI](NASA FIRMS (2025). Archival NRT FIRMS Global VIIRS and MODIS Vector Data.) | — |
| [NASA FIRMS](https://www.earthdata.nasa.gov/data/tools/firms) | 2025 | 375 м (VIIRS) / 1 км (MODIS) | Да | Актуальный | [DOI](Giglio, L. et al. (2016). MODIS Collection 6 Active Fire Product. https://doi.org/10.5067/FIRMS/MODIS/MOD14A1.006) | — |
| [MCD19A2 MAIAC Aerosol Optical Depth](https://developers.google.com/earth-engine/datasets/catalog/MODIS_061_MCD19A2_GRANULES) | 2025 | 1 км | Да | Актуальный, ежедневно | [DOI](Lyapustin, A. et al. (2018). MCD19A2 MODIS/Terra+Aqua MAIAC Land Aerosol Product. NASA LP DAAC.) | — |
| [Burning Index (CEMS)](https://app.climateengine.org/climateEngine) | 2025 | 0.25° | Нет (Climate Engine) | Актуальный | [DOI](Copernicus EMS (2023). Fire danger indices historical data. https://doi.org/10.24381/cds.ca755de7) | — |
| [Fire Weather Index (CEMS)](https://app.climateengine.org/climateEngine) | 2025 | 0.25° | Нет (Climate Engine) | Актуальный | [DOI](Copernicus EMS (2023). Fire danger indices historical data. https://doi.org/10.24381/cds.ca755de7) | — |
| [GFW Fire Alerts (VIIRS)](https://gee-community-catalog.org/projects/gfw_fire) | 2025 | 375 м | Да (Community Catalog) | Актуальный, ежедневно | [DOI](Global Forest Watch (2025). VIIRS Active Fire Alerts. https://www.globalforestwatch.org) | — |
| [Wildfire Risk to Communities (WRC)](https://gee-community-catalog.org/projects/wrc) | 2020 | 30 м - 270 м | Да (Community Catalog) | 2020 | [DOI](USDA Forest Service (2020). Wildfire Risk to Communities. https://www.wildfirerisk.org) | — |
| [WGLC 2022 Update](zenodo.org/rec…277101) | 2022 | 5 аркминут | Нет | 2022 | [DOI](Kaplan, J. O. and Lau, K. H.-K.: World Wide Lightning Location Network (WWLLN) Global Lightning Climatology (WGLC) and time series, 2022 update, Earth Syst. Sci. Data, 14, 5665–5670, https://doi.org/10.5194/essd-14-5665-2022, 2022.) | — |
| [TRMM-LIS/OTD Gridded Lightning Climatology](https://ghrc.nsstc.nasa.gov/home/field-campaigns/lisotd) | 2014 | 0.5° и 2.5° | Нет | 1995–2015 | [DOI](Cecil, D. J., Buechler, D. E., and Blakeslee, R. J.: Gridded lightning climatology from TRMM-LIS and OTD: Dataset description, Atmos. Res., 135-136, 404-414, https://doi.org/10.1016/j.atmosres.2012.06.028, 2014.) | — |
| [ISS LIS (Lightning Imaging Sensor on ISS)](https://earthdata.nasa.gov/data/catalog/ghrc-daac-isslis-v2-fin-2) | 2020 | 0.05° (~5.5 км) в исходных данных | Нет | 2017–2023 | [DOI](Blakeslee, R. J., Koshak, W. J., Mach, D. M., and Stewart, M. F.: Algorithm Theoretical Basis Document (ATBD) for the Lightning Imaging Sensor (LIS) on the International Space Station (ISS), NASA/TM-2020, 2020.) | — |
| [Combined ISS & TRMM LIS Annual Thunder Hour](https://earthdata.nasa.gov/data/catalog/ghrc-daac-comblisath-1) | 2025 | 0.05° (~5.5 км) | Нет | 1998–2023 (24 года) | [DOI](Virts, K. and Lang, T.: Annual Mean Combined Lightning Imaging Sensor (LIS) Thunder Hour Data, NASA GHRC DAAC, https://doi.org/10.5067/COMBLIS/ATH/DATA101, 2025.) | — |
| [GOES GLM (Geostationary Lightning Mapper)](https://www.goes-r.gov/spacesegment/glm.html) | 2018 | ~8 км (в надире), 0.2° для L3 продуктов | Нет | 2018 — настоящее время | [DOI](Goodman, S. J., Blakeslee, R. J., Koshak, W. J., Mach, D., Stewart, M., McCaul, E. W., Jr., et al.: The GOES-R Geostationary Lightning Mapper (GLM), Atmos. Res., 125-126, 34-49, https://doi.org/10.1016/j.atmosres.2013.01.006, 2013.) | — |
| [MTG Lightning Imager (EUMETSAT)](https://user.eumetsat.int/resources/user-guides/mtg-li-level-2-data-guide) | 2024 | ~4.5 км (в надире) | Нет | 2024 — настоящее время | [DOI](EUMETSAT: MTG Lightning Imager Level 2 Product Guide, EUM/MTG-LI/PG, 2024. https://user.eumetsat.int/resources/user-guides/mtg-li-level-2-data-guide) | — |
| [FLASHMAP — Global Gridded Lightning Dataset (high resolution)](https://edepot.wur.nl/709084) | 2025 | 0.1° (~10 км) | Нет (публикуется) | В публикации | [DOI](Qie, X., Liu, M., and Soula, S.: FLASHMAP: A new global gridded lightning dataset with high spatial and temporal resolution, EGU General Assembly 2025, EGU25-8351, https://doi.org/10.5194/egusphere-egu25-8351, 2025.) | — |

---

## Как цитировать / How to cite

Пуреховский А.Ж., Институт географии РАН (2026). *Каталог глобальных геопространственных покрытий природных факторов*. Zenodo. https://doi.org/10.5281/zenodo.22730919

Purekhovsky A.Zh., Institute of Geography RAS (2026). *Global Geospatial Dataset Catalog of Natural Factors*. Zenodo. https://doi.org/10.5281/zenodo.22730919

---

## Лицензия / License

[Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/)

При использовании — указывать авторов и ссылку на репозиторий / When using — please cite the authors and link to this repository.
