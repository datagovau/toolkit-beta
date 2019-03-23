---
title: Platform Information
layout: default
permalink: /platform-information
---
<div >

<h1>Data.gov.au Platform</h1>
<p>Data.gov.au platform is cloud based installation of CKAN, an open source data catalogue software.
</p><p>The customised plugins used for the platform are available on Github at <a href="https://github.com/datagovau">https://github.com/datagovau</a>
</p>
<h2>Platform Architecture</h2>
<div ><div ><a href="/assets/file/Ckan_Architecture.gif" ><img alt="Ckan Architecture.gif" src="/images/0/09/Ckan_Architecture.gif" width="540" height="824"></a></div></div>
<h2>Harvest filters</h2>
<p>For CSW service providers, the following filters may be used:
</p><p>Format:
csv, kml, shp, shapefile, xls, MapInfo, wms, wfs, csv, pGDB, tab, dat, misc, ArcGIS-grid,&nbsp;%grid%,&nbsp;%dat%,&nbsp;%tab%,&nbsp;%misc%
</p><p>Organisation:
Antarctic Climate and Ecosystems Cooperative Research Centre (ACE CRC), Antarctic CRC - The University of Tasmania, Busselton Underwater Observatory, Commonwealth of Australia (Geoscience Australia), Commonwealth of Australia (Geoscience Australia, LOSAMBA), Commonwealth Scientific and Industrial Research Organisation (CSIRO), CSIRO Marine and Atmospheric Research (CMAR), Department of Industry and Investment (DII), Department of Natural Resources and Mines, Queensland, NSW Department of Primary Industries, Department of Transport, Derwent Estuary Program, DTIRIS Resources &amp; Energy NSW, ECOCEAN, eMarine Information Infrastructure (eMII), Emergency Services GIS, Fisheries NSW, Primary Industries, Flinders University, Flinders University, School of Chemistry, Physics and Earth Sciences, Flinders University, School of Chemistry, Physics and Earth Sciences,, Flinders University, School of Chemisty, Physics and Earth Sciences, Geological Survey Division, Department of Mines and Petroleum, IMAS, University of Tasmania, Institute for Marine and Antarctic Studies (IMAS), University of Tasmania, Land and Property Information, Land and Property Information-NSW, Manly Hydraulics Laboratory, Marine Futures Project, The University of Western Australia (UWA), Marine Policy and Planning Branch, Department of Environment and Conservation, National Tidal Centre, NIWA National Institute of Water &amp; Atmospheric Research, NSW Department of Environment, Climate Change and Water (DECCW), NSW Department of Planning and Infrastructure, NSW Office of Environment and Heritage, NSW Rural Fire Service, Ocean Technology Group, University of Sydney, Office of Environment and Heritage, Office of Environment and Heritage (OEH), Oregon State University, Organisation at time of data collection, RPS MetOcean Pty. Ltd., SARDI Aquatic Sciences, School of Environment, Flinders University, School of Environmental Science, Murdoch University, School of the Environment, Flinders University, Tasmanian Aquaculture and Fisheries Institute, The Australian National University (ANU), The University of Sydney, University of Melbourne, University of Sydney, WA Department of Fisheries, WA Department of Fisheries - Scientific Custodian, WA Department of Fisheries - Technical Custodian, Water Corporation, Australian Bureau of Meteorology (BOM), Australian Electoral Commission (AEC), Australian Government Department of Sustainability, Environment, Water, Population and Communities, Australian Government Department of the Environment, Australian Governement Department of the Environment and Water Resources, Birds Australia, Centre for Plant Biodiversity Research, Centre for Research on Ecological Impacts of Coastal Cities (EICC), The University of Sydney (USYD), CSIRO Oceans &amp; Atmosphere Flagship - Hobart, Department of Earth and Marine Sciences (DEMS), The Australian National University (ANU) (Research School of Earth Sciences), Department of Primary Industries NSW, Department of the Environment, Department of Transport (WA), Discipline of Anatomy and Histology, The University of Sydney (USYD), Great Barrier Reef Marine Park Authority (GBRMPA), Institute for Marine and Antarctic Studies (IMAS), National Tidal Centre Unit, Research School of Earth Sciences (RSES), The Australian National University (ANU), School of Botany, The University of Melbourne, School of Chemistry, Physics and Earth Sciences (SoCPES), Flinders University, School of Geosciences, The University of Sydney (USYD), Tasmanian Aquaculture and Fisheries Institute (TAFI), The University of Sydney (USYD), Western Australian Museum (WAM), Western Australian Museum
</p>
<h2>Platform Changelog</h2>
<ul><li>27 January 2016 - Energy rating harvester set to run weekly instead of daily</li>
<li>22 January 2016 - Changed AGLS extension to pull license title from package dictionary when generating XML</li>
<li>12 January 2016 - Added non-labeled items to the energy rating for household appliances harvester</li>
<li>11 January 2016 - Fixed dataset template to have the correct link for published/unpublished datasets</li>
<li>8 January 2016 - Add zip extractor for automatic resource generation from Zipped files</li>
<li>8 January 2016 - Fixed validation error on dataset deletion for DataJSON harvester</li>
<li>8 January 2016 - Fixed harvesting issue with HTML being incorrectly escaped with DataJSON harvests</li>
<li>4 January 2016 - Fixed HTTPS redirect issue in the CKAN controller causing 503 errors</li>
<li>21 December 2015 - Fixed spatial ingestor trying to access the geoserver with incorrect credentials</li>
<li>8 December 2015 - Fixed Google analytics controller controller to correctly display datasets by publisher</li>
<li>3 December 2015 - Fixed resource_data template that was causing an internal server error when accessing certain datastore pages</li>
<li>2 November 2015 - Added Zip Preview and OData API plugins</li>
<li>30 October 2015 - More unpublished functionality including statistics and licences</li>
<li>22 October 2015 - Unpublished Dataset functionality added.</li>
<li>30 September 2015 - CORS API fixes</li>
<li>10 July 2015 - Added csv-geo-au format to automatically display CSVs on National Map, added additional optional views such as simple charts and dashboards</li>
<li>9 July 2015 - Backported patch for Data Explorer to handle special characters in column names</li>
<li>6 July 2015 - Improved datastore sql search API analytics and wiki redirect.</li>
<li>29 June 2015 - National Map viewer HTTPS and ArcGIS Open Data harvest enabled</li>
<li>10 June 2015 - 2.3 bugfix where API resources did not have format specified</li>
<li>4 June 2015 - CKAN 2.3 upgrade</li>
<li>27 May 2015 - KML resources ingested will have standard GDAL fields like icon removed</li>
<li>22 May 2015 - Add file sizes for resources, add monthly unique users for analytics reports</li>
<li>20 March 2015 - Fix group editing during dataset editing</li>
<li>04 March 2015 - Accessiblity Improvements: keyboard navigation including skip links improved, color choices for format badges changed to increase contrast and readability, search form structure changed to be more user friendly for screen reader/keyboard navigation users, organisation and use case layout changed, image "alt" text and heading structure reviewed</li>
<li>04 March 2015 - WMS Metadata improvements: geospatial dataset ingest records the actual spatial extent of the data and the WMS layer name in the metadata.</li>
<li>04 March 2015 - Search Partnership: Results from other Australian data portals appear in searches and link back to their source site.</li>
<li>07 February 2015 - Fix API Documentation links</li>
<li>22 January 2015 - More robust data matching between datasets and organisations in Site Analytics feature</li>
<li>09 January 2015 - Modified geospatial dataset ingest to unzip SHP/KMZ containing ZIP files while ignoring folder structure to maximize chance of data files being found</li>
<li>14 November 2014 - Expose support for hierarchies of organisations, enable Web Accessible Folder source for spatial data harvesting.</li>
<li>05 November 2014 - Add HTTPS CORS and JSONP to Geoserver, Add annual update frequency for metadata</li>
<li>24 October 2014 - Upgrade to CSW harvester to support more datasets from <a href="http://find.ga.gov.au">FIND</a></li>
<li>16 October 2014 - Upgrade to CKAN 2.2.1 and caching of Geoserver dataset listing.</li>
<li>25 September 2014 - Raster geospatial dataset ingest and API feature added.</li></ul>