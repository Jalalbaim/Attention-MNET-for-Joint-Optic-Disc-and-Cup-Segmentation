# Final Project: Attention-MNET for Joint Optic Disc and Cup Segmentation

### Author

**Name**: BAIM Mohamed Jalal  
**Student ID**: 313551810  
**Institution**: NYCU

---

## Project Overview

This repository contains implementations and evaluations of different variations of the MNet architecture for joint segmentation of optic discs and cups. The focus is on exploring the impact of attention mechanisms, residual blocks, and squeeze-and-excitation (SE) blocks on segmentation performance.

---

## Repository Contents

1. **`Attention_Mnet.ipynb`**

   - Implements the MNet model with **attention gates** in the skip connections.

2. **`Attention_residual_MNET.ipynb`**

   - Extends the Attention-MNet by adding **residual blocks** in both the encoder and decoder.

3. **`SE_MNET.ipynb`**

   - Combines the features of Attention-MNet with **residual blocks** in the encoder and **SE blocks** in the decoder.

4. **`Original_MNET.ipynb`**

   - Reproduces the **original MNet** architecture as described in the reference paper [1].

5. **`MNet-eval.ipynb`**
   - Evaluates and compares the performance of the various MNet model variants implemented in this project.

---

## Reference

[1] H. Fu, J. Cheng, Y. Xu, D. W. K. Wong, J. Liu, and X. Cao, "Joint Optic Disc and Cup Segmentation Based on Multi-Label Deep Network and Polar Transformation," IEEE Transactions on Medical Imaging.
