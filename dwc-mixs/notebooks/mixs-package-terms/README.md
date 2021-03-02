# MIxS Package Terms

These notebooks produce spreadsheets that contain the  MIxS package specific terms, but exclude the MIxS core terms.

## Makefile
The `Makefile` is used to download the source MIxS spreadsheets. Command summary:

- `make clean`: deletes spreadsheets from the `data` directory.
- `make data/mixs_v5.xlsx`: downloads the MIxS 5 spreadsheet from the MIxS Github repository into the `data` directory.
- `make data/mixs_v6.xlsx`: downloads the MIxS 6 Google spreadsheet into the `data` directory.