---
title: Data
layout: default
permalink: /data
---

<h1>Data</h1>
<h2>What is data?</h2>
<p>Please check out the Toolkit section on "<a href="/definitions">What is open data</a>" for information about different data types, what to prioritise, and how to publish unit record data in an appropriate way for public consumption.
</p>
<h2>Clean data</h2>
<p>Make sure at least one of the data files you upload to your dataset is as clean as possible. This will make it easier for others to reuse. As outlined above the best option for this is a CSV file, with as few mistakes or bad data entries as possible. For instance, make sure all the dates are a common format, and that there are no missing entries and there is no non-text data embedded. For tabular data you just want a spreadsheet with a single header row and then multiple fields. KML data has its own format that must be followed.
</p><p>CKAN specifically understands tabular and spatial data types and generates API access to such datasets, if the data files are clean. Clean means the datasets are raw and appropriately structured data. More information on clean data can be found here <a href="http://www.clean-sheet.org/">http://www.clean-sheet.org/</a>
</p><p>For example:
</p>
<table>
<caption>This is an example of raw clean tabular data:
</caption>
<tbody><tr>
<th>Date
</th>
<th>Age
</th>
<th>Gender
</th>
<th>Postcode
</th></tr>
<tr>
<td>20/10/2013
</td>
<td>12
</td>
<td>M
</td>
<td>2580
</td></tr>
<tr>
<td>10/01/2013
</td>
<td>15
</td>
<td>F
</td>
<td>1462
</td></tr>
<tr>
<td>02/11/2011
</td>
<td>22
</td>
<td>M
</td>
<td>3652
</td></tr>
<tr>
<td>12/05/2012
</td>
<td>45
</td>
<td>F
</td>
<td>1464
</td></tr>
<tr>
<td>19/01/2010
</td>
<td>75
</td>
<td>F
</td>
<td>1800
</td></tr></tbody></table>
<table>
<caption>This is not raw clean data:
</caption>
<tbody><tr>
<th >Copyright of Dept. X
</th>
<th colspan="3">
</th></tr>
<tr>
<td colspan="4">&nbsp;
</td></tr>
<tr>
<th>Date
</th>
<th>Age
</th>
<th>Gender
</th>
<th>Postcode
</th></tr>
<tr>
<td>01/20/2013
</td>
<td>Fifteen
</td>
<td>M
</td>
<td>Barton
</td></tr>
<tr>
<td>10th Dec 11
</td>
<td>15
</td>
<td>Fem
</td>
<td>&nbsp;
</td></tr>
<tr>
<td>02/11/2011
</td>
<td>xx
</td>
<td>Male
</td>
<td>3652
</td></tr>
<tr>
<td>12/05/2012
</td>
<td>45
</td>
<td>F
</td>
<td>1464
</td></tr></tbody></table>
<table >

<tbody><tr>
<th>Important Note
</th></tr>
<tr>
<td>Due to the nature of our database if you would like to allow API access to your dataset you will need to keep your <b>column headings under 63 characters</b>.
</td></tr></tbody></table>
<p><br>
</p>
<table >

<tbody><tr>
<th>Removing Author Metadata
</th></tr>
<tr>
<td>It is possible that some filetypes will contain additional author metadata. It is possible to remove this metadata using the Windows interface.
</td></tr></tbody></table>
<h2>Spatial data</h2>
<p>At the end of 2013 we expanded the geospatial functionality of data.gov.au. These changes established additional and improved support specifically for spatial data services. This means data.gov.au can now present a spatial API endpoint for certain types of spatial files. An example of the new functionality can be found seen in the <a href="https://data.gov.au/dataset/geelong-roofprints-kml">Geelong Roofprints dataset</a>.
</p><p>When any of the supported filetypes (outlined below) are uploaded through the CKAN platform they will automatically be added to the GeoServer. There should be no need for user intervention but it can take up to 24 hours for the file to be ingested. At the moment data ingested daily. We are looking at ways to make ingestion more immediate.
</p><p>Spatial data on data.gov.au is also viewable through the <a href="http://nationalmap.nicta.com.au/">National Map</a>. To access the visualisation click the <b>Data</b> button on the left, click <b>Data Providers</b>and then click data.gov.au. It may take up to 24 hours for newly added datasets to become available on the National Map.
</p>
<ul >
		<li  ><div >
			<div  ><div ><a href="/assets/file/Spatial-generated-resources.jpg" ><img alt="" src="/images/thumb/6/66/Spatial-generated-resources.jpg/169px-Spatial-generated-resources.jpg" width="169" height="120" srcset="/images/thumb/6/66/Spatial-generated-resources.jpg/253px-Spatial-generated-resources.jpg 1.5x, /images/thumb/6/66/Spatial-generated-resources.jpg/337px-Spatial-generated-resources.jpg 2x"></a></div></div>
			<div >
