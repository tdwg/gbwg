# Memorandum of Understanding (MoU) between TDWG and the GSC

## Preamble
The Biodiversity Information Standards (TDWG) group and the Genomic Standards Consortium (GSC) have emerged as de facto (meta)data standards authorities in the biodiversity domain. The former’s scope spans biodiversity data at large, while the latter focuses on genomic, and then multi-omic, data and metadata such as lab protocols or chemical/physical measurements. Their activities, technologies, and management structures have been largely parallel, with some notable exceptions catalysed through joint interest groups such as the Genomic Biodiversity Working Group (GBWG).

The overlap of TDWG and the GSC in multi-omic biodiversity data is an opportunity to begin sustainable convergence of the (meta)data standards these organisations maintain. Most notably among these, are the Darwin Core (DwC) and the Minimal Information about any (x) Sequence (MIxS) specifications. This memorandum builds on the output of a [GBWG task group](https://www.tdwg.org/community/gbwg/MIxS/) to propose a solution for sustained mapping and scalable interoperation of both DwC and MIxS. Its goal is to ensure that TDWG and the GSC create a lasting and continuous model to synchronise their standards, eventually promoting full bi-lateral integration.

## Memorandum

**Recognizing** that both the Biodiversity Information Standards (TDWG) group and the Genomic Standards Consortium (GSC) have established well-adopted and community-driven (meta)data specifications for sequence-based biodiversity data;

**Further recognizing** that users of one standard specification should not have to invest additional effort in independently translating their (meta)data into another;

**It is resolved that:**
- The GSC and TDWG will maintain and endorse an authoritative and machine-readable [mapping](https://github.com/tdwg/gbwg/tree/v2.0.0/dwc-mixs/mapping) of the fields in their MIxS and DwC (meta)data standard specifications;
- These authoritative mappings (in SSSOM-compliant tab-separated value files) and other digital references will be maintained in the GBWG GitHub repository within the TDWG organisation and with TDWG-issued IRIs for the mapping files;
- Further, both organisations will provide bilaterally endorsed reference implementations of how to use their counterpart’s specification in their data structures (e.g., a DwC Archive incorporating fields mapped to MIxS in a DwC extension);
- Any necessary modification of identifiers (URNs, URLs, URIs, IRIs, etc.) or other components of a standard issued by one organisation which impacts the other should be declared and the particulars agreed upon in documented appendices to this MoU;
- When one specification is updated, the TDWG DwC Maintenance Group and the GSC Compliance and Interoperability Group (CIG) will hold joint sessions to update and validate any mappings and reference implementations to ensure clarity in the multi-omic biodiversity data community.
- The communication channels to communicate updates of either specification will be the [MIxS issue tracker](https://github.com/GenomicsStandardsConsortium/mixs/issues) and the [DwC issue tracker](https://github.com/tdwg/dwc/issues). If any of the terms in the mapping are subject to review, the parties will notify each other through those communication channels.

**Additionally recognizing that** unilateral innovation and research actions will propose and implement alternative mappings and extensions to sequence-based metadata specifications.

**It is further resolved that:**
- Only those modifications which have been reviewed and endorsed by mechanisms bi-laterally convened by TDWG and the GSC will be considered standardised;
- Innovation is still welcome, and both organisations will welcome input and inspiration from application-driven modifications of the base standard.

## Signatories:

Representative of TDWG Executive (Deborah Paul) 

Representative of the GSC Board (Lynn Schriml)
