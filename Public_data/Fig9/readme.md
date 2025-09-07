# README

This dataset contains fractions of samples with larger biases in the network than in a single detector, as a function of the time threshold 
$\Delta t_{\rm th}$
for overlapping signals.

## File: Fig9_data.hdf5

The HDF5 file contains the following datasets:
- **thresholds**: An array of time thresholds for overlapping signals.
- **real**: Fractions based on $|B_\alpha|$ for each configuration.
- **complex**: Fractions based on $\max_{\Delta \phi_c} \left| B_\alpha \right|$ for each configuration.

For the datasets **real** and **complex**, the configurations are indicated by the following names:
- **Time_delay**: Only considering the time delay effect.
- **Pattern_function**: Only considering the pattern function effect.
- **Both_effects**: Considering both effects.
