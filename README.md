# Binary black hole mass distribution: compactness peaks

This repository contains results and supplementary materials for the work presented in [arXiv:XXXX.XXXXX](https://arxiv.org/abs/XXXX.XXXXX) **_Compactness peaks: An astrophysical interpretation of the mass distribution of merging binary black holes_**

## Abstract:
With the growing number of detections of binary black hole mergers, we are beginning to probe structure in the population distribution of masses. A recent study by Schneider et al. proposes that isolated binary evolution of stripped stars naturally gives rise to the peaks at $\mathcal{M} \sim 8 M_\odot$, $14 M_\odot$ in the chirp mass distribution and explains the dearth of black holes between $\mathcal{M}\approx 10-12 M_\odot$. The gap in chirp mass results from an apparent gap in the component mass distribution between $m_1, m_2 \approx 10-15 M_\odot$ and specific pairing of these black holes. This component mass gap results from the variation in core compactness of the progenitor, where a drop in compactness of Carbon-Oxygen core mass will no longer form black holes from core collapse. We develop a population model motivated by this scenario to probe the structure of the component mass distribution of binary black holes consisting of two populations: 1) two peak components to represent black holes formed in the \textit{compactness peaks}, and 2) a powerlaw component to account for any _polluting events_, these are binaries that may have formed from different channels (e.g. dynamical). We perform hierarchical Bayesian inference to analyse the events from the third gravitational-wave transient catalogue (GWTC-3) with this model. We find that there is a preference for the lower mass peak to drop off sharply at $\sim 11 M_\odot$ and the upper mass peak to turn on at $\sim 13 M_\odot$, in line with predictions from Schneider et al. We also find mild support for the two populations to have different spin distributions. In addition to these population results, we highlight observed events of interest that differ from the expected population distribution of compact objects formed from stripped stars.

## Repository contents
* [posterior samples](./posterior_samples) - the samples from the event posteriors read in for the population analysis
* [hyperposterior samples](./hyperposterior_samples) - samples for the population analysis using the _Extended_ spin model
* [figures](./figures) - contains the figures from the publication and additional plots

If you have any questions about the data and/or results please contact me via email at sgalaudage@gmail.com

## Science summary

Two subpopulations for spin disribution of merging binary black holes.
1. There is support for the lower mass peak to drop off sharply at $\sim 11 M_\odot$ and the upper mass peak to turn on at $\sim 13 M_\odot$, in line with predictions from Schneider et al.
2. The peaked components in primary mass distribution have mass ratio distributions that prefer $q\sim1$
3. There is some suppport for the powerlaw and peaked components to have diferent spin distributions. The peaked components have spin distribution consistent with isolated evolution. The powerlaw component has more support for more rapidly spinning, misaligned spins than the peaked component, possibly from dynmically formed populations.

The _Compactness Peaks_ model is significantly favoured (by a $\log_{10}$ Bayes factor of ~4.63) compared to the _Multi Peak_ model. However, there is no _clear_ evidence for gap in component masses between $10-15 M_\odot$

## Other key publications relevant to this study

[Schneider et al. 2023](https://arxiv.org/abs/2305.02380): Bimodal black-hole mass distribution and chirp masses of binary black-hole mergers
[Adamcewicz et al. 2024](https://arxiv.org/abs/2406.11111): No evidence for a dip in the binary black hole mass spectrum

