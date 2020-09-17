# FAIR + Indicators 
> version 0.1



## Index



| ID              | Indicators                                                   |
| --------------- | ------------------------------------------------------------ |
| [F+S01](#F+S01) | Data is reported by following community specific minimum information guidelines |
| [F+S02](#F+S02) | Metadata documents and provides references about all data biological data types and formats in data is expressed. |
| [F+S03](#F+S03) | Data is structured by following a life sciences domain model, core classes and their semantic relations refers to a common data model. |
| [F+A01](#F+A01) | Data is encoded in a community specific exchange standard.   |
| [F+A02](#F+A02) | A formal description of the structure of data is available in a machine and human readable format including types, properties. |
| [F+A03](#F+A03) | Data is described with terminology standards.                |



### Study Level

#### F+S01

|                 |                                                              |
| --------------- | ------------------------------------------------------------ |
| Description     | A reporting standard ensures recording the information (metadata) required to unambiguously communicate experimental designs, treatments and analyses, to con-textualize the data generated. Such standards are also known as data content or minimum information standards (Chervitz, et all.). See examples:  reporting standards  for health care, for life sciences data, collection of FAIRsharing |
| Related DU Area | Reproducibility + Repurposing                                |



####  F+S02

|                 |                                                              |
| --------------- | ------------------------------------------------------------ |
| Description     | Biological and biomedical research has been considered an especially challenging research field in this regard, as data types are extremely heterogeneous and not all have defined data standards ([Griffin, et. all](https://www.biorxiv.org/content/10.1101/167619v1.full)). Metadata should capture all data types and format names in a study, if possible provide a reference or URL for format specification, if not possible have a description. [Example](https://www.biorxiv.org/highwire/markup/341342/expansion?width=1000&height=500&iframe=true&postprocessors=highwire_tables%2Chighwire_reclass%2Chighwire_figures%2Chighwire_math%2Chighwire_inline_linked_media%2Chighwire_embed) list of common standard data formats for omics data. <br>Extends RDA-I1-01M Metadata uses knowledge representation expressed in standardised format. |
| Related DU Area | Interpretability                                             |



#### F+S03

|                 |                                                              |
| --------------- | ------------------------------------------------------------ |
| Description     | Meaningful exchange of information is a fundamental challenge in life sciences research. A domain model A domain is an abstract, implementation-independent representation of the grammar, or semantics, of a domain ([Freimuth, et. all)](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3486731/) . Domain models define core classes and the semantic relationships between them, as well as providing unambiguous definitions for concepts required to describe life sciences research. Examples of life sciences common data models are [OMOP](https://www.ohdsi.org/data-standardization/the-common-data-model/), [BRIDG](https://bridgmodel.nci.nih.gov/high-level-concept), [Lifesciences DAM](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3486731/), [functional genomics](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1262694/figure/F1/) data modelling. |
| Related DU Area | Interpretability + Integration                               |



### Assays / Data Set Level: 

#### F+A01

|                 |                                                              |
| --------------- | ------------------------------------------------------------ |
| Description     | A data exchange standard defined the encoding format of data. A data exchange standard delineates what data types can be encoded and the particular way they should be encoded (e.g., tab-delimited columns, XML, binary, etc. They facilitate the exchange of information between researchers and organizations, and between software programs or information storage systems. ). They provide syntax standards but do not specify what the document should contain in order to be considered complete ([Chervitz, et all.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4152841/)). See examples for [omic data](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4152841/table/T4/), for microarray-based [transcriptomics](https://www.researchgate.net/publication/257204855_A_sea_of_standards_for_omics_data_Sink_or_swim/figures) , for [clinical data](https://en.wikipedia.org/wiki/Clinical_Data_Interchange_Standards_Consortium#Individual_standards).<br/><br/>Extends RDA-I1-01D Data uses knowledge representation expressed in standardised format |
| Related DU Area | Interpretability                                             |

#### F+A02

|                 |                                                              |
| --------------- | ------------------------------------------------------------ |
| Description     | A schema describes the structure of the data. Special schemes have meanings associated with databases, such as community agreed profiles. A schema consists of a key dimension and its properties, expected types, constraints, cardinalities and associated controlled vocabularies (preferably refers to existing ontologies). Schemas and profiles can be registered and reused, see examples [Schema.org](https://schema.org/docs/schemas.html), [Bioschemas](https://bioschemas.org/profiles/), [HL7 resources](https://www.hl7.org/fhir/resourcelist.html).<br>Extends RDA-I1-01D Data uses knowledge representation expressed in standardised format |
| Related DU Area | Integration                                                  |



#### F+A03

|                 |                                                              |
| --------------- | ------------------------------------------------------------ |
| Description     | Terminology standards is typically defined by the use cases and provides control vocabularies to support and competency questions it is designed to answer. In life sciences domain ontologies are common ways to encode terminology standards ([Chervitz, et all.](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4152841/)). Terminology standards add an interpretive layer to the data by defining the concepts or terms in a domain, and in some cases the relationships between them ([Tenenbaum et. all](https://doi.org/10.1136/amiajnl-2013-002066)). See an example list for [terminology standards](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4152841/table/T5/). For a complete listing see the [OBO](http://www.obofoundry.org) Foundry. |
| Related DU Area | Interpretability                                             |






### 
