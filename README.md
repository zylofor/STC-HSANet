## Abstract

Skeletal detection-based analysis of human behavior is of significant value for health monitoring. This study leverages 4D millimeter-wave (mmWave) radar technology to conduct continuous indoor skeletal analysis. Initially, we introduce the radar visual human activity dataset (RVHAD), an extensive benchmark comprising 240,000 radar frames that capture various human actions, including standing, sitting, and falling. Additionally, we propose a fully automated frame correlation labeling technique capable of annotating radar frames autonomously, even in instances of visual system failure. Subsequently, we develop the spatio-temporal constrained human skeletal analysis network (STC-HSANet). This network employs a 3D siamese plain pyramid network (3D-SPPN) to generate multi-level collaborative features, integrates salient features through a context information interaction module (CIIM), and refines the decoded keypoint locations using a positional modulation strategy (PMS). Our experimental results demonstrate that STC-HSANet surpasses current state-of-the-art methods, offering robust performance even under conditions of visual impairment. 



## RVHAD 

RVHAD dataset is available. The following is the method to apply for a dataset：
1) Use the school's email address (edu, stu, etc.) and send an email to: eezylofor@mail.scut.edu.cn
2) Sign the relevant agreement to ensure that it will only be used for scientific research and not for commercial purposes. A scanned version of the agreement that requires a handwritten signature. Both Chinese and English signatures are acceptable.
3) Authorization will be obtained in 1-3 days.
(Notice: If you use this dataset as the benchmark dataset for your paper, please cite the paper)

## Citation

Please cite this if you want to use it in your work.

```
@ARTICLE{Ziyi Jiang,
  title={Learning to Analyze Human Skeletal by Radar-Camera Supervision}, 
  author={Ziyi Jiang, Feng Ke, Wenyuan Kang, Yikui Zhai, Qian Zhang, Xiu Yin Zhang, Xiangmin Xu},
  journal={IEEE TRANSACTIONS ON INSTRUMENTATION AND MEASUREMENT}, 
  year={2025},
  volume={-},
  number={-},
  pages={-},
  doi={-}
}
```
