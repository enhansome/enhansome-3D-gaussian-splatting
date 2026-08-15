# Awesome 3D Gaussian Splatting with stars

<div align="center">
  A curated collection of resources focused on 3D Gaussian Splatting (3DGS) and related technologies.

[**Browse the Paper List**](https://mrnerf.github.io/awesome-3D-gaussian-splatting/) | [**LichtFeld Studio**](https://lichtfeld.io) | [**Contribute**](CONTRIBUTING.md) | [**MrNeRF**](https://www.mrnerf.com)

</div>

## Contents

* [Papers & Documentation](#papers--documentation)
* [Implementations](#implementations)
* [Viewers & Game Engine Support](#viewers--game-engine-support)
* [Tools & Utilities](#tools--utilities)
* [Learning Resources](#learning-resources)
* [Credits](#credits)

## Papers & Documentation

### Papers Database

Visit our comprehensive, searchable database of 3D Gaussian Splatting papers:
[Papers Database](https://mrnerf.github.io/awesome-3D-gaussian-splatting/)

### Courses & Tutorials

* [MIT Inverse Rendering Lectures (Module 2)](https://www.scenerepresentations.org/courses/inverse-graphics-23/) - Academic deep dive into inverse rendering
* [3DGS Tutorial](https://3dgstutorial.github.io/) - Tutorial from the authors of the original 3DGS paper

### Datasets

* [NERDS 360 Multi-View dataset](https://zubair-irshad.github.io/projects/neo360.html) - High-quality outdoor scene dataset

## Implementations

### Official Reference

* [Original Gaussian Splatting](https://github.com/graphdeco-inria/gaussian-splatting) ⭐ 22,955 | 🐛 713 | 🌐 Python | 📅 2025-10-17 - The reference implementation by the original authors

### Community Implementations

| Implementation                                                                                                                                     | Language       | License    | Description                                                                                                                                                                 |
| -------------------------------------------------------------------------------------------------------------------------------------------------- | -------------- | ---------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [LichtFeld Studio](https://github.com/MrNeRF/LichtFeld-Studio) ⭐ 3,526 \| 🐛 174 \| 🌐 C++ \| 📅 2026-08-15 ([lichtfeld.io](https://lichtfeld.io)) | C++/CUDA       | GPL-3.0    | The modular workstation for 3D Gaussian Splatting — train, inspect, edit, automate, and export from a single native app                                                     |
| [Nerfstudio gsplat](https://github.com/nerfstudio-project/gsplat) ⭐ 5,539 \| 🐛 359 \| 🌐 Python \| 📅 2026-08-15                                  | Python/CUDA    | Apache-2.0 | Integration with Nerfstudio                                                                                                                                                 |
| [OpenSplat](https://github.com/pierotofy/OpenSplat) ⭐ 2,144 \| 🐛 38 \| 🌐 C++ \| 📅 2026-08-14                                                    | C++/CPU/GPU    | AGPL-3.0   | Cross-platform solution                                                                                                                                                     |
| [Taichi 3D GS](https://github.com/wanmeihuali/taichi_3d_gaussian_splatting) ⭐ 753 \| 🐛 38 \| 🌐 Jupyter Notebook \| 📅 2024-03-12                 | Taichi         | Apache-2.0 | Taichi-based implementation                                                                                                                                                 |
| [taichi-splatting](https://github.com/uc-vision/taichi-splatting) ⭐ 120 \| 🐛 6 \| 🌐 Python \| 📅 2025-11-25                                      | Taichi/PyTorch | Apache-2.0 | Modular rasterizer for Taichi and PyTorch                                                                                                                                   |
| [Grendel Distributed 3DGS](https://github.com/nyu-systems/Grendel-GS) ⭐ 682 \| 🐛 36 \| 🌐 Python \| 📅 2025-09-24                                 | Python/CUDA    | Apache-2.0 | Multi-GPU distributed training                                                                                                                                              |
| [Warp 3DGS](https://github.com/guoriyue/3dgs-warp-scratch) ⭐ 284 \| 🐛 0 \| 🌐 Python \| 📅 2025-09-28                                             | Warp/Python    | AGPL-3.0   | Warp-based implementation                                                                                                                                                   |
| [RI3D](https://github.com/Asus-Monitor/ri3d-impl) ⭐ 5 \| 🐛 0 \| 🌐 Python \| 📅 2026-05-10                                                        | Python/CUDA    | Unlicense  | Few-shot gaussian splatting pipeline                                                                                                                                        |
| [gaussian\_splatting](https://github.com/joeyan/gaussian_splatting) ⭐ 235 \| 🐛 9 \| 🌐 Python \| 📅 2025-09-19                                    | Python/CUDA    | MIT        | Readable implementation with a [written derivation of the math](https://github.com/joeyan/gaussian_splatting/blob/main/MATH.md) ⭐ 235 \| 🐛 9 \| 🌐 Python \| 📅 2025-09-19 |
| [3d-gaussian-splatting](https://github.com/WangFeng18/3d-gaussian-splatting) ⭐ 370 \| 🐛 6 \| 🌐 Python \| 📅 2024-10-25                           | Python/CUDA    | MIT        | Compact reimplementation                                                                                                                                                    |
| [gaussian\_splatting\_3d](https://github.com/heheyas/gaussian_splatting_3d) ⭐ 42 \| 🐛 3 \| 🌐 Jupyter Notebook \| 📅 2023-07-27                   | Python/CUDA    |            | Early community reimplementation                                                                                                                                            |
| [My-exp-Gaussians](https://github.com/ingra14m/My-exp-Gaussian) ⭐ 125 \| 🐛 1 \| 🌐 Python \| 📅 2024-03-26                                        | Python/CUDA    |            | Enhances the ability of 3D Gaussians to model complex scenes                                                                                                                |
| [360-gaussian-splatting](https://github.com/inuex35/360-gaussian-splatting) ⭐ 224 \| 🐛 0 \| 🌐 Python \| 📅 2024-09-29                            | Python         |            | Trains splats directly from 360° images                                                                                                                                     |
| [2D Gaussian Splatting](https://github.com/OutofAi/2D-Gaussian-Splatting) ⭐ 455 \| 🐛 5 \| 🌐 Jupyter Notebook \| 📅 2025-03-03                    | Jupyter        | MIT        | Notebook walkthrough of 2D gaussian splatting                                                                                                                               |
| [DGSO](https://github.com/An-u-rag/stylized-gaussian-splatting) ⭐ 29 \| 🐛 1 \| 🌐 Python \| 📅 2024-05-09                                         | Python         | MIT        | Style transfer applied during gaussian optimization                                                                                                                         |

### Frameworks

* [GauStudio](https://github.com/GAP-LAB-CUHK-SZ/gaustudio) ⭐ 1,762 | 🐛 34 | 🌐 Jupyter Notebook | 📅 2025-11-05 - Unified framework with multiple implementations
* [DriveStudio](https://github.com/ziyc/drivestudio) ⭐ 1,249 | 🐛 55 | 🌐 Python | 📅 2025-08-27 - Urban scene reconstruction framework
* [gaussian-splatting-lightning](https://github.com/yzslab/gaussian-splatting-lightning) ⭐ 1,092 | 🐛 32 | 🌐 Jupyter Notebook | 📅 2026-05-25 - Derived algorithms plus an interactive web viewer
* [Pointrix](https://github.com/pointrix-project/pointrix) ⭐ 218 | 🐛 5 | 🌐 Python | 📅 2025-03-31 - Differentiable point-based rendering
* [msplat](https://github.com/pointrix-project/msplat) ⭐ 216 | 🐛 3 | 🌐 Cuda | 📅 2024-07-28 - Modular differential gaussian rasterization library
* [GSCodecStudio](https://github.com/JasonLSC/GSCodec_Studio) ⭐ 140 | 🐛 1 | 🌐 Python | 📅 2025-11-13 - Compression and Dynamic splattings

## Viewers & Game Engine Support

### Game Engines

* [PlayCanvas Engine](https://github.com/playcanvas/engine) ⭐ 16,490 | 🐛 539 | 🌐 JavaScript | 📅 2026-08-15
* [Unity Plugin](https://github.com/aras-p/UnityGaussianSplatting) ⭐ 3,383 | 🐛 43 | 🌐 C# | 📅 2025-10-17
* [Unreal Plugin (XScene-UEPlugin)](https://github.com/xverse-engine/XScene-UEPlugin) ⭐ 1,122 | 🐛 100 | 🌐 C++ | 📅 2025-07-30
* [Unity Plugin (gsplat-unity)](https://github.com/wuyize25/gsplat-unity) ⭐ 270 | 🐛 14 | 🌐 C# | 📅 2026-08-02
* [Godot Plugin (gdgs)](https://github.com/ReconWorldLab/godot-gaussian-splatting) ⭐ 269 | 🐛 3 | 🌐 GDScript | 📅 2026-07-30 - Real-time 3DGS rendering plugin for Godot 4.3+
* [Unreal Plugin (MLSLabsGaussianSplattingRenderer-UE)](https://github.com/mlslabs/MLSLabsGaussianSplattingRenderer-UE) ⭐ 258 | 🐛 3 | 🌐 C++ | 📅 2026-07-25
* [Unity Plugin (DynGsplat-unity)](https://github.com/HiFi-Human/DynGsplat-unity) ⭐ 105 | 🐛 4 | 🌐 C# | 📅 2025-12-27 - For dynamic splattings

### Web Viewers

**WebGL**

* [Splat Viewer](https://github.com/antimatter15/splat) ⭐ 3,057 | 🐛 37 | 🌐 JavaScript | 📅 2025-11-16
* [GaussianSplats3D](https://github.com/mkkellogg/GaussianSplats3D) ⭐ 2,859 | 🐛 97 | 🌐 JavaScript | 📅 2025-10-19
* [gsplat.js](https://github.com/huggingface/gsplat.js) ⭐ 1,653 | 🐛 42 | 🌐 TypeScript | 📅 2026-05-26
* [PlayCanvas Model Viewer](https://github.com/playcanvas/model-viewer) ⭐ 704 | 🐛 19 | 🌐 TypeScript | 📅 2026-08-13
* [Gauzilla](https://github.com/BladeTransformerLLC/gauzilla) ⭐ 634 | 🐛 0 | 🌐 JavaScript | 📅 2025-05-23
* [SuperSplat Viewer](https://github.com/playcanvas/supersplat-viewer) ⭐ 536 | 🐛 34 | 🌐 TypeScript | 📅 2026-08-15
* [Interactive Viewer](https://github.com/kishimisu/Gaussian-Splatting-WebGL) ⭐ 270 | 🐛 5 | 🌐 JavaScript | 📅 2024-03-21
* [A-Frame](https://github.com/quadjr/aframe-gaussian-splatting) ⭐ 227 | 🐛 9 | 🌐 JavaScript | 📅 2023-12-20
* [splaTV](https://github.com/antimatter15/splaTV) ⭐ 171 | 🐛 5 | 🌐 JavaScript | 📅 2024-03-26 - Viewer for 4D Gaussians, with a [live demo](http://antimatter15.com/splaTV/)
* [WebRTC viewer](https://github.com/dylanebert/gaussian-viewer) ⭐ 133 | 🐛 5 | 🌐 Python | 📅 2023-09-09

**WebGPU**

* [EPFL Viewer](https://github.com/cvlab-epfl/gaussian-splatting-web) ⭐ 666 | 🐛 12 | 🌐 TypeScript | 📅 2024-03-13
* [WebGPU Splat](https://github.com/KeKsBoTer/web-splat) ⭐ 292 | 🐛 14 | 🌐 Rust | 📅 2026-03-31
* [gaussian-splatting-webgpu](https://github.com/MarcusAndreasSvensson/gaussian-splatting-webgpu) ⭐ 90 | 🐛 7 | 🌐 TypeScript | 📅 2024-06-25

### Desktop Viewers

* [Nerfstudio Viser](https://github.com/viser-project/viser) ⭐ 2,735 | 🐛 111 | 🌐 Python | 📅 2026-08-14
* [splatviz](https://github.com/Florian-Barthel/splatviz) ⭐ 1,546 | 🐛 12 | 🌐 Python | 📅 2026-05-20 - Edit the rendering code at runtime or display multiple scenes at once
* [3DGS.cpp](https://github.com/shg8/3DGS.cpp) ⭐ 779 | 🐛 16 | 🌐 C++ | 📅 2025-05-19 - C++/Vulkan renderer for Windows, macOS, Linux, iOS and visionOS
* [OpenGL Viewer](https://github.com/limacv/GaussianSplattingViewer) ⭐ 448 | 🐛 15 | 🌐 Python | 📅 2024-06-11 - PyOpenGL viewer, also with official CUDA backend
* [vkgs](https://github.com/jaesung-cs/vkgs) ⭐ 159 | 🐛 3 | 🌐 C++ | 📅 2026-07-17 - Cross-platform C++/Vulkan renderer
* [Nerfstudio (gaussian\_splatting branch)](https://github.com/yzslab/nerfstudio/tree/gaussian_splatting) ⭐ 157 | 🐛 3 | 🌐 Python | 📅 2024-06-28
* [Jupyter notebook viewer](https://github.com/shumash/gaussian-splatting/blob/mshugrina/interactive/interactive.ipynb) ⭐ 28 | 🐛 0 | 🌐 Python | 📅 2024-07-17
* [Taichi Viewer](https://github.com/uc-vision/splat-viewer) ⭐ 27 | 🐛 0 | 🌐 Python | 📅 2025-10-06 - Renderer with benchmarking capability
* [LiteViz-GS](https://github.com/panxkun/liteviz-gs) ⭐ 18 | 🐛 0 | 🌐 C++ | 📅 2025-06-15
* [DearGaussianGUI](https://github.com/leviome/DearGaussianGUI) ⭐ 15 | 🐛 0 | 🌐 Python | 📅 2025-05-15

### Native Applications

* [Blender Add-on (KIRI)](https://github.com/Kiri-Innovation/3dgs-render-blender-addon) ⭐ 1,141 | 🐛 1 | 🌐 Python | 📅 2026-08-13
* [Blender Add-on](https://github.com/ReshotAI/gaussian-splatting-blender-addon) ⭐ 586 | 🐛 31 | 🌐 Python | 📅 2024-08-30
* [iOS Metal Viewer](https://github.com/laanlabs/metal-splats) ⭐ 364 | 🐛 8 | 🌐 Swift | 📅 2023-10-22
* [ROS2 Support](https://github.com/shadygm/ROSplat) ⭐ 260 | 🐛 2 | 🌐 Python | 📅 2026-06-19
* [VR Support (OpenXR)](https://github.com/hyperlogic/splatapult) ⭐ 229 | 🐛 8 | 🌐 C++ | 📅 2024-10-16
* [Houdini Viewport Renderer](https://github.com/rubendhz/houdini-gsplat-renderer) ⭐ 120 | 🐛 0 | 🌐 C | 📅 2025-08-07 - HDK/GLSL implementation of Gaussian Splatting in Houdini
* [Blender Add-on (404—GEN)](https://github.com/404-Repo/404-gen-blender-add-on) ⭐ 28 | 🐛 0 | 🌐 Python | 📅 2026-05-22

## Tools & Utilities

### Data Processing

* [SplatTransform](https://github.com/playcanvas/splat-transform) ⭐ 1,292 | 🐛 27 | 🌐 TypeScript | 📅 2026-08-10 - CLI tool for converting and editing splats
* [3DGS Converter](https://github.com/francescofugazzi/3dgsconverter) ⭐ 590 | 🐛 0 | 🌐 Python | 📅 2026-08-01 - Format conversion tool
* [Kapture](https://github.com/naver/kapture) ⭐ 542 | 🐛 0 | 🌐 Python | 📅 2026-04-17 - Unified data format for visual localization
* [gsbox Converter](https://github.com/gotoeasy/gsbox) ⭐ 191 | 🐛 2 | 🌐 Go | 📅 2026-06-18 - PLY SPLAT SPZ SPX conversion tool
* [GaussForge](https://github.com/3dgscloud/GaussForge) ⭐ 62 | 🐛 1 | 🌐 C++ | 📅 2026-05-25 - C++/WASM-based conversion between PLY, SPZ, SPLAT, and KSPLAT
* [VGGT Factor Refinement](https://github.com/jashshah999/vggt-factor-refinement) ⭐ 49 | 🐛 1 | 🌐 Python | 📅 2026-06-16 - COLMAP-free pipeline using VGGT + factor graph, from video to COLMAP-format output
* [SpectacularAI](https://github.com/SpectacularAI/point-cloud-tools) ⭐ 48 | 🐛 1 | 🌐 Python | 📅 2026-03-28 - Conversion scripts for different 3DGS conventions
* [Point Cloud Editor](https://github.com/JohannesKrueger/pointcloudeditor) ⭐ 23 | 🐛 1 | 🌐 HTML | 📅 2024-10-12 - Web-based point cloud editing
* [SPZ Converter](https://github.com/stytim/spz) ⭐ 21 | 🐛 0 | 🌐 C++ | 📅 2025-01-16 - SPZ conversion tool
* [splatreg](https://github.com/Archerkattri/splatreg) ⭐ 13 | 🐛 0 | 🌐 Python | 📅 2026-07-25 - pip-installable splat registration: align & merge two 3DGS scans into one SE(3)/Sim(3) frame (recovers scale), CLI + pure-PyTorch API, no manual gizmo
* [AURA](https://github.com/Archerkattri/aura) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2026-07-25 - Calibrated per-splat confidence for 3DGS assets: held-out reliability labels, isotonic calibration, and a distribution-free conformal pruning certificate with a certified LOD ladder; exports via glTF/OpenUSD/SPZ (pip install aura-splat)
* [Kapture image cropper](https://gist.github.com/jo-chemla/258e6e40d3d6c2220b29518ff3c17c40) - Undistorted image cropper to remove black borders

### Development Tools

* [SuperSplat](https://github.com/playcanvas/supersplat) ⭐ 9,854 | 🐛 109 | 🌐 TypeScript | 📅 2026-08-13 - Browser-based 3DGS editor
* [GSOPs for Houdini](https://github.com/cgnomads/GSOPs) ⭐ 613 | 🐛 0 | 🌐 Python | 📅 2026-08-14 - Houdini integration tools
* [camorph](https://github.com/Fraunhofer-IIS/camorph) ⭐ 118 | 🐛 3 | 🌐 Python | 📅 2025-07-10 - Camera parameter conversion

## Learning Resources

### Blog Posts

* [Discussion about gs universal format](https://github.com/mkkellogg/GaussianSplats3D/issues/47#issuecomment-1801360116) ⭐ 2,859 | 🐛 97 | 🌐 JavaScript | 📅 2025-10-19
* [Implementation Details](https://github.com/kwea123/gaussian_splatting_notes) ⭐ 603 | 🐛 0 | 📅 2023-11-12 - Technical deep dive
* [Mathematical details of forward and backward passes](https://github.com/joeyan/gaussian_splatting/blob/main/MATH.md) ⭐ 235 | 🐛 9 | 🌐 Python | 📅 2025-09-19
* [Mathematical Foundation](https://github.com/chiehwangs/3d-gaussian-theory) ⭐ 139 | 🐛 1 | 📅 2024-11-16 - Theory explanation
* [3DGS Introduction](https://huggingface.co/blog/gaussian-splatting) - HuggingFace guide
* [Comprehensive overview of Gaussian Splatting](https://towardsdatascience.com/a-comprehensive-overview-of-gaussian-splatting-e7d570081362)
* [Very good (technical) intro to 3D Gaussian Splatting](https://medium.com/@AriaLeeNotAriel/numbynum-3d-gaussian-splatting-for-real-time-radiance-field-rendering-kerbl-et-al-60c0b25e5544)
* [Gaussian Splatting is pretty cool](https://aras-p.info/blog/2023/09/05/Gaussian-Splatting-is-pretty-cool/)
* [Making Gaussian Splats smaller](https://aras-p.info/blog/2023/09/13/Making-Gaussian-Splats-smaller/)
* [Making Gaussian Splats more smaller](https://aras-p.info/blog/2023/09/27/Making-Gaussian-Splats-more-smaller/)
* [Compressing Gaussian Splats](https://blog.playcanvas.com/compressing-gaussian-splats/)
* [PyTorch Implementation](https://myasincifci.github.io/) - Curated implementation of Vanilla 3DGS in PyTorch
* [NeRFs vs. 3DGS](https://edwardahn.me/writing/NeRFvs3DGS/)
* [Gaussian Head Avatars: A Summary](https://towardsdatascience.com/gaussian-head-avatars-a-summary-2bd17bd48500)
* [3D in Geospatial: NeRFs, Gaussian Splatting, and Spatial Computing](https://ckoziol.com/blog/2024/radiance_methods/)
* [Capture Guide](https://medium.com/@heyulei/capture-images-for-gaussian-splatting-81d081bbc826) - Image capture tutorial

### Talks

* [Gaussian Splats: Ready for Standardization?](https://www.youtube.com/watch?v=0xdPpKSkO3I) - Metaverse Standards Forum 1/28/2025
* [Unity Integration Guide](https://www.youtube.com/watch?v=pM_HV2TU4rU\&t=5298s) - Metaverse Standards Forum 5/6/2025

### Video Tutorials

* [Getting Started (Windows)](https://youtu.be/UXtuigy_wYc)
* [Two-Minute Explanation](https://youtu.be/HVv_IQKlafQ)
* [Computerphile 3DGS explanation](https://youtu.be/VkIJbpdTujE)
* [Gaussian Splats Town Hall - Part 2](https://youtu.be/5_GaPYBHqOo)
* [Intro to gaussian splatting (and Unity plugin)](https://www.xuanprada.com/blog/2023/10/22/intro-to-gaussian-splatting)
* [Jupyter Tutorial](https://www.youtube.com/watch?v=OcvA7fmiZYM)

## Credits

* Thanks to [Leonid Keselman](https://github.com/leonidk) for informing me about the release of the paper "Real-time Photorealistic Dynamic Scene Representation and Rendering with 4D Gaussian Splatting".
* Thanks to [Eric Haines](https://github.com/erich666) for suggesting the jupyter notebook viewer, windows tutorial and for fixing text hyphenations and other issues.
* Thanks to [Henry Pearce](https://github.com/henrypearce4D) for maintaining contributions.
* [Yehe Liu](https://x.com/YeheLiu)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-15._
