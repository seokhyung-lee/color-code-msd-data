# Data for "Low-overhead magic state distillation with color codes"

See the original paper [arXiv:2409.07707](https://arxiv.org/abs/2409.07707) for details. Please contact [me](https://seokhyung-lee.github.io) if you have any questions on these data.

## MSD Performance Analysis
Pandas dataframe format; for Fig. 12 and Table I.
- `df_msd_analysis_sng.pkl`: Data for the single-level MSD scheme.

**Note**: The performance analysis dataset for the cultivation-MSD scheme is too large (1.8GB) to upload to GitHub. Please contact [me](https://seokhyung-lee.github.io) directly to request access.

## MSD Performance Analysis under Improved Thresholds
Pandas dataframe format; for Fig. 13.
- `df_msd_improved_thrs_sng.pkl`: Data for the single-level scheme under improved thresholds.
- `df_msd_improved_thrs_cult.pkl`: Data for the cultivation-MSD scheme under improved thresholds.

## Memory and Stability Experiment Analysis
Pandas dataframe format; for Fig. 23.
- `df_tri_memory.pkl`: Triangular patch memory experiment data.
- `df_rec_memory.pkl`: Rectangular patch memory experiment data.
- `df_stability.pkl`: Stability experiment data.

## Growing Operation Analysis
Pandas dataframe format; for Figs. 10, 17, 18.
- `df_growing.pkl`: Simulation data for the growing operation with post-selection.

## Symbolic Expressions
Sympy expression format.
- `sympy_infid_sng.pkl`: Output infidelity of single-level MSD.
- `sympy_succ_prob_sng.pkl`: Success probability of single-level MSD.
- `sympy_infid_cult.pkl`: Output infidelity of cultivation-MSD.
- `sympy_succ_prob_cult.pkl`: Success probability of cultivation-MSD.