# Robust-DOA-Estimation-for-Movable-Antenna-Arrays-With-Partial-Gain-and-Phase-Errors-MATLAB-code

[![Paper](https://img.shields.io/badge/IEEE_Xplore-Paper-blue)](https://ieeexplore.ieee.org/document/11235488/)

This repository contains the official demo code for the paper **"Robust DOA Estimation for Movable Antenna Arrays With Partial Gain and Phase Errors,"** authored by Chengzhi Ye.

## 📖 Abstract
In this letter, we investigate the direction-of-arrival (DOA) estimation problem for wireless sensing systems with movable antenna (MA) arrays. To achieve high DOA estimation accuracy in the presence of partial gain and phase errors (GPE) induced by calibration imperfections, we propose a two-stage multiple signal classification (MUSIC)-based self-calibrated DOA estimation method, which jointly estimates and compensates for the GPE. In the first stage, we utilize the optimized MA array configurations to build rotation-invariant signal subspaces, converting the GPE estimation into a constrained least-squares problem. This problem is then solved via the Lagrange multiplier technique, yielding a closed-form expression for GPE estimation. In the second stage, we derive the denoised covariance matrix, followed by GPE compensation utilizing the estimated GPE, and subsequently perform the DOA estimation via the MUSIC method. Simulation results demonstrate the superior DOA estimation performance of the proposed self-calibrated method for MA arrays as compared to the existing approaches.

## 🔗 Paper Link
The full manuscript can be accessed on IEEE Xplore at:  
[https://ieeexplore.ieee.org/document/11235488/](https://ieeexplore.ieee.org/document/11235488/)

## 📌 Citation
If you find this code helpful, relevant to your work, or if you utilize it in your own research, please consider citing our paper.

**Plain Text:**
> [1] C. Ye, R. Zhang, C. Hu, L. Yao, W. Wu and C. Yuen, "Robust DOA Estimation for Movable Antenna Arrays With Partial Gain and Phase Errors," in IEEE Wireless Communications Letters, vol. 15, pp. 545-549, 2026, doi: 10.1109/LWC.2025.3630221.

**BibTeX:**
```bibtex
@ARTICLE{ChengzhiYeMAGPEDOA2026,
  author={Ye, Chengzhi and Zhang, Ruoyu and Hu, Changcheng and Yao, Lei and Wu, Wen and Yuen, Chau},
  journal={IEEE Wireless Communications Letters}, 
  title={Robust DOA Estimation for Movable Antenna Arrays With Partial Gain and Phase Errors}, 
  year={2026},
  volume={15},
  number={},
  pages={545-549},
  keywords={Antenna arrays;Estimation;Direction-of-arrival estimation;Antennas;Covariance matrices;Sensors;Array signal processing;Vectors;Wireless sensor networks;Wireless communication;DOA estimation;movable antenna arrays;partial gain and phase errors},
  doi={10.1109/LWC.2025.3630221}
}
