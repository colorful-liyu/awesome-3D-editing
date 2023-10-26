# awesome-3D-editing



## Open-source Toolboxes and Foundation Models 


| Methods | Task | Github|
|:-----:|:-----:|:-----:|
| [threestudio](https://github.com/threestudio-project/threestudio)   | T23D Generation | [![Star](https://img.shields.io/github/stars/threestudio-project/threestudio.svg?style=social&label=Star)](https://github.com/threestudio-project/threestudio) |
| [DreamGaussian](https://dreamgaussian.github.io/)  | T23D Generation | [![Star](https://img.shields.io/github/stars/dreamgaussian/dreamgaussian.svg?style=social&label=Star)](https://github.com/dreamgaussian/dreamgaussian) |



## Table of Contents 

- [Preliminary: milestones for generation and editing](#preliminary:-milestones-for-generation-and-editing)
  - [Classical representation](#classical-representation)
  - [Classical text-3d generation](#classical-text-3d-generation)
  - [Single-view reconstruction](#single-view-reconstruction)
- [3D general editing](#3D-general-editing)
  - [3D local editing](#3D-local-editing)
  - [3D (global) editing](#3D-(global)-editing)
  - [Part-based editing](#part-based-editing)
  - [Inpainting](#inpainting)
  - [Sketch-based editing](#sketch-based-editing)
  - [Reference-image based editing](#reference-image-based-editing)
- [Appearance-specific editing](#appearance-specific-editing)
  - [Stylization](#stylization)
  - [Re-texture](#re-texture)
  - [Re-light](#re-light)
- [Deformation](#deformation)
  - [Cage](#cage)
  - [Control point](#control-point)
- [Avatar-related editing](#avatar-related-editing)
- [Scene editing](#scene-editing)
- [4D editing](#4D-editing)
     
    

# Paper list (Latest Update: 2023/10/26)

## Preliminary: milestones for generation and editing
 
### Classical representation
 
 
| Title | arXiv | WebSite | Github | Pub. |
|---|---|---|---|---|
| [3D Gaussian Splatting for Real-Time Radiance Field Rendering](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/3d_gaussian_splatting_high.pdf) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/3d_gaussian_splatting_high.pdf) | [![Website](https://img.shields.io/badge/Website-9cf)](https://repo-sam.inria.fr/fungraph/3d-gaussian-splatting/) | [![Star](https://img.shields.io/github/stars/graphdeco-inria/gaussian-splatting.svg?style=social&label=Star)](https://github.com/graphdeco-inria/gaussian-splatting) | SIGGRAPH 2023 |
| [Instant Neural Graphics Primitives](https://nvlabs.github.io/instant-ngp/assets/mueller2022instant.pdf) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://nvlabs.github.io/instant-ngp/assets/mueller2022instant.pdf) | [![Website](https://img.shields.io/badge/Website-9cf)](https://nvlabs.github.io/instant-ngp/) | [![Star](https://img.shields.io/github/stars/NVlabs/instant-ngp.svg?style=social&label=Star)](https://github.com/NVlabs/instant-ngp) | SIGGRAPH 2022 |
 
 
### Classical text-3d generation
 
 
| Title | arXiv | WebSite | Github | Pub. |
|---|---|---|---|---|
| [ATT3D: Amortized Text-to-3D Object Synthesis](https://arxiv.org/abs/2306.07349) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.07349) | [![Website](https://img.shields.io/badge/Website-9cf)](https://research.nvidia.com/labs/toronto-ai/ATT3D/) | - | ICCV 2023 |
| [FantASIA3D: Disentangling Geometry and Appearance for High-quality Text-to-3D Content Creation](https://arxiv.org/abs/2303.13873) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.13873) | [![Website](https://img.shields.io/badge/Website-9cf)](https://fantASIA3d.github.io/) | [![Star](https://img.shields.io/github/stars/Gorilla-Lab-SCUT/Fantasia3D.svg?style=social&label=Star)](https://github.com/Gorilla-Lab-SCUT/Fantasia3D) | ICCV 2023 |
| [Zero-1-to-3: Zero-shot One Image to 3D Object](https://arxiv.org/abs/2303.11328) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.11328) | [![Website](https://img.shields.io/badge/Website-9cf)](https://zero123.cs.columbia.edu/) | [![Star](https://img.shields.io/github/stars/cvlab-columbia/zero123.svg?style=social&label=Star)](https://github.com/cvlab-columbia/zero123) | ICCV 2023 |
| [Magic3D: High-Resolution Text-to-3D Content Creation](https://arxiv.org/abs/2211.10440) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.10440) | [![Website](https://img.shields.io/badge/Website-9cf)](https:// deepimagination.cc/ Magic3D) | - | CVPR 2023 |
| [Zero123++: a Single Image to Consistent Multi-view Diffusion Base Model](https://arxiv.org/abs/2310.15110) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.15110) | - | [![Star](https://img.shields.io/github/stars/SUDO-AI-3D/zero123plus.svg?style=social&label=Star)](https://github.com/SUDO-AI-3D/zero123plus) | ArXiv, 2023, 10 |
| [SyncDreamer: Generating Multiview-consistent Images from a Single-view Image](https://arxiv.org/abs/2309.03453) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.03453) | [![Website](https://img.shields.io/badge/Website-9cf)](https://liuyuan-pal.github.io/SyncDreamer/) | [![Star](https://img.shields.io/github/stars/liuyuan-pal/SyncDreamer.svg?style=social&label=Star)](https://github.com/liuyuan-pal/SyncDreamer) | ArXiv, 2023, 09 |
| [MVDream: Multi-view Diffusion for 3D Generation](https://arxiv.org/abs/2308.16512) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.16512) | [![Website](https://img.shields.io/badge/Website-9cf)](https://MV-Dream.github.io) | [![Star](https://img.shields.io/github/stars/bytedance/MVDream.svg?style=social&label=Star)](https://github.com/bytedance/MVDream) | ArXiv, 2023, 08 |
| [One-2-3-45: Any Single Image to 3D Mesh in 45 Seconds without Per-Shape Optimization](https://arxiv.org/abs/2306.16928) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.16928) | [![Website](https://img.shields.io/badge/Website-9cf)](http://one-2-3-45.com) | [![Star](https://img.shields.io/github/stars/One-2-3-45/One-2-3-45.svg?style=social&label=Star)](https://github.com/One-2-3-45/One-2-3-45) | ArXiv, 2023, 06 |
| [Shap·E: Generating Conditional 3D Implicit Functions](https://arxiv.org/abs/2305.02463) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.02463) | - | [![Star](https://img.shields.io/github/stars/openai/shap-e.svg?style=social&label=Star)](https://github.com/openai/shap-e) | ArXiv, 2023, 05 |
| [Latent-NeRF for Shape-Guided Generation of 3D Shapes and Textures](https://arxiv.org/abs/2211.07600) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.07600) | - | [![Star](https://img.shields.io/github/stars/eladrich/latent-nerf.svg?style=social&label=Star)](https://github.com/eladrich/latent-nerf) | ArXiv, 2022, 11 |
| [DreamFusion: Text-to-3D using 2D Diffusion](https://arxiv.org/abs/2209.14988) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2209.14988) | [![Website](https://img.shields.io/badge/Website-9cf)](https://dreamfusion3d.github.io/) | [![Star](https://img.shields.io/github/stars/ashawkey/stable-dreamfusion.svg?style=social&label=Star)](https://github.com/ashawkey/stable-dreamfusion) | ArXiv, 2022, 09 |
| [DreamGaussian: Generative Gaussian Splatting for Efficient 3D Content Creation](https://ArXiv.org/abs/2309.16653) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2309.16653) | [![Website](https://img.shields.io/badge/Website-9cf)](https://dreamgaussian.github.io/) | [![Star](https://img.shields.io/github/stars/dreamgaussian/dreamgaussian.svg?style=social&label=Star)](https://github.com/dreamgaussian/dreamgaussian) | ArXiv |
| [Consistent-1-to-3: Consistent Image to 3D View Synthesis via Geometry-aware Diffusion Models](https://arxiv.org/pdf/2310.03020) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2310.03020) | [![Website](https://img.shields.io/badge/Website-9cf)](https://jianglongye.com/consistent123/) | - | 3DV 2024 |


### Single-view reconstruction
 
 
| Title | arXiv | WebSite | Github | Pub. |
|---|---|---|---|---|
| [Make-It-3D: High-Fidelity 3D Creation from A Single Image with Diffusion Prior](https://arxiv.org/abs/2303.14184) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.14184) | [![Website](https://img.shields.io/badge/Website-9cf)](https://make-it-3d.github.io/) | [![Star](https://img.shields.io/github/stars/junshutang/Make-It-3D.svg?style=social&label=Star)](https://github.com/junshutang/Make-It-3D) | ICCV 2023 |
| [Zero-1-to-3: Zero-shot One Image to 3D Object](https://arxiv.org/abs/2303.11328) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.11328) | [![Website](https://img.shields.io/badge/Website-9cf)](https://zero123.cs.columbia.edu/) | [![Star](https://img.shields.io/github/stars/cvlab-columbia/zero123.svg?style=social&label=Star)](https://github.com/cvlab-columbia/zero123) | ICCV 2023 |
| [Zero123++: a Single Image to Consistent Multi-view Diffusion Base Model](https://arxiv.org/abs/2310.15110) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2310.15110) | - | [![Star](https://img.shields.io/github/stars/SUDO-AI-3D/zero123plus.svg?style=social&label=Star)](https://github.com/SUDO-AI-3D/zero123plus) | ArXiv, 2023, 10 |
| [SyncDreamer: Generating Multiview-consistent Images from a Single-view Image](https://arxiv.org/abs/2309.03453) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.03453) | [![Website](https://img.shields.io/badge/Website-9cf)](https://liuyuan-pal.github.io/SyncDreamer/) | [![Star](https://img.shields.io/github/stars/liuyuan-pal/SyncDreamer.svg?style=social&label=Star)](https://github.com/liuyuan-pal/SyncDreamer) | ArXiv, 2023, 09 |
| [Magic123: One Image to High-Quality 3D Object Generation Using Both 2D and 3D Diffusion Priors](https://arxiv.org/abs/2306.17843) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.17843) | [![Website](https://img.shields.io/badge/Website-9cf)](https://guochengqian.github.io/project/magic123/) | [![Star](https://img.shields.io/github/stars/guochengqian/Magic123.svg?style=social&label=Star)](https://github.com/guochengqian/Magic123) | ArXiv, 2023, 06 |
| [DreamGaussian: Generative Gaussian Splatting for Efficient 3D Content Creation](https://ArXiv.org/abs/2309.16653) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2309.16653) | [![Website](https://img.shields.io/badge/Website-9cf)](https://dreamgaussian.github.io/) | [![Star](https://img.shields.io/github/stars/dreamgaussian/dreamgaussian.svg?style=social&label=Star)](https://github.com/dreamgaussian/dreamgaussian) | ArXiv |
 

 
## 3D general editing

### 3D local editing
 
 
| Title | arXiv | WebSite | Github | Pub. |
|---|---|---|---|---|
| [FocalDreamer: Text-driven 3D Editing via Focal-fusion Assembly](https://arxiv.org/abs/2308.10608) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.10608) | [![Website](https://img.shields.io/badge/Website-9cf)](https://focaldreamer.github.io/) | [![Star](https://img.shields.io/github/stars/colorful-liyu/focaldreamer.svg?style=social&label=Star)](https://github.com/colorful-liyu/focaldreamer) | ArXiv, 2023, 08 |
| [DreamEditor: Text-Driven 3D Scene Editing with Neural Fields](https://arxiv.org/abs/2306.13455) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.13455) | [![Website](https://img.shields.io/badge/Website-9cf)](https://github.com/zjy526223908/dreameditor) | - | SIGGRAPH ASIA 2023 |
| [OBJect 3DIT: Language-guided 3D-aware Image Editing](http://ArXiv.org/abs/2307.11073) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](http://ArXiv.org/abs/2307.11073) | [![Website](https://img.shields.io/badge/Website-9cf)](https://prior.allenai.org/projects/object-edit) | - | NeurIPS 2023 |
| [Vox-E: Text-guided Voxel Editing of 3D Objects](https://arxiv.org/abs/2303.12048) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.12048) | [![Website](https://img.shields.io/badge/Website-9cf)](http://vox-e.github.io/) | [![Star](https://img.shields.io/github/stars/TAU-VAILab/Vox-E.svg?style=social&label=Star)](https://github.com/TAU-VAILab/Vox-E) | ICCV 2023 |
| [Locally Stylized Neural Radiance Fields](https://ArXiv.org/abs/2309.10684) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2309.10684) | - | - | ICCV 2023 |
| [Seal-3D: Interactive Pixel-Level Editing for Neural Radiance Fields](https://ArXiv.org/abs/2307.15131) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2307.15131) | [![Website](https://img.shields.io/badge/Website-9cf)](https://windingwind.github.io/seal-3d/) | [![Star](https://img.shields.io/github/stars/windingwind/seal-3d.svg?style=social&label=Star)](https://github.com/windingwind/seal-3d) | ICCV 2023 |
| [Local 3D Editing via 3D Distillation of CLIP Knowledge](https://arxiv.org/abs/2306.12570) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.12570) | - | - | CVPR 2023 |
| [RePaint-NeRF: NeRF Editting via Semantic Masks and Diffusion Models](https://ArXiv.org/abs/2309.07125) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2309.07125) | - | - | CVPR 2023 |
| [SINE: Semantic-driven Image-based NeRF Editing with Prior-guided Editing Field](https://arxiv.org/abs/2303.13277) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.13277) | [![Website](https://img.shields.io/badge/Website-9cf)](https://zju3dv.github.io/sine/) | [![Star](https://img.shields.io/github/stars/zju3dv/SINE.svg?style=social&label=Star)](https://github.com/zju3dv/SINE) | CVPR 2023 |
| [SKED: Sketch-guided Text-based 3D Editing](https://arxiv.org/abs/2303.10735) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.10735) | - | - | CVPR 2023 |
| [Nerflets: Local Radiance Fields for Efficient Structure-Aware 3D Scene Representation from 2D Supervision](https://ArXiv.org/abs/2303.03361) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2303.03361) | [![Website](https://img.shields.io/badge/Website-9cf)](https://jetd1.github.io/nerflets-web/) | - | CVPR 2023 |
| [Progressive3D: Progressively Local Editing for Text-to-3D Content Creation with Complex Semantic Prompts](https://ArXiv.org/abs/2310.11784) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2310.11784) | [![Website](https://img.shields.io/badge/Website-9cf)](https://cxh0519.github.io/projects/Progressive3D/) | [![Star](https://img.shields.io/github/stars/cxh0519/Progressive3D.svg?style=social&label=Star)](https://github.com/cxh0519/Progressive3D) | ArXiv |
| [Language-driven Object Fusion into Neural Radiance Fields with Pose-Conditioned Dataset Updates](https://ArXiv.org/abs/2309.11281) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2309.11281) | - | - | ArXiv |
| [ED-NeRF: Efficient Text-Guided Editing of 3D Scene using Latent Space NeRF](https://ArXiv.org/abs/2310.02712) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2310.02712) | - | - | ArXiv |
 
 

### 3D (global) editing
 
 
| Title | arXiv | WebSite | Github | Pub. |
|---|---|---|---|---|
| [NeRF-Art: Text-Driven Neural Radiance Fields Stylization](https://ArXiv.org/abs/2212.08070) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2212.08070) | [![Website](https://img.shields.io/badge/Website-9cf)](https://cassiepython.github.io/nerfart/) | [![Star](https://img.shields.io/github/stars/cassiePython/NeRF-Art.svg?style=social&label=Star)](https://github.com/cassiePython/NeRF-Art) | TVCG 2023 |
| [3D-aware Blending with Generative NeRFs](https://arxiv.org/abs/2302.06608) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.06608) | [![Website](https://img.shields.io/badge/Website-9cf)](https://blandocs.github.io/blendnerf) | [![Star](https://img.shields.io/github/stars/naver-ai/BlendNeRF.svg?style=social&label=Star)](https://github.com/naver-ai/BlendNeRF) | ICCV 2023 |
| [Instruct-NeRF2NeRF: Editing 3D Scenes with Instructions](https://arxiv.org/abs/2303.12789) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.12789) | [![Website](https://img.shields.io/badge/Website-9cf)](https://instruct-nerf2nerf.github.io/) | [![Star](https://img.shields.io/github/stars/ayaanzhaque/instruct-nerf2nerf.svg?style=social&label=Star)](https://github.com/ayaanzhaque/instruct-nerf2nerf) | ICCV 2023 |
| [Vox-E: Text-guided Voxel Editing of 3D Objects](https://arxiv.org/abs/2303.12048) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.12048) | [![Website](https://img.shields.io/badge/Website-9cf)](http://vox-e.github.io/) | [![Star](https://img.shields.io/github/stars/TAU-VAILab/Vox-E.svg?style=social&label=Star)](https://github.com/TAU-VAILab/Vox-E) | ICCV 2023 |
| [3D Semantic Subspace Traverser: Empowering 3D Generative Model with Shape Editing Capability](https://ArXiv.org/abs/2307.14051) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2307.14051) | - | [![Star](https://img.shields.io/github/stars/TrepangCat/3D_Semantic_Subspace_Traverser.svg?style=social&label=Star)](https://github.com/TrepangCat/3D_Semantic_Subspace_Traverser) | ICCV 2023 |
| [DreamBooth3D: Subject-Driven Text-to-3D Generation](https://ArXiv.org/abs/2303.13508) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2303.13508) | [![Website](https://img.shields.io/badge/Website-9cf)](https://dreambooth3d.github.io/) | - | ICCV 2023 |
| [Blending-NeRF: Text-Driven Localized Editing in Neural Radiance Fields](https://ArXiv.org/pdf/2308.11974) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/pdf/2308.11974) | [![Website](https://img.shields.io/badge/Website-9cf)](https://seokhunchoi.github.io/Blending-NeRF/) | - | ICCV 2023 |
| [Learning Unified Decompositional and Compositional NeRF for Editable Novel View Synthesis](https://ArXiv.org/abs/2308.02840) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2308.02840) | [![Website](https://img.shields.io/badge/Website-9cf)](https://w-ted.github.io/publications/udc-nerf/) | - | ICCV 2023 |
| [Edit-DiffNeRF: Editing 3D Neural Radiance Fields using 2D Diffusion Model](https://arxiv.org/abs/2306.09551) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.09551) | [![Website](https://img.shields.io/badge/Website-9cf)](https://sirwyver.github.io/DiffRF/) | - | CVPR 2023 |
| [Frequency-Modulated Point Cloud Rendering with Easy Editing](https://ArXiv.org/abs/2303.07596) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2303.07596) | - | [![Star](https://img.shields.io/github/stars/yizhangphd/FreqPCR.svg?style=social&label=Star)](https://github.com/yizhangphd/FreqPCR) | CVPR 2023 |
| [IT3D: Improved Text-to-3D Generation with Explicit View Synthesis](https://arxiv.org/pdf/2309.03453) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/pdf/2309.03453) | - | [![Star](https://img.shields.io/github/stars/buaacyw/IT3D-text-to-3D.svg?style=social&label=Star)](https://github.com/buaacyw/IT3D-text-to-3D) | ArXiv, 2023, 09 |
| [Blended-NeRF: Zero-Shot Object Generation and Blending in Existing Neural Radiance Fields](https://arxiv.org/abs/2306.12760) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.12760) | - | - | ArXiv, 2023, 06 |
| [Watch Your Steps: Local Image and Scene Editing by Text Instructions](https://ArXiv.org/abs/2308.08947) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2308.08947) | [![Website](https://img.shields.io/badge/Website-9cf)](https://ashmrz.github.io/WatchYourSteps/) | - | ArXiv |


### Part-based editing
 
 
| Title | arXiv | WebSite | Github | Pub. |
|---|---|---|---|---|
| [PartNeRF: Generating Part-Aware Editable 3D Shapes without 3D Supervision](https://arxiv.org/abs/2303.09554) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.09554) | [![Website](https://img.shields.io/badge/Website-9cf)](https://ktertikas.github.io/part_nerf) | [![Star](https://img.shields.io/github/stars/ktertikas/part_nerf.svg?style=social&label=Star)](https://github.com/ktertikas/part_nerf) | CVPR 2023 |
| [FocalDreamer: Text-driven 3D Editing via Focal-fusion Assembly](https://arxiv.org/abs/2308.10608) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.10608) | [![Website](https://img.shields.io/badge/Website-9cf)](https://focaldreamer.github.io/) | [![Star](https://img.shields.io/github/stars/colorful-liyu/focaldreamer.svg?style=social&label=Star)](https://github.com/colorful-liyu/focaldreamer) | ArXiv, 2023, 08 |
| [VQ-NeRF: Neural Reflectance Decomposition and Editing with Vector Quantization](https://ArXiv.org/abs/2310.11864) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2310.11864) | [![Website](https://img.shields.io/badge/Website-9cf)](https://jtbzhl.github.io/VQ-NeRF.github.io/) | - | ArXiv |
 
 

### Inpainting
 
 
| Title | arXiv | WebSite | Github | Pub. |
|---|---|---|---|---|
| [OBJect 3DIT: Language-guided 3D-aware Image Editing](http://ArXiv.org/abs/2307.11073) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](http://ArXiv.org/abs/2307.11073) | [![Website](https://img.shields.io/badge/Website-9cf)](https://prior.allenai.org/projects/object-edit) | - | NeurIPS 2023 |
| [Reference-guided Controllable Inpainting of Neural Radiance Fields](https://ArXiv.org/abs/2304.09677) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2304.09677) | [![Website](https://img.shields.io/badge/Website-9cf)](https://ashmrz.github.io/reference-guided-3d/) | - | ICCV 2023 |
| [Removing Objects From Neural Radiance Fields](https://arxiv.org/abs/2212.11966) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.11966) | [![Website](https://img.shields.io/badge/Website-9cf)](https://nianticlabs.github.io/nerf-object-removal/) | [![Star](https://img.shields.io/github/stars/nianticlabs/nerf-object-removal.svg?style=social&label=Star)](https://github.com/nianticlabs/nerf-object-removal) | CVPR 2023 |
| [SPIn-NeRF: Multiview Segmentation and Perceptual Inpainting with Neural Radiance Fields](https://ArXiv.org/abs/2211.12254) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2211.12254) | [![Website](https://img.shields.io/badge/Website-9cf)](https://spinnerf3d.github.io/) | [![Star](https://img.shields.io/github/stars/SamsungLabs/SPIn-NeRF.svg?style=social&label=Star)](https://github.com/SamsungLabs/SPIn-NeRF) | CVPR 2023 |
| [InpaintNeRF360: Text-Guided 3D Inpainting on Unbounded Neural Radiance Fields](https://arxiv.org/abs/2305.15094) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.15094) | - | - | ArXiv, 2023, 05 |
| [OR-NeRF: Object Removing from 3D Scenes Guided by Multiview Segmentation with Neural Radiance Fields](https://arxiv.org/abs/2305.10503) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.10503) | - | [![Star](https://img.shields.io/github/stars/cuteyyt/or-nerf.svg?style=social&label=Star)](https://github.com/cuteyyt/or-nerf) | ArXiv, 2023, 05 |
| [NeRF-In: Free-Form NeRF Inpainting with RGB-D Priors](https://arxiv.org/abs/2206.04901) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2206.04901) | - | - | ArXiv, 2022, 06 |


### Sketch-based editing
 
 
| Title | arXiv | WebSite | Github | Pub. |
|---|---|---|---|---|
| [FantASIA3D: Disentangling Geometry and Appearance for High-quality Text-to-3D Content Creation](https://arxiv.org/abs/2303.13873) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.13873) | [![Website](https://img.shields.io/badge/Website-9cf)](https://fantASIA3d.github.io/) | [![Star](https://img.shields.io/github/stars/Gorilla-Lab-SCUT/Fantasia3D.svg?style=social&label=Star)](https://github.com/Gorilla-Lab-SCUT/Fantasia3D) | ICCV 2023 |
| [Sketch2Mesh: Reconstructing and editing 3D shapes from sketches](https://arxiv.org/abs/2104.00482) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2104.00482) | - | [![Star](https://img.shields.io/github/stars/cvlab-epfl/sketch2mesh.svg?style=social&label=Star)](https://github.com/cvlab-epfl/sketch2mesh) | ICCV 2021 |
| [SKED: Sketch-guided Text-based 3D Editing](https://arxiv.org/abs/2303.10735) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.10735) | - | - | CVPR 2023 |
| [Latent-NeRF for Shape-Guided Generation of 3D Shapes and Textures](https://arxiv.org/abs/2211.07600) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2211.07600) | - | [![Star](https://img.shields.io/github/stars/eladrich/latent-nerf.svg?style=social&label=Star)](https://github.com/eladrich/latent-nerf) | ArXiv, 2022, 11 |

### Reference-image based editing
 
 
| Title | arXiv | WebSite | Github | Pub. |
|---|---|---|---|---|
| [Seal-3D: Interactive Pixel-Level Editing for Neural Radiance Fields](https://ArXiv.org/abs/2307.15131) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2307.15131) | [![Website](https://img.shields.io/badge/Website-9cf)](https://windingwind.github.io/seal-3d/) | [![Star](https://img.shields.io/github/stars/windingwind/seal-3d.svg?style=social&label=Star)](https://github.com/windingwind/seal-3d) | ICCV 2023 |
| [SINE: Semantic-driven Image-based NeRF Editing with Prior-guided Editing Field](https://arxiv.org/abs/2303.13277) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.13277) | [![Website](https://img.shields.io/badge/Website-9cf)](https://zju3dv.github.io/sine/) | [![Star](https://img.shields.io/github/stars/zju3dv/SINE.svg?style=social&label=Star)](https://github.com/zju3dv/SINE) | CVPR 2023 |
| [Language-driven Object Fusion into Neural Radiance Fields with Pose-Conditioned Dataset Updates](https://ArXiv.org/abs/2309.11281) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2309.11281) | - | - | ArXiv |


## Appearance-specific editing


### Stylization
 
 
| Title | arXiv | WebSite | Github | Pub. |
|---|---|---|---|---|
| [NeRF-Art: Text-Driven Neural Radiance Fields Stylization](https://ArXiv.org/abs/2212.08070) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2212.08070) | [![Website](https://img.shields.io/badge/Website-9cf)](https://cassiepython.github.io/nerfart/) | [![Star](https://img.shields.io/github/stars/cassiePython/NeRF-Art.svg?style=social&label=Star)](https://github.com/cassiePython/NeRF-Art) | TVCG 2023 |
| [TeSTNeRF: Text-Driven 3D Style Transfer via Cross-Modal Learning](https://ArXiv.org/abs/2306.05668) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2306.05668) | - | - | IJCAI 2023 |
| [X-Mesh:Towards Fast and Accurate Text-driven 3D Stylization via Dynamic Textual Guidance](https://ArXiv.org/abs/2303.15764) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2303.15764) | [![Website](https://img.shields.io/badge/Website-9cf)](https://xmu-xiaoma666.github.io/Projects/X-Mesh/) | [![Star](https://img.shields.io/github/stars/xmu-xiaoma666/X-Mesh.svg?style=social&label=Star)](https://github.com/xmu-xiaoma666/X-Mesh) | ICCV 2023 |
| [Locally Stylized Neural Radiance Fields](https://ArXiv.org/abs/2309.10684) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2309.10684) | - | - | ICCV 2023 |
| [Transforming Radiance Field with Lipschitz Network for Photorealistic 3D Scene Stylization](https://arxiv.org/abs/2303.13232) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.13232) | - | - | CVPR 2023 |
| [PaletteNeRF: Palette-based Appearance Editing of Neural Radiance Fields](https://ArXiv.org/abs/2212.10699) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2212.10699) | [![Website](https://img.shields.io/badge/Website-9cf)](https://palettenerf.github.io/) | [![Star](https://img.shields.io/github/stars/zfkuang/PaletteNeRF.svg?style=social&label=Star)](https://github.com/zfkuang/PaletteNeRF) | CVPR 2023 |
| [StyleRF: Zero-shot 3D Style Transfer of Neural Radiance Fields](https://ArXiv.org/abs/2303.10598) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2303.10598) | [![Website](https://img.shields.io/badge/Website-9cf)](https://kunhao-liu.github.io/StyleRF/) | [![Star](https://img.shields.io/github/stars/Kunhao-Liu/StyleRF.svg?style=social&label=Star)](https://github.com/Kunhao-Liu/StyleRF) | CVPR 2023 |
| [Ref-NPR: Reference-Based Non-Photorealistic Radiance Fields for Controllable Scene Stylization](https://ArXiv.org/abs/2212.02766) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2212.02766) | [![Website](https://img.shields.io/badge/Website-9cf)](https://ref-npr.github.io/) | [![Star](https://img.shields.io/github/stars/dvlab-research/Ref-NPR.svg?style=social&label=Star)](https://github.com/dvlab-research/Ref-NPR) | CVPR 2023 |
| [MM-NeRF: Multimodal-Guided 3D Multi-Style Transfer of Neural Radiance Field](https://ArXiv.org/abs/2309.13607) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2309.13607) | - | - | ArXiv |
| [Text-driven Editing of 3D Scenes without Retraining](https://ArXiv.org/abs/2309.04917) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2309.04917) | [![Website](https://img.shields.io/badge/Website-9cf)](https://sk-fun.fun/DN2N/) | [![Star](https://img.shields.io/github/stars/Fangkang515/DN2N.svg?style=social&label=Star)](https://github.com/Fangkang515/DN2N) | ArXiv |
 
 
### Re-texture
 
 
| Title | arXiv | WebSite | Github | Pub. |
|---|---|---|---|---|
| [ ICE-NeRF: Interactive Color Editing of NeRFs via Decomposition-Aware Weight Optimization](https://openaccess.thecvf.com/content/ICCV2023/papers/Lee_ICE-NeRF_Interactive_Color_Editing_of_NeRFs_via_Decomposition-Aware_Weight_Optimization_ICCV_2023_paper.pdf) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://openaccess.thecvf.com/content/ICCV2023/papers/Lee_ICE-NeRF_Interactive_Color_Editing_of_NeRFs_via_Decomposition-Aware_Weight_Optimization_ICCV_2023_paper.pdf) | [![Website](https://img.shields.io/badge/Website-9cf)](https://heuyklee.github.io/ice-nerf/) | - | ICCV 2023 |
| [Texture Generation on 3D Meshes with Point-UV Diffusion](https://ArXiv.org/abs/2308.10490) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2308.10490) | [![Website](https://img.shields.io/badge/Website-9cf)](https://cvmi-lab.github.io/Point-UV-Diffusion) | [![Star](https://img.shields.io/github/stars/CVMI-Lab/Point-UV-Diffusion.svg?style=social&label=Star)](https://github.com/CVMI-Lab/Point-UV-Diffusion) | ICCV 2023 |
| [X-Mesh:Towards Fast and Accurate Text-driven 3D Stylization via Dynamic Textual Guidance](https://ArXiv.org/abs/2303.15764) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2303.15764) | [![Website](https://img.shields.io/badge/Website-9cf)](https://xmu-xiaoma666.github.io/Projects/X-Mesh/) | [![Star](https://img.shields.io/github/stars/xmu-xiaoma666/X-Mesh.svg?style=social&label=Star)](https://github.com/xmu-xiaoma666/X-Mesh) | ICCV 2023 |
| [Text2Tex: Text-driven Texture Synthesis via Diffusion Models](https://daveredrum.github.io/Text2Tex/static/Text2Tex.pdf) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://daveredrum.github.io/Text2Tex/static/Text2Tex.pdf) | [![Website](https://img.shields.io/badge/Website-9cf)](https://daveredrum.github.io/Text2Tex/) | [![Star](https://img.shields.io/github/stars/daveredrum/Text2Tex.svg?style=social&label=Star)](https://github.com/daveredrum/Text2Tex) | ICCV 2023 |
| [NeuMesh: Learning Disentangled Neural Mesh-based Implicit Field for Geometry and Texture Editing](https://arxiv.org/abs/2207.11911) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2207.11911) | [![Website](https://img.shields.io/badge/Website-9cf)](https://zju3dv.github.io/neumesh/) | [![Star](https://img.shields.io/github/stars/zju3dv/neumesh.svg?style=social&label=Star)](https://github.com/zju3dv/neumesh) | ECCV 2022 |
| [PaletteNeRF: Palette-based Appearance Editing of Neural Radiance Fields](https://ArXiv.org/abs/2212.10699) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2212.10699) | [![Website](https://img.shields.io/badge/Website-9cf)](https://palettenerf.github.io/) | [![Star](https://img.shields.io/github/stars/zfkuang/PaletteNeRF.svg?style=social&label=Star)](https://github.com/zfkuang/PaletteNeRF) | CVPR 2023 |
| [StyleRF: Zero-shot 3D Style Transfer of Neural Radiance Fields](https://ArXiv.org/abs/2303.10598) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2303.10598) | [![Website](https://img.shields.io/badge/Website-9cf)](https://kunhao-liu.github.io/StyleRF/) | [![Star](https://img.shields.io/github/stars/Kunhao-Liu/StyleRF.svg?style=social&label=Star)](https://github.com/Kunhao-Liu/StyleRF) | CVPR 2023 |
| [Ref-NPR: Reference-Based Non-Photorealistic Radiance Fields for Controllable Scene Stylization](https://ArXiv.org/abs/2212.02766) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2212.02766) | [![Website](https://img.shields.io/badge/Website-9cf)](https://ref-npr.github.io/) | [![Star](https://img.shields.io/github/stars/dvlab-research/Ref-NPR.svg?style=social&label=Star)](https://github.com/dvlab-research/Ref-NPR) | CVPR 2023 |
| [TensoIR: Tensorial Inverse Rendering](https://ArXiv.org/abs/2304.12461) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2304.12461) | [![Website](https://img.shields.io/badge/Website-9cf)](https://haian-jin.github.io/TensoIR/) | [![Star](https://img.shields.io/github/stars/Haian-Jin/TensoIR.svg?style=social&label=Star)](https://github.com/Haian-Jin/TensoIR) | CVPR 2023 |
| [Text-guided High-definition Consistency Texture Model](https://arxiv.org/abs/2305.05901) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.05901) | - | - | ArXiv, 2023, 05 |
| [Farm3D: Learning Articulated 3D Animals by Distilling 2D Diffusion](https://arxiv.org/abs/2304.10535) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.10535) | [![Website](https://img.shields.io/badge/Website-9cf)](https://farm3d.github.io/) | - | ArXiv, 2023, 04 |
| [ProteusNeRF: Fast Lightweight NeRF Editing using 3D-Aware Image Context](https://ArXiv.org/abs/2310.09965) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2310.09965) | [![Website](https://img.shields.io/badge/Website-9cf)](https://proteusnerf.github.io/) | - | ArXiv |
| [Text-driven Editing of 3D Scenes without Retraining](https://ArXiv.org/abs/2309.04917) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2309.04917) | [![Website](https://img.shields.io/badge/Website-9cf)](https://sk-fun.fun/DN2N/) | [![Star](https://img.shields.io/github/stars/Fangkang515/DN2N.svg?style=social&label=Star)](https://github.com/Fangkang515/DN2N) | ArXiv |
| [Dyn-E: Local Appearance Editing of Dynamic Neural Radiance Fields](https://ArXiv.org/abs/2307.12909) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2307.12909) | [![Website](https://img.shields.io/badge/Website-9cf)](https://dyn-e.github.io/) | - | ArXiv |
| [TEGLO: High Fidelity Canonical Texture Mapping from Single-View Images](https://ArXiv.org/abs/2303.13743) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2303.13743) | [![Website](https://img.shields.io/badge/Website-9cf)](https://teglo-nerf.github.io/) | - | ArXiv |
| [RecolorNeRF: Layer Decomposed Radiance Fields for Efficient Color Editing of 3D Scenes](https://arxiv.org/abs/2301.07958) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2301.07958) | [![Website](https://img.shields.io/badge/Website-9cf)](https://sites.google.com/view/recolornerf) | [![Star](https://img.shields.io/github/stars/yuehaowang/RecolorNeRF.svg?style=social&label=Star)](https://github.com/yuehaowang/RecolorNeRF) | ACM MM 2023 |
| [RecolorNeRF: Layer Decomposed Radiance Fields for Efficient Color Editing of 3D Scenes](https://ArXiv.org/abs/2301.07958) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2301.07958) | [![Website](https://img.shields.io/badge/Website-9cf)](https://sites.google.com/view/recolornerf) | [![Star](https://img.shields.io/github/stars/yuehaowang/RecolorNeRF.svg?style=social&label=Star)](https://github.com/yuehaowang/RecolorNeRF) | ACM MM 2023 |
 



### Re-light
 
 
| Title | arXiv | WebSite | Github | Pub. |
|---|---|---|---|---|
| [ENVIDR: Implicit Differentiable Renderer with Neural Environment Lighting](https://ArXiv.org/abs/2303.13022) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2303.13022) | [![Website](https://img.shields.io/badge/Website-9cf)](https://nexuslrf.github.io/ENVIDR/) | [![Star](https://img.shields.io/github/stars/nexuslrf/ENVIDR.svg?style=social&label=Star)](https://github.com/nexuslrf/ENVIDR) | ICCV 2023 |
| [ReNeRF: Relightable Neural Radiance Fields with Nearfield Lighting](https://openaccess.thecvf.com/content/ICCV2023/papers/Xu_ReNeRF_Relightable_Neural_Radiance_Fields_with_Nearfield_Lighting_ICCV_2023_paper.pdf) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://openaccess.thecvf.com/content/ICCV2023/papers/Xu_ReNeRF_Relightable_Neural_Radiance_Fields_with_Nearfield_Lighting_ICCV_2023_paper.pdf) | - | - | ICCV 2023 |
| [IntrinsicNeRF: Learning Intrinsic Neural Radiance Fields for Editable Novel View Synthesis](https://ArXiv.org/abs/2303.12074) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2303.12074) | [![Website](https://img.shields.io/badge/Website-9cf)](https://zju3dv.github.io/intrinsic_nerf/) | [![Star](https://img.shields.io/github/stars/zju3dv/IntrinsicNeRF.svg?style=social&label=Star)](https://github.com/zju3dv/IntrinsicNeRF) | ICCV 2023 |
| [Neural Fields meet Explicit Geometric Representations for Inverse Rendering of Urban Scenes](https://arxiv.org/abs/2304.03266) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.03266) | - | - | CVPR 2023 |
| [TensoIR: Tensorial Inverse Rendering](https://ArXiv.org/abs/2304.12461) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2304.12461) | [![Website](https://img.shields.io/badge/Website-9cf)](https://haian-jin.github.io/TensoIR/) | [![Star](https://img.shields.io/github/stars/Haian-Jin/TensoIR.svg?style=social&label=Star)](https://github.com/Haian-Jin/TensoIR) | CVPR 2023 |





## Deformation
 
 
| Title | arXiv | WebSite | Github | Pub. |
|---|---|---|---|---|
| [Real-time Locally Injective Volumetric Deformation](https://dl.acm.org/doi/abs/10.1145/3450626.3459794) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://dl.acm.org/doi/abs/10.1145/3450626.3459794) | - | [![Star](https://img.shields.io/github/stars/lwt831/Real-time-Locally-Injective-Volumetric-Deformation.svg?style=social&label=Star)](https://github.com/lwt831/Real-time-Locally-Injective-Volumetric-Deformation) | TOG 2021 |
| [Variational Harmonic Maps for Space Deformation](https://dl.acm.org/doi/10.1145/1531326.1531340) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://dl.acm.org/doi/10.1145/1531326.1531340) | - | - | TOG 2009 |
| [GestureDiffuCLIP: Gesture Diffusion Model with CLIP Latents](https://arxiv.org/abs/2303.14613) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.14613) | [![Website](https://img.shields.io/badge/Website-9cf)](https://pku-mocca.github.io/GestureDiffuCLIP-Page/) | - | SIGGRAPH 2023 |
| [TextDeformer: Geometry Manipulation using Text Guidance](https://arxiv.org/abs/2304.13348) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.13348) | [![Website](https://img.shields.io/badge/Website-9cf)](https://threedle.github.io/TextDeformer/) | [![Star](https://img.shields.io/github/stars/threedle/TextDeformer.svg?style=social&label=Star)](https://github.com/threedle/TextDeformer) | SIGGRAPH 2023 |
| [Neural Shape Deformation Priors](https://ArXiv.org/abs/2210.05616) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2210.05616) | [![Website](https://img.shields.io/badge/Website-9cf)](https://tangjiapeng.github.io/projects/NSDP/) | [![Star](https://img.shields.io/github/stars/tangjiapeng/NSDP.svg?style=social&label=Star)](https://github.com/tangjiapeng/NSDP) | NeurIPS 2022 |
| [ARAPReg: An As-Rigid-As Possible Regularization Loss for Learning Deformable Shape Generators](https://arxiv.org/abs/2108.09432) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2108.09432) | - | [![Star](https://img.shields.io/github/stars/GitBoSun/ARAPReg.svg?style=social&label=Star)](https://github.com/GitBoSun/ARAPReg) | ICCV 2021 |
| [Deforming Radiance Fields with Cages](https://arxiv.org/abs/2207.12298) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2207.12298) | [![Website](https://img.shields.io/badge/Website-9cf)](https://xth430.github.io/deforming-nerf/) | [![Star](https://img.shields.io/github/stars/xth430/deforming-nerf.svg?style=social&label=Star)](https://github.com/xth430/deforming-nerf) | ECCV 2022 |
| [NeuMesh: Learning Disentangled Neural Mesh-based Implicit Field for Geometry and Texture Editing](https://arxiv.org/abs/2207.11911) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2207.11911) | [![Website](https://img.shields.io/badge/Website-9cf)](https://zju3dv.github.io/neumesh/) | [![Star](https://img.shields.io/github/stars/zju3dv/neumesh.svg?style=social&label=Star)](https://github.com/zju3dv/neumesh) | ECCV 2022 |
| [NeuralEditor: Editing Neural Radiance Fields via Manipulating Point Clouds](https://ArXiv.org/abs/2305.03049) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2305.03049) | [![Website](https://img.shields.io/badge/Website-9cf)](https://immortalco.github.io/NeuralEditor/) | [![Star](https://img.shields.io/github/stars/immortalCO/NeuralEditor.svg?style=social&label=Star)](https://github.com/immortalCO/NeuralEditor) | CVPR 2023 |
| [NeRF-Editing: Geometry Editing of Neural Radiance Fields](https://arxiv.org/abs/2205.04978) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2205.04978) | - | [![Star](https://img.shields.io/github/stars/IGLICT/NeRF-Editing.svg?style=social&label=Star)](https://github.com/IGLICT/NeRF-Editing) | CVPR 2022 |
| [Neural Cages for Detail-Preserving 3D Deformations](https://arxiv.org/abs/1912.06395) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/1912.06395) | - | [![Star](https://img.shields.io/github/stars/yifita/deep_cage.svg?style=social&label=Star)](https://github.com/yifita/deep_cage) | CVPR 2020 |
| [SPIDR: SDF-based Neural Point Fields for Illumination and Deformation](https://arxiv.org/abs/2210.08398) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2210.08398) | [![Website](https://img.shields.io/badge/Website-9cf)](https://nexuslrf.github.io/SPIDR_webpage/) | [![Star](https://img.shields.io/github/stars/nexuslrf/SPIDR.svg?style=social&label=Star)](https://github.com/nexuslrf/SPIDR) | ArXiv, 2022, 10 |
| [VolTeMorph: Realtime, Controllable and Generalisable Animation of Volumetric Representations](https://arxiv.org/abs/2208.00949) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2208.00949) | - | - | ArXiv, 2022, 08 |
| [MovingParts: Motion-based 3D Part Discovery in Dynamic Radiance Field](https://ArXiv.org/abs/2303.05703) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2303.05703) | [![Website](https://img.shields.io/badge/Website-9cf)](https://silenkzyoung.github.io/MovingParts-WebPage/) | [![Star](https://img.shields.io/github/stars/SilenKZYoung/MovingParts.svg?style=social&label=Star)](https://github.com/SilenKZYoung/MovingParts) | ArXiv |
 

 ### Cage
 
 
| Title | arXiv | WebSite | Github | Pub. |
|---|---|---|---|---|
| [Neural Cages for Detail-Preserving 3D Deformations](https://arxiv.org/abs/1912.06395) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/1912.06395) | - | [![Star](https://img.shields.io/github/stars/yifita/deep_cage.svg?style=social&label=Star)](https://github.com/yifita/deep_cage) | CVPR 2020 |


### Control point
 
 
| Title | arXiv | WebSite | Github | Pub. |
|---|---|---|---|---|
| [Real-time Locally Injective Volumetric Deformation](https://dl.acm.org/doi/abs/10.1145/3450626.3459794) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://dl.acm.org/doi/abs/10.1145/3450626.3459794) | - | [![Star](https://img.shields.io/github/stars/lwt831/Real-time-Locally-Injective-Volumetric-Deformation.svg?style=social&label=Star)](https://github.com/lwt831/Real-time-Locally-Injective-Volumetric-Deformation) | TOG 2021 |
| [Variational Harmonic Maps for Space Deformation](https://dl.acm.org/doi/10.1145/1531326.1531340) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://dl.acm.org/doi/10.1145/1531326.1531340) | - | - | TOG 2009 |
| [ARAPReg: An As-Rigid-As Possible Regularization Loss for Learning Deformable Shape Generators](https://arxiv.org/abs/2108.09432) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2108.09432) | - | [![Star](https://img.shields.io/github/stars/GitBoSun/ARAPReg.svg?style=social&label=Star)](https://github.com/GitBoSun/ARAPReg) | ICCV 2021 |
| [EditableNeRF: Editing Topologically Varying Neural Radiance Fields by Key Points](https://arxiv.org/abs/2212.04247) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.04247) | [![Website](https://img.shields.io/badge/Website-9cf)](https://chengwei-zheng.github.io/EditableNeRF/) | - | CVPR 2023 |
| [NeRF-Editing: Geometry Editing of Neural Radiance Fields](https://arxiv.org/abs/2205.04978) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2205.04978) | - | [![Star](https://img.shields.io/github/stars/IGLICT/NeRF-Editing.svg?style=social&label=Star)](https://github.com/IGLICT/NeRF-Editing) | CVPR 2022 |
 


 
## Avatar-related editing
 
 
| Title | arXiv | WebSite | Github | Pub. |
|---|---|---|---|---|
| [AvatarStudio: Text-driven Editing of 3D Dynamic Human Head Avatars](https://arxiv.org/abs/2306.00547) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.00547) | [![Website](https://img.shields.io/badge/Website-9cf)](https://vcai.mpi-inf.mpg.de/projects/AvatarStudio/) | - | SIGGRAPH ASIA 2023 |
| [Single-Shot Implicit Morphable Faces with Consistent Texture Parameterization](https://arxiv.org/abs/2305.03043) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.03043) | [![Website](https://img.shields.io/badge/Website-9cf)](https://research.nvidia.com/labs/toronto-ai/ssif/) | - | SIGGRAPH 2023 |
| [CLIPFace: Text-guided Editing of Textured 3D Morphable Models](https://arxiv.org/abs/2212.01406) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.01406) | [![Website](https://img.shields.io/badge/Website-9cf)](https://shivangi-aneja.github.io/projects/clipface/) | [![Star](https://img.shields.io/github/stars/shivangi-aneja/ClipFace.svg?style=social&label=Star)](https://github.com/shivangi-aneja/ClipFace) | SIGGRAPH 2023 |
| [DreamFace: Progressive Generation of Animatable 3D Faces under Text Guidance](https://arxiv.org/abs/2304.03117) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.03117) | [![Website](https://img.shields.io/badge/Website-9cf)](https://sites.google.com/view/dreamface) | - | SIGGRAPH 2023 |
| [AvatarCLIP: Zero-Shot Text-Driven Generation and Animation of 3D Avatars](https://arxiv.org/abs/2205.08535) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2205.08535) | [![Website](https://img.shields.io/badge/Website-9cf)](https://hongfz16.github.io/projects/AvatarCLIP.html) | [![Star](https://img.shields.io/github/stars/hongfz16/AvatarCLIP.svg?style=social&label=Star)](https://github.com/hongfz16/AvatarCLIP) | SIGGRAPH 2022 |
| [FDNeRF: Semantics-Driven Face Reconstruction, Prompt Editing and Relighting with Diffusion Models](https://arxiv.org/abs/2306.00783) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.00783) | - | [![Star](https://img.shields.io/github/stars/BillyXYB/FDNeRF.svg?style=social&label=Star)](https://github.com/BillyXYB/FDNeRF) | NeurIPS 2023 |
| [DeformToon3D: Deformable 3D Toonification from Neural Radiance Fields](https://ArXiv.org/abs/2309.04410) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2309.04410) | [![Website](https://img.shields.io/badge/Website-9cf)](https://www.mmlab-ntu.com/project/deformtoon3d/) | [![Star](https://img.shields.io/github/stars/junzhezhang/DeformToon3D.svg?style=social&label=Star)](https://github.com/junzhezhang/DeformToon3D) | ICCV 2023 |
| [Towards High-Fidelity Text-Guided 3D Face Generation and Manipulation Using only Images](https://ArXiv.org/abs/2308.16758) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2308.16758) | - | - | ICCV 2023 |
| [FaceCLIPNeRF: Text-driven 3D Face Manipulation using Deformable Neural Radiance Fields](https://ArXiv.org/abs/2307.11418) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2307.11418) | [![Website](https://img.shields.io/badge/Website-9cf)](https://faceclipnerf.github.io/) | - | ICCV 2023 |
| [CLIP-Actor: Text-Driven Recommendation and Stylization for Animating Human Meshes](https://arxiv.org/abs/2206.04382) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2206.04382) | [![Website](https://img.shields.io/badge/Website-9cf)](https://clip-actor.github.io/) | [![Star](https://img.shields.io/github/stars/postech-ami/CLIP-Actor.svg?style=social&label=Star)](https://github.com/postech-ami/CLIP-Actor) | ECCV 2022 |
| [Learning Locally Editable Virtual Humans](https://openaccess.thecvf.com/content/CVPR2023/papers/Ho_Learning_Locally_Editable_Virtual_Humans_CVPR_2023_paper.pdf) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://openaccess.thecvf.com/content/CVPR2023/papers/Ho_Learning_Locally_Editable_Virtual_Humans_CVPR_2023_paper.pdf) | [![Website](https://img.shields.io/badge/Website-9cf)](https://custom-humans.github.io/) | [![Star](https://img.shields.io/github/stars/custom-humans/editable-humans.svg?style=social&label=Star)](https://github.com/custom-humans/editable-humans) | CVPR 2023 |
| [MEGANE: Morphable Eyeglass and Avatar Network](https://arxiv.org/abs/2302.04868) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2302.04868) | [![Website](https://img.shields.io/badge/Website-9cf)](https://junxuan-li.github.io/megane/) | - | CVPR 2023 |
| [UV Volumes for Real-time Rendering of Editable Free-view Human Performance](https://ArXiv.org/abs/2203.14402) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2203.14402) | [![Website](https://img.shields.io/badge/Website-9cf)](https://fanegg.github.io/UV-Volumes/) | [![Star](https://img.shields.io/github/stars/fanegg/UV-Volumes.svg?style=social&label=Star)](https://github.com/fanegg/UV-Volumes) | CVPR 2023 |
| [HumanGen: Generating Human Radiance Fields with Explicit Priors](https://ArXiv.org/abs/2212.05321) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2212.05321) | - | - | CVPR 2023 |
| [TECA: Text-Guided Generation and Editing of Compositional 3D Avatars](https://arxiv.org/abs/2309.07125) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2309.07125) | [![Website](https://img.shields.io/badge/Website-9cf)](https://yfeng95.github.io/teca/) | - | ArXiv, 2023, 09 |
| [MagicAvatar: Multimodal Avatar Generation and Animation](https://arxiv.org/abs/2308.14748) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.14748) | [![Website](https://img.shields.io/badge/Website-9cf)](https://magic-avatar.github.io/) | [![Star](https://img.shields.io/github/stars/magic-research/magic-avatar.svg?style=social&label=Star)](https://github.com/magic-research/magic-avatar) | ArXiv, 2023, 08 |
| [HeadSculpt: Crafting 3D Head Avatars with Text](https://arxiv.org/abs/2306.03038) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2306.03038) | [![Website](https://img.shields.io/badge/Website-9cf)](https://brandonhan.uk/HeadSculpt/) | - | ArXiv, 2023, 06 |
| [Control4D: Dynamic Portrait Editing by Learning 4D GAN from 2D Diffusion-based Editor](https://arxiv.org/abs/2305.20082) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.20082) | [![Website](https://img.shields.io/badge/Website-9cf)](https://control4dArXiv.github.io/) | - | ArXiv, 2023, 05 |
| [Rodin: A Generative Model for Sculpting 3D Digital Avatars Using Diffusion](https://arxiv.org/abs/2212.06135) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.06135) | [![Website](https://img.shields.io/badge/Website-9cf)](https://3d-avatar-diffusion.microsoft.com/) | - | ArXiv, 2022, 12 |
| [LatentSwap3D: Semantic Edits on 3D Image GANs](https://ArXiv.org/abs/2212.01381) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2212.01381) | [![Website](https://img.shields.io/badge/Website-9cf)](https://enis.dev/latentswap3d/) | [![Star](https://img.shields.io/github/stars/enisimsar/latentswap3d.svg?style=social&label=Star)](https://github.com/enisimsar/latentswap3d) | ArXiv |
| [Semantic 3D-aware Portrait Synthesis and Manipulation Based on Compositional Neural Radiance Field](https://ArXiv.org/abs/2302.01579) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2302.01579) | - | [![Star](https://img.shields.io/github/stars/TianxiangMa/CNeRF.svg?style=social&label=Star)](https://github.com/TianxiangMa/CNeRF) | AAAI 2023 |
| [TADA! Text to Animatable Digital Avatars](https://arxiv.org/abs/2308.10899) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2308.10899) | [![Website](https://img.shields.io/badge/Website-9cf)](https://tada.is.tue.mpg.de/) | [![Star](https://img.shields.io/github/stars/TingtingLiao/TADA.svg?style=social&label=Star)](https://github.com/TingtingLiao/TADA) | 3DV 2024 |



## Scene editing
 
 
| Title | arXiv | WebSite | Github | Pub. |
|---|---|---|---|---|
| [IntrinsicNeRF: Learning Intrinsic Neural Radiance Fields for Editable Novel View Synthesis](https://ArXiv.org/abs/2303.12074) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2303.12074) | [![Website](https://img.shields.io/badge/Website-9cf)](https://zju3dv.github.io/intrinsic_nerf/) | [![Star](https://img.shields.io/github/stars/zju3dv/IntrinsicNeRF.svg?style=social&label=Star)](https://github.com/zju3dv/IntrinsicNeRF) | ICCV 2023 |
| [Diffusion-based Generation, Optimization, and Planning in 3D Scenes](https://arxiv.org/abs/2301.06015) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2301.06015) | [![Website](https://img.shields.io/badge/Website-9cf)](https://scenediffuser.github.io) | - | CVPR 2023 |
| [I2-SDF: Intrinsic Indoor Scene Reconstruction and Editing via Raytracing in Neural SDFs](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhu_I2-SDF_Intrinsic_Indoor_Scene_Reconstruction_and_Editing_via_Raytracing_in_CVPR_2023_paper.pdf) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://openaccess.thecvf.com/content/CVPR2023/papers/Zhu_I2-SDF_Intrinsic_Indoor_Scene_Reconstruction_and_Editing_via_Raytracing_in_CVPR_2023_paper.pdf) | [![Website](https://img.shields.io/badge/Website-9cf)](https://jingsenzhu.github.io/i2-sdf) | [![Star](https://img.shields.io/github/stars/jingsenzhu/i2-sdf.svg?style=social&label=Star)](https://github.com/jingsenzhu/i2-sdf) | CVPR 2023 |
| [Neural Fields meet Explicit Geometric Representations for Inverse Rendering of Urban Scenes](https://arxiv.org/abs/2304.03266) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2304.03266) | - | - | CVPR 2023 |
| [SIEDOB: Semantic Image Editing by Disentangling Object and Background](https://arxiv.org/abs/2303.13062) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2303.13062) | - | [![Star](https://img.shields.io/github/stars/WuyangLuo/SIEDOB.svg?style=social&label=Star)](https://github.com/WuyangLuo/SIEDOB) | CVPR 2023 |
| [Text2Scene: Text-driven Indoor Scene Stylization with Part-aware Details](https://openaccess.thecvf.com/content/CVPR2023/papers/Hwang_Text2Scene_Text-Driven_Indoor_Scene_Stylization_With_Part-Aware_Details_CVPR_2023_paper.pdf) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://openaccess.thecvf.com/content/CVPR2023/papers/Hwang_Text2Scene_Text-Driven_Indoor_Scene_Stylization_With_Part-Aware_Details_CVPR_2023_paper.pdf) | - | - | CVPR 2023 |
| [NeRFEditor: Differentiable Style Decomposition for Full 3D Scene Editing](https://arxiv.org/abs/2212.03848) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2212.03848) | [![Website](https://img.shields.io/badge/Website-9cf)](https://chuny1.github.io/NeRFEditor/nerfeditor.html) | - | ArXiv 2022 |
| [Set-the-Scene: Global-Local Training for Generating Controllable NeRF Scenes](https://ArXiv.org/abs/2303.13450) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2303.13450) | [![Website](https://img.shields.io/badge/Website-9cf)](https://danacohen95.github.io/Set-the-Scene/) | [![Star](https://img.shields.io/github/stars/DanaCohen95/Set-the-Scene.svg?style=social&label=Star)](https://github.com/DanaCohen95/Set-the-Scene) | ArXiv |

 
 
## 4D editing
 
 
| Title | arXiv | WebSite | Github | Pub. |
|---|---|---|---|---|
| [NeuPhysics: Editable Neural Geometry and Physics from Monocular Videos](https://arxiv.org/abs/2210.12352) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2210.12352) | - | [![Star](https://img.shields.io/github/stars/gaoalexander/neuphysics.svg?style=social&label=Star)](https://github.com/gaoalexander/neuphysics) | NeurIPS 2022 |
| [Text-guided High-definition Consistency Texture Model](https://arxiv.org/abs/2305.05901) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://arxiv.org/abs/2305.05901) | - | - | ArXiv, 2023, 05 |
| [Dyn-E: Local Appearance Editing of Dynamic Neural Radiance Fields](https://ArXiv.org/abs/2307.12909) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](https://ArXiv.org/abs/2307.12909) | [![Website](https://img.shields.io/badge/Website-9cf)](https://dyn-e.github.io/) | - | ArXiv |
| [Make-It-4D: Synthesizing a Consistent Long-Term Dynamic Scene Video from a Single Image](None) | [![arXiv](https://img.shields.io/badge/arXiv-b31b1b.svg)](None) | - | - | ACM MM 2023 |
 
