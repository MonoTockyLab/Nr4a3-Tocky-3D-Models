# Nr4a3-Tocky-3D-Models

**Author:** Dr Masahiro Ono  
**Date:** 15 March 2026

---

Interactive three-dimensional visualisations of the **Nr4a3-Tocky developmental-temporal framework** generated from `mCanonicalTockySeq`.

This repository hosts browser-viewable HTML models showing thymocytes in **CD4 differentiation score × CD8 differentiation score × Tocky Time** space. The models were generated from the Nr4a3-Tocky thymocyte analysis and are intended to provide an intuitive view of the shared developmental-temporal geometry reconstructed by `mCanonicalTockySeq`.

## mCanonicalTockySeq

The three-dimensional models were generated using our R package `mCanonicalTockySeq`.


<a href="https://monotockylab.github.io/mCanonicalTockySeq/index.html">
<img src="assets/mCanonicalTockySeqLogo.jpg" align="center" width="100%">
</a>


**mCanonicalTockySeq** is available at GitHub: [mCanonicalTockySeq](https://github.com/MonoTockyLab/mCanonicalTockySeq).

### Package Documentation

[![Documentation](https://img.shields.io/badge/docs-GitHub_Pages-blue.svg)](https://monotockylab.github.io/mCanonicalTockySeq/index.html)

The **mCanonicalTockySeq** package documentation is available online: [https://monotockylab.github.io/mCanonicalTockySeq/index.html](https://monotockylab.github.io/mCanonicalTockySeq/index.html)

## Live site

The interactive models can be viewed at:

**GitHub Pages:**  
[https://MonoTockyLab.github.io/Nr4a3-Tocky-3D-Models/](https://MonoTockyLab.github.io/Nr4a3-Tocky-3D-Models/)

## Repository contents

- `index.html`  
  Landing page embedding the interactive 3D models

- `plotTockyFate3D.html`  
  3D developmental-temporal model coloured by **Tocky Time**

- `plotTockyFate3D_Lineages.html`  
  3D developmental-temporal model coloured by **gene-associated tube identities**

## What the models show

These models display thymocytes in a three-dimensional space defined by:

- **CD4 differentiation score**
- **CD8 differentiation score**
- **Tocky Time**

This geometry was reconstructed from the Nr4a3-Tocky single-cell transcriptomic analysis using `mCanonicalTockySeq`, `mGradientTockySeq`, `mGetFateScores`, and trajectory-tube analysis.

### Tocky Time model
The base model shows the continuous Tocky temporal coordinate across the inferred developmental-temporal manifold.

### Gene-associated tube identity model
The lineage-coloured model shows overlapping **gene-associated developmental corridors** inferred from trajectory-tube analysis, allowing non-mutually exclusive developmental identities to be visualised directly.

## How to use

Open the GitHub Pages site or the HTML files locally in a web browser.

Interactive controls:
- **Click and drag** to rotate
- **Scroll** to zoom
- **Hover** to inspect values
- **Open fullscreen** for easier exploration

## Biological context

The Nr4a3-Tocky system uses a Fluorescent Timer reporter to provide an experimentally anchored readout of strong T-cell receptor signalling history. In the thymus, this allows temporal progression associated with TCR signalling to be analysed jointly with developmental progression toward CD4 and CD8 single-positive states.

These interactive 3D models are intended as visual summaries of that shared developmental-temporal structure.

## Citation

If you use or refer to these models, please cite the mCanonicalTockySeq package and paper.


### bioRxiv preprint

For a detailed description of the biological applications and the underlying methodology of **mCanonicalTockySeq**, please refer to our preprint:


> **Canonical Analysis of Fluorescent Timer-Anchored Transcriptomes Resolves Joint Temporal and Developmental Progression**. 
> Nobuko Irie, Omnia Reda, Yorifumi Satou, Masahiro Ono.
> *bioRxiv* (2026). DOI: 




```bibtex
@article{Ono2026mCanonicalTocky,
  author = {Ono, Masahiro and others},
  title = {Canonical Analysis of Fluorescent Timer-Anchored Transcriptomes Resolves Joint Temporal and Developmental Progression},
  elocation-id = {},
  year = {2026},
  doi = {},
  publisher = {Cold Spring Harbor Laboratory},
  journal = {bioRxiv},
  url = {https://www.biorxiv.org}
}
```

### R package


```bibtex
@Manual{OnomCanonicalTockySeq,
  title = {mCanonicalTockySeq: Multidimensional Canonical Tocky Analysis of Temporal and Developmental Structure in Single-Cell Transcriptomes},
  author = {Masahiro Ono},
  year = {2026},
  note = {R package version 0.1.0},
  url = {https://github.com/MonoTockyLab/mCanonicalTockySeq},
  doi = {}
}
```

<a href="https://monotockylab.github.io/mCanonicalTockySeq/index.html">
<img src="assets/mCanonicalTockySeqTransparent.jpg" align="center" width="100%">
</a>



## Contact and More

**Email**:
<a href="mailto:m.ono@imperial.ac.uk">
<img src="https://upload.wikimedia.org/wikipedia/commons/e/ec/Circle-icons-mail.svg" alt="Email" width="10%">
</a>

**Personal Homepage**:
<a href="http://monotockylab.github.io">
<img src="assets/MonoLab.jpg" alt="MonoTockyLab Homepage" align="center" width="30%"/>
</a>

**GitHub**:
<a href="https://github.com/MonoTockyLab">
<img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" alt="GitHub" align="center" width="70" height="70"/>
</a>

**Twitter**:
<a href="https://twitter.com/MonoTockyLab">
<img src="https://upload.wikimedia.org/wikipedia/commons/6/6f/Logo_of_Twitter.svg" alt="Twitter" align="center" width="50" height="50"/>
</a>

**Professional Homepage**: [Imperial College London - Masahiro Ono](https://www.imperial.ac.uk/people/m.ono)

<a href="https://monotockylab.github.io/mCanonicalTockySeq/index.html">
<img src="assets/TockyToki.jpg" align="center" width="30%">
</a>


