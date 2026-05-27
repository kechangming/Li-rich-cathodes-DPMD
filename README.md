# Li-rich-cathodes-DPMD

This repository provides the Deep Potential model, training dataset, DP-GEN input files, and representative structures generated during the iterative workflow for Li-rich cathode materials.

## Contents

- **frozen_model_compress.pb**  
  Compressed frozen Deep Potential model.

- **data.tar.gz**  
  Training dataset used for Deep Potential model fitting.

- **configurations1.zip**  
  Structures generated and used during the DP-GEN iterations.

- **configurations2.zip**  
  Additional structures generated and used during the DP-GEN iterations.

- **input_dpgen.json**  
  Input file for the DP-GEN workflow.

- **last_MDs.tar.gz**  
  Molecular dynamics runs from the final DP-GEN iteration.

  - **Trajectory files**

The trajectory files generated in this work are provided as release assets due to their file size.

They can be downloaded from the GitHub Releases page:

[Download trajectory files](https://github.com/kechangming/Li-rich-cathodes-DPMD/releases/latest)

The release contains the trajectory files associated with the Li-rich cathode DPMD simulations.

## Notes

- The `*.pb` file can be used directly for DeepMD/LAMMPS simulations.
- The archived datasets and configurations should be extracted before reuse.
- `configurations1.zip` and `configurations2.zip` correspond to structures collected in different stages of the DP-GEN workflow.

