#data/mixs_v5.xlsx:
# Retirve
.PHONY: clean

clean:
	@rm -f data/mixs_v5.xlsx
	@rm -f data/mixs_v6.xlsx

data/mixs_v5.xlsx:
# Download the MIxS 5 spreadsheet for the mixs-legacy github site
	curl -L -s \
	https://github.com/GenomicsStandardsConsortium/mixs-legacy/blob/master/mixs5/mixs_v5.xlsx?raw=true \
	> file.tmp && mv file.tmp $@

data/mixs_v6.xlsx:
	curl -L -s \
	https://docs.google.com/spreadsheets/d/1QDeeUcDqXes69Y2RjU2aWgOpCVWo5OVsBX9MKmMqi_o/export?format=xlsx \
	> file.tmp && mv file.tmp $@
