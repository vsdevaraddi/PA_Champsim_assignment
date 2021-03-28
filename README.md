# VL803 Processor Architecture - Cache Simulation using ChampSim assignment
-----------------------------------

### Introduction to software simulator

[ChampSim](https://github.com/ChampSim/ChampSim) is a trace-based simulator for a microarchitecture study which uses traces to emulate a processor execution. ChampSim comes with example implementation of branch predictors, pre-fetchers and Replacement policies. In this assignment we have implemented,

### Students

- [Sai Manish Sasanapuri](https://github.com/Sai-Manish/)
- [Shubhayu Das](https://github.com/Shubhayu-Das/)
- [Veerendra S. Devaraddi](https://github.com/vsdevaraddi)


### Implementations
 
 The three of use implemented the following(in the above order):

- Prefetcher -> Best Offset Predictor pre-fetcher
- Replacement policy -> BIP, DIP-SD policies
- Branch Predictors -> Three variants of Gshare, Pshare, Tournament branch predictors

See our report and the references papers for details on our implementations.

### Results

All our implementations were run on the 8 traces listed in the report. The results can be found in(see results folder):

1. [branch predictors](https://github.com/vsdevaraddi/PA_Champsim_assignment/tree/main/results/branch_predictors_results)
2. [pre-fetchers](https://github.com/vsdevaraddi/PA_Champsim_assignment/tree/main/results/prefetcher_results)
3. [replacement policies](https://github.com/vsdevaraddi/PA_Champsim_assignment/tree/main/results/cache_replacement_results)


### Instructions for use

To utilize our implementations, copy the requisite files from folders in this repo to the corresponding folders in the
ChampSim repo. After this, build ChampSim, with the requisite policies as command line arguments.
