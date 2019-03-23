---
title: Publishing your data
layout: default
permalink: /publishing-your-data
---

<h2>Publishing open data</h2>
<p>A fundamental aspect of open data is that it’s available for re-use with formats and licencing that allow others to re-use and remix the data.
This section will guide you through topics like:
</p>
<ul><li><a href="/publishing-your-data#publishing_open_data" title="Publishing your data">How to create datasets</a> from new or existing data</li>
<li>What <a href="/publishing-your-data#intro_to_metadata" title="Publishing your data">metadata</a> is and how you should add it</li>
<li>What <a href="/publishing-your-data#licensing_your_data" title="Publishing your data">licences</a> can be used for open data</li>
<li>Tools for finding <a href="/publishing-your-data#data_portals" title="Publishing your data">published data</a></li></ul>
<h3>Process to opening a dataset</h3>
<p>While each organisation’s approach to open data will vary, the first step is to determine the classification of the data. If it is unclassified then it is appropriate for public access. If it is classified, then you need to consider secure and non-open approaches to sharing the data. 
For a guide to improving your organisation’s open data capability, see the <a href="/planning#open_data_self-assessment" title="Planning">open data self-assessment</a>.
</p><p><b>Steps</b>
</p>
<ol><li><a href="/publishing-your-data#sourcing_data" title="Publishing your data">Choose data sets</a> for release in line with your organisation’s approach and your users’ needs.</li>
<li>Clarify who will be responsible for preparing, releasing and updating the data.</li>
<li><a href="/publishing-your-data#licensing_your_data" title="Publishing your data">Apply an open licence</a> – the APS default is Creative Commons Attribution</li>
<li><a href="/publishing-your-data#creating_datasets" title="Publishing your data">Make the data available</a></li>
<li><a href="/use-datagovau" title="How to use data.gov.au">Make the data discoverable on or through data.gov.au</a></li></ol>
<h2>Sourcing data</h2>
<p>These possible sources of data that your organisation could open should be considered as part of a larger process to develop and maintain an open data strategy.
</p>
<h3>Data from new projects</h3>
<p>When commissioning research, collecting data or establishing a new ICT system, adopt information management and procurement practices that ensure you have access to associated raw data in an open format and the right to publish that data online under an open licence. See <a href="/publishing-your-data#licensing_your_data" title="Publishing your data">Licensing your data</a> for more information. This is important if a service provider is contracted to collect the data or to develop a website or mobile app built on an agency data source. Effective information governance (<a href="http://www.oaic.gov.au/information-policy/information-policy-resources/information-policy-agency-resources/principles-on-open-public-sector-information">PSI Principle 3</a>) will help you ensure that your agency has access to the raw data that was used to create existing publications or apps.
</p><p>You should also ensure that other people in your organisation are aware that these governance processes and practices exist and are followed.
</p>
<h3>Releasing unpublished data</h3>
<p>Consider whether your agency has unpublished data that could be released as open data. This may come from public reports, studies and newsletters that have only included processed data with select results from internal analysis.
</p><p>Internal data such as project locations, demographic research and administrative data should also be considered for release.
</p><p>Agencies wishing to convert or release previously unpublished data should first consider legislative and policy requirements that may prevent publication or require modification of the data before release. 
</p><p>In particular, you should consider obligations under the Australian Privacy Principles (APPs) in the Privacy Act 1988. Guidance about the Privacy Act is available in the OAIC's <a href="http://www.oaic.gov.au/privacy/applying-privacy-law/app-guidelines/">APP Guidelines</a>. In addition, the OAIC's <a href="http://www.oaic.gov.au/information-policy/information-policy-resources/information-policy-agency-resources/information-policy-agency-resource-1-de-identification-of-data-and-information">Information Policy Agency Resource 1 — De-identification of data and information</a> discusses de-identification as a technique that allows agencies to balance privacy and transparency objectives when publishing open data. 
</p>
<h2>Creating datasets</h2>
<h3>Creating a basic open data set</h3>
<p>Creating a dataset can be a quick and easy process. At its most basic, a data set is simply a structured presentation of data, such as a spreadsheet, with some special features. These features can be designed as part of the data set from the beginning, or changed before publishing. 
</p><p>An open data set must be:
</p>
<h4>Saved in an open format</h4>
<p>Any type of data can be shared in an open format but sometimes this means transforming the data from the original format to a different format. The benefit to agencies in publishing data in an open format is it makes it easier for someone else to reuse the data, such as another government agency or company. The benefits of open data come often from the ability to analyse and remix data alongside other data sets.
</p><p>The table below rates common file types for their accessibility to users with a range of computing systems and access requirements.
</p><p>For data.gov.au, it should be noted that users can publish any data file type, and that Finance encourages organisations to publish the most machine readable and open format. Data.gov.au automatically generates full API access to tabular and spatial datasets uploaded to data.gov.au (through CKAN and Geoserver) and is investigating similar support for other data types. Agencies should contact the data.gov.au team if they are considering publishing relational databases, realtime data or other data types.
</p><p>If you are creating data for analysis or machine processing, it is important to note that spatial files, CSV and XLS are the only formats that automatically generate visualisations or API access for your data set on data.gov.au. CSV/XLS files will need to be structured according to the advice on the creating data sets page. Data.gov.au provides mapping services for some geospatial data types including KML, and will advise on additional formats as they are supported. 
</p>
<table>
<caption>Data formats
</caption>
<tbody><tr>
<th colspan="3">Tabular
</th></tr>
<tr>
<th>File type</th>
<th>Openness</th>
<th>Notes
</th></tr>
<tr>
<td>CSV</td>
<td>High</td>
<td>The best format for opening structured data (eg. As spreadsheets)
</td></tr>
<tr>
<td>XLS or XLSX</td>
<td>Low</td>
<td>Limits machine reading and use on non-Microsoft systems
</td></tr>
<tr>
<th colspan="3">Spatial
</th></tr>
<tr>
<th>File type</th>
<th>Openness</th>
<th>Notes
</th>
<td>
</td></tr>
<tr>
<td>KML</td>
<td>High</td>
<td>An open standard developed for Google Earth. May not translate to other systems. KMZ is also available as a packaged set of KML files.
</td></tr>
<tr>
<td>WMS</td>
<td>High</td>
<td>Standardised format for georeferenced map images
</td></tr>
<tr>
<td>WFS</td>
<td>High</td>
<td>Standardised format for geographical features
</td></tr>
<tr>
<th colspan="3">Text
</th></tr>
<tr>
<th>File type</th>
<th>Openness</th>
<th>Notes
</th></tr>
<tr>
<td>TXT</td>
<td>High</td>
<td>Simple text format readable on most operating systems. No formatting is available
</td></tr>
<tr>
<td>RTF</td>
<td>High</td>
<td>Simple text format readable on most operating systems which retains some formatting
</td></tr>
<tr>
<td>ODT</td>
<td>Medium</td>
<td>Limits machine reading
</td></tr>
<tr>
<td>DOC or DOCX</td>
<td>Low</td>
<td>Limits machine reading and use on non-Microsoft systems
</td></tr>
<tr>
<td>PDF</td>
<td>Low</td>
<td>Useful for document exchange to preserve formatting, but has limitations for machine reading, character recognition and remixing.
</td></tr>
</tbody></table>
<h4>Formatted properly for tabular data</h4>
<p>Any tabular data should be published in a CSV file as well as being included as a report. This allows users to analyse the data without having to convert it to an appropriate format. This is especially important for reports in formats such as PDF which restrict access to data and limit the ability for people to share and remix. PDFs should be made accessible or converted to an alternative format whenever possible. Tabular data for publishing should be both:
</p>
<ul><li>raw – presented in the simplest possible format with a single header row – and</li>
<li>clean – using uniform data formatting (eg. Numerical dates, postcodes in every field) with no missing entries, no embedded non-text information, data in every field and as few mistakes as possible.</li></ul>
<p>Obtaining raw, clean data can be a challenge if you’re converting an existing file into a file for uploading as part of a data set. It’s particularly important to look out for elements like merged cells and formulas which can prevent the data from being read.
</p><p>The examples below show how clean data can be easily compared and combined by a computer, whereas the non-clean data would confuse the system. For example, the use of Fem, Female and F could be processed as separate genders, and the ‘Copyright of Dept. X’ could cause an error in automatic processing of the data
</p>
<table>
<caption>Examples of raw, clean data
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
<td>20/10/2013</td>
<td>12</td>
<td>M</td>
<td>2580
</td></tr>
<tr>
<td>10/01/2013</td>
<td>-</td>
<td>F</td>
<td>1462
</td></tr>
<tr>
<td>02/11/2011</td>
<td>22</td>
<td>M</td>
<td>-
</td></tr>
<tr>
<td>12/05/2012</td>
<td>45</td>
<td>F</td>
<td>1464
</td></tr>
<tr>
<td>19/01/2010</td>
<td>75</td>
<td>F</td>
<td>1800
</td></tr></tbody></table>
<table>
<caption>Example of data that is not raw or clean
</caption>
<tbody><tr>
<td scope="row" colspan="4">Copyright of Dept. X
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
<td>01/20/2013</td>
<td>Fifteen</td>
<td>Female</td>
<td>Barton
</td></tr>
<tr>
<td>10th Dec 11</td>
<td>15</td>
<td>Fem</td>
<td>-
</td></tr>
<tr>
<td>02/11/2011</td>
<td>xx</td>
<td>Male</td>
<td>3652
</td></tr>
<tr>
<td>12/05/2012</td>
<td>45*</td>
<td>F</td>
<td>1464
</td></tr>
<tr>
<td>* Footnote information</td>
<td></td>
<td></td>
<td>
</td></tr></tbody></table>
<h4>Accompanied by supportive/contextual documentation</h4>
<p>Supportive documentation, caveats and contextual information should be included in descriptive information about the data set. If the information is extensive, it may also be possible to upload it as an additional resource to the dataset. <b>Please do not </b>put the data into the documentation itself, as it will restrict access to the data. This means the data will become less accessible to users, and will not be able to be picked up by APIs, data visualisation tools or other machine-to-machine processes.
</p>
<h4>Formatted to be useful</h4>
<p>Data should be published with consideration for how it will be most useful. For example, column labels with internal codes like ‘DBQ-12-W’ will be a lot less useful than human-readable labels like ‘Drop Bear Queries 2012 Western Site’.
</p><p>This is also a consideration when publishing data. For example, a data set on ‘procurement contract data’ with individual files for each year will make it easier for users to locate related data than individual data sets for each year. It will also be easier for data custodians to manage and maintain.
</p>
<h4>Extra credit</h4>
<p>As noted in the <a href="http://webguide.gov.au/">Australian Government Web Guide</a>, once the data is ready to publish in an open format, the agency should:
</p>
<ul><li>prepare appropriate metadata to accompany the dataset to ensure the data is discoverable and meaningful to the public. See <a href="/publishing-your-data#intro_to_metadata" title="Publishing your data">intro to metadata</a> for more information.</li>
<li>publish the data in an appropriate place, such as the agency website, data.gov.au, or an existing domain-specific collection or catalogue repository. See the <a href="/publishing-your-data#where_to_publish" title="Publishing your data">where to publish</a> page and the section on <a href="/use-datagovau">using data.gov.au</a>.</li></ul>
<p>You should also consider how to refine your approach so that the data (or subsequent releases of equivalent data) remains relevant and useful in future. This could include engaging with stakeholders; assessing how the data was reused; and considering whether the data should be presented in a different format or made accessible in different ways, such as through an application programming interface or API that allows programmers to easily reuse the data.
</p>
<h2>Where to publish</h2>
<p>There are a range of data publishing options available to government organisations based on the jurisdiction and type of data. See below for national data publishing options, or visit the <a href="/publishing-your-data#data_portals" title="Publishing your data">data portals</a> section for more information on state, territory and local data sites, as well as other resources like state globes.
</p><p>Federal
</p>
<ul><li><a href="https://data.gov.au/">Data.gov.au</a>: The single point of discovery for Federal open data. See <a href="/use-datagovau#what_is_data.gov.au_and_how_does_it_work.3f" title="How to use data.gov.au">What is data.gov.au</a> for more information</li>
<li><a href="http://www.nationalmap.gov.au">NationalMap</a>: A spatial visualisation tool for government open data. Users can’t publish information directly to the site, but it draws data from data.gov.au and directly from agencies when relevant. See the <a href="/publishing-your-data#nationalmap" title="Publishing your data">NationalMap section</a> for more information</li>
<li><a href="http://find.ga.gov.au/">FIND</a>: A catalogue of spatial data or services from governments, the private sector and research and education organisations. Published through negotiation with Geoscience Australia. See the <a href="/publishing-your-data#find" title="Publishing your data">FIND section</a> for more information</li></ul>
<h2>Intro to metadata</h2>
<h3>What is metadata?</h3>
<p>Metadata is information about data. It describes the content, format, quality, currency and availability of data in a consistent and meaningful way.
</p><p>Metadata is useful for cataloguing single documents, but is most important for managing a large body of data. This is particularly important for open government data, as people who work with the data may be combining data sets from a wide range sources, both inside and outside of government.
</p><p>Establishing a common vocabulary for metadata – <a href="/publishing-your-data#standards" title="Publishing your data">using standards</a> – makes it possible for users to find and remix data in a clear and structured way. As open data infrastructure evolves, detailed metadata will not only allow more people to find your data, it will also allow them to re-use the data in more meaningful ways.
</p>
<h3>How is it used?</h3>
<p>There are a range of metadata standards that are used based on the data that is being described and where it is available. Each metadata standard contains elements, or fields, that describe the data. A common example of a metadata element is the ‘Title’, which contains the name of the dataset.
</p><p>The <a href="/use-datagovau#metadata" title="How to use data.gov.au">data.gov.au metadata</a> section has information on the simple form on data.gov.au that is used to make data discoverable through the sites. For people who need technical information, the metadata requirements for specific data types such as spatial data are also described there.
</p><p>Agencies considering the establishment of their own data catalogues should consider the <a href="https://data.gov.au/dataset/data-gov-au-metadata-and-other-schemas">data.gov.au metadata profile</a>, based on <a href="http://www.w3.org/TR/vocab-dcat/">DCAT</a>. Spatial data catalogues should use the <a href="http://www.anzlic.gov.au/resources/anzlic_metadata_profile">ANZLIC metadata schema</a> (which also maps to the data.gov.au DCAT schema).
</p><p><a href="http://find.ga.gov.au/">FIND</a>, the Australian Government spatial data catalogue, works with <a href="https://data.gov.au">data.gov.au</a> to provide access to a network of government data. The FIND metadata profile includes information on <a href="https://toolkit.data.gov.au/images/5/57/FIND-coreMetadata-ANZLIC-profile-20140903.csv">how to structure spatial metadata</a> (XLS) so that your data can be made interoperable and accessible, as well as discoverable through FIND.
</p>
<h2>Licensing your data</h2>
<p>Licences provide a clear and standardised guide for other people about how they can use your data, including the option to reuse, remix and share the content.
</p><p>The <a href="http://www.ag.gov.au/RightsAndProtections/IntellectualProperty/Pages/AustralianGovernmentIPrules.aspx">Statement of IP Principles for Australian Government Agencies</a> requires agencies to encourage public use and easy access to published material. This includes permission for public use and re-use of material without requiring royalties and on a non-exclusive basis.
</p><p>The default licence for the Australian Government is the Creative Commons Attribution 3.0 Australia (CC BY 3.0 AU) for publishing data and information, unless a clear case is made for another open licence. You can access the licence text on the Creative Commons website in either <a href="http://creativecommons.org/licenses/by/3.0/au/deed.en">plain English</a> or <a href="http://creativecommons.org/licenses/by/3.0/au/legalcode">legal code</a>.
</p><p>For support and guidance with licensing, see the <a href="https://theodi.org/article/publishers-guide-to-open-data-licensing/">ODI website</a>, which gives more detail on the open licences that can be used by government, risk management for implementing open licences and information on licensing for special cases such as software.
</p>
<h2>Privacy and security</h2>
<p>It is important to ensure you approach data publishing with privacy and security principles in mind. For more information about privacy and security considerations, please refer to the <a href="https://www.oaic.gov.au/information-policy/information-policy-resources/principles-on-open-public-sector-information">Principles on Open Public Sector Information</a> from the Office of the Australian Information Commissioner.
</p>
<h2>Standards</h2>
<p>Standards are an important aspect of open data, as they ensure data is accessible and interoperable. Please see the section on [Data Formats] for information about open data standards. Below are some additional standards agencies should consider.
</p>
<h3>Implementing standards</h3>
<p>There are a wide range of standards that may be relevant to data projects, relating to issues like spatial information, metadata and addressing. The <a href="/publishing-your-data#intro_to_metadata" title="Publishing your data">metadata</a> page of this toolkit have more information on how to use relevant standards.
</p>
<h3>Standards management</h3>
<p>System owners and data owners should, wherever possible, consider relevant international and Australian standards for their data. 
</p><p>Standards bodies dealing with data include: 
</p>
<ul><li><a href="http://www.iso.org/iso/catalogue_ics">International Organization for Standardization</a> (ISO)</li>
<li><a href="http://www.opengeospatial.org/standards">Open Geospatial Consortium</a> (OGC)</li>
<li><a href="http://www.standards.org.au/">Standards Australia</a></li></ul>
<p>Australian Government Standards that have been adopted for use include: 
</p>
<ul><li><a href="http://www.agls.gov.au/">AGLS</a> (National Archives standard for making online information and services visible, manageable and interoperable)</li>
<li><a href="http://www.anzlic.gov.au/">ANZLIC</a> Spatial Metadata Profile</li>
<li><a href="http://www.abs.gov.au/ausstats/abs@.nsf/Lookup/1407.0.55.002main+features22013">SDMX</a> (Statistical Data and Metadata Exchange standard managed by the Australian Bureau of Statistics)</li>
<li><a href="http://www.aixm.aero/public/subsite_homepage/homepage.html">AIXM</a> (Aeronautical Information Exchange Model standard)</li>
<li>AS/NZS4819 Rural and Urban Addressing</li>
<li>AS4590 Interchange of client information</li></ul>
<p>This section will be updated as guidance evolves. 
</p>
<h2>Intro to spatial data</h2>
<p>Spatial data is any data that refers to places in the physical world. This can include:
</p>
<ul><li>Geographic features like mountains and lakes</li>
<li>Man-made objects like houses and roads</li>
<li>Non-physical objects or information about the location like electoral boundaries or internet quality</li></ul>
<p>Spatial data sets are fundamentally the same as all other data sets; they simply contain fields for spatial information such as latitude and longitude as well as their other information. This means all the guides to making data open still apply.
</p>
<h3>The Statistical Spatial Framework</h3>
<p>The ABS's <a href="http://www.nss.gov.au/nss/home.nsf/pages/Statistical%20Spatial%20Framework%20Homepage">Statistical Spatial Framework</a> provides a principals based framework for spatially enabling socio-economic datasets, including administrative datasets, to ensure consistency and comparability.  Implementation of the framework is supported by guidance material and resources, and references existing standards and infrastructure. Key <a href="http://www.nss.gov.au/nss/home.nsf/pages/Statistical%20Spatial%20Framework%20Guidance%20Material">guidance materials</a> include: 
</p>
<ul><li><a href="http://www.nss.gov.au/nss/home.NSF/pages/Statistical+Spatial+Framework+on+a+page/$File/SSF%20on%20a%20page.pdf">SSF-on-a-page</a> (includes resource links)</li>
<li><a href="http://www.nss.gov.au/nss/home.NSF/pages/Statistical+Spatial+Framework+Guidance+Material/$File/Geocoding%20Unit%20Record%20Data.pdf">Geocoding Using Address</a></li>
<li><a href="http://www.nss.gov.au/nss/home.NSF/pages/Statistical+Spatial+Framework+Guidance+Material/$File/SSF%20Guidance_Geographic%20Boundaries%20and%20Classifications_1.pdf">Using Geography with Statistics</a></li>
<li><a href="http://www.nss.gov.au/nss/home.NSF/pages/Statistical+Spatial+Framework+Guidance+Material/$File/SSF%20Guidance_Geographic%20Differencing_1.pdf">Protecting Privacy for Geospatially Enabled Statistics</a></li></ul>
<h2>NationalMap</h2>
<h3>What is the NationalMap</h3>
<p>The NationalMap is a website for map-based access to government spatial data. It is designed to:
</p>
<ul><li>Provide easy access to data for government, business and the public</li>
<li>Integrate datasets into a ‘front end map’ for <a href="https://data.gov.au">data.gov.au</a></li>
<li>Provide an open framework of geospatial data services that supports commercial and community innovation</li>
<li>Provide agencies with an easy map to embed on their own websites</li></ul>
<p><br>
<a href="/assets/file/NationalMap_screenshot.PNG" ><img alt="NationalMap screenshot.PNG" src="/images/f/f9/NationalMap_screenshot.PNG" width="959" height="473"></a>
</p>
<h3>How do you use the data?</h3>
<p>To view a data set on the NationalMap, go to <a href="http://nationalmap.gov.au/">http://nationalmap.gov.au/</a>, select Data then National Data Sets. This will display a list of available data topics. 
</p><p>Other tips:
</p>
<ul><li>To zoom to a data set’s area on the map, click on the name of the data set.</li>
<li>For detail about specific information captured in a data set, click on the specific point, line or area on the map.</li>
<li>For detail about the entire data set, click ‘info’ next to the name of a data set for more information, conditions of use and a link to download the data.</li></ul>
<p>NationalMap is best used with a browser with WebGL support such as the latest versions of Google Chrome, Mozilla Firefox and Internet Explorer 11.  It will work with limited functionality in older browsers such as Internet Explorer 9 and Internet Explorer 10. 
</p><p>Possible uses for the NationalMap include:
</p>
<ul><li>Finding data sets and services (for any data set or service visible in the NationalMap, click "info" to view how to access the data set/service directly).</li>
<li>Set up a Web Map Service (WMS) or Web Feature Service (WFS) and load the URL for that service into NationalMap.  For example, you can use the open source software Geoserver to do this or use one of many commercial GIS systems such as ESRI ArcGIS Server, Pitney Bowes' Mapinfo or Google Maps Engine and enable WMS and/or WFS services from it.</li>
<li>Build a website that uses the value-add service API. Email <a href="mailto:nationalmap@lists.csiro.au">nationalmap@lists.csiro.au</a> to find out how.</li></ul>
<h3>How do you add data?</h3>
<p>Government data can be added to the NationalMap by uploading it to <a href="https://data.gov.au">data.gov.au</a> in a common spatial data format. The main data formats supported by the NationalMap are GeoJSON, KML, KMZ and CSV (with latitude and longitude columns). The NationalMap routinely harvests spatial services from <a href="https://data.gov.au">data.gov.au</a> and FIND. It takes between 24 - 48 hours from when a spatial data set is uploaded to <a href="https://data.gov.au">data.gov.au</a> for it to appear on the NationalMap.
</p><p>If uploaded spatial data to <a href="https://data.gov.au">data.gov.au</a> is not showing on NationalMap, start by checking the data is in one of the formats listed above. If the issues is not resolved, email <a href="mailto:spatial@pmc.gov.au">spatial@pmc.gov.au</a>. 
</p><p>A data set can be added to NationalMap for a single session by dragging it on to the map or clicking on ‘Add Data’ under the Data tab. This is particularly relevant when working with personal, private or temporary data that cannot be uploaded to <a href="https://data.gov.au">data.gov.au</a>. Data added to a map in this way will not be saved on the NationalMap and cannot be shared using the share button on the site.
</p><p>For large data sets that are better streamed than uploaded, email <a href="mailto:nationalmap@lists.csiro.au">nationalmap@lists.csiro.au</a> to discuss options for making data available in more detail.
</p>
<h3>How does the NationalMap work?</h3>
<p>The NationalMap is a fully open architecture that provides a direct link between the user and the government department or agency who is the custodian of the data. For example, if you access data relating to "broadband availability and quality", you are accessing that directly from the Department of Communications and the Arts; when you access data relating to surface geology, it is accessed directly from Geoscience Australia. The NationalMap itself does not store any data - it provides a map-based view to data that is stored by a growing number of government bodies.
</p>
<h3>Open source software</h3>
<p>The NationalMap was created with the following open source software. The developers contribute back to the software projects as appropriate.
</p>
<ul><li><a href="http://cesiumjs.org/">Cesium</a> (open source under the Apache 2.0 licence)</li>
<li><a href="http://leafletjs.com/">Leaflet</a> (open source under the simplified BSD licence)</li>
<li><a href="http://geoserver.org/">Geoserver</a> (open source under the GNU GPL 2.0 licence)</li>
<li><a href="http://jquery.com/">jquery</a>, <a href="http://medialize.github.io/URI.js/">URI.js</a>, <a href="http://proj4js.org/">proj4js</a>, <a href="http://html2canvas.hertzen.com/">html2canvas</a>, <a href="http://knockoutjs.com/">knockout</a> (all open source under the MIT licence)</li>
<li><a href="https://github.com/Esri/esri-leaflet">esri-leaflet.js</a> (open source under the Apache 2.0 licence)</li>
<li><a href="https://github.com/mapbox/togeojson">togeojson</a>, <a href="https://gist.github.com/pagameba/1221998">Tilelayer.Bing.js</a> (open source under the wtfpl ver 2)</li></ul>
<p>See the Data61 Github page for <a href="https://github.com/TerriaJS/nationalmap">more information about the NationalMap</a>.
</p>
<h2>Data portals</h2>
<p>See below for an incomplete list of open data portals and resources in Australia and New Zealand. Please send any suggestions for additions to the list to <a href="mailto:data@pmc.gov.au">data@pmc.gov.au</a>.
</p>
<h3>Federal</h3>
<ul><li>The Federal <a href="http://toolkit.data.gov.au/">Open Data Toolkit</a> including information about all data policies and guidance for the Federal Government.</li>
<li>The <a href="https://data.gov.au">data.gov.au</a> portal for Federal data. Also includes metadata sharing from other Australian governments.</li>
<li><a href="http://www.nationalmap.gov.au">NationalMap</a> provides a mapping service auto-generated from data.gov.au, with the capability to add private data sets for visualisation and comparison.</li>
<li>The <a href="http://www.opendata500.com/au">Australian Open Data 500</a> was a Dept Communications initiative to identify private sector demand for public sector data.</li>
<li><a href="http://find.ga.gov.au">FIND</a> is a catalogue of Australian spatial datasets which queries data from Australian federal, state and territory governments as well as research organisations.</li>
<li>The <a href="https://data.gov.au/">data.gov.au</a> team created a <a href="http://www.finance.gov.au/blog/2013/10/26/government-data-landscape-australia/">mindmap of the the government data landscape in Australia</a>. Any updates to this mindmap are welcome.</li></ul>
<h3>Australian Capital Territory</h3>
<ul><li>The <a href="http://data.act.gov.au/">data.act.gov.au</a> portal for ACT government data.</li>
<li>The <a href="http://www.cmd.act.gov.au/__data/assets/pdf_file/0011/859430/2016-Proactive-Release-of-Data-Open-Data-Policy.pdf">ACT Open Data policy</a>, released on GitHub in 2013.</li></ul>
<h3>New South Wales</h3>
<ul><li>The <a href="http://arp.nsw.gov.au/dfs-c2013-06-open-data-policy">NSW Open Data Policy</a></li>
<li>The <a href="http://data.nsw.gov.au/">data.nsw.gov.au</a> portal for NSW government data.</li>
<li>The <a href="http://data.nsw.gov.au/plan">NSW Open Data Implementation Plan and Dashboard</a></li>
<li>The <a href="http://finance.nsw.gov.au/ict/resources">NSW Open Data Policy, Implementation Plan and Guidelines</a>.</li>
<li><a href="http://globe.six.nsw.gov.au/">NSW Globe</a>, a mapping and data application for exploring spatial data and spatially referenced NSW open data.</li></ul>
<h3>Queensland</h3>
<ul><li>The <a href="https://data.qld.gov.au/">data.qld.gov.au</a> portal for Queensland government data.</li>
<li><a href="http://www.dnrm.qld.gov.au/mapping-data/queensland-globe/about">Queensland Globe</a>, a mapping and data application for exploring spatial data and spatially referenced Queensland open data.</li></ul>
<h3>South Australia</h3>
<ul><li>The <a href="http://data.sa.gov.au/">data.sa.gov.au</a> portal for South Australian government data, notable for releasing an enormous amount of new and high value datasets.</li>
<li>The South Australian <a href="http://www.dpc.sa.gov.au/open-data">Open Data Toolkit</a>, launched in November 2014 including departmental reporting.</li>
<li>The <a href="http://dpc.sa.gov.au/news/sa-open-government-data-all">Open Data Declaration</a> launched in September 2013.</li></ul>
<h3>Victoria</h3>
<ul><li>The <a href="http://www.data.vic.gov.au/">data.vic.gov.au</a> portal for Victorian government data.</li>
<li>The <a href="http://www.data.vic.gov.au/cms/policy-and-standards/285">DataVic Access Policy and the Intellectual Property Policy</a> launched in August 2012.</li>
<li>The <a href="http://www.data.vic.gov.au/blog/datavic-access-policy-standards-and-guidelines/297">DataVic Access Policy Standards and Guidelines</a> released in April 2013.</li></ul>
<h3>Western Australia</h3>
<ul><li>The <a href="http://data.wa.gov.au/">Western Australian Government Open Data</a> policy and portal</li>
<li>The <a href="https://www2.landgate.wa.gov.au/web/guest/about-slip">Shared Land Information Platform (SLIP)</a>, which gives users access to Western Australia's significant land and geographic information resources over the web.</li></ul>
<h3>Tasmania</h3>
<ul><li>All foundational spatial datasets (property, contours, roads, etc) now available on <a href="http://data.thelist.tas.gov.au">redeveloped LIST system</a> with 50 high value datasets freely availabel under CC-BY.</li>
<li>Have been working primarily on <a href="http://www.dpipwe.tas.gov.au/sif">spatial data requirements for the state</a> and with the <a href="http://www.sense-t.org.au/">Sense-T sensor data project</a>.</li>
<li><a href="https://www.thelist.tas.gov.au/app/content/data">www.thelist.tas.gov.au/app/content/data</a></li></ul>
<h3>Local Governments</h3>
<h4>On data.gov.au</h4>
<ul><li>Several Local Councils are publishing data on data.gov.au. The latest list can be found (with a few exceptions) by  <a href="https://data.gov.au/organization?q=council&amp;sort=name+asc">searching for council on data.gov.au</a></li></ul>
<h4>Glenorchy</h4>
<ul><li>The Glenorchy City Council <a href="http://www.gcc.tas.gov.au/content/Policies_Corporate_Services.GCC?ActiveID=1155">open data policy</a> was released in November 2014.</li>
<li>Data for the council area is available on <a href="https://data.gov.au/dataset?q=Glenorchy">data.gov.au</a>.</li></ul>
<h4>City of Melbourne</h4>
<ul><li>The <a href="http://data.melbourne.vic.gov.au">Melbourne beta open data portal</a> launched in May 2014.</li></ul>
<h4>Brisbane City Council</h4>
<ul><li>The <a href="https://www.data.brisbane.qld.gov.au/">Brisbane City Council portal</a></li></ul>
<h3>Community</h3>
<ul><li><a href="http://govhack.org/">GovHack</a> was first run in 2009 to draws together people from government, industry, academia and, of course, the general public to mashup, reuse, and remix government data. In 2014, this included over 1300 participants and observers in 11 cities creating more than 170 added-value open data projects.</li>
<li>The Random Hacks of Kindness communities in <a href="http://rhokadelaide.org/">Adelaide</a>, <a href="http://rhokmelbourne.org/">Melbourne</a> and <a href="http://www.rhoksydney.org/">Sydney</a>.</li></ul>
<h3>International</h3>
<h4>New Zealand</h4>
<ul><li>The NZ Government’s <a href="http://data.govt.nz/">data.govt.nz</a> portal for New Zealand government data.</li>
<li>The NZ <a href="http://ict.govt.nz/programmes/open-and-transparent-government/open-data-case-studies/">open data case studies</a> site, which Finance highly recommend. The case study of the release of traffic density data which led to improved prediction of GDP growth and decline in the New Zealand economy is particularly recommended.</li>
<li><a href="https://webtoolkit.govt.nz/blog/2015/07/fyi-brasil-is-unlocking-the-value-of-government-information-and-data/">FYI: Brasil is unlocking the value of government information and data</a> on the New Zealand Government Web Toolkit blog.</li></ul>
<h4>United States of America</h4>
<ul><li>data.gov has a list of <a href="http://www.data.gov/open-gov/">international data portals</a></li></ul>
<p>This page is maintained by the data.gov.au team. Please contact <a href="mailto:data@digital.gov.au">data@digital.gov.au</a> with any questions, comments or congratulations.
</p>