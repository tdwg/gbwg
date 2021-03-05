# A Darwin Core extension for DNA derived data

The draft extension is [here](extension/dna_derived_data.xml) (human readable version [here](https://thomasstjerne.github.io/gbwg/dwc-mixs/dwc/extension/dna_derived_data.xml)).

DwC vocabularies for MIxS terms with enumeration value syntax are [here](#vocabularies).

The initial draft was prepared as part of the "Publishing DNA-derived data through biodiversity data platforms" (https://doi.org/10.35035/doc-vf1a-nr22) 

## Terms included in the extension

### Source: MIxS

The extension based primarily on MIxS and includes all terms from MIxS v6 core, with the exception the following considered redundant to terms in [DwC:Location](https://dwc.tdwg.org/terms/#location).

- `lat_lon` 
- `depth`
- `alt`
- `elev`
- `geo_loc_name`
- `collection_date`

The extension also includes some atomized terms based on the `pcr_primers` field:

- `pcr_primer_forward`
- `pcr_primer_reverse`

And the following related terms

- `pcr_primer_name_forward`
- `pcr_primer_name_reverse`
- `pcr_primer_reference`

### Source: GGBN

- `concentration`
- `concentrationUnit`
- `methodDeterminationConcentrationAndRatios`
- `ratioOfAbsorbance260_230`
- `ratioOfAbsorbance260_280`
  

### Souce: MIQE

These terms was included to support data derived from qPCR and ddPCR assays.
See https://doi.org/10.1373/clinchem.2008.112797

- `annealingTemp`
- `annealingTempUnit`
- `probeReporter`
- `probeQuencher`
- `ampliconSize`
- `thresholdQuantificationCycle`
- `baselineValue`
- `quantificationCycle`
- `automaticThresholdQuantificationCycle`
- `automaticBaselineValue`
- `contaminationAssessment`
- `partitionVolume`
- `partitionVolumeUnit`
- `estimatedNumberOfCopies`
- `amplificationReactionVolume`
- `amplificationReactionVolumeUnit`
- `pcr_analysis_software`

## Vocabularies

DwC vocabularies for MIxS terms with enumeration value syntax are [here](vocabulary/).
These are used for picklists in the IPT when mapping data.
Human readable versions:

- [assembly_qual (MIXS:0000056)](https://thomasstjerne.github.io/gbwg/dwc-mixs/dwc/vocabulary/assembly_qual.xml)
- [bin_param (MIXS:0000077)](https://thomasstjerne.github.io/gbwg/dwc-mixs/dwc/vocabulary/bin_param.xml)
- [bin_software (MIXS:0000078)](https://thomasstjerne.github.io/gbwg/dwc-mixs/dwc/vocabulary/bin_software.xml)
- [biotic_relationship (MIXS:0000028)](https://thomasstjerne.github.io/gbwg/dwc-mixs/dwc/vocabulary/biotic_relationship.xml)
- [compl_appr (MIXS:0000071)](https://thomasstjerne.github.io/gbwg/dwc-mixs/dwc/vocabulary/compl_appr.xml)
- [contam_screen_input (MIXS:0000005)](https://thomasstjerne.github.io/gbwg/dwc-mixs/dwc/vocabulary/contam_screen_input.xml)
- [decontam_software (MIXS:0000074)](https://thomasstjerne.github.io/gbwg/dwc-mixs/dwc/vocabulary/decontam_software.xml)
- [detec_type (MIXS:0000084)](https://thomasstjerne.github.io/gbwg/dwc-mixs/dwc/vocabulary/detec_type.xml)
- [env_package (MIXS:0000019)](https://thomasstjerne.github.io/gbwg/dwc-mixs/dwc/vocabulary/env_package.xml)
- [health_disease_stat (MIXS:0000031)](https://thomasstjerne.github.io/gbwg/dwc-mixs/dwc/vocabulary/health_disease_stat.xml)
- [host_pred_appr (MIXS:0000088)](https://thomasstjerne.github.io/gbwg/dwc-mixs/dwc/vocabulary/host_pred_appr.xml)
- [lib_layout (MIXS:0000041)](https://thomasstjerne.github.io/gbwg/dwc-mixs/dwc/vocabulary/lib_layout.xml)
- [mag_cov_software (MIXS:0000080)](https://thomasstjerne.github.io/gbwg/dwc-mixs/dwc/vocabulary/mag_cov_software.xml)
- [pred_genome_struc (MIXS:0000083)](https://thomasstjerne.github.io/gbwg/dwc-mixs/dwc/vocabulary/pred_genome_struc.xml)
- [pred_genome_type (MIXS:0000082)](https://thomasstjerne.github.io/gbwg/dwc-mixs/dwc/vocabulary/pred_genome_type.xml)
- [rel_to_oxygen (MIXS:0000015)](https://thomasstjerne.github.io/gbwg/dwc-mixs/dwc/vocabulary/rel_to_oxygen.xml)
- [seq_meth (MIXS:0000050)](https://thomasstjerne.github.io/gbwg/dwc-mixs/dwc/vocabulary/seq_meth.xml)
- [single_cell_lysis_appr (MIXS:0000076)](https://thomasstjerne.github.io/gbwg/dwc-mixs/dwc/vocabulary/single_cell_lysis_appr.xml)
- [sort_tech (MIXS:0000075)](https://thomasstjerne.github.io/gbwg/dwc-mixs/dwc/vocabulary/sort_tech.xml)
- [source_uvig (MIXS:0000035)](https://thomasstjerne.github.io/gbwg/dwc-mixs/dwc/vocabulary/source_uvig.xml)
- [tax_ident (MIXS:0000053)](https://thomasstjerne.github.io/gbwg/dwc-mixs/dwc/vocabulary/tax_ident.xml)
- [trophic_level (MIXS:0000032)](https://thomasstjerne.github.io/gbwg/dwc-mixs/dwc/vocabulary/trophic_level.xml)
- [virus_enrich_appr (MIXS:0000036)](https://thomasstjerne.github.io/gbwg/dwc-mixs/dwc/vocabulary/virus_enrich_appr.xml)
- [wga_amp_appr (MIXS:0000055)](https://thomasstjerne.github.io/gbwg/dwc-mixs/dwc/vocabulary/wga_amp_appr.xml)