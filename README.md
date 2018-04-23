# Masters of Time
An Overview of the NTP Ecosystem

This repository holds the data used for the EuroS&P 2018 paper [Masters of Time: An Overview of the NTP Ecosystem](https://www.syssec.rub.de/research/publications/NTP-Study/).

## Evaluation Data

The data used for our NTP study is available at [zenodo.org](https://zenodo.org/record/1227126).

## BibTex:
```
@inproceedings{rytilahti2018ntp,
    author = {Rytilahti, Teemu and Tatang, Dennis and Köpper, Janosch and Holz, Thorsten},
    title = {{Masters of Time: An Overview of the NTP Ecosystem}},
    year = {2018},
    booktitle = {IEEE EuroS&P} 
}
```

## Organization

- crawler_pcaps: incoming dns & ntp traffic from our crawling server
- graph_export: contains our graph database in xml & gson format
- client_mode: mongodb database dump from v4-wide normal mode scans
- client_pcaps: samples of anonymized client data (tbd)

## Contact

Visit our [website](https://www.syssec.rub.de).