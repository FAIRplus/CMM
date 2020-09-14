# FAIR + Indicators 
> version 0.1

### Study Level


|||
|------------------|-------------------------------|
|F+-A-01M|Metadata follows common data profiles, models, schemas|
|F+-A-02M|Metadata contains variable names and their description|
|F+A-01D|There is a persistence policy about how long data will be maintained.|
|F+SXX|Data is structured by following a life sciences domain model, core classes and their semantic relations refers to a common data model.<br><br>Meaningful exchange of information is a fundamental challenge in life sciences research. A domain model A domain is an abstract, implementation-independent representation of the grammar, or semantics, of a domain ([Freimuth, et. all)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3486731/) . Domain models define core classes and the semantic relationships between them, as well as providing unambiguous definitions for concepts required to describe life sciences research. Examples of life sciences common data models are [OMOP](https://www.ohdsi.org/data-standardization/the-common-data-model/), [BRIDG](https://bridgmodel.nci.nih.gov/high-level-concept), [Lifesciences DAM](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3486731/), [functional genomics](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1262694/figure/F1/) data modelling.<br><br>Related DU Area : Interpretability + Integration|



### Assays / Data Set Level:


|||
|----------------|-------------------------------|
|F+AXX|Data is encoded in a community specific exchange standard.<br><br>A data exchange standard defined the encoding format of data. A data exchange standard delineates what data types can be encoded and the particular way they should be encoded (e.g., tab-delimited columns, XML, binary, etc. They facilitate the exchange of information between researchers and organizations, and between software programs or information storage systems. ). They provide syntax standards but do not specify what the document should contain in order to be considered complete ([Chervitz, et all.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4152841/)). See examples for [omic data](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4152841/table/T4/), for microarray-based [transcriptomics](https://www.researchgate.net/publication/257204855_A_sea_of_standards_for_omics_data_Sink_or_swim/figures) , for [clinical data](https://en.wikipedia.org/wiki/Clinical_Data_Interchange_Standards_Consortium#Individual_standards).<br><br>Related DU Area : Interoperability <br><br> Extends RDA-I1-01D Data uses knowledge representation expressed in standardised format|
|F+AXX|A machine and human readable formal description of the structure of data is available including types, properties.<br><br>A schema describes the structure of the data. Special schemes have meanings associated with databases, such as community agreed profiles. A schema consists of a key dimension and its properties, expected types, constraints, cardinalities and associated controlled vocabularies (preferably refers to existing ontologies). Schemas and profiles can be registered and reused, see examples [Schema.org](https://schema.org/docs/schemas.html), [Bioschemas](https://bioschemas.org/profiles/), [HL7 resources](https://www.hl7.org/fhir/resourcelist.html).<br><br>Related DU Area : Integration<br><br>Extends RDA-I1-01D Data uses knowledge representation expressed in standardised format|
