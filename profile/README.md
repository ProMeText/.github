# ProMedTEXT

Centre for PROcessing MEDieval TEXTs (ProMeText) — medieval corpora & alignment tools. 

We provide methods and data to align (mostly) medieval romance texts (13th-16th centuries). 

Supported languages:
- latin
- french
- castilian
- portuguese
- catalan
- english
- italian

Feel free to contact us if you want to add more languages ! 

## Data

### Gold standard segmentation data

We've created a golden standard dataset for phrase segmentation: see our [multilingual-segmentation-dataset](https://github.com/ProMeText/multilingual-segmentation-dataset). To cite this work: 

> Ing, L., Gille Levenson, M., & Macedo, C. (2026). Phrase-Level Segmentation on Medieval Corpora for Aligning Multilingual Texts. In Proceedings of the Fifteenth Language Resources and Evaluation Conference (LREC 2026) (pp. 936–946). European Language Resources Association (ELRA). https://doi.org/10.63317/32huzuuokpfr.

```
@inproceedings{ing-etal-2026-phrase,
  title = {Phrase-Level Segmentation on Medieval Corpora for Aligning Multilingual Texts},
  author = {Ing, Lucence and Gille Levenson, Matthias and Macedo, Carolina},
  booktitle = {Proceedings of the Fifteenth Language Resources and Evaluation Conference (LREC 2026)},
  month = {May},
  year = {2026},
  pages = {936--946},
  address = {Palma, Mallorca, Spain},
  publisher = {European Language Resources Association (ELRA)},
  editor = {Piperidis, Stelios and Bel, Núria and van den Heuvel, Henk and Ide, Nancy and Krek, Simon and Toral, Antonio},
  doi = {10.63317/32huzuuokpfr},
  abstract = {This paper presents an approach to multilingual alignment for medieval languages, focusing on the prior step of"phrase" segmentation. It outlines the challenges posed by historical data and describes different strategies forsegmenting texts in multiple languages. It releases a gold-standard segmentation corpus based on various literaryand historical works from the late Middle Ages in Europe. This corpus consists of texts in seven medieval languages (French, Castilian, Catalan, Portuguese, Latin, Italian, English). Several architectures are tested with both in-domain and out-of-domain evaluation sets.}
}
```

### Gold standard alignment data

Work In Progress...

## Tools

### Aquilign

Aquilign allows to align multilingual texts at the "sentence" level. The source code can be found here: [Aquilign](https://github.com/ProMeText/Aquilign). To cite this work: 

> Gille Levenson, Matthias, Lucence Ing, & Jean-Baptiste Camps, « Textual Transmission without Borders: Multiple Multilingual Alignment and Stemmatology of the ``Lancelot en prose’’ (Medieval French, Castilian, Italian) », Proceedings of the Computational Humanities   Research Conference 2024, 3834, 2024, p. 65‑92, Aarhus : CEUR (CEUR Workshop Proceedings), 2024, p. 65‑92, en ligne : [URL] [https://ceur-ws.org/Vol-3834/paper104.pdf].

```
@inproceedings{gillelevensonTextualTransmissionBorders2024,
  title = {Textual {{Transmission}} without {{Borders}}: {{Multiple Multilingual Alignment}} and {{Stemmatology}} of the ``{{Lancelot}} En Prose'' ({{Medieval French}}, {{Castilian}}, {{Italian}})},
  shorttitle = {Textual {{Transmission}} without {{Borders}}},
  booktitle = {Proceedings of the {{Computational Humanities}}   {{Research Conference}} 2024},
  author = {Gille Levenson, Matthias and Ing, Lucence and Camps, Jean-Baptiste},
  editor = {Haverals, Wouter and Koolen, Marijn and Thompson, Laure},
  year = 2024,
  series = {{{CEUR Workshop Proceedings}}},
  volume = {3834},
  pages = {65--92},
  publisher = {CEUR},
  address = {Aarhus},
  issn = {1613-0073},
  urldate = {2024-12-09},
  langid = {english},
  file = {/home/mgl/Bureau/Travail/Bibliotheque_zoteros/storage/CIH7IAHV/Levenson et al. - 2024 - Textual Transmission without Borders Multiple Multilingual Alignment and Stemmatology of the ``Lanc.pdf}
}
```


## Notebooks

The repo to test our code on test (or your) data is here: [multilingual-medieval-aligner-notebooks](https://github.com/ProMeText/multilingual-medieval-aligner-notebooks)
