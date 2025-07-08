# Facades Material Munich (FaMatMuc) - Semantic Segmentation and Classification dataset

[![DOI](https://img.shields.io/badge/DOI-10.14459%2F2025mp1784789-blue)](https://doi.org/10.14459/2025mp1784789)
[![Paper](https://img.shields.io/badge/Paper-DOI%3A10.17868%2Fstrath.00093240-green)](https://doi.org/10.17868/strath.00093240)

**Date:** July-2025  
**Authors:** Noll, Leonhard; Noichl, Florian; Borrmann, André  
**Corresponding author:** Florian Noichl; florian.noichl@tum.de  
**Institution:** Technical University of Munich  

**Download Link:** https://doi.org/10.14459/2025mp1784789

This dataset was developed and published in conjunction with the paper "Decoding Building Facades: Automated Element and Material Recognition in Street-Level Images for Large-Scale Building Stock Assessments" (https://doi.org/10.17868/strath.00093240), presented at the International Workshop on Intelligent Computing in Engineering in Glasgow, 2025.

To support the proposed approaches, a dedicated material dataset with intra-urban facades in the city of Munich was created with two types of annotations, semantic segmentation masks and classification labels. The semantic segmentation dataset comprises 100 annotated high-resolution images (5304 x 7952 pixels); the classification dataset includes 541 close-up patches (256 x 256 pixels) extracted from these 100 images. This dataset primarily features single residential and office buildings taken from a frontal perspective.

## Method of Data Assessment

The photos were taken using a Sony a7r III camera equipped with a Sony FE 16-35mm F/2.8 GM lens, enabling the capture of entire facades even from relatively short distances. The images were used as-is for semantic segmentation labeling without prior undistortion. The annotation process itself was carried out manually using X-AnyLabeling (Wei Wang, 2023, URL: https://github.com/CVHub520/X-AnyLabeling), with the annotations saved in the LabelMe format (B. C. Russell et al., 2008, DOI: 10.1007/s11263-007-0090-8).

Annotated classes are Plaster, Brick, Stone, Concrete, Glass, Timber, and Other.

**Data Types for Annotation:** .JSON (Semantic Segmentation), .csv (Classification)

**Note on Semantic Segmentation Annotation:** Additionally to the .JSON files png-masks are provided.

Please, see the accompanying technical report for details. If you make use of the dataset, we would ask you to cite the following references (dataset and / or scientific paper) in resulting publications:

## Citation

### Dataset

```bibtex
@dataset{noll_noichl_2025_famatmuc,
  author            = {L. Noll and F. Noichl and A. Borrmann},
  title             = {Facades Material Munich (FaMatMuc): Semantic Segmentation and Classification Dataset},
  year              = {2025},
  publisher         = {Technical University of Munich},
  doi               = {10.14459/2025mp1784789},
  note              = {Corresponding author: Florian Noichl (\texttt{florian.noichl@tum.de})},
  relatedPublication = {Noll, Noichl, Kiper, and Borrmann, "Decoding Building Facades: Automated Element and Material Recognition in Street‑Level Images for Large‑Scale Building Stock Assessments", International Workshop on Intelligent Computing in Engineering, Glasgow, 2025, DOI:10.17868/strath.00093240}
}
```

### Paper

```bibtex
@inproceedings{noll_noichl_2025_egice,
author = {L. Noll and F. Noichl and B. Kiper and A. Borrmann},
title = {Decoding Building Facades: Automated Element and Material Recognition in Street‐Level Images for Large‐Scale Building Stock Assessments},
booktitle = {EG‑ICE 2025: AI‑Driven Collaboration for Sustainable and Resilient Built Environments},
editor = {Alejandro Moreno‑Rangel and Bimal Kumar},
year = {2025},
doi = {10.17868/strath.00093240},
publisher = {University of Strathclyde Publishing},
isbn = {9781914241826},
}
```

## Acknowledgements
This research has been partially funded by the GeoAI4Retrofit project supported by the Federal Ministry for Economic Affairs and Climate Action Germany.
