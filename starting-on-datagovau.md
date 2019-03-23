---
title: Starting on datagovau
layout: default
permalink: /starting-on-datagovau
---

<h1>Starting on Data.gov.au</h1>
<h2>Getting an Account</h2>
<p>Anyone can create an account on data.gov.au which can be used for commenting or liking datasets.
</p><p>To publish government data you must register an account with a .gov.au or .csiro.au email address. Before doing this you must have appropriate permission from your entity to publish on their behalf. You will also be required to request publishing permissions from the data.gov.au support staff.
</p><p>The Digital Transformation Agency (DTA) requires all new data custodians to get sign off from their organisation to before creating a publishing account. The DTA reviews publisher accounts periodically to ensure appropriate access to publishing on data.gov.au is maintained.
</p><p><b>We strongly recommend that you do not use an individual’s email address for the main management account for your data.gov.au organisation</b>. It is much better to use a shared inbox as it provides for continuity should the named data custodian change.
</p><p>To create an account, go to <a href="https://data.gov.au/user/register">https://data.gov.au/user/register</a> and complete the form on the page. Then email <a href="mailto:data@digital.gov.au">data@digital.gov.au</a> with the following text to verify who you are and that you wish to be granted publishing privileges:
</p><p><br>
</p>
<dl><dd><dl><dd><dl><dd>Dear DTA,</dd></dl></dd></dl></dd></dl>
<dl><dd><dl><dd><dl><dd>On behalf of the &lt;<i>entity name</i>&gt;, I request a data publishing account on data.gov.au. &lt;<i>entity name</i>&gt; will be responsible for the management of this account and the data that is published using it. &lt;<i>entity name</i>&gt; will notify the Digital Transformation Agency (DTA) to any changes in ownership of the account and of any issues if they arise. The responsibility of publishing data appropriately, in accordance with privacy, security and other relevant considerations rest entirely with the data publisher and the DTA take no responsibility.</dd></dl></dd></dl></dd></dl>
<dl><dd><dl><dd><dl><dd>I have registered the account name &lt;<i>account name</i>&gt; with email address &lt;<i>email address</i>&gt; on data.gov.au and request access to the organisation(s) &lt;organisation name(s)&gt; to publish data.</dd></dl></dd></dl></dd></dl>
<dl><dd><dl><dd><dl><dd>I understand the DTA intends to continue to provide data.gov.au as a whole of government data publishing platform at no cost to government data publishers. If circumstances change, the DTA will give data publishers at least 2 months notice. The DTA will also provide documentation and minimal free technical support to data publishers.</dd></dl></dd></dl></dd></dl>
<p><br>
</p>
<h3>Opportunity for councils</h3>
<p>Councils joining data.gov.au can follow the standards and recommendations published at <a href="http://opencouncildata.org">opencouncildata.org</a>. 
</p><p>The Open Data Council’s initiative aims to maximise reuse and interoperability of datasets by promoting the release of specific high-value, commonly-available datasets, with standard data schemas. The goal is that datasets can be easily joined up for greater value (for example, <a href="http://opentrees.org">state-wide register of trees</a>) ) and apps developed for one dataset will work across council boundaries (for example, <a href="http://www.openbinmap.org/">a bin night reminder app</a>).
</p><p>The standards are created and refined by a working group of local government representatives, which is free and open for anyone to join.
</p>
<h2>Resetting your password</h2>
<p>If you already have an account, go to <a href="https://data.gov.au/user/login">https://data.gov.au/user/login</a> to change your password and then let us know at <a href="mailto:data@digital.gov.au">data@digital.gov.au</a> which organisation(s) you need to publish data to. <a href="https://data.gov.au">Data.gov.au</a> staff may need to verify that you come from the correct organisation before granting you publishing privileges.
</p>
<h2>Creating and editing your organisations information and data categorisation</h2>
<p>Each entity has their own “organisation” in CKAN, and as the entity representative, you will have administrator privileges to your organisation. This means you can edit the description and logo of your organisation, you can add and remove other publishers from your organisation, and you can of course add, edit and delete datasets belonging to your organisation.
</p>
<h3>Organisation</h3>
<p>Your organisation is both the name under which all your entity/jurisdiction datasets are published, but it is the entity you can edit. For instance, if you have a Machinery of Government (MoG) change you may be required to change your organisation name and details. DPMC recommends you have your organisation logo and some descriptive text about your organisation.
</p>
<h3>Updating an organisation’s details</h3>
<ol><li>Visit your <a href="https://data.gov.au/organisation"><b>organisation's page</b></a></li>
<li>Click the <b>Manage</b> button located near top right of the page</li>
<li>In the Edit tab you’ll be able to change attributes associated with your organisation;
<dl><dd><dl><dd><ul><li><b>Name</b>: the name displayed to users for your organisation</li>
<li><b>URL</b>: the location at which your organisation can be found on data.gov.au (<a href="http://www.data.gov.au/organisation/{URL}">http://www.data.gov.au/organisation/{URL}</a>)<br>The URL also acts as an identifier for your organisation and every organisation must have a unique URL</li>
<li><b>Image URL</b>:  the crest to be displayed alongside your organisation’s name. <br>To ensure clarity and uniformity we recommend the image be 350 x 350 pixels</li>
<li><b>Parent</b>: the parent entity of your organisation – can be used when a specific section of an organisation is required to publish a large volume (100+) of datasets</li>
<li><b>Jurisdiction</b>: the jurisdiction to which your organisation belongs</li>
<li><b>Geospatial Coverage</b>: the area covered by your organisation. Can be plain text (Australia, Victoria, Brisbane City, etc) but can also receive GeoJSON as input. For  example a bounding box around Australia could be represented as:<br>:: {"type": "Polygon", "coordinates": [[[112.0, -44.0], [154.0, -44.0], [154.0, -9.0], [112.0, -9.0], [112.0, -44.0]]]}</li>
<li><b>Website</b>: your organisation’s website</li>
<li><b>Email</b>: a generic contact point for your organisation. We strongly recommend you use a shared inbox for this field</li>
<li><b>Telephone</b>: a generic phone contact point for your organisation</li></ul></dd></dl></dd></dl></li>
<li>Once you have made the required changes click the <b>Update Organisation</b> button</li></ol>
<h3>Adding users to your organisation</h3>
<p>Once the user has registered on data.gov.au, log in as the Admin user:
</p>
<ol><li>Visit your <a href="https://data.gov.au/organization"><b>organisation's page</b></a></li>
<li>Click the <b>Manage</b> button located near top right of the page</li>
<li>Click the <b>Members</b> tab button located on the top centre of the page</li>
<li>Click the <b>+ Add Member</b>  button</li>
<li>Select the drop down under <b>Existing User:</b> and type in the username of the account you wish to add as an uploader</li>
<li>Select a <b>Role</b> from the dropdown - Member, Editor or Admin.
<dl><dd><dl><dd><ul><li><b>Members</b> - are able access all datasets, including those set to private, under the organisation but will not be able to edit content.</li>
<li><b>Editors</b> - can create, edit and delete datasets and organisational information.</li>
<li><b>Admin</b> - can perform the same functions as editors and can also assign privileges to other users.</li></ul></dd></dl></dd></dl></li>
<li>Click <b>Add Member</b> located to the bottom right of the page.</li></ol>
<h3>Adding users to your organisation images</h3>
<ul >
		<li  ><div >
			<div  ><div ><a href="/assets/file/1_users_Manage.jpg" ><img alt="" src="/images/thumb/b/b4/1_users_Manage.jpg/250px-1_users_Manage.jpg" width="250" height="75" srcset="/images/thumb/b/b4/1_users_Manage.jpg/375px-1_users_Manage.jpg 1.5x, /images/thumb/b/b4/1_users_Manage.jpg/500px-1_users_Manage.jpg 2x"></a></div></div>
			<div >
<p><b>Manage Button</b>
</p>
			</div>
		</div></li>
		<li  ><div >
			<div  ><div ><a href="/assets/file/2_members.jpg" ><img alt="" src="/images/thumb/e/e3/2_members.jpg/250px-2_members.jpg" width="250" height="48" srcset="/images/thumb/e/e3/2_members.jpg/375px-2_members.jpg 1.5x, /images/thumb/e/e3/2_members.jpg/500px-2_members.jpg 2x"></a></div></div>
			<div >
<p><b>Members Tab</b>
</p>
			</div>
		</div></li>
		<li  ><div >
			<div  ><div ><a href="/assets/file/3_add_members.jpg" ><img alt="" src="/images/thumb/7/7d/3_add_members.jpg/250px-3_add_members.jpg" width="250" height="42" srcset="/images/thumb/7/7d/3_add_members.jpg/375px-3_add_members.jpg 1.5x, /images/thumb/7/7d/3_add_members.jpg/500px-3_add_members.jpg 2x"></a></div></div>
			<div >
<p><b>Add Member</b>
</p>
			</div>
		</div></li>
		<li  ><div >
			<div  ><div ><a href="/assets/file/4_users_and_roles.jpg" ><img alt="" src="/images/thumb/e/e5/4_users_and_roles.jpg/250px-4_users_and_roles.jpg" width="250" height="93" srcset="/images/thumb/e/e5/4_users_and_roles.jpg/375px-4_users_and_roles.jpg 1.5x, /images/thumb/e/e5/4_users_and_roles.jpg/500px-4_users_and_roles.jpg 2x"></a></div></div>
			<div >
<p><b>User and Roles</b>
</p>
			</div>
		</div></li>
</ul>
<h3>Removing users to your organisation</h3>
<ol><li>Visit your <a href="https://data.gov.au/organization"><b>organisation's page</b></a></li>
<li>Click the <b>Manage</b> button located near top right of the page</li>
<li>Click the <b>Members</b> tab button located on the top centre of the page</li>
<li>From the list of <b>members</b> locate the user you are looking to remove and click the <i>red x'</i> button.</li>
<li>You’ll be asked to <b>Confirm</b> that you’d like to remove the user.</li></ol>
