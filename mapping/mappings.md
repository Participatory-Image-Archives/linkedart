# Metadata Mapping

Mappings were done in the context of the database migration of the photographic archives of the Swiss Society for Folkflore Studies (SSFS / _Schweizerische Gesellschaft für Volkskunde, SGV_) and for the [PIA research project](https://about.participatory-archives.ch), where different APIs (including IIIF and Linked Art) will be leveraged (see the simplified overview of the PIA Architecture below)

![PIA Architecture - Simplified Overview](../assets/pia_simplifiedoverview.jpg)

## Models

- Old SSFS/SGV Data Model hosted on [Salsah](https://www.salsah.org/)
- New SSFS/SGV Data Model, which has for most of its properties external mapping to [Schema.org](https://schema.org/). It will be hosed on the [DaSCH Service Platform](https://docs.dasch.swiss/) (DSP)
- [PIA JSON API](https://data.participatory-archives.ch/) which is based on a [database dump]() that was extracted from a [Salsah export mid-2021 containing metatada relavant to PIA](https://github.com/Participatory-Image-Archives/pia-data-model/tree/main/salsah-export) and which has and continues to evolve to accomodate the research project needs. After the migration of the database, this will also be amended in terms of properties and the metadata will be updated. The synchronisation process, for example via the DSP API, is still to be investigated. 
- [Linked Art](https://linked.art/)

Access to the CSV Table...