# Measuring Manuscripts Project 2026

## Overview

This project explores the textual transmission of the *Novellino*'s Prologue through the comparison of five manuscript and printed witnesses. It was developed as part of the **Measuring Manuscripts 2026** project and combines traditional philological methods with digital collation and clustering techniques to investigate textual relationships.

The project is published as a static website through GitHub Pages:

https://christopherbenedetti.github.io/measuringmanuscriptproject2026/

---

## Research Question

The *Novellino* is one of the earliest collections of novellas in Italian literature. Its textual tradition is particularly complex because the prologue survives only in a limited number of witnesses and exhibits significant textual variation.

The aim of this project is to determine the degree of textual affinity among the surviving witnesses by identifying shared variants and reconstructing their relationships through computational methods.

---

## Corpus

The analysis considers five witnesses:

| Siglum | Witness |
|--------|----------|
| **V** | Vatican City, Biblioteca Apostolica Vaticana, MS Vaticano latino 3214 |
| **P** | Florence, Biblioteca Nazionale Centrale, MS Panciatichiano 32 |
| **Gz** | *Editio princeps* (1525), edited by Carlo Gualteruzzi |
| **Gz2** | Reprint of the *editio princeps* |
| **Bn** | Fourth printed edition (1572), edited by Vincenzio Borghini |

---

## Methodology

The workflow consisted of four main stages.

1. Diplomatic transcriptions of the five witnesses were prepared.

2. The witnesses were collated using **CollateX**.

3. The texts were orthographically normalized in order to eliminate purely graphic variation. The *apparatus* function was then used to identify and classify both scribal errors and redactional variants.

4. Finally, the shared variants were subjected to clustering analysis in order to generate a dendrogram representing the textual relationships among the witnesses.

---

## Results

The principal output of the project is a dendrogram that visualizes the affinities among the witnesses on the basis of their shared textual variants.

The interactive website also includes:

- a brief description of the project;
- the resulting dendrogram;
- a synoptic table of selected textual variants;
- downloadable datasets.

---

## Repository Structure

```
.
├── index.html                Website
├── style.css                 CSS stylesheet
├── stemma_prologue.png       Dendrogram
├── novellino_prologo_parma.jpg
├── tabella_varianti.csv      Variant table
├── data.csv                  Sample data
├── LICENSE
└── README.md
```

---

## Technologies

- HTML5
- CSS3
- GitHub Pages
- CollateX
- Computational clustering techniques

---

## License

Unless otherwise specified, the contents of this repository are distributed under the Creative Commons Attribution 4.0 International (CC BY 4.0) License.

See the `LICENSE` file for details.

---

## Author

Christopher Benedetti

Measuring Manuscripts Project 2026

---

## Citation

If you use this project or its data, please cite:

> Benedetti, Christopher. *The Novellino's Prologue: Between Manuscripts and Printed Editions*. Measuring Manuscripts Project 2026.
