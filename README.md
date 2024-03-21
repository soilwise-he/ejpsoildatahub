# Soilinfohub

This repository is a participative effort to collect and maintain a series of descriptions of soil datasets (metadata) in the EU to facilitate discovery of these resources. As a soil scientist or practitioner you are very much invited to contribute to this effort by creating [issues](../../issues) or [pull requests](../../pulls) with improvement suggestions and/or flagging incomplete content.

If a dataset is already described elsewhere ([INSPIRE](https://inspire-geoportal.ec.europa.eu/overview.html?view=themeOverview&theme=so), [OpenAire](https://explore.openaire.eu/search/find/dataproviders?fv0=soil&f0=q), ...) a reference should be made to the external source, so the metadata can be automatically synchronised. Use the metadata:dataseturi property to capture a reference to the remote document. For now we support either a DOI or a iso19139:2007 document.

The initial format for data submission is CSV, according to a predefined template. Records in the CSV's are converted to [MCF](https://github.com/geopython/pygeometa), an optimal format for content versioning in GIT. The MCF is later transformed to iso19139 which can be ingested by common catalog products, such as [pycsw](https://pycsw.org) 

<hr>

## Soilwise Horizon Europe

This repository is maintained in the scope of the [Soilwise HE](https://soilwise-he.eu/) project.

<hr>

## EJP Soil

The initial content of this repository has been collected as part of the [EJP Soil project](https://ejpsoil.eu/), which has run a number of [stock takes](https://ejpsoil.eu/fileadmin/projects/ejpsoil/WP2/Deliverable_2.2_Stocktaking_on_soil_quality_indicators_and_associated_decision_support_tools__including_ICT_tools.pdf) of available soil datasets in EU member states. 

Dataset descriptions are stored in a format called [metadata control file](https://geopython.github.io/pygeometa/reference/mcf/) (MCF), which is a subset of [ISO19115](https://www.iso.org/standard/53798.html) encoded as [YAML](https://yaml.org/), an optimal encoding for content versioning. An online editor for MCF files is [MDME](https://osgeo.github.io/mdme). 

At intervals the content of this repository is published is a repository which is searchable through [CSW](https://www.ogc.org/standard/cat/), [STAC](https://stacspec.org/en), [OAI-PMH](https://www.openarchives.org/pmh/) and [OGC API Records](https://ogcapi.ogc.org/records/) enpoints. 
