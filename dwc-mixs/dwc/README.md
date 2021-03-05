# A Darwin Core extension for DNA derived data

The draft extension is [here](/gbwg/blob/main/dwc-mixs/dwc/extension/dna_derived_data.xml) ([human readable version here](https://thomasstjerne.github.io/gbwg/dwc-mixs/dwc/extension/dna_derived_data.xml)).

The initial draft was prepared as part of the "Publishing DNA-derived data through biodiversity data platforms" (https://doi.org/10.35035/doc-vf1a-nr22) 

## Terms included in the extension

### Source: MIxS

The extension based primarily on MIxS and includes all terms from MIxS v6 core, with the exception the following considered redundant to terms in DwC:Occurrence and DwC:Event

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