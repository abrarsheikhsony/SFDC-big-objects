# Salesforce Big Objects

## What are Big Objects?

<ul>
<li>Big objects allow you to store and manage a massive amount of data on the Salesforce platform.</li>
<li>Big objects provide consistent performance for a "billion records or more", and are accessible with a standard set of APIs to your org or external system.</li>
</ul>

There are two flavors of Big objects:

<ol type="1">
<li>Standard Big Objects</li>
Defined by Salesforce and are included in Salesforce products.
<ul>
<li>FieldHistoryArchive (Field Audit Trail product)</li>
<li>FieldHistoryArchive (allows you to store up to ten years’ worth of archived field history data, helping you comply with industry regulations related to auditing and data retention)</li>
</ul>
<li>Custom Big objects</li>
Defined and deployed by you through the Metadata API.
To define a custom Big object, you create:
<ul>
<li>An object file that contains its definition, fields, and index, along with a permissionset to define the permissions for each field, and a package file to define the contents of the object metadata.</li>
<li>The fields defined in a Big object’s index determine the Big object’s identity and its ability to be queried.</li>
</ul>
</ol>





<ul>
<li>Coffee</li>
</ul>

<ol type="1">
<li>TEST</li>
</ol>


<img src="supportedimages/image1.png"/>
<img src="supportedimages/image2.png"/>

## Salesforce Trailhead
<ul>
<li><a href="https://trailhead.salesforce.com/content/learn/modules/big_objects" target="_blank" alt="Big Objects Basics">Big Objects Basics</a></li>
</ul>

## Salesforce Guide
<ul>
<li><a href="https://developer.salesforce.com/docs/atlas.en-us.216.0.bigobjects.meta/bigobjects/big_object.htm" target="_blank" alt="Big Objects Implementation Guide">Big Objects Implementation Guide</a></li>
</ul>
