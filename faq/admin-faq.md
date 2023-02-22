# Admin FAQ

<details>

<summary>How do I publish a Shapefile using ArcGIS Online?</summary>

Have you created content (e.g., sketches, survey responses) that you would like to add to your Data Layers? You know how to export your data from SeaSketch, but do you know how to create a map service using the data you exported? The directions are fairly simple. [Follow this link to Esri's help document](https://doc.arcgis.com/en/arcgis-online/share-maps/publish-features.htm#ESRI\_SECTION1\_49CE0570C3BA4AD8BF2DB28929FF7280).\
\
Once you have successfully published your shapefile as a Feature Layer, you can copy the service URL from ArcGIS online, then add it as you would any other map service in the SeaSketch Admin interface.&#x20;

</details>

<details>

<summary>How do I securely add layers to a SeaSketch project for select user groups?</summary>

t's common to have datasets in a SeaSketch project that need to be visualized by a select user group. They may be sensitive in nature, and not to be made publicly accessible. SeaSketch can interoperate with web services published in ArcGIS Server with token-based authentication enabled to support this use case.

### Adding Secure Services

#### Prerequisites

You will need the url of service hosted in ArcGIS Server >= 10.1 with token-based authentication enabled, as well as a valid username and password for that service. See [Esri's documentation](http://resources.arcgis.com/en/help/main/10.1/index.html#/About\_ArcGIS\_tokens/0154000005r6000000/) for details on how to setup token-based authentication in ArcGIS Server. We recommend that the service be configured with an account to be used by SeaSketch exclusively, with read-only access to the data. This will prevent users from using their token to publish or alter services, as well as for distinguishing SeaSketch requests from others in the ArcGIS Server logs.

</details>

<details>

<summary>How do I organize my layer tree?</summary>

The layer tree is organized by the administrator under the Data Layers tab.&#x20;

Once you have added a few data layers (map services) into your project, consider the following:

* Add headers to group layers together under a common theme. For example, you might create headers for "Biological Data" and "Administrative Boundaries". Add a header by clicking the drop down menu under the Data Layers tab called "+Add" and choose "Heading". You can also simply hold down the "a" and "h" keys simultaneously to bring up the add heading dialog box.&#x20;

</details>
