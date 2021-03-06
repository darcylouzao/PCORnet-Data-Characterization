# PCORnet Data Characterization Query Package

### Version v3.03

### Purpose
The purpose of the Data Characterization Query Package v3.03 is to characterize the data in 11 PCORnet Common Data Model (CDM) v3.0 tables. The package consists of 117 queries and an Empirical Data Characterization Report which summarizes key information from the query output and evaluates the results against PCORnet’s Data Checks.

### PCORnet data partners run code packages distributed through PopMedNet
It's crucially important for data partners to follow the process of running the exact code module distributed to your DataMart by the Operations Center (via PopMedNet). This process ensures that end-to-end provenance is preserved. Complete instructions on how to run this code are provided to PCORnet DataMarts when the query is distributed to a given DataMart. 

### This GitHub repository is a copy for reference
PCORnet's Distributed Research Network Operations Center (DRN OC) is responsible for distribution of the production code package to data partners, which happens within PopMedNet.

Waves of data partner querying may result in more than one code package being active at any given time. Beta testing is also an important ongoing activity.

Therefore, **this repository is not the production version of the code package**, but instead serves as a copy for reference and knowledge sharing.

### System Requirements
This code is designed to run in SAS versions 9.3 or higher with SAS/GRAPH.

### Scope
Output tables are produced by running the SAS code against static local DataMarts in PCORnet CDM v3.0 with SAS data types. 

CDM specifications are available at [http://www.pcornet.org/pcornet-common-data-model/] (http://www.pcornet.org/pcornet-common-data-model/). This version of the query allows DataMarts to incorporate [CDM errata identified as of January 20, 2016] (https://github.com/CDMFORUM/CDM-ERRATA/blob/master/2016-01-20%20PCORnet%20CDM%20v3dot0%20errata.pdf).

### Acknowledgments
This code package was developed by the Data Characterization Development Team in the DRN OC, with members from the Duke Clinical Research Institute. We gratefully acknowledge their work and individual contributions.
