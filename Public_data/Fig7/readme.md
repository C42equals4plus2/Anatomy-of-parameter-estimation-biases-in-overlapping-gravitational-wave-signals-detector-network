# README

This dataset the joint distribution between the modulus of the bias integral $|J_{\alpha}^{\rm net}|$ and the coalescence time difference $\Delta t_c$ for
four variables $\cal M$, $\eta$, $d_L$, and $t_c$, where only the time delay effect is considered.
## File: Fig7_data.hdf5

The HDF5 file contains the following datasets and groups:

- **delta_tc**: An array representing the time differences $\Delta t_c$.

- **Baseline**: A group containing the baseline $\sqrt{3}|\bar{J}_\alpha(\Delta t_c)|$, above which the points are expected to
have a larger reduced bias in the network than in a single detector.
  - **chirp_mass**: Baseline data for chirp mass $\cal M$.
  - **eta**: Baseline data for eta $\eta$.
  - **distance**: Baseline data for distance $d_L$.
  - **tc**: Baseline data for coalescence time $t_c$.

- **Distribution_of_dt**: An array representing the samples of $\Delta t_c$.

- **Distribution_of_Js_net**: A group containing the samples of the modulus of the bias integral
$|J_{\alpha}^{\rm net}|$ for each parameter:
  - **chirp_mass**: Baseline data for chirp mass $\cal M$.
  - **eta**: Baseline data for eta $\eta$.
  - **distance**: Baseline data for distance $d_L$.
  - **tc**: Baseline data for coalescence time $t_c$.