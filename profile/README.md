[![Paper: CHR 2024](https://img.shields.io/badge/Paper-CHR%202024-blue)](https://ceur-ws.org/Vol-3834/paper104.pdf)
[![Paper: LREC 2026](https://img.shields.io/badge/Paper-LREC%202026-blue)](https://doi.org/10.63317/32HUZUUOKPFR)
[![Dataset: Zenodo](https://img.shields.io/badge/Dataset-Zenodo-blue)](https://doi.org/10.5281/zenodo.16992629)

# ProMeTEXT

**ProMeTEXT** — the **Centre for PROcessing MEdieval TEXTs** — develops corpora, methods, and tools for the segmentation and multilingual alignment of medieval texts.

Our work focuses primarily on medieval romance texts from the **13th to 16th centuries**, with the aim of supporting research in textual transmission, multilingual corpora, computational humanities, and historical language processing.

## Scope

ProMeTEXT provides resources for working with medieval texts in multiple languages, including:

- phrase-level segmentation data
- multilingual alignment tools
- evaluation datasets
- notebooks and reproducible workflows
- resources for medieval textual transmission studies

## Supported Languages

Current resources cover the following medieval languages:

- Latin
- French
- Castilian
- Portuguese
- Catalan
- English
- Italian

We welcome collaboration on additional languages. Please feel free to contact us if you would like to contribute data, methods, or language-specific expertise.

## Data

### Gold-Standard Segmentation Data

We provide a gold-standard dataset for phrase-level segmentation of medieval corpora.

- [Repository](https://github.com/ProMeText/multilingual-segmentation-dataset)
- [Zenodo record](https://zenodo.org/records/16992629)

#### Dataset Citation

Please cite the dataset itself as follows when using the released data:

**APA**  
Ing, L., Gille Levenson, M., & Macedo, C. (2025). *Multilingual Segmentation Dataset for Historical Prose (13th–16th c.)* (Version 1.0) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.16992629

**BibTeX**

```bibtex
@dataset{ing2025multilingual,
  author       = {Ing, L. and Gille Levenson, M. and Macedo, C.},
  title        = {Multilingual Segmentation Dataset for Historical Prose (13th--16th c.)},
  year         = {2025},
  publisher    = {Zenodo},
  version      = {1.0},
  doi          = {10.5281/zenodo.16992629},
  url          = {https://doi.org/10.5281/zenodo.16992629},
  license      = {Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International}
}
```
#### Related Publication

For the method, experiments, and scientific context, please cite the related publication:

**APA**  
Ing, L., Gille Levenson, M., & Macedo, C. (2026). Phrase-Level Segmentation on Medieval Corpora for Aligning Multilingual Texts. In *Proceedings of the Fifteenth Language Resources and Evaluation Conference (LREC 2026)* (pp. 936–946). European Language Resources Association (ELRA). https://doi.org/10.63317/32huzuuokpfr

**BibTeX**

```bibtex
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
  doi = {10.63317/32huzuuokpfr}
}

```

### Gold-Standard Alignment Data

We provide gold-standard alignment data for parallel medieval and historical texts through the following repository:

- [parallelium-scriptures-alignment-dataset](https://github.com/ProMeText/parallelium-scriptures-alignment-dataset)

Other parallel corpora and alignment datasets are currently under construction.

## Tools

### Aquilign

[**Aquilign**](https://github.com/ProMeText/Aquilign) is a tool for aligning multilingual texts at phrase level. It was designed for medieval textual traditions and supports multilingual alignment workflows across related witnesses and translations.

Please cite **Aquilign** as follows:

**APA**  
Gille Levenson, M., Ing, L., & Camps, J.-B. (2024). Textual Transmission without Borders: Multiple Multilingual Alignment and Stemmatology of the “Lancelot en prose” (Medieval French, Castilian, Italian). In *Proceedings of the Computational Humanities Research Conference 2024*, CEUR Workshop Proceedings, 3834, 65–92. https://ceur-ws.org/Vol-3834/paper104.pdf

**BibTeX**

```bibtex
@inproceedings{gillelevensonTextualTransmissionBorders2024,
  title = {Textual Transmission without Borders: Multiple Multilingual Alignment and Stemmatology of the ``Lancelot en prose'' (Medieval French, Castilian, Italian)},
  shorttitle = {Textual Transmission without Borders},
  booktitle = {Proceedings of the Computational Humanities Research Conference 2024},
  author = {Gille Levenson, Matthias and Ing, Lucence and Camps, Jean-Baptiste},
  editor = {Haverals, Wouter and Koolen, Marijn and Thompson, Laure},
  year = {2024},
  series = {CEUR Workshop Proceedings},
  volume = {3834},
  pages = {65--92},
  publisher = {CEUR},
  address = {Aarhus},
  issn = {1613-0073},
  url = {https://ceur-ws.org/Vol-3834/paper104.pdf},
  langid = {english}
}
```

## Apps

### Aquilign Explorer

A demo app for Aquilign Explorer is available on Hugging Face Spaces:

[**Aquilign Explorer**](https://huggingface.co/spaces/ProMeText/aquilign-explorer)

It provides an early interface for testing and demonstrating multilingual medieval text alignment workflows.


## Notebooks

Example notebooks and reproducible workflows are available here:

[multilingual-medieval-aligner-notebooks](https://github.com/ProMeText/multilingual-medieval-aligner-notebooks)

These notebooks can be used to test **ProMeTEXT** tools on sample data or on your own medieval textual corpora.

## Citation

Please cite the relevant dataset, tool, or paper depending on the resource you use:

- For the released segmentation dataset, cite Ing, Gille Levenson, and Macedo 2025.
- For the phrase-level segmentation method and experiments, cite Ing, Gille Levenson, and Macedo 2026.
- For Aquilign and multilingual alignment workflows, cite Gille Levenson, Ing, and Camps 2024.

## Contact and Contributions

We welcome collaboration with researchers, developers, and institutions working on medieval texts, historical languages, digital philology, computational humanities, and multilingual corpora.

You can contribute by:

- suggesting or adding support for additional medieval languages
- contributing annotated corpora
- improving segmentation or alignment workflows
- testing the tools on new textual traditions
- reporting issues in the relevant repositories

For questions, feedback, or collaboration proposals, please open an issue in the relevant repository or contact the ProMeTEXT team.
