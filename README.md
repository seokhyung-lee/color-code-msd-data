# Data for "Low-overhead magic state distillation with color codes"

See the original paper [arXiv:2409.07707](https://arxiv.org/abs/2409.07707) for details. Please contact [me](https://seokhyung-lee.github.io) if you have any questions on these data.

## MSD Performance Analysis
Pandas dataframe format; for Fig. 12 and Table I.
- `df_msd_analysis_sng.pkl`: Data for the single-level MSD scheme.
- `dfs_msd_analysis_cult/`: Dataset for the cultivation-MSD scheme (split due to a large file size)
  - Files named as `p_{p_value}_dout_{dout_value}.pkl`
  - p values: 0.0005, 0.001
  - dout values range from 5 to 71 for p=0.0005, and from 5 to 91 for p=0.001
- `dfs_msd_analysis_cult_simple_growing/`: Dataset for the cultivation-MSD scheme without post-selected growing (split due to a large file size)
  - Files named as `p_{p_value}_dout_{dout_value}.pkl`
  - p values: 0.0001, 0.0005, 0.001
  - dout values range from 5 to 31 for p=0.0001, from 5 to 71 for p=0.0005, and from 5 to 91 for p=0.001

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