<p><b>GeoJSON, WMS and WFS resources will be automatically added to spatial datasets if ingested correctly</b>
</p>
			</div>
		</div></li>
</ul>
<h3>Supported Filetypes</h3>
<p>Currently supported vector filetypes are MapInfo TAB, KML, KMZ and SHP. Currently supported raster filetypes are GeoTIFF and ESRI ArcGRID (ASCII and binary)
</p><p>For the moment other formats can be converted using the Feature Manipulation Engine (FME) or Geospatial Data Abstraction Library (GDAL). There is currently no limit for the size of a file uploaded but whenever possible please make the data.gov.au team aware should you need to upload a large file.
</p>
<h3>Uploading spatial data</h3>
<p>At this time data.gov.au only supports a single spatial file per dataset. If a dataset contains multiple spatial resources it will be ignored by the geoserver ingestor. Once the spatial file is successfully ingested into the geoserver data.gov.au will automatically generate a number of additional resources for the dataset.
</p>
<h4>KML / KMZ files</h4>
<p>data.gov.au will accept either KML and KMZ files. Simply upload the file using the normal process as outlined in the, <a href="/use-datagovau#Posting_a_new_dataset">‘posting a dataset’ section</a>.
</p>
<h4>Shape files</h4>
<p>Before uploading a shape file you should zip all the relevant files into a single archive. When adding the zip file as a resource set the format to ‘shp’.
</p>
<h4>Colors/Styles/Symbology</h4>
<p>It is possible that the incorrect display style for spatial data is displayed in the WMS preview. It is important to note that this does not modify the data as it is served via the WMS/WFS APIs. 
</p><p>To provide a custom display style, attach another data resource in "SLD" Styled Layer Definition format <a href="http://docs.geoserver.org/latest/en/user/styling/sld/cookbook/index.html#sld-cookbook">http://docs.geoserver.org/latest/en/user/styling/sld/cookbook/index.html#sld-cookbook</a> 
</p><p>It may be possible to convert ESRI .style/.lyr files to SLD <a href="https://github.com/nyalldawson/slyr">https://github.com/nyalldawson/slyr</a>
</p><p>It is also possible to modify the default display type for the data for any user which has admin access to the GeoServer.
</p>
<ol><li>Point your browser to <a href="https://data.gov.au/geoserver/web/">https://data.gov.au/geoserver/web/</a></li>
<li>If required login using the form at the top of the page.</li>
<li>From the admin screen select the Layers link.</li>
<li>From here select the layer you’d like to change by clicking the Layer Name.</li>
<li>Select the Publishing tab.</li>
<li>From the Default Style dropdown select the style you’d like to use.</li>
<li>Scroll to the bottom of the page and click the Save button.</li></ol>
<h2>Spatial API Access</h2>
<p>Web Map Service (WMS) and Web Feature Service (WFS) API links will be created with the datasets when a supported filetype is added. Information about available methods can be found at: <a href="http://docs.geoserver.org/stable/en/user/services/wfs/index.html">http://docs.geoserver.org/stable/en/user/services/wfs/index.html</a> and, <a href="http://docs.geoserver.org/stable/en/user/services/wms/index.html">http://docs.geoserver.org/stable/en/user/services/wms/index.html</a>.
</p>
