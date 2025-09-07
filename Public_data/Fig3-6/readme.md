# README

These datasets contain the bias integral $J_D$ for each detector as a function of the coalescence time difference $\Delta t_c$ for the parameter $\cal M$. The data is organized according to different configurations and effects considered.

## Common Structure

Each file contains:
- **delta_tc**: Values of $\Delta t_c$.
- **J_D**: Group containing datasets for each detector:
  - **H1**: Complex $J_D$ values for the H1 detector.
  - **L1**: Complex $J_D$ values for the L1 detector.
  - **V1**: Complex $J_D$ values for the V1 detector.

## File Descriptions

### Fig3_data.hdf5

Considers only the time delay effect, ignoring pattern functions.

### Fig4_data.hdf5

Considers the time delay effect with data organized by direction pairs (H1-L1, V1-H1, L1-V1).

### Fig5_data.hdf5

Considers only the pattern functions of the detectors, ignoring the time delay effect.

### Fig6_data.hdf5

Considers both the time delay and pattern function effects.

The bias integral is in arbitrary units, focusing on its dependence on $\Delta t_c$ for each configuration.

## J_bar_data.hdf5

Contains the bias integral $\bar{J}_\alpha$ for the parameter $\cal M$ as a function of the coalescence time difference $\Delta t_c$. This is used for comparison and is applicable to the left panels of Fig3, Fig5, and Fig6, showing the gray curves.

The bias integral is in arbitrary units, focusing on its dependence on $\Delta t_c$ for each configuration.