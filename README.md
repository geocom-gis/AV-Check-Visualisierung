# AV-Check-Visualisierung 
AV-Check-Visualisierung imports INTERLIS 1 (EPSG:2056) files based on the data model ERRORLOG14 and visualizes the imported content based on GEONIS expert technology. The table of content is structured based on the data model DM.01-AV-CH_LV95.

The data transfer (INTERLIS 1 to ArcGIS-Geodatabase) is built on FME Desktop (x86).

Detailed documentation is available in the folder ..\av_checkvis\documentation. (german only)

DISCLAMER: Please be aware that this product is not supported. Further information can be found in the license file.

For more information please contact: support@geocom.ch

Your Team VertiGIS AV

# Requirements
Minimal requirements: FME only (without GEONIS Data Converter)
* FME Desktop (32-bit) 2018.0.1.1 (Build 18312) or newer
* ArcGIS Desktop 10.6.(.1) and 10.8.(.1)
* GEONIS expert 2021.0 or newer

Additional requirements: Integrated usage with GEONIS Data Converter 
* GEONIS Data Converter 2021.0 or newer

# Installation

1.	Download av_checkvis.zip
2.	Unzip the file into ..\media
3.	Follow the instructions documented in ..\media\ \av_checkvis\documentation\Benutzerhandbuch-AV-Check-Visualisierung.pdf

# Usage

AV-Check-Visualisierung imports the data into a secondary database specialized for the ERRORLOG14 data model.

After the tool is set up and configured, the table of contents is expanded with the information from the INTERLIS file, and the imported data is visualized.

There are 4 preconfigured table of content extensions:

*	Only errors
*	Errors and warnings
*	Errors and warnings sorted by topic – name
*	Only warnings
The table of content configuration (legend.xsd) files can be modified for own purposes.
The configurations can be combined with legend profiles configured by GEONIS Administrator.

<ins> Important hint: </ins>

Even though the data are not visualized all data from the source INTERLIS files are imported. Just the table of content configuration file must be extended by the other Topics.
Restrictions of the available configuration and documentation
*	The delivered detailed manual is German only. But with more advanced GEONIS configuration knowledge there is no need for it.
*	The visualization is configured for the topics based on the data model DM.01-AV-CH_LV95. The queries within the table of content configuration (legend.xsd) can be easily changed with the other languages or the topics from the cantons extensions.

# Restrictions of the available configuration and documentation

* The delivered detailed manual is German only. But with more advanced GEONIS configuration knowledge there is no need for it.
* The visualization is configured for the topics based on the data model DM.01-AV-CH_LV95. The queries within the table of content configuration (legend.xsd) can be easily changed with the other languages or the topics from the cantons extensions.
