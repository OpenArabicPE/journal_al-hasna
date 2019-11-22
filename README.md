# journal_al-hasna

This repository holds a scaffolding edition of the journal *al-Ḥasna*, published by ... in Beirut between 19.. and 19.. It is based on digital imagery from the British Library's Endangered Archives Programme (EAP). Each issues is represented by a TEI XML file with links to the image files in the `<facsimile>` node. Structural mark-up of articles, including heads and bylines, is manually added using OpenArabicPE's TEI Boilerplate.

## to do

- add links to online facsimiles at EAP
-

## Experimental HTR with Transkribus

- Imagery is downloaded, processed for clarity (bw TIFF) using ScanTailor, and uploaded to [Transkribus]().
- Sinai Rusinek trained a HTR model on OpenArabicPE's edition of *al-Muqtabas* 1(1) using Transkribus's Image2Text linking tool
- This model will be further improved with further validated transcriptions from OpenArabicPE's corpus
- The model is used for applying HTR to the images of *al-Ḥasna*
- Transkribus's TEI output is transformed to OpenArabicPE's schema.
