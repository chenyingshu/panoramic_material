# <p align='center'>`awesome indoor panoramic materials`</p>
Some indoor panoramic datasets and related papers.

<!-- ## Contributing

If you think I have missed out on something (or) have any suggestions (papers, implementations and other resources), feel free to [pull a request](https://github.com/chenyingshu/panoramic_material/pulls)

Feedback and contributions are welcome!

markdown format:
``` markdown
**Here is the Paper Name.**<br>
*[Author 1](homepage), Author 2, and Author 3.*<br>
Conference or Journal Year. [[PDF](link)] [[Project](link)] [[Github](link)] [[Video](link)] [[Data](link)]
``` -->

## Table of Contents
- [Panoramic Datasets](#panoramic-datasets)
- [Papers using Panoramas](#papers)

## Panoramic Datasets

**[Laval HDR database](http://indoor.hdrdb.com/).**<br>
Learning to Predict Indoor Illumination from a Single Image <br>
_Gardner, M.-A., Sunkavalli, K., Yumer, E., Shen, X., Gambaretto, E., Gagné, C., and Lalonde, J.F._ <br>
ACM Transactions on Graphics (SIGGRAPH Asia), 9(4), 2017.<br>
[[Paper](https://dl.acm.org/doi/10.1145/3130800.3130891)] [[Project](http://vision.gel.ulaval.ca/~jflalonde/publications/projects/deepIndoorLight/)] [[HDR Data](http://indoor.hdrdb.com/)] [[SUN360 Data Info](http://vision.gel.ulaval.ca/~jflalonde/publications/projects/deepIndoorLight/#data)]

Features:
- _Real_ indoor scenes.
- 2100+ high resolution and fully HDR indoor panoramas, captured using a Canon 5D Mark III and a robotic panoramic tripod head.
- Diverse lighting conditions.
- Around 400 light sources hand-labeled LDR panoramas (SUN360).
<br>

**360-Indoor**
360-Indoor: Towards Learning Real-World Objects in 360° Indoor Equirectangular Images<br>
_Shih-Han Chou, Cheng Sun, Wen-Yen Chang, Wan-Ting Hsu, Min Sun, Jianlong Fu_<br>
Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision (WACV). 2020.<br>
[[Project](https://aliensunmin.github.io/project/360-dataset/)] [[Data](https://forms.gle/qvNBFHyKX75bThtQA)]

Features:
- _Real_ indoor scenes
- Information:
  - Object annotations (37 cateogories, incld. light)  

**Im2Pano3D (RGB-D Panorama).**
Im2Pano3D: Extrapolating 360° Structure and Semantics Beyond the Field of View <br>
_Shuran Song, Andy Zeng, Angel X. Chang, Manolis Savva, Silvio Savarese, Thomas Funkhouser_ <br>
[[Project](http://im2pano3d.cs.princeton.edu/)]

<br>

**[Structured3D](https://structured3d-dataset.org/) (panoramas).**<br>
Structured3D: A Large Photo-realistic Dataset for Structured 3D Modeling<br>
_Jia Zheng*, Junfei Zhang*, Jing Li, Rui Tang, Shenghua Gao, Zihan Zhou_ <br>
European Conference on Computer Vision (ECCV), 2020<br>
[[Code](https://github.com/bertjiazheng/Structured3D)] [[Paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123540494.pdf)] [[Supplementary Material](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123540494-supp.pdf)] [[Benchmark](https://competitions.codalab.org/competitions/24183)]

Features:
- _Synthetic_ indoor scenes 
- 
- Rendering contains empty/unfurnished (w/ all lights), full(w/ all lights), simple versions(w/ all lights)
- Information: 
  - 2d rendering (raw, cold, wram lighting)
  - normal
  - depth
  - albedo
  - semantic (also annotate light fixtures)
  - structure/layout annotation (wall, ceiling, floor).
<br>

**Matterport3D**

**Matterport3D Variants**

**[ZInD](https://github.com/zillow/zind).**<br>
Zillow Indoor Dataset: Annotated Floor Plans With 360º Panoramas and 3D Room Layouts <br>
_Steve Cruz*, Will Hutchcroft*, Yuguang Li, Naji Khosravan, Ivaylo Boyadzhiev, Sing Bing Kang_ <br>
Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2021<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Cruz_Zillow_Indoor_Dataset_Annotated_Floor_Plans_With_360deg_Panoramas_and_CVPR_2021_paper.pdf)]
[[Supplementary Material](https://openaccess.thecvf.com/content/CVPR2021/supplemental/Cruz_Zillow_Indoor_Dataset_CVPR_2021_supplemental.pdf)]

Features:
- _Real_ residential rooms
- 1575 scenes
- Unfurnished rooms (decorated with basic lights, e.g. ceilling lamps)
- Information:
  - Panoramas of daytime captures with lights on
  - Layout annotation (wall, ceilling, floor, window, door)
  - Floor plans (raster, vector)
  
<br>

## Papers
