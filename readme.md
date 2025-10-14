<div align="center">
<h1>MICCAI 2025: A Novel Framework for Integrating 3D Ultrasound into Percutaneous Liver Tumour Ablation</h1>

<a href="https://xingorno.github.io/3DLIVUS/"><img src="https://img.shields.io/badge/Project-red" alt="Project Page"></a>
<a href="https://link.springer.com/chapter/10.1007/978-3-032-05114-1_3" target="_blank" rel="noopener noreferrer">
  <img src="https://img.shields.io/badge/Publication-MICCAI2025-green" alt="Publication">
</a>
<a href="https://arxiv.org/abs/2506.21162"><img src="https://img.shields.io/badge/Paper-arXiv-green" alt="arXiv"></a>
</div>

### Overview

<p align="justify">
3D ultrasound (US) imaging has shown significant benefits in enhancing the outcomes of percutaneous liver tumour ablation. Its clinical integration is crucial for transitioning 3D US into the therapeutic domain. In this work, our contribution is to propose a novel robotic 3D US integration framework into percutaneous tumour ablation and demonstrate its clinical efficacy without disrupting standard clinical workflow. This work advanced the capabilities of 3D US imaging in improving liver tumour ablation and showed the potential to expand the therapeutic role of 3D US in clinical interventions. To the best of our knowledge, this topic has not been well discussed before.
</p>

<p align="justify">
Figure 2 illustrates the proposed framework for integrating 3D US into the standard workflow for ablation. The standard ablation workflow is enhanced with US–CT/MRI registration, multimodal visualization, and tumour coverage assessment, as highlighted in the brown block. Given our previous work on <a href="https://github.com/Xingorno/3DUS-Based-Tumor-Coverage-Evaluation-And-Optimization" target="_blank" rel= "noopener noreferrer"> tumour coverage assessment </a>, this work primarily focuses on <strong>2D US–CT/MRI registration and visualization</strong>.
</p>

<div align="center">
  <img src="Figs/3DLIVUS_integration_framework_black.png" alt="3DLIVUS system" width="80%">
  <br>
  <a>Figure 1. Framework for 3D US integration into conventional 2D US guidance. (a) 3D LIVUS system; (b) intra-procedural guidance. Note: the role of 3D US is highlighted in a brown block. (Regi: registration, Recon: 3D US reconstruction)</a>
</div>

### Why Need 2D US–CT/MRI Registration and Improved Visualization?

<p align="justify">
In conventional US guidance, some liver tumours have low conspicuity or are nearly undetectable when imaging small lesions or tumours located in challenging regions, such as the liver dome (see Figure 2). In addition, tumour mimics, such as regenerative nodules and prior ablation sites, may cause further confusion, making it even more challenging for physicians to accurately identify the tumour, as shown in Figure 3. Registration of 2D US–CT/MRI is a commonly used solution, but has not seen a clinically effective one so far. In addition, checking the alignment between US and CT/MRI is always necessary for physicians to give their confidence to proceed with the treatment. How to effectively visualize multiple image modalities without adding significant workload during the procedure is a critical topic to investigate.
</p>
<br>
<table align="center" border="0" cellspacing="0" cellpadding="0" style="border:none !important; border-collapse:collapse !important; border-spacing:0 !important; border-top:0 !important; border-bottom:0 !important;">
  <tr>
    <td align="center" width="50%" style="border:none !important; padding:0 !important;">
        <img src="Figs/Invisible_tumours_1.png" 
             alt="Invisible tumour 1" 
             width="90%">
      <br>
      <a> Figure 2. Left: invisible tumour in US; Right: visible tumour in MRI</a>
    </td>
    <td align="center" width="50%" style="border:none !important; padding:0 !important;">
        <img src="Figs/Invisible_tumours_2.png" 
             alt="Invisible tumour 2" 
             width="80%">
      <br>
      <a> Figure 3. Left: benign regenerative nodule; Right: malignant HCC</a>
    </td>
  </tr>
</table>


