# Passolo SDK Documentation #
Passolo is a localization tool that enables you to translate the user interfaces of software applications. You can find all the information about working with the Passolo SDK in the downloadable ZIP files. The ZIP files contains a compiled help file CHM with all the documenation, header files and samples.

The SDK documentation from the CHM file is not available on this site. The plan is to move it to this site in the near future.

## What does the Passolo SDK cover? ##
Passolo is a core application developed in C++. All available add-ins shipped with the product were developed using this SDK. Customers with specific requirements can use this SDK to develop their own Add-Ins. Add-Ins are grouped into the following types.
* Exporting string entries into files (for external translation), including uploading to external systems
* Importing string entries (from previously exported files), including import from external systems 
* Parse custom resources (other than standard) from executables and DLLs 
* Parse any user defined resource file format 
* Resource display to visualize and edit translatable resources from translation list resources
* Segmentation to split parsed key/value pairs into single sentences for better matching and translation
* Find translation matches in external TMs, find known terminology in external termbases, connect to external MT systems, store translations into TMs
* Implement your own spell checking Add-Ins 
* Add functionality to and define additional menu commands into the Tools menu


### Development Environment
Passolo Add-Ins can be developed in C++ and C# using Visual Studio. For C++ developments the SDK contains a header file addin.h with all definitions. For C# .NET wrapper DLLs are deployed with the product that must be referenced in Visual Studio.

### Passolo 2018 SDK Download
The SDK ZIP file can be downloaded [here](Passolo_2018_AddIn_SDK.zip).

### Passolo 2022 SDK Download
The SDK ZIP file can be downloaded [here](Passolo_2022_AddIn_SDK.zip).
