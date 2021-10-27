# <p align='center'>`awesome indoor panoramic materials`<br>`awesome indoor lighting papers`</p>

Some indoor panoramic datasets and related indoor lighting papers.

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
- [Panoramic Indoor Datasets](#panoramic-indoor-datasets)
- [Other Indoor Datasets](#other-indoor-datasets)
- [Papers using Panoramas](#papers)

## Panoramic Indoor Datasets

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

**360-Indoor.**<br>
360-Indoor: Towards Learning Real-World Objects in 360° Indoor Equirectangular Images<br>
_Shih-Han Chou, Cheng Sun, Wen-Yen Chang, Wan-Ting Hsu, Min Sun, Jianlong Fu_<br>
Proceedings of the IEEE/CVF Winter Conference on Applications of Computer Vision (WACV). 2020.<br>
[[Project](https://aliensunmin.github.io/project/360-dataset/)] [[Data](https://forms.gle/qvNBFHyKX75bThtQA)] 

Features:
- _Real_ indoor scenes
- Information:
  - Object annotations (37 cateogories, incld. light)  
<br>
<!--  -->

**[Structured3D](https://structured3d-dataset.org/) (panoramas).**<br>
Structured3D: A Large Photo-realistic Dataset for Structured 3D Modeling<br>
_Jia Zheng*, Junfei Zhang*, Jing Li, Rui Tang, Shenghua Gao, Zihan Zhou_ <br>
European Conference on Computer Vision (ECCV), 2020<br>
[[Code](https://github.com/bertjiazheng/Structured3D)] [[Paper](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123540494.pdf)] [[Supplementary Material](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123540494-supp.pdf)] [[Benchmark](https://competitions.codalab.org/competitions/24183)]

Features:
- _Synthetic_ indoor scenes 
- 3,500 scenes, 21,835 rooms
- Rendering contains empty/unfurnished (w/ all lights), full(w/ all lights), simple versions(w/ all lights)
- Information: 
  - 2d rendering (raw, cold, wram lighting)
  - normal
  - depth
  - albedo
  - semantic (also annotate light fixtures)
  - structure/layout annotation (wall, ceiling, floor).
<br>

**[Matterport3D](https://niessner.github.io/Matterport/).**<br>
Matterport3D: Learning from RGB-D Data in Indoor Environments<br>
_A. Chang, A. Dai, T. Funkhouser, M. Halber, M. Niessner, M. Savva, S. Song, A. Zeng, Y. Zhang_<br>
International Conference on 3D Vision (3DV 2017)
[[Project](https://niessner.github.io/Matterport/)] [[Code]()] [[Paper](https://arxiv.org/pdf/1709.06158.pdf)]

Features:
- A large-scale RGB-D dataset containing 10,800 panoramic views from 194,400 RGB-D images of 90 building-scale scenes.
- Information:
  - RGB
  - HDR
  - Depth
  - Normal
  - Semantic
  - Camera poses
  - Textured 3D mesh
<br>

**Matterport3D Variants - Im2Pano3D (RGB-D Panorama).**<br>
Im2Pano3D: Extrapolating 360° Structure and Semantics Beyond the Field of View <br>
_Shuran Song, Andy Zeng, Angel X. Chang, Manolis Savva, Silvio Savarese, Thomas Funkhouser_ <br>
Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR). 2018.<br>
[[Project](http://im2pano3d.cs.princeton.edu/)] [[Code](https://github.com/shurans/im2pano3d/)] [[Paper](https://arxiv.org/abs/1712.04569)]

Features:
- Generate RGB-D Panorama imaes from SUNCG dataset(Not available now) and [Matterport](https://niessner.github.io/Matterport/) dataset.
- Information:
  -  color image
  -  semantic segmentation
  -  depth
  -  plane encoding (plane distance and surface normal)
<br>

**[ZInD](https://github.com/zillow/zind).**<br>
Zillow Indoor Dataset: Annotated Floor Plans With 360º Panoramas and 3D Room Layouts <br>
_Steve Cruz*, Will Hutchcroft*, Yuguang Li, Naji Khosravan, Ivaylo Boyadzhiev, Sing Bing Kang_ <br>
Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2021<br>
[[Paper](https://openaccess.thecvf.com/content/CVPR2021/papers/Cruz_Zillow_Indoor_Dataset_Annotated_Floor_Plans_With_360deg_Panoramas_and_CVPR_2021_paper.pdf)]
[[Supplementary Material](https://openaccess.thecvf.com/content/CVPR2021/supplemental/Cruz_Zillow_Indoor_Dataset_CVPR_2021_supplemental.pdf)]

Features:
- _Real_ residential rooms
- 1575 scenes (71,474 panoramas in 1524 unfurnished rediential homes)
- Unfurnished rooms (decorated with basic lights, e.g. ceilling lamps)
- Information:
  - Panoramas of daytime captures with lights on
  - Layout annotation (wall, ceilling, floor, window, door)
  - Floor plans (raster, vector)
  
<br>

## Other Indoor Datasets

**[InteriorNet](https://interiornet.org/) (LARGE)**<br>
InteriorNet: Mega-scale Multi-sensor Photo-realistic Indoor Scenes Dataset<br>
Wenbin Li, Sajad Saeedi, John McCormac, Ronald Clark, Dimos Tzoumanikas, Qing Ye, Yuzhong Huang, Rui Tang and Stefan Leutenegger <br>
British Machine Vision Conference (BMVC), 2018. <br>
[[Project](https://interiornet.org/)] [[Paper](https://interiornet.org/items/interiornet_paper.pdf)]

Features:
- Professional designed indoor CAD models
- 10,000 scenes
- 1.7 million rooms 
- Released dataset (consisting of the rendered sequences and images) as well as ExaRenderer, ViSim, and a subset of the 3D models and layouts used for evaluations.
- Information:
  - rendered perpective sequences and **panoramas** (pano: except for HD7)
  - rearrangement
  - random lighting
  - depth
  - semantic instance
  - semantic class segmentation.

The InteriorNet dataset is split into the following: (ref: [InteriorNet2ROSBag](https://github.com/ethz-asl/interiornet_to_rosbag))
1. 705 scenes with 3 ground truth trajectories and IMU data, color and depth images, ground truth instance images, with 1000 frames each, at 25 frames per second. Each trajectory is available in regular lighting and random lighting. *[HD1-HD6]*


2. 20000 scenes with 20 random views containing ground truth camera pose, color and depth images and ground truth instance and object class images. These views are also available in both regular lighting and random lighting. *[HD7]*


**[Replica](https://github.com/facebookresearch/Replica-Dataset).**<br>
The Replica dataset: A digital replica of indoor spaces<br>
Julian Straub and Thomas Whelan and Lingni Ma and Yufan Chen and Erik Wijmans and Simon Green and Jakob J. Engel and Raul Mur-Artal and Carl Ren and Shobhit Verma and Anton Clarkson and Mingfei Yan and Brian Budge and Yajie Yan and Xiaqing Pan and June Yon and Yuyang Zou and Kimberly Leon and Nigel Carter and Jesus Briales and  Tyler Gillingham and  Elias Mueggler and Luis Pesqueira and Manolis Savva and Dhruv Batra and Hauke M. Strasdat and Renzo De Nardi and Michael Goesele and Steven Lovegrove and Richard Newcombe  <br>
arXiv, 2019. <br>
[[Code](https://github.com/facebookresearch/Replica-Dataset)] [[Paper](https://arxiv.org/abs/1906.05797)]

Features:
- 18 3D reconstructed scenes
- provide own renderer: ReplicaRenderer 
- Information:
  - 3D mesh 
  - Some surface materials such as glass, mirrors
  - Texture
  - 3D segmentation
  - ReplicaRenderer


## Papers
### Lighting related papers using panoramas
**Learning to Estimate Indoor Lighting from 3D Objects**<br>
_Weber, Henrique, Donald Prévost, and Jean-François Lalonde_.<br>
International Conference on 3D Vision (3DV). IEEE, 2018.<br>
[[Code](https://github.com/weberhen/learning_indoor_lighting)] [[Project](http://vision.gel.ulaval.ca/~jflalonde/publications/projects/illumPredict/index.html)] [[Paper](https://arxiv.org/abs/1806.03994)]

**Deep Parametric Indoor Lighting Estimation**<br>
_Marc-Andre Gardner, Yannick Hold-Geoffroy, Kalyan Sunkavalli, Christian Gagne, Jean-Francois Lalonde_. <br>
In Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV) 2019.<br>
[[Reproduce Code](https://github.com/WinterCyan/Gardner2019)] [[Paper](https://openaccess.thecvf.com/content_ICCV_2019/html/Gardner_Deep_Parametric_Indoor_Lighting_Estimation_ICCV_2019_paper.html)]

**Deep Lighting Environment Map Estimation from Spherical Panoramas**<br>
_Gkitsas, V., Zioulis, N., Alvarez, F., Zarpalas, D., & Daras, P._<br>
In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops (CVPRW), 2020.<br>
[[Code](https://github.com/VCL3D/DeepPanoramaLighting)] [[Project](https://vcl3d.github.io/DeepPanoramaLighting/)] [[Paper](https://openaccess.thecvf.com/content_CVPRW_2020/papers/w38/Gkitsas_Deep_Lighting_Environment_Map_Estimation_From_Spherical_Panoramas_CVPRW_2020_paper.pdf)]

**[hot:fire:] Lighthouse: Predicting Lighting Volumes for Spatially-Coherent Illumination**<br>
_Pratul P. Srinivasan, Ben Mildenhall, Matthew Tancik, Jonathan T. Barron, Richard Tucker, Noah Snavely._ <br>
In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2020. <br>
[[Code](https://github.com/pratulsrinivasan/lighthouse)] [[Paper](https://openaccess.thecvf.com/content_CVPR_2020/html/Srinivasan_Lighthouse_Predicting_Lighting_Volumes_for_Spatially-Coherent_Illumination_CVPR_2020_paper.html)]
- I/O: panoramas, panoramic lighting map
- Input: stereo pair of RGB images
- Outpu: a multiscale RGBA lighting volume
- Data: InteriorNet

**[hot:fire:] Inverse Rendering for Complex Indoor Scenes: Shape, Spatially-Varying Lighting and SVBRDF from a Single Image** <br>
_Zhengqin Li, Mohammad Shafiei, Ravi Ramamoorthi, Kalyan Sunkavalli, Manmohan Chandraker._ <br>
In Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR) 2020. <br>
[[Code and Data](https://github.com/lzqsd/InverseRenderingOfIndoorScene)] [[Project](http://cseweb.ucsd.edu/~viscomp/projects/CVPR20InverseIndoor/)]
- Data: OpenRooms (CVPR2021)

**HDR Environment Map Estimation for Real-Time Augmented Reality**<br>
_Gowri Somanath, Daniel Kurz._
Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR), 2021.<br>
[[Code](https://github.com/apple/ml-envmapnet)] [[Project](https://machinelearning.apple.com/research/hdr-environment-map-estimation)] [[Paper](https://openaccess.thecvf.com/content/CVPR2021/html/Somanath_HDR_Environment_Map_Estimation_for_Real-Time_Augmented_Reality_CVPR_2021_paper)]
- I/O: LDR normal single image; HDR panoramic environmental map
- Data: Laval HDR Database

**Lighting, Reflectance and Geometry Estimation from 360° Panoramic Stereo**<br>
_Li, Junxuan, Hongdong Li, and Yasuyuki Matsushita._ <br>
Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR). 2021.
[[Code](https://github.com/junxuan-li/LRG_360Panoramic)] [[Paper](https://openaccess.thecvf.com/content/CVPR2021/html/Li_Lighting_Reflectance_and_Geometry_Estimation_From_360deg_Panoramic_Stereo_CVPR_2021_paper)]
- I/O: two (top+bottom) **stereo** panoramas (and predicted depth); panoramic lighting, reflectance and geometry estimation
- Dataset: Structured3D panoramas (training), [360SD-Net](https://albert100121.github.io/360SD-Net-Project-Page/) (stereo input, depth estimation)

