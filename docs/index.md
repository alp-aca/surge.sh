# :fontawesome-solid-paw:{ .icons } Welcome to ALP-aca

[![Version](https://img.shields.io/badge/version-1.1.0-teal?logo=GitHub)](https://github.com/alp-aca/alp-aca/tree/v1.1.0)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.16447036.svg)](https://doi.org/10.5281/zenodo.16447036) [![arxiv](https://img.shields.io/badge/arXiv-2508.08354_[hep--ph]-B31B1B.svg?style=flat&logo=arxiv&logoColor=B31B1B)](https://arxiv.org/abs/2508.08354)

Welcome to the ALP Automated Computed Algorithm (ALP-aca)!

![ALPaca logo](https://raw.githubusercontent.com/alp-aca/alp-aca/main/docs/_static/logo.png)

ALP-aca is an open-source Python library for the phenomenology of Axion-Like Particles (ALPs) with masses in the ranges of $m_a \sim 0.01 - 10\,\mathrm{GeV}$, mainly in processes involving mesons.

ALP-aca integrates the full analysis with an easy-to-use syntax:

* Matching of selected UV-complete models (DFSZ-like, KSVZ-like, flaxions, etc.) to the ALP-EFT.
* Numerical running and matching of the ALP-EFT coefficients down to the physical relevant scales, including ALP-$\chi\!$ PT.
* Calulation of decay rates for processes involving ALPs:
  * ALP production in rare meson decays $M_1\to M_2 a$, quarkonia decays $V\to \gamma a$ and non-resonant production $e^+e^- \to \gamma a$,
  * ALP decays into photons, leptons and mesons,
  * Processes mediated by on-shell ALPs in the Narrow Width Approximation,
  * Leptonic and radiative meson decays, and meson mixing, with off-shell ALPs.
* Calculation of ALP decay lengths and probability of decaying outside the detector, with a displaced vertex or in the prompt region.
* $\chi^2$ statistical analysis, with fine-grained control of the observables and experimental measurements included.
* Generation of publication-grade exclusion plots.
* Automatic management of the bibliographical references used in the analysis.

## :fontawesome-solid-people-group:{ .icons } The ALP-aca team

* [**Jorge Alda**](blog/author/Jorge): Università degli Studi di Padova & INFN Sezione di Padova & CAPA Zaragoza.
* [**Marta Fuentes Zamoro**](blog/author/Marta): Universidad Autónoma de Madrid & IFT Madrid.
* [**Luca Merlo**](blog/author/Luca): Universidad Autónoma de Madrid & IFT Madrid.
* [**Xavier Ponce Díaz**](blog/author/Xavi): University of Basel.
* [**Stefano Rigolin**](blog/author/Stefano): Università degli Studi di Padova & INFN Sezione di Padova.

## :fontawesome-solid-crosshairs:{ .icons } ALP-aca in action

In [this repositoy](https://github.com/alp-aca/examples) you can find examples, tutorials and applications of ALP-aca.

ALP-aca has been used in the following publications:

* J. Alda, M. Fuentes Zamoro, L. Merlo, X. Ponce Díaz, S. Rigolin: *Comprehensive ALP searches in Meson Decays*. [arXiv:2507.19578](https://arxiv.org/abs/2507.19578)

* M. Fuentes Zamoro, J. Alda, L. Merlo, X. Ponce Diaz, S. Rigolin: *Tackling ALP searches in meson decays with ALPaca: a phenomenological approach*. [PoS(COSMICWISPers2025) (2026) 057](https://pos.sissa.it/507/057)

* J. Alda: *Lecture notes on Machine Learning applications for global fits*. [arXiv:2604.07520](https://arxiv.org/abs/2604.07520)

If you have used ALP-aca in your publication and want to be featured in this list, please [contact us](https://github.com/alp-aca/alp-aca/issues/new?template=publication-using-alpaca.md).

## :fontawesome-solid-comments:{ .icons } Feedback

If you encounter bugs or want to propose a new feature, you can contact us using [Gihub issues](https://github.com/alp-aca/alp-aca/issues/new/choose).