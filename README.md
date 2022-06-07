---
title: "Readme: Journal *al-Ḥasnāʾ*"
author: Till Grallert
date: 2020-07-25
ORCID: orcid.org/0000-0002-5739-8094
---

# An open, collaborative, and scholarly digital edition of Jirjī Niqūlā Bāz's monthly journal *al-Ḥasnāʾ* (Beirut, 1909--11)

[![GitHub release](https://img.shields.io/github/release/openarabicpe/journal_al-hasna.svg)](https://github.com/openarabicpe/journal_al-hasna/releases)
<!-- DOI needs updating once released -->
[![DOI](https://zenodo.org/badge/171870239.svg)](https://zenodo.org/badge/latestdoi/171870239)

This repository holds a scaffolding edition of the journal *al-Ḥasnāʾ*, published by Jirjī Niqūlā Bāz in Beirut between 1909 and 1911 It is based on digital imagery from the British Library's Endangered Archives Programme (EAP). Each issues is represented by a TEI XML file with links to the image files in the `<facsimile>` node. Structural mark-up of articles, including heads and bylines, is manually added based on the facsimiles. To enter a webview click [here](https://openarabicpe.github.io/journal_al-hasna/tei/oclc_792756327-v_1-i_1.TEIP5.xml).

This digital edition is part of and follows the principles of [Open Arabic Periodical Editions (OpenArabicPE)](https://openarabicpe.github.io) that were originally developped in the context of [Digital Muqtabas](https://github.com/openarabicpe/journal_al-muqtabas). Digital imagery is available from the British Library's *Endangered Archives Programme* (EAP).

## to do

- add links to online facsimiles at EAP using IIIF.
    - **done** volume 1

## Experimental HTR with Transkribus

- Imagery is downloaded, processed for clarity (bw TIFF) using ScanTailor, and uploaded to [Transkribus]().
- Sinai Rusinek trained a HTR model on OpenArabicPE's edition of *al-Muqtabas* 1(1) using Transkribus's Image2Text linking tool
- This model will be further improved with further validated transcriptions from OpenArabicPE's corpus
- The model is used for applying HTR to the images of *al-Ḥasna*
- Transkribus's TEI output is transformed to OpenArabicPE's schema.
