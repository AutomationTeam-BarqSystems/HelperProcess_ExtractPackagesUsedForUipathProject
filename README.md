# HelperProcess_ExtractPackagesUsedForUipathProject

A workflow is designed to extract all dependencies used across a set of UiPath projects, such as Dispatcher, Performer, and Reporting, from the local development machine's NuGet folder to a specified directory. 
This is particularly useful when working with two separate orchestrators, especially if the production orchestrator is air-gapped and cannot resolve certain dependencies from online sources.

inputs:  

-in_UipathProjectFolderPathsList *new list(of String) From {"Uipath Project1 Directory","Uipath Project2 Directory"}*


-in_ExtractionFolderPath *All Dependencies will be copied to this folder*
