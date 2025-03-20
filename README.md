# Peptide Splicing Analysis

This repository contains code for analyzing amino acid preferences at peptide splicing junctions.

## Key Findings

The enrichment/depletion analysis revealed:

### N-terminal Side (Last amino acid of first segment)
- **Alanine (A)**: 4.86x enriched
- **Glutamine (Q)**, **Tryptophan (W)**, and **Leucine (L)** showing moderate enrichment (1.17-1.18x)
- Severe depletion of **Proline (P)** (0.15x), **Asparagine (N)** (0.10x), and **Valine (V)** (0.11x)

### C-terminal Side (First amino acid of second segment)
- **Valine (V)** dominates with 7.26x enrichment
- **Leucine (L)** (1.48x), **Glutamine (Q)** (1.28x), and **Asparagine (N)** (1.11x) also enriched
- **Proline (P)** is strongly avoided (0.13x), as is **Threonine (T)** (0.17x)

## Files
- `protienseqanalysis.ipynb`: Jupyter notebook containing the analysis code
- `INPUT/ProteasomeDB.csv`: Dataset containing peptide splicing information

## Analysis Features
- Frequency analysis of amino acids at junction positions
- Property distribution analysis
- Splice type-specific preferences
- Enrichment/depletion analysis relative to background frequencies
- Structural and mechanistic interpretation
