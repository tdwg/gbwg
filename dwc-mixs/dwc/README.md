# A Darwin Core extension for DNA derived data

Example of how MIxS terms could be used in a DwC extension is [here](extension/mixs_darwin_core_extension.xml) (human readable version [here](https://tdwg.github.io/gbwg/dwc-mixs/dwc/extension/mixs_darwin_core_extension.xml)).

DwC vocabularies for MIxS terms with enumeration value syntax are [here](#vocabularies).

## MIxS terms excluded from the extension

The extension based on MIxS and includes all terms from MIxS v6 core, with the exception the following considered redundant to DwC terms. See [SSSOM mapping DwC-MIxS interoperability](https://docs.google.com/spreadsheets/d/1k6Xe1OREUVISLjw1XLrtLqWsE7QgvWf7lSIXEbqXDpA/edit#gid=0).

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


## Vocabularies

DwC vocabularies for MIxS terms with enumeration value syntax are [here](vocabulary/).
These are used for picklists in the IPT when mapping data.
Human readable versions:

- [assembly_qual (MIXS:0000056)](https://tdwg.github.io/gbwg/dwc-mixs/dwc/vocabulary/assembly_qual.xml)
- [bin_param (MIXS:0000077)](https://tdwg.github.io/gbwg/dwc-mixs/dwc/vocabulary/bin_param.xml)
- [bin_software (MIXS:0000078)](https://tdwg.github.io/gbwg/dwc-mixs/dwc/vocabulary/bin_software.xml)
- [compl_appr (MIXS:0000071)](https://tdwg.github.io/gbwg/dwc-mixs/dwc/vocabulary/compl_appr.xml)
- [contam_screen_input (MIXS:0000005)](https://tdwg.github.io/gbwg/dwc-mixs/dwc/vocabulary/contam_screen_input.xml)
- [decontam_software (MIXS:0000074)](https://tdwg.github.io/gbwg/dwc-mixs/dwc/vocabulary/decontam_software.xml)
- [detec_type (MIXS:0000084)](https://tdwg.github.io/gbwg/dwc-mixs/dwc/vocabulary/detec_type.xml)
- [host_pred_appr (MIXS:0000088)](https://tdwg.github.io/gbwg/dwc-mixs/dwc/vocabulary/host_pred_appr.xml)
- [lib_layout (MIXS:0000041)](https://tdwg.github.io/gbwg/dwc-mixs/dwc/vocabulary/lib_layout.xml)
- [mag_cov_software (MIXS:0000080)](https://tdwg.github.io/gbwg/dwc-mixs/dwc/vocabulary/mag_cov_software.xml)
- [pred_genome_struc (MIXS:0000083)](https://tdwg.github.io/gbwg/dwc-mixs/dwc/vocabulary/pred_genome_struc.xml)
- [pred_genome_type (MIXS:0000082)](https://tdwg.github.io/gbwg/dwc-mixs/dwc/vocabulary/pred_genome_type.xml)
- [rel_to_oxygen (MIXS:0000015)](https://tdwg.github.io/gbwg/dwc-mixs/dwc/vocabulary/rel_to_oxygen.xml)
- [seq_meth (MIXS:0000050)](https://tdwg.github.io/gbwg/dwc-mixs/dwc/vocabulary/seq_meth.xml)
- [single_cell_lysis_appr (MIXS:0000076)](https://tdwg.github.io/gbwg/dwc-mixs/dwc/vocabulary/single_cell_lysis_appr.xml)
- [sort_tech (MIXS:0000075)](https://tdwg.github.io/gbwg/dwc-mixs/dwc/vocabulary/sort_tech.xml)
- [source_uvig (MIXS:0000035)](https://tdwg.github.io/gbwg/dwc-mixs/dwc/vocabulary/source_uvig.xml)
- [tax_ident (MIXS:0000053)](https://tdwg.github.io/gbwg/dwc-mixs/dwc/vocabulary/tax_ident.xml)
- [trophic_level (MIXS:0000032)](https://tdwg.github.io/gbwg/dwc-mixs/dwc/vocabulary/trophic_level.xml)
- [virus_enrich_appr (MIXS:0000036)](https://tdwg.github.io/gbwg/dwc-mixs/dwc/vocabulary/virus_enrich_appr.xml)
- [wga_amp_appr (MIXS:0000055)](https://tdwg.github.io/gbwg/dwc-mixs/dwc/vocabulary/wga_amp_appr.xml)
