# ClutterDexGrasp: A Sim-to-Real System for General Dexterous Grasping in Cluttered Scenes
<div align="center">

[Zeyuan Chen*](https://chenzyn.github.io), [**Qiyang Yan\***](https://qiyangyan.github.io/web/), [Yuanpei Chen*](https://cypypccpy.github.io/)  
[Tianhao Wu†](http://tianhaowuhz.github.io/), [Jiyao Zhang†](https://jiyao06.github.io/), [Zihan Ding](https://quantumiracle.github.io/webpage/), [Jinzhou Li](https://kingchou007.github.io/), [Yaodong Yang](https://www.yangyaodong.com/), [Hao Dong✉](https://zsdonghao.github.io/)

<sup>1</sup>CFCS, School of Computer Science, Peking University  
<sup>2</sup>PKU-AgiBot Lab, <sup>3</sup>PKU-PsiBot Lab, <sup>4</sup>Princeton University  

*: Equal Contribution, †: Project Lead, ✉: Corresponding Author  

**Conference on Robot Learning (CoRL) 2025 — Oral**  

[[Website]](https://clutterdexgrasp.github.io/) • [[arXiv]](https://arxiv.org/abs/2506.14317) • [[Video]](https://www.youtube.com/watch?v=RuSxGEG-nlc) 

[![Python Version](https://img.shields.io/badge/Python-3.8+-blue.svg)](#)  
[<img src="https://img.shields.io/badge/Framework-PyTorch-red.svg"/>](https://pytorch.org/)  
______________________________________________________________________
</div>

Dexterous grasping in cluttered scenes presents significant challenges due to diverse object geometries, occlusions, and potential collisions. Existing methods primarily focus on single-object grasping or grasp-pose prediction without interaction, which are insufficient for complex, cluttered scenes. Recent vision-language-action models offer a potential solution but require extensive real-world demonstrations, making them costly and difficult to scale.  

To address these limitations, we revisit the sim-to-real transfer pipeline and develop key techniques that enable zero-shot deployment in reality while maintaining robust generalization.  

We propose **ClutterDexGrasp**, a two-stage teacher-student framework for closed-loop target-oriented dexterous grasping in cluttered scenes. The framework features a teacher policy trained in simulation using clutter density curriculum learning, incorporating both a novel geometry- and spatially-embedded scene representation and a comprehensive safety curriculum, enabling general, dynamic, and safe grasping behaviors. Through imitation learning, we distill the teacher's knowledge into a student 3D diffusion policy (DP3) that operates on partial point cloud observations.  

To the best of our knowledge, this represents the **first zero-shot sim-to-real closed-loop system** for target-oriented dexterous grasping in cluttered scenes, demonstrating robust performance across diverse objects and layouts.

---

## Table of Contents
1. [Installation](#installation)  
2. [Usage](#usage)  
3. [Check out Our Paper](#check-out-our-paper)  
4. [License](#license)  

---

## Installation
<!-- Empty as requested -->

---

## Usage
<!-- Empty as requested -->

---

## Citation
Our paper is available on [arXiv](https://arxiv.org/abs/2506.14317).  
If you find our work useful, please consider citing:  

```bibtex
@inproceedings{chen2025clutterdexgrasp,
  title     = {ClutterDexGrasp: A Sim-to-Real System for General Dexterous Grasping in Cluttered Scenes},
  author    = {Chen, Zeyuan and Yan, Qiyang and Chen, Yuanpei and Wu, Tianhao and Zhang, Jiyao and Ding, Zihan and Li, Jinzhou and Yang, Yaodong and Dong, Hao},
  booktitle = {Conference on Robot Learning (CoRL)},
  year      = {2025}
}
