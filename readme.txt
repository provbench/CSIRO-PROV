# Mandatory information
Creators:    Heiko Mueller, Chris Peters, Yanfeng Shu, Andrew Terhorst
Submitter:   Heiko Mueller
Organization:	CSIRO
Date created:	2013-01-23
Date submitted:	2013-01-23
Tool used:	XArch, Java, Apache Jena
Data license:	cc-by-nc-sa

# Optional information
Provenance representation model: PROV-O, OWL
Domain of stud:	Workflow, Domain specific (Hydrology, Environmental Modelling, Streamflow Forecasting)
Project:  South Esk Flow Forecast (SEFF)
Link to provenance traces: http://www.csiro.au/sensorweb/seff/prov

# Files

seff-prov-traces.tar.gz:
A collection of 4,091 provenance traces of a streamflow forecasting workflow collected between 2011-09-01 and 2012-05-12. Provenance traces are represented as instances of a streamflow forecasting ontology that extends PROV-O. Individual traces are named seff-trace-<index>.owl.gz where <index> reflects the temporal order of traces.

seff-run-dates.txt:
A mapping of trace indexes to actual run dates. These dates can also be extracted from the individual OWL files.

timeseries-trace-1350.tar.gz-timeseries-trace-1449.tar.gz:
The individual provenance traces in seff-prov-traces.tar.gz do not contain the actual input and output time series data to save storage space. They contain references to these time series instead (e.g., http://www.csiro.au/sensorweb/seff/prov/rsgrid/version/7597/gridcell/147.6/-41.6). For 100 traces (1350-1449) we provide copies of the time series data. Here we chose a period of high rainfall activity at the end of November 2011.

# Web Access

All provenance traces are accessible on the Web at http://www.csiro.au/sensorweb/seff/prov. This includes individual time series for provenance traces (referenced in the submitted OWL files). The default data format is RDF. For most URL’s there is an option to also access the data in more compact XML or JSON format by adding the suffix .xml or .json to the URL.



License
- cc-by-nc-sa: Creative Commons Attribution-Noncommercial-Share Alike 3.0 Unported License, http://creativecommons.org/licenses/by-nc-sa/3.0/
