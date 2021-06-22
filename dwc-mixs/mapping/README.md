# A DwC to MIxS mapping

The content of this folder is the result of an extensive mapping in the direction of DwC to MIxS using Simple Standard for Sharing Ontology Mappings ([SSSOM](https://github.com/mapping-commons/SSSOM)) in combination with the Simple Knowledge Organization System ([SKOS](https://www.w3.org/TR/skos-reference/)) ontology to qualify the mapping. 

To serve all MIxS core terms, the mapping should be used in combination with the [MIxS-DwC extension](https://github.com/tdwg/gbwg/tree/main/dwc-mixs/dwc).

## Content of this folder
This folder contains three mapping files in tab-separated value files:
* DwC-MIxS_mappingSemantic.tsv
   * includes relevant [SSSOM metadata elements](https://github.com/mapping-commons/SSSOM/blob/master/SSSOM.md#sssom-metadata-elements).
* DwC-MIxS_mappingSyntactic.tsv
   * includes relevant [SSSOM metadata elements](https://github.com/mapping-commons/SSSOM/blob/master/SSSOM.md#sssom-metadata-elements), however notes the syntactic mapping predicate [`syntax_predicate_id`] and accompanying comments[`syntax_comment`] instead of the semantic predicate.
* DwC-MIxS_mappingSupport.tsv
   * includes relevant [SSSOM metadata elements](https://github.com/mapping-commons/SSSOM/blob/master/SSSOM.md#sssom-metadata-elements), syntactic mapping predicates and accompanying comments, as well as additional metadata on the mapped terms (definitions [`subject_definition`, `object_definition`], syntax requirements [`subject_valueSyntax`, `object_valueSyntax`]).


## Terms included in the mapping

DwC terms included in this mapping
- Verbatim Coordinates
- Decimal Latitude
- Decimal Longitude
- Verbatim Latitude
- Verbatim Longitude
- Verbatim Depth
- Minimum Distance Above Surface in Meters
- Maximum Distance Above Surface in Meters
- Minimum Depth In Meters
- Maximum Depth In Meters
- Minimum Distance Above Surface in Meters
- Maximum Distance Above Surface in Meters
- Verbatim Elevation
- Minimum Elevation in Meters
- Maximum Elevation in Meters
- Country
- Water Body
- Higher Geography
- Event Date
- Material Sample ID
- Associated Organisms
- Sampling Protocol
- Sampling Protocol
- Sample Size Value
- Sample Size Unit
- References
- Associated Media
- Associated Occurrences
- Associated Organisms
- Associated References
- Associated Sequences
- Associated Taxa


MIxS terms included in this mapping
- `lat_lon` 
- `depth`
- `alt`
- `elev`
- `geo_loc_name`
- `collection_date`
- `source_mat_id`
- `biotic_relationship`
- `samp_collect_device`
- `samp_mat_process`
- `samp_size`
- `url`
