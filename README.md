# Open Source at Aquatic Informatics

![Logo](https://github.com/AquaticInformatics/aquarius-sdk-net/raw/develop/images/aquatic-informatics.svg)

Welcome to the Aquatic Informatics (AQI) open source offerings on GitHub. Hopefully this guide can get you pointed in the right direction.

# Aquarius Time-Series Tools, sample data files

Most of the items can be downloaded from their Github release pages if they are  open sourced. If the tool is closed sourced, you will be redirected to the KB article on AQI Support portal. <br>
If you find issues, for the open source tools, go to the tool's Github project and create an issue there. For the closed source tools, raise a support ticket. <br>
Many of the Aquarius Time-Series console utilities share some common logic for parsing command-line arguments. You can find it [here](https://github.com/AquaticInformatics/examples/wiki/Common-command-line-options).

| Download link | Doc | Description |
| --- | --- | --- |
|ReportRunner.exe <br>  ([Download from AQI Support Portal](https://aquaticinformatics.deskpro.com/kb/articles/2414-aquarius-time-series-report-runner-utility)) | [Here](https://github.com/AquaticInformatics/getting-started/wiki/ReportRunner) | The `ReportRunner.exe` tool is a command-line tool for running and downloading reports on/from an AQTS system.|
| [Sample field data files](https://github.com/AquaticInformatics/examples/tree/master/TimeSeries/SampleFiles/FieldData) | [Here](https://github.com/AquaticInformatics/examples/tree/master/TimeSeries/SampleFiles/FieldData/Readme.md)| This page lists a description of each field data file formats supported by Aquarius Time-Series. A sample of each file type is provided for download. |
|[FieldVisitHotFolderService.zip](https://github.com/AquaticInformatics/aquarius-field-data-framework/blob/master/src/FieldVisitHotFolderService/Readme.md#compatibility-matrix)| [Here](https://github.com/AquaticInformatics/aquarius-field-data-framework/blob/master/src/FieldVisitHotFolderService/Readme.md#field-visit-hot-folder-service)| A Windows service which can monitor a folder for field visit files and upload visits to AQTS. |
|[UserImporter.exe](https://github.com/AquaticInformatics/examples/releases) | [Here](https://github.com/AquaticInformatics/examples/tree/master/TimeSeries/PublicApis/SdkExamples/UserImporter#userimporter)| A console tool for quickly provisioning users in your AQTS system from a CSV file. |
|[PointZilla.exe](https://github.com/AquaticInformatics/examples/releases/) | [Here](https://github.com/AquaticInformatics/examples/blob/master/TimeSeries/PublicApis/SdkExamples/PointZilla/Readme.md)| A console tool for quickly appending points to a time-series. |
|[TimeSeriesChangeMonitor.exe](https://github.com/AquaticInformatics/examples/releases/) | [Here](https://github.com/AquaticInformatics/examples/blob/master/TimeSeries/PublicApis/SdkExamples/TimeSeriesChangeMonitor/Readme.md)| A console tool for monitoring how quickly changes in a time-series become available on the Publish API. Use it along side PointZilla to precisely measure the behaviour of your data flow. 
|[LocationDeleter.exe](https://github.com/AquaticInformatics/examples/releases) | [Here](https://github.com/AquaticInformatics/examples/blob/master/TimeSeries/PublicApis/SdkExamples/LocationDeleter/Readme.md)| A console tool for deleting locations and/or visits and/or time-series during initial system configuration. You obviously won't want to run this on a production system. |
|[ExcelCsvExtractor.exe](https://github.com/AquaticInformatics/examples/releases) | [Here](https://github.com/AquaticInformatics/examples/blob/master/TimeSeries/PublicApis/SdkExamples/ExcelCsvExtractor/Readme.md)| A console tool for extracting sheets from an Excel workbook into individual CSV files. |
|[OGC SOS Proxy](https://github.com/AquaticInformatics/examples/tree/master/TimeSeries/PublicApis/SdkExamples/SosExporter/docker-proxy#sos-proxy-for-aquarius-time-series) | [Here](https://github.com/AquaticInformatics/examples/tree/master/TimeSeries/PublicApis/SdkExamples/SosExporter/docker-proxy#sos-proxy-for-aquarius-time-series)| An API proxy for exporting time-series data to an OCG SOS server as sensor observations, suitable for consumption by national aggregation systems like [LAWA](https://www.lawa.org.nz/). |
|ProvisioningTool.zip <br> ([Download from AQI Support Portal](https://aquaticinformatics.deskpro.com/kb/articles/2891-aquarius-time-series-provisioning-tool)) | [Here](https://github.com/AquaticInformatics/getting-started/wiki/ProvisioningTool)| A console tool for performing bulk provisioning operations of an AQTS system from CSV data. The ZIP archive includes sample CSV files for many types of AQTS entities. |
|RatingModelExchange.exe <br>([Download from AQI Support Portal](https://aquaticinformatics.deskpro.com/kb/articles/1127-aquarius-time-series-rating-model-exchange-utility))  | [Here](https://github.com/AquaticInformatics/getting-started/wiki/RatingModelExchange)| A console tool for importing and exporting rating models into AQTS 201x systems, supporting both HydroML formats (XML) and a simpler CSV format. |
|AttachmentUploader.exe ([Download from AQI Support Portal](https://aquaticinformatics.deskpro.com/kb/articles/1260-aquarius-time-series-attachment-uploader))  | [Here](https://github.com/AquaticInformatics/getting-started/wiki/AttachmentUploader)| A console tool for uploading location and field visit attachments into AQTS 201x systems. |
|SystemSizer.exe <br> ([Download from AQI Support Portal](https://aquaticinformatics.deskpro.com/kb/articles/586-aquarius-how-to-use-the-systemsizer-program-to-collect-logs))  | [Here](https://github.com/AquaticInformatics/getting-started/wiki/SystemSizer)| A console tool to run on an AQTS, WebPortal, or Connect app server and determine the basic size and configuration of the system. The `SystemSizer.log` file generated by this tool contains useful information when diagnosing issues with our Support Team. |
|[FlowTracker2Converter.exe](https://github.com/AquaticInformatics/flowtracker2-field-data-plugin/releases) | [Here](https://github.com/AquaticInformatics/flowtracker2-field-data-plugin/blob/master/src/FlowTracker2Converter/Readme.md)| Use this GUI tool to convert FlowTracker2 `*.ft` files into FlowTracker1 `*.dis` files which can be imported into your AQTS  system. |

## Field data plugins help pages

From AQTS 2022.1, field data plugins are distributed in the standard server installation package. Here are some useful help pages. <br>
**Note**: AQI plan to make these open source plugin projects private. The links below may change when that happens. 

| Plugin help page | Description|
| --- | --- |
| [FlowTracker2Plugin.plugin](https://github.com/AquaticInformatics/flowtracker2-field-data-plugin#flowtracker2-field-data-plugin) |  A field data plugin to import FlowTracker2 `*.ft` discharge measurements.|
|[TabularCsv.plugin](https://github.com/AquaticInformatics/tabular-field-data-plugin/wiki/Tabular-CSV-plugin-overview)|A user-configurable field data plugin to import nearly any field visit activity from a CSV file. |
| [JsonFieldData.plugin](https://github.com/AquaticInformatics/aquarius-field-data-framework/blob/master/src/JsonFieldData/Readme.md#json-field-data-plugin) | A field data plugin to import visits from JSON files. Used by the `FieldVisitHotFolderService`. |
|[MultiFile.plugin](https://github.com/AquaticInformatics/aquarius-field-data-framework/blob/master/src/MultiFile/Readme.md#multifile-field-data-plugin) | A field data plugin to import visits from ZIP archives containing other plugin visit data files. |
| [SxSPro.plugin](https://github.com/AquaticInformatics/sxs-pro-field-data-plugin#sxs-pro-field-data-plugin) | A field data plugin to import discharge summary XML measurements from Teledyne SxS Pro software. |
| [AquaCalc5000.plugin](https://github.com/AquaticInformatics/aquacalc-5000-field-data-plugin#aquacalc-5000-field-data-plugin) | A field data plugin to import discharge summary measurements from AquaCalc 5000 CSV files. |
| [QRev.plugin](https://github.com/AquaticInformatics/qrev-field-data-plugin/blob/master/src/QRev/Readme.md#qrev-field-data-plugin) | A field data plugin to import discharge summary XML measurements from USGS QRev software.|
 

# Are you a developer, looking for code?

We have many software projects that allow you to easily extend or integrate with your Aquarius products.

Some are full software projects, with contiuous integration and unit tests, deployed via standard package distribution networks like NuGet or the Maven Central Repository.

Other projects are smaller proof-of-concept examples, which can be a useful starting point or inspiration for your own integrations.

You can find a list of open source projects at https://github.com/AquaticInformatics. 


### Platform SDKs

We have two SDK offerings, one for .NET and one for Java. These SDKs provide complete support for all the Aquarius products with public APIs (currently Aquarius Time-Series and Aquarius Samples, but more products will be added soon to these SDKs).

https://github.com/AquaticInformatics/aquarius-sdk-net - The .NET Platform SDK, available via [NuGet](https://www.nuget.org/packages/Aquarius.SDK).
https://github.com/AquaticInformatics/aquarius-sdk-java - The Java Platform SDK, available via the [Maven Central Repository](https://search.maven.org/#artifactdetails%7Ccom.aquaticinformatics%7Caquarius.sdk%7C18.7.1%7Cjar).

The functionality within each SDK is equivalent, handling the fussy parts of consuming REST APIs robustly:
- Authentication
- Session management
- JSON serialization
- Error handling
- File upload events
- Version checking

With these fussy parts handled for you, your integration code can more succinctly focus on consuming the documented public APIs. Using one of the SDKs greatly improves your team's productivity when writing large integrations.

### Which SDK should I choose? .NET or Java?

If you can choose your integration environment, we recommend using the .NET SDK over the Java SDK, simply because the .NET SDK is integrated into a number of Aquarius add-on products like Aquarius WebPortal, Aquarius DAS, Aquarius EnviroSCADA, and Aquarius Forecast. Since we use the .NET SDK internally for our own products, any issues tend to be noticed and resolved very quickly.

That said, the Java SDK is a fine choice if you prefer to work in Java, and we welcome any suggestions or contributions from the community to improve either SDK.


# What level of support can I expect?
Aquatic Informatics hosts some open source software projects on GitHub at https://github.com/AquaticInformatics. These projects can provide sample code, freely-downloadable tools, and/or extensions compatible with Aquarius products.

You can use them at your own risk, according to each project's open source license terms, which are clearly disclosed on the home page of each open source repository. These offerings are not part of the official released packages and therefore are not supported under the regular Service and Maintenance Agreement.

Our Support Team tries their best to help you but if you have questions/issues, it is recommended that you raise an issue on the project's Issues page. Our GitHub projects are managed by our Applications Engineering Team and they will get back to you.

# Code of Conduct

Each open source repository is governed by a code of conduct, derived from the from the [Contributor Covenant][homepage], version 1.4, available at [http://contributor-covenant.org/version/1/4][version].

The basic summary is "don't be a jerk" and everything should be fine.

[homepage]: http://contributor-covenant.org
[version]: http://contributor-covenant.org/version/1/4/
