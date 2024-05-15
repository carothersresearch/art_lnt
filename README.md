Code for running the Automated Recommendation Tool (https://doi.org/10.1038/s41467-020-18008-4) to optimize Lacto-N-tetraose (LNT) production based on changing the length of three different CRISPRa guide RNAs. This code is related to the paper:
Guide RNA structure design enables combinatorial CRISPRa programs for biosynthetic profiling
Fontana, Sparkman-Yeager, Faulkner, et al. Nat Comm 2024
DOI: 

- run_art.ipynb: Train an ART model on the LNT data.
- art_pred_vs_real.ipynb: Plot the performance of the ART model, reproducing supplementary figure 13. 
- art_pred_visualize.ipynb: Plot recommendations from ART, reproducing figure 6D and supplementary figure 14.
- art_check_model_performance.ipynb: View the performance of different models contained in the trained ART ensemble.  

Notebooks can be viewed on github, but code must be run in an ART docker environment. 
