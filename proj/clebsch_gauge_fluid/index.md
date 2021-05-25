---
title: Clebsch Gauge Fluid
--- 

# Clebsch Gauge Fluid

[Shuqi Yang<sup>1</sup>](https://y-sq.github.io/), Shiying Xiong<sup>1</sup>, Yaorui Zhang<sup>1</sup>, Fan Feng<sup>1</sup>, Jinyuan Liu<sup>1</sup>, and [Bo Zhu<sup>1</sup>](https://www.cs.dartmouth.edu/~bozhu/)  
<sup>1</sup>Dartmouth College

<img src="res/overview.png"/>

## Paper 
**Clebsch Gauge Fluid**  
ACM Transactions on Graphics (SIGGRAPH 2021)  
[Shuqi Yang](https://y-sq.github.io/), Shiying Xiong, Yaorui Zhang, Fan Feng, Jinyuan Liu, and [Bo Zhu](https://www.cs.dartmouth.edu/~bozhu/)  
**[[paper](https://www.cs.dartmouth.edu/~bozhu/papers/clebsch_gauge_fluid.pdf)]** **[<a href="res/code.zip" download="code.zip">code</a>]**  **[[webpage](https://y-sq.github.io/proj/clebsch_gauge_fluid/)]**

## Abstract
We propose a novel gauge fluid solver based on Clebsch wave functions to solve incompressible fluid equations. Our method combines the expressive power of Clebsch wave functions to represent coherent vortical structures and the generality of gauge methods to accommodate a broad array of fluid phenomena. By evolving a transformed wave function as the system's gauge variable enhanced by an additional projection step to enforce pressure jumps on the free boundaries, our method can significantly improve the vorticity generation and preservation ability for a broad range of gaseous and liquid phenomena. Our approach can be easily implemented by modifying a standard grid-based fluid simulator. It can be used to solve various fluid dynamics, including complex vortex filament dynamics, fluids with different obstacles, and surface-tension flow.

## Video / Results
<video src="res/video.mp4" controls="controls" width="100%">Video</video>

## Citation
```
@article{yang2021clebsch,
  title={Clebsch Gauge Fluid},
  author={Yang, Shuqi and Xiong, Shiying and Zhang, Yaorui and Feng, Fan and Liu, Jinyuan and Zhu, Bo},
  journal={ACM Transactions on Graphics (TOG)},
  volume={40},
  number={4},
  article={99},
  pages={1--11},
  year={2021},
  month={8},
  publisher={ACM},
  address = {New York, NY, USA}
}
```
