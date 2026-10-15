# Information Theory for Biologists

A free, self-paced interactive course introducing the mathematical and physical principles of information theory across genomics, systems biology, protein evolution, cell signaling, neuroscience, and evolutionary thermodynamics.


## Curriculum Overview

| # | Module | Biological Applications & Examples | Verified Landmark Papers |
|---|--------|------------------------------------|--------------------------|
| 1 | Foundations: Surprise, Shannon Entropy & Biological Uncertainty | Compositional bias in extremophile/parasite genomes, immune repertoire diversity, Hill numbers (`2^H`) in microbial ecology | Shannon (1948), Jost (2006) |
| 2 | Genomic Motifs, Sequence Logos & Relative Entropy | Transcription factor Position Weight Matrices (PWMs), sequence logo stack heights (`R_seq`), binding free energy (`ΔΔG`) | Stormo et al. (1982), Berg & von Hippel (1987), Schneider & Stephens (1990) |
| 3 | Mutual Information & Gene Regulatory Network Inference | Non-monotonic gene regulation, pruning indirect cascades with the Data Processing Inequality (ARACNE), single-cell synergy (PIDC) | Basso et al. (2005), Margolin et al. (2006), Chan, Stumpf & Babtie (2017) |
| 4 | Protein Coevolution, Maximum Entropy & Direct Coupling Analysis | Separating direct 3D contacts from transitive correlations via Potts models and covariance matrix inversion (mfDCA) | Schneidman et al. (2006), Weigt et al. (2009), Morcos et al. (2011) |
| 5 | Biochemical Signaling Networks as Noisy Channels | Blahut-Arimoto channel capacity in TNF-α / NF-κB signaling, morphogen positional information in *Drosophila* gap genes | Tkačik, Callan & Bialek (2008), Cheong et al. (2011), Dubuis et al. (2013) |
| 6 | Neural Coding, Spike Train Entropy & Efficient Representations | Laughlin's histogram equalization in insect vision, bits/spike in PSTHs, the Information Bottleneck | Barlow (1961), Laughlin (1981), Bialek et al. (1991), Strong et al. (1998), Tishby, Pereira & Bialek (1999) |
| 7 | Evolutionary Information, Maxwell's Demon & Thermodynamics of Life | Adami genomic physical complexity `I(G; E)`, Landauer's bound (`k_B T ln 2`) vs. ribosomal kinetic proofreading | Landauer (1961), Hopfield (1974), Adami, Ofria & Collier (2000), England (2013) |
| 8 | Temporal Causality, Transfer Entropy & Single-Cell Information Landscapes | Directed Transfer Entropy in time-series, Jensen-Shannon Divergence in scRNA-seq, stem cell differentiation potency | Schreiber (2000), Barnett, Barrett & Seth (2009), Teschendorff & Enver (2017) |


## Contributing

Pull requests adding new worked biological problems, open-access tutorials, or additional Python/R exercises are welcome.

## Acknowledgments

- Foundational Information Theory & Statistical Physics:
  - Claude E. Shannon (Bell Labs) for *A Mathematical Theory of Communication* (1948).
  - Edwin T. Jaynes for the Principle of Maximum Entropy (1957).
  - Rolf Landauer (IBM) and Charles H. Bennett for the thermodynamics of information processing (1961, 1982).
- Quantitative & Systems Biology Pioneers:
  - Thomas D. Schneider, R. Michael Stephens, Gary D. Stormo, Otto G. Berg, and Peter H. von Hippel for sequence logos, PWMs, and statistical mechanics of DNA-protein binding.
  - William Bialek, Gašper Tkačik, Curtis G. Callan Jr., Thomas Gregor, Eric F. Wieschaus, Rob R. de Ruyter van Steveninck, Fred Rieke, and Naftali Tishby for biophysical information flow, neural spike train coding, positional information in bits, and the Information Bottleneck.
  - Andre Levchenko, Ilya Nemenman, and Raymond Cheong for biochemical signaling channel capacity.
  - Andrea Califano and Adam A. Margolin for ARACNE and information-theoretic network reverse engineering.
  - Martin Weigt, Terence Hwa, José N. Onuchic, Debora S. Marks, Chris Sander, and Faruck Morcos for Direct Coupling Analysis (DCA) of residue coevolution.
  - Horace B. Barlow and Simon B. Laughlin for the Efficient Coding Hypothesis in sensory systems.
  - Christoph Adami for evolutionary physical complexity and John J. Hopfield for kinetic proofreading.
  - Michael P. H. Stumpf, Thalia E. Chan, and Ann C. Babtie for multivariate information measures in single-cell transcriptomics (PIDC).
- Textbooks & Software Packages:
  - *Biophysics: Searching for Principles* by William Bialek (Princeton University Press).
  - *Spikes: Exploring the Neural Code* by Fred Rieke, David Warland, Rob de Ruyter van Steveninck, and William Bialek (MIT Press).
  - *Elements of Information Theory* by Thomas M. Cover and Joy A. Thomas (Wiley).
  - Software packages: `WebLogo`, `Bioconductor minet`, `SLEMI`, `pydca`, `PIDC`, and `JIDT`.
- Coding assistance: Gemini (Google).

## License

This work is licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).