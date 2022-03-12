# Open Source at Aquatic Informatics

![Logo](https://github.com/AquaticInformatics/aquarius-sdk-net/raw/develop/images/aquatic-informatics.svg)

Welcome to the Aquatic Informatics open source offerings on GitHub. Hopefully this guide can get you pointed in the right direction.

# Are you a customer, just looking for some files?

You may have been directed here, and are just looking to download some prepackaged tool or extension for an AQUARIUS product you own. The GitHub web pages are very programmer-centric, and it can be a bit hard to navigate and find the specific files you need.

| AQUARIUS Product | Download link | Documentation | Description |
| --- | --- | --- | --- |
| AQUARIUS Time-Series 2017.3+ | [ReportRunner.exe](https://github.com/AquaticInformatics/getting-started/releases/download/ReportRunner/ReportRunner.exe) | [Here](https://github.com/AquaticInformatics/getting-started/wiki/ReportRunner) | The `ReportRunner.exe` tool is a command-line tool for running reports on an AQTS system. It can also wait for the report to be rendered by the app server and download the generated PDF or CSV.<br/><br/>The `ReportRunner.exe` tool is also included in the "201X.Y.Reports.zip" archives above. |
| AQUARIUS Time-Series 2021.1+ | [2021.1 R-based report plugins](https://github.com/AquaticInformatics/getting-started/releases/download/v2021.1-aqts/2021.1.R-Reports.zip) | [Operation](https://github.com/AquaticInformatics/getting-started/releases/download/v2021.1-aqts/Profile.Report.pdf) and [Installation](https://github.com/AquaticInformatics/getting-started/releases/download/v2021.1-aqts/Readme.pdf) | This ZIP archive contains 1 report plugin (the [Profile Report](https://github.com/AquaticInformatics/getting-started/releases/download/v2021.1-aqts/Profile.Report.pdf)), which uses the [R runtime](https://cran.r-project.org/) to render its output. Use the System Config page to install this plugin, and run the `InstallMissingPackages.cmd` script with Administrator priveleges to install the required R runtime and package dependencies. |
| AQUARIUS Time-Series 3.x and 20xx | [Sample field data files](https://github.com/AquaticInformatics/examples/tree/master/TimeSeries/SampleFiles/FieldData) | [Here](https://github.com/AquaticInformatics/examples/tree/master/TimeSeries/SampleFiles/FieldData/Readme.md)| This page lists a description of each field data file formats supported by AQUARIUS Time-Series. A sample of each file type is provided for download. |
| AQUARIUS Time-Series 3.x | [FlowTracker2Converter.exe](https://github.com/AquaticInformatics/flowtracker2-field-data-plugin/releases/download/v19.2.12/FlowTracker2Converter.exe) | [Here](https://github.com/AquaticInformatics/flowtracker2-field-data-plugin/blob/master/src/FlowTracker2Converter/Readme.md)| Use this GUI tool to convert FlowTracker2 `*.ft` files into FlowTracker1 `*.dis` files which can be imported into your AQTS 3.X system. |
| AQUARIUS Time-Series 20xx | [FlowTracker2Plugin.plugin](https://github.com/AquaticInformatics/flowtracker2-field-data-plugin#plugin-compatibility-matrix) | [Here](https://github.com/AquaticInformatics/flowtracker2-field-data-plugin#flowtracker2-field-data-plugin)| A field data plugin to import FlowTracker2 `*.ft` discharge measurements. |
| AQUARIUS Time-Series 2019.4+ | [TabularCsv.plugin](https://github.com/AquaticInformatics/tabular-field-data-plugin#plugin-compatibility-matrix) | [Here](https://github.com/AquaticInformatics/tabular-field-data-plugin/wiki/Tabular-CSV-plugin-overview)| A user-configurable field data plugin to import nearly any field visit activity from a CSV file. |
| AQUARIUS Time-Series 2018.4+ | [JsonFieldData.plugin](https://github.com/AquaticInformatics/aquarius-field-data-framework/tree/master/src/JsonFieldData#plugin-compatibility-matrix) | [Here](https://github.com/AquaticInformatics/aquarius-field-data-framework/blob/master/src/JsonFieldData/Readme.md#json-field-data-plugin)| A field data plugin to import visits from JSON files. Used by the `FieldVisitHotFolderService`. |
| AQUARIUS Time-Series 2018.4+ | [MultiFile.plugin](https://github.com/AquaticInformatics/aquarius-field-data-framework/blob/master/src/MultiFile/Readme.md#plugin-compatibility-matrix) | [Here](https://github.com/AquaticInformatics/aquarius-field-data-framework/blob/master/src/MultiFile/Readme.md#multi-file-field-data-plugin)| A field data plugin to import visits from ZIP archives containing other plugin visit data files. |
| AQUARIUS Time-Series 20xx | [SxSPro.plugin](https://github.com/AquaticInformatics/sxs-pro-field-data-plugin#sxs-pro-field-data-plugin) | [Here](https://github.com/AquaticInformatics/sxs-pro-field-data-plugin#sxs-pro-field-data-plugin)| A field data plugin to import discharge summary XML measurements from Teledyne SxS Pro software. |
| AQUARIUS Time-Series 20xx | [AquaCalc5000.plugin](https://github.com/AquaticInformatics/aquacalc-5000-field-data-plugin#plugin-compatibility-matrix) | [Here](https://github.com/AquaticInformatics/aquacalc-5000-field-data-plugin#aquacalc-5000-field-data-plugin)| A field data plugin to import discharge summary measurements from AquaCalc 5000 CSV files. |
| AQUARIUS Time-Series 202x | [QRev.plugin](https://github.com/AquaticInformatics/qrev-field-data-plugin#qrev-field-data-plugin) | [Here](https://github.com/AquaticInformatics/qrev-field-data-plugin/blob/master/src/QRev/Readme.md#qrev-field-data-plugin)| A field data plugin to import discharge summary XML measurements from USGS QRev software. |
| AQUARIUS Time-Series 2018.4+ | [FieldVisitHotFolderService.zip](https://github.com/AquaticInformatics/aquarius-field-data-framework/blob/master/src/FieldVisitHotFolderService/Readme.md#compatibility-matrix) | [Here](https://github.com/AquaticInformatics/aquarius-field-data-framework/blob/master/src/FieldVisitHotFolderService/Readme.md#field-visit-hot-folder-service)| A Windows service which can monitor a folder for field visit files and upload visits to AQTS. |
| AQUARIUS Time-Series 20xx | [UserImporter.exe](https://github.com/AquaticInformatics/examples/releases/download/v1.0.376/UserImporter.exe) | [Here](https://github.com/AquaticInformatics/examples/tree/master/TimeSeries/PublicApis/SdkExamples/UserImporter#userimporter)| A console tool for quickly provisioning users in your AQTS system from a CSV file. |
| AQUARIUS Time-Series 20xx | [PointZilla.exe](https://github.com/AquaticInformatics/examples/releases/download/v1.0.376/PointZilla.exe) | [Here](https://github.com/AquaticInformatics/examples/blob/master/TimeSeries/PublicApis/SdkExamples/PointZilla/Readme.md)| A console tool for quickly appending points to a time-series. |
| AQUARIUS Time-Series 20xx | [TimeSeriesChangeMonitor.exe](https://github.com/AquaticInformatics/examples/releases/download/v1.0.376/TimeSeriesChangeMonitor.exe) | [Here](https://github.com/AquaticInformatics/examples/blob/master/TimeSeries/PublicApis/SdkExamples/TimeSeriesChangeMonitor/Readme.md)| A console tool for monitoring how quickly changes in a time-series become available on the Publish API. Use it along side PointZilla to precisely measure the behaviour of your data flow. |
| AQUARIUS Time-Series 20xx | [LocationDeleter.exe](https://github.com/AquaticInformatics/examples/releases/download/v1.0.374/LocationDeleter.exe) | [Here](https://github.com/AquaticInformatics/examples/blob/master/TimeSeries/PublicApis/SdkExamples/LocationDeleter/Readme.md)| A console tool for deleting locations and/or visits and/or time-series during initial system configuration. You obviously won't want to run this on a production system. |
| AQUARIUS Time-Series 202x | [OGC SOS Proxy](https://github.com/AquaticInformatics/examples/tree/master/TimeSeries/PublicApis/SdkExamples/SosExporter/docker-proxy#sos-proxy-for-aquarius-time-series) | [Here](https://github.com/AquaticInformatics/examples/tree/master/TimeSeries/PublicApis/SdkExamples/SosExporter/docker-proxy#sos-proxy-for-aquarius-time-series)| An API proxy for exporting time-series data to an OCG SOS server as sensor observations, suitable for consumption by national aggregation systems like [LAWA](https://www.lawa.org.nz/). |
| AQUARIUS Time-Series 20xx | [ProvisioningTool.zip](https://github.com/AquaticInformatics/getting-started/releases/download/ProvisioningTool/ProvisioningTool.zip) | [Here](https://github.com/AquaticInformatics/getting-started/wiki/ProvisioningTool)| A console tool for performing bulk provisioning operations of an AQTS system from CSV data. The ZIP archive includes sample CSV files for many types of AQTS entities. |
| AQUARIUS Time-Series 20xx | [RatingModelExchange.exe](https://github.com/AquaticInformatics/getting-started/releases/download/RatingModelExchange/RatingModelExchange.exe) | [Here](https://github.com/AquaticInformatics/getting-started/wiki/RatingModelExchange)| A console tool for importing and exporting rating models into AQTS 201x systems, supporting both HydroML formats (XML) and a simpler CSV format. |
| AQUARIUS Time-Series 20xx | [AttachmentUploader.exe](https://github.com/AquaticInformatics/getting-started/releases/download/AttachmentUploader/AttachmentUploader.exe) | [Here](https://github.com/AquaticInformatics/getting-started/wiki/AttachmentUploader)| A console tool for uploading location and field visit attachments into AQTS 201x systems. |
| AQUARIUS Time-Series 3.x and 20xx<br/>AQUARIUS WebPortal<br/>AQUARIUS Connect | [SystemSizer.exe](https://github.com/AquaticInformatics/getting-started/releases/download/SystemSizer/SystemSizer.exe) | [Here](https://github.com/AquaticInformatics/getting-started/wiki/SystemSizer)| A console tool to run on an AQTS, WebPortal, or Connect app server and determine the basic size and configuration of the system. The `SystemSizer.log` file generated by this tool contains useful information when diagnosing issues with our Support Team. |

## Legacy content

For product versions that are no longer officially supported:

| AQUARIUS Product | Download link | Documentation | Description |
| --- | --- | --- | --- |
| AQUARIUS Time-Series 20xx | [SosExporter.exe](https://github.com/AquaticInformatics/examples/releases/download/v1.0.297/SosExporter.exe) | [Here](https://github.com/AquaticInformatics/examples/blob/master/TimeSeries/PublicApis/SdkExamples/SosExporter/Readme.md)| A console tool for exporting time-series data to an OCG SOS server as sensor observations, suitable for consumption by national aggregation systems like [LAWA](https://www.lawa.org.nz/). |
| AQUARIUS Time-Series<br/>2019.2 | [2019.2 Report plugins](https://github.com/AquaticInformatics/getting-started/releases/download/v2019.2-aqts/2019.2.Reports.zip) | [Operation](https://github.com/AquaticInformatics/getting-started/releases/download/v2019.2-aqts/Report.Documentation.-.2019.2.Beta.Release.pdf) and [Installation](https://github.com/AquaticInformatics/getting-started/releases/download/v2019.2-aqts/ReportPluginInstaller.Readme.pdf) | This ZIP archive contains 12 report plugins and a report plugin installer, to add more reporting features to AQTS 2019.2. Use the [Report Plugin Installer](https://github.com/AquaticInformatics/getting-started/releases/download/v2019.2-aqts/ReportPluginInstaller.Readme.pdf) tool, included in the ZIP archive, to install these plugins. |
| AQUARIUS Time-Series<br/>2019.1<br/>2018.4 | [2018.4 Report plugins](https://github.com/AquaticInformatics/getting-started/releases/download/v2018.4-aqts/2018.4.Reports.zip) | [Operation](https://github.com/AquaticInformatics/getting-started/releases/download/v2018.4-aqts/Report.Documentation.-.2018.4.Beta.Release.pdf) and [Installation](https://github.com/AquaticInformatics/getting-started/releases/download/v2018.4-aqts/ReportPluginInstaller.Readme.pdf) | This ZIP archive contains 12 report plugins and a report plugin installer, to add more reporting features to AQTS 2018.4 and AQTS 2019.1. Use the [Report Plugin Installer](https://github.com/AquaticInformatics/getting-started/releases/download/v2018.4-aqts/ReportPluginInstaller.Readme.pdf) tool, included in the ZIP archive, to install these plugins. <br/><br/> Starting with AQTS 2018.4, previous report plugins will be preserved. There is no longer a need to uninstall previous report plugins after upgrading to AQTS 2018.4. |
| AQUARIUS Time-Series 2018.3 | [2018.3 Report plugins](https://github.com/AquaticInformatics/getting-started/releases/download/v2018.3-aqts/2018.3.Reports.zip) | [Operation](https://github.com/AquaticInformatics/getting-started/releases/download/v2018.3-aqts/Report.Documentation.-.2018.3.Beta.Release.pdf) and [Installation](https://github.com/AquaticInformatics/getting-started/releases/download/v2018.3-aqts/ReportPluginInstaller.Readme.pdf) | This ZIP archive contains 10 report plugins and a report plugin installer, to add more reporting features to AQTS 2018.3. Use the [Report Plugin Installer](https://github.com/AquaticInformatics/getting-started/releases/download/v2018.2-aqts/ReportPluginInstaller.Readme.pdf) tool, included in the ZIP archive, to install these plugins. <br/><br/> **Note that all beta report plugins from previous versions must be removed prior to installing the 2018.3 beta report plugins.** <br/><br/> The Report Plugin Installer tool can be used to uninstall 2018.2 report plugins and install 2018.3 report plugins. |
| AQUARIUS Time-Series 2018.2 | [2018.2 Report plugins](https://github.com/AquaticInformatics/getting-started/releases/download/v2018.2-aqts/2018.2.Reports.zip) | [Operation](https://github.com/AquaticInformatics/getting-started/releases/download/v2018.2-aqts/Report.Documentation.-.2018.2.Beta.Release.pdf) and [Installation](https://github.com/AquaticInformatics/getting-started/releases/download/v2018.2-aqts/ReportPluginInstaller.Readme.pdf) | This ZIP archive contains 7 report plugins and a report plugin installer, to add more reporting features to AQTS 2018.2. |

# Are you a developer, looking for code?

We have many software projects that allow you to easily extend or integrate with your AQUARIUS products.

Some are full software projects, with contiuous integration and unit tests, deployed via standard package distribution networks like NuGet or the Maven Central Repository.

Other projects are smaller proof-of-concept examples, which can be a useful starting point or inspiration for your own integrations.

### Platform SDKs

We have two SDK offerings, one for .NET and one for Java. These SDKs provide complete support for all the AQUARIUS products with public APIs (currently AQUARIUS Time-Series and AQUARIUS Samples, but more products will be added soon to these SDKs).

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

If you can choose your integration environment, we recommend using the .NET SDK over the Java SDK, simply because the .NET SDK is integrated into a number of AQUARIUS add-on products like AQUARIUS WebPortal, AQUARIUS DAS, AQUARIUS EnviroSCADA, and AQUARIUS Forecast. Since we use the .NET SDK internally for our own products, any issues tend to be noticed and resolved very quickly.

That said, the Java SDK is a fine choice if you prefer to work in Java, and we welcome any suggestions or contributions from the community to improve either SDK.

## Other open-source projects we host
| Project | Description |
| --- | --- |
| https://github.com/AquaticInformatics/aquarius-field-data-framework | A field data plugin development framework, so you can write custom plugins to consume your organization's unique field data. The framework is available on [NuGet](https://www.nuget.org/packages/Aquarius.FieldDataFramework) and includes testing and packaging tools. |
| https://github.com/AquaticInformatics/flowtracker2-field-data-plugin | A plugin for parsing SonTek's FlowTracker2 `*.ft` files. |
| [Python integration](https://github.com/AquaticInformatics/examples/tree/master/TimeSeries/PublicApis/Python) | A sample API wrapper for AQUARIUS Time-Series. |
| [R integration](https://github.com/AquaticInformatics/examples/tree/master/TimeSeries/PublicApis/R) | A fairly rich API wrapper for consuming time-series data in R. |
| https://github.com/AquaticInformatics/examples | Many examples, in many technologies. |


# What level of support can I expect?
Aquatic Informatics hosts some open source software projects on GitHub at https://github.com/AquaticInformatics. These projects can provide sample code, freely-downloadable tools, and/or extensions compatible with AQUARIUS products.

You can use them at your own risk, according to each project's open source license terms, which are clearly disclosed on the home page of each open source repository. These offerings are not part of the official released packages and therefore are not supported under the regular Service and Maintenance Agreement.

Our Support Team tries their best to help you but if you have questions/issues, it is recommended that you raise an issue on the project's Issues page. Our GitHub projects are managed by our Applications Engineering Team and they will get back to you.

# Code of Conduct

Each open source repository is governed by a code of conduct, derived from the from the [Contributor Covenant][homepage], version 1.4, available at [http://contributor-covenant.org/version/1/4][version].

The basic summary is "don't be a jerk" and everything should be fine.

[homepage]: http://contributor-covenant.org
[version]: http://contributor-covenant.org/version/1/4/
