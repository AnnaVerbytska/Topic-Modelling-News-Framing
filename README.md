# Topic Modelling For News Framing Analysis

This repository contains the technical framework and metadata for **the VolkswagenStiftung research project D07310175 'Emotional Journalism in Media Discourse: The Case of Russia and Ukraine Full-Scale War in 2023'**. The investigation focuses on the linguistic construction and emotional journalism within media discourse, specifically analyzing how news organizations shape narratives through strategic framing during the 2022–2024 period.

## Dataset & Privacy

To respect the terms of service and copyright of the original publishers, **full-text content has been omitted** from this repository. This dataset provides the metadata required to replicate the study by 're-hydrating' the text from original sources.

The provided metadata.csv includes the following attributes for each entry:

**Title:** The headline of the article.

**Date_str:** Publication date.

**SiteName**: The source platforms - Euronews & Kyiv Post.

**Sentiment**: Automated sentiment score.

**Authors**: Credits for the original reporting.

**URL**: Direct link to the source material (use this to fetch full text).

## Setup

`pip install -r requirements.txt`

## Language
[![Python 3.11.5](https://img.shields.io/badge/python-3.11.5-blue.svg)](https://www.python.org/downloads/release/python-360/)

## Citation

If you use this code or the associated methodology, please cite the following publication:

Verbytska, A. (2024). Topic modelling as a method for framing analysis of news coverage of the Russia-Ukraine war in 2022–2023. Language & Communication, 99, 174-193. https://doi.org/10.1016/j.langcom.2024.10.004

#### BibTeX
```bibtex
@article{Verbytska2024,
  author = {Verbytska, Anna},
  title = {Topic modelling as a method for framing analysis of news coverage of the Russia-Ukraine war in 2022–2023},
  journal = {Language & Communication},
  volume = {99},
  pages = {174-193},
  year = {2024},
  doi = {10.1016/j.langcom.2024.10.004},
  publisher = {Elsevier}
}
