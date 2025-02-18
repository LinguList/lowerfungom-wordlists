# CLDF dataset derived from Tschonghongei's Wordlists Collected for the KPAAM-CAM Project from 2021

## How to cite

If you use these data please cite
- the original source
  > Tschonghongei, Nelson C. Wordlist collected for the KPAAM-CAM project. 2021.
- the derived dataset using the DOI of the [particular released version](../../releases/) you were using

## Description


## Notes

## Export data to EDICTOR

```
$ pip install pyedictor
$ edictor wordlist --name edictor/kpaamcam-edictor --preprocessing=raw/preprocess.py
```

This creates the file `edictor/kpaamcam-edictor.tsv`, which can be browed with https://lingulist.de/edictor/ and alignments can be investigated. From EDICTOR, nexus files can be exported to load data into SplitsTree.



## Statistics


![Glottolog: 100%](https://img.shields.io/badge/Glottolog-100%25-brightgreen.svg "Glottolog: 100%")
![Concepticon: 0%](https://img.shields.io/badge/Concepticon-0%25-red.svg "Concepticon: 0%")
![Source: 0%](https://img.shields.io/badge/Source-0%25-red.svg "Source: 0%")
![BIPA: 100%](https://img.shields.io/badge/BIPA-100%25-brightgreen.svg "BIPA: 100%")
![CLTS SoundClass: 100%](https://img.shields.io/badge/CLTS%20SoundClass-100%25-brightgreen.svg "CLTS SoundClass: 100%")

- **Varieties:** 49
- **Concepts:** 140
- **Lexemes:** 5,924
- **Sources:** 0
- **Synonymy:** 1.00
- **Invalid lexemes:** 0
- **Tokens:** 26,763
- **Segments:** 282 (0 BIPA errors, 0 CTLS sound class errors, 279 CLTS modified)
- **Inventory size (avg):** 83.02

## Possible Improvements:



- Entries missing sources: 5924/5924 (100.00%)

# Contributors

Name | GitHub user | Description | Role
--- | --- | --- | ---
Jeff Good | @jcgood | maintainer | Other
Nelson C. Tschonghongei | | data collector | Author



## CLDF Datasets

The following CLDF datasets are available in [cldf](cldf):

- CLDF [Wordlist](https://github.com/cldf/cldf/tree/master/modules/Wordlist) at [cldf/cldf-metadata.json](cldf/cldf-metadata.json)