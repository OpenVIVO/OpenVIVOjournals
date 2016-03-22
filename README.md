# OpenVIVOjournals

This repository contains journals data from publicaly available sources: [CrossRef] (http://www.crossref.org/titleList/) and NLM. 

The two data sources were merged in [_SAS_] (http://www.sas.com/en_us/home.html) based on the ISSN (print) as unique identifier. 

Three resulting tab separated files were generated: 


1. journal titles that exists in both data sources: Crossref and NLM - cross_nlm_matched.tsv


2. journal titles that exists only in CrossRef - cross_unmatched.tsv
 

3. journal titles that exists only in NLM - nlm_unmatched.tsv

[Karma data integration tool] (http://usc-isi-i2.github.io/karma/) was used to map the data to the ontologies used in VIVO.

Resulting N-Triples files are in the folder: N-Triples.


