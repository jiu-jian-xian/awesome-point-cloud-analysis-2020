# awesome-point-cloud-analysis [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

for anyone who wants to do research about 3D point cloud.   

If you find the awesome paper/code/dataset or have some suggestions, please contact linhua2017@ia.ac.cn. Thanks for your valuable contribution to the research community :smiley:   

<h1> 

```diff
- Recent papers (from 2017)
```

</h1>

# Table of Contents

- [2017](#2017)
- [2018](#2018)
- [2019](#2019)
- [2020](#2020)

<h3> Keywords </h3>

__`dat.`__: dataset &emsp; | &emsp; __`cls.`__: classification &emsp; | &emsp; __`rel.`__: retrieval &emsp; | &emsp; __`seg.`__: segmentation     
__`det.`__: detection &emsp; | &emsp; __`tra.`__: tracking &emsp; | &emsp; __`pos.`__: pose &emsp; | &emsp; __`dep.`__: depth     
__`reg.`__: registration &emsp; | &emsp; __`rec.`__: reconstruction &emsp; | &emsp; __`aut.`__: autonomous driving     
__`oth.`__: other, including normal-related, correspondence, mapping, matching, alignment, compression, generative model...

Statistics: :fire: code is available & stars >= 100 &emsp;|&emsp; :star: citation >= 50

---
## 2019
- [[CVPR](http://export.arxiv.org/abs/1904.07601)] Relation-Shape Convolutional Neural Network for Point Cloud Analysis. [[pytorch](https://github.com/Yochengliu/Relation-Shape-CNN)] [__`cls.`__ __`seg.`__ __`oth.`__] :fire:
- [[CVPR](https://raoyongming.github.io/files/SFCNN.pdf)] Spherical Fractal Convolutional Neural Networks for Point Cloud Recognition. [__`cls.`__ __`seg.`__]
- [[CVPR](https://arxiv.org/abs/1811.11397)] DeepMapping: Unsupervised Map Estimation From Multiple Point Clouds. [[code](https://ai4ce.github.io/DeepMapping/)] [__`reg.`__]
- [[CVPR](https://arxiv.org/abs/1812.07179)] Pseudo-LiDAR from Visual Depth Estimation: Bridging the Gap in 3D Object Detection for Autonomous Driving. [[code](https://github.com/mileyan/pseudo_lidar)] [__`det.`__ __`dep.`__ __`aut.`__]
- [[CVPR](https://arxiv.org/abs/1812.04244)] PointRCNN: 3D Object Proposal Generation and Detection from Point Cloud. [[pytorch](https://github.com/sshaoshuai/PointRCNN)] [__`det.`__ __`aut.`__] :fire:
- [[CVPR](https://arxiv.org/abs/1809.07016)] Generating 3D Adversarial Point Clouds. [[code](https://github.com/xiangchong1/3d-adv-pc)] [__`oth.`__]
- [[CVPR](https://arxiv.org/abs/1904.03375v1)] Modeling Point Clouds with Self-Attention and Gumbel Subset Sampling. [__`cls.`__ __`seg.`__]
- [[CVPR](http://export.arxiv.org/abs/1904.08017)] A-CNN: Annularly Convolutional Neural Networks on Point Clouds. [[tensorflow](https://github.com/artemkomarichev/a-cnn)][__`cls.`__ __`seg.`__]
- [[CVPR](https://arxiv.org/abs/1811.07246)] PointConv: Deep Convolutional Networks on 3D Point Clouds. [[tensorflow](https://github.com/DylanWusee/pointconv)] [__`cls.`__ __`seg.`__] :fire:
- [[CVPR](https://arxiv.org/abs/1812.11647)] Path-Invariant Map Networks. [[tensorflow](https://github.com/zaiweizhang/path_invariance_map_network)] [__`seg.`__ __`oth.`__]
- [[CVPR](https://arxiv.org/abs/1812.02713)] PartNet: A Large-scale Benchmark for Fine-grained and Hierarchical Part-level 3D Object Understanding. [[code](https://github.com/daerduoCarey/partnet_dataset)] [__`dat.`__ __`seg.`__]
- [[CVPR](http://export.arxiv.org/abs/1901.00680)] GeoNet: Deep Geodesic Networks for Point Cloud Analysis. [__`cls.`__ __`rec.`__ __`oth.`__]
- [[CVPR](https://arxiv.org/abs/1902.09852)] Associatively Segmenting Instances and Semantics in Point Clouds. [[tensorflow](https://github.com/WXinlong/ASIS)] [__`seg.`__] :fire:
- [[CVPR](https://arxiv.org/abs/1811.08988)] Supervised Fitting of Geometric Primitives to 3D Point Clouds. [[tensorflow](https://github.com/csimstu2/SPFN)] [__`oth.`__]
- [[CVPR](https://arxiv.org/abs/1903.00343)] Octree guided CNN with Spherical Kernels for 3D Point Clouds. [[extension](https://arxiv.org/pdf/1909.09287.pdf)] [[code](https://github.com/hlei-ziyan/SPH3D-GCN)] [__`cls.`__ __`seg.`__]
- [[CVPR](https://arxiv.org/abs/1903.05711)] PointNetLK: Point Cloud Registration using PointNet. [[pytorch](https://github.com/hmgoforth/PointNetLK)] [__`reg.`__]
- [[CVPR](https://arxiv.org/abs/1904.00699v1)] JSIS3D: Joint Semantic-Instance Segmentation of 3D Point Clouds with Multi-Task Pointwise Networks and Multi-Value Conditional Random Fields. [[pytorch](https://github.com/pqhieu/JSIS3D)] [__`seg.`__]
- [[CVPR](https://arxiv.org/abs/1904.02113)] Point Cloud Oversegmentation with Graph-Structured Deep Metric Learning. [__`seg.`__]
- [[CVPR](https://arxiv.org/abs/1812.05784)] PointPillars: Fast Encoders for Object Detection from Point Clouds. [[pytorch](https://github.com/nutonomy/second.pytorch)] [__`det.`__] :fire:
- [[CVPR](https://arxiv.org/abs/1811.11286)] Patch-based Progressive 3D Point Set Upsampling. [[tensorflow](https://github.com/yifita/3PU)] [__`oth.`__]
- [[CVPR](https://arxiv.org/abs/1904.09793)] PCAN: 3D Attention Map Learning Using Contextual Information for Point Cloud Based Retrieval. [[code](https://github.com/XLechter/PCAN)] [__`rel.`__]
- [[CVPR](https://arxiv.org/abs/1903.00709)] PartNet: A Recursive Part Decomposition Network for Fine-grained and Hierarchical Shape Segmentation. [[pytorch](https://github.com/FoggYu/PartNet)] [__`dat.`__ __`seg.`__] 
- [[CVPR](https://arxiv.org/abs/1806.02170)] PointFlowNet: Learning Representations for Rigid Motion Estimation from Point Clouds. [[code](https://github.com/aseembehl/pointflownet)] [__`det.`__ __`dat.`__ __`oth.`__] 
- [[CVPR](https://arxiv.org/abs/1904.03483)] SDRSAC: Semidefinite-Based Randomized Approach for Robust Point Cloud Registration without Correspondences. [[matlab](https://github.com/intellhave/SDRSAC)] [__`reg.`__]
- [[CVPR](https://arxiv.org/abs/1903.04019)] Deep Reinforcement Learning of Volume-guided Progressive View Inpainting for 3D Point Scene Completion from a Single Depth Image. [__`rec.`__ __`oth.`__]
- [[CVPR](https://arxiv.org/abs/1904.03461)] Embodied Question Answering in Photorealistic Environments with Point Cloud Perception. [__`oth.`__]
- [[CVPR](https://arxiv.org/abs/1812.10775v1)] 3D Point-Capsule Networks. [[pytorch](https://github.com/yongheng1991/3D-point-capsule-networks)] [__`cls.`__ __`rec.`__ __`oth.`__]
- [[CVPR](http://export.arxiv.org/abs/1904.08755)] 4D Spatio-Temporal ConvNets: Minkowski Convolutional Neural Networks. [[pytorch](https://github.com/StanfordVL/MinkowskiEngine)] [__`seg.`__] :fire:
- [[CVPR](https://arxiv.org/abs/1811.06879v2)] The Perfect Match: 3D Point Cloud Matching with Smoothed Densities. [[tensorflow](https://github.com/zgojcic/3DSmoothNet)] [__`oth.`__]
- [[CVPR](https://arxiv.org/abs/1811.10136)] FilterReg: Robust and Efficient Probabilistic Point-Set Registration using Gaussian Filter and Twist Parameterization. [[code](https://bitbucket.org/gaowei19951004/poser/src/master/)] [__`reg.`__]
- [[CVPR](https://arxiv.org/abs/1806.01411)] FlowNet3D: Learning Scene Flow in 3D Point Clouds. [__`oth.`__]
- [[CVPR](https://arxiv.org/abs/1811.07782)] Modeling Local Geometric Structure of 3D Point Clouds using Geo-CNN. [__`cls.`__ __`det.`__]
- [[CVPR](http://www.linliang.net/wp-content/uploads/2019/04/CVPR2019_PointClound.pdf)] ClusterNet: Deep Hierarchical Cluster Network with Rigorously Rotation-Invariant Representation for Point Cloud Analysis. [__`cls.`__]
- [[CVPR](http://jiaya.me/papers/pointweb_cvpr19.pdf)] PointWeb: Enhancing Local Neighborhood Features for Point Cloud Processing. [[pytorch](https://github.com/hszhao/PointWeb)] [__`cls.`__ __`seg.`__]
- [[CVPR](https://arxiv.org/abs/1904.12304)] RL-GAN-Net: A Reinforcement Learning Agent Controlled GAN Network for Real-Time Point Cloud Shape Completion. [[code](https://github.com/iSarmad/RL-GAN-Net)] [__`oth.`__]
- [[CVPR](https://arxiv.org/abs/1903.05711)] PointNetLK: Robust & Efficient Point Cloud Registration using PointNet. [[pytorch](https://github.com/hmgoforth/PointNetLK)] [__`reg.`__]
- [[CVPR](https://www.researchgate.net/publication/332240602_Robust_Point_Cloud_Based_Reconstruction_of_Large-Scale_Outdoor_Scenes)] Robust Point Cloud Based Reconstruction of Large-Scale Outdoor Scenes. [[code](https://github.com/ziquan111/RobustPCLReconstruction)] [__`rec.`__]
- [[CVPR](https://arxiv.org/abs/1812.00709)] Nesti-Net: Normal Estimation for Unstructured 3D Point Clouds using Convolutional Neural Networks. [[tensorflow](https://github.com/sitzikbs/Nesti-Net)] [__`oth.`__]
- [[CVPR](https://arxiv.org/abs/1812.03320)] GSPN: Generative Shape Proposal Network for 3D Instance Segmentation in Point Cloud. [__`seg.`__]
- [[CVPR](http://openaccess.thecvf.com/content_CVPR_2019/papers/Wang_Graph_Attention_Convolution_for_Point_Cloud_Semantic_Segmentation_CVPR_2019_paper.pdf)] Graph Attention Convolution for Point Cloud Semantic Segmentation. [__`seg.`__]
- [[CVPR](https://arxiv.org/abs/1812.02050)] Point-to-Pose Voting based Hand Pose Estimation using Residual Permutation Equivariant Layer. [__`pos.`__]
- [[CVPR](https://arxiv.org/abs/1903.08701v1)] LaserNet: An Efficient Probabilistic 3D Object Detector for Autonomous Driving. [__`det.`__ __`aut.`__]
- [[CVPR](https://arxiv.org/pdf/1904.03498.pdf)] LP-3DCNN: Unveiling Local Phase in 3D Convolutional Neural Networks. [[project](https://sites.google.com/view/lp-3dcnn/home)] [__`cls.`__ __`seg.`__]
- [[CVPR](http://openaccess.thecvf.com/content_CVPR_2019/papers/Duan_Structural_Relational_Reasoning_of_Point_Clouds_CVPR_2019_paper.pdf)] Structural Relational Reasoning of Point Clouds. [__`cls.`__ __`seg.`__]
- [[CVPR](https://arxiv.org/abs/1903.03322)] 3DN: 3D Deformation Network. [[tensorflow](https://github.com/laughtervv/3DN)] [__`rec.`__ __`oth.`__]
- [[CVPR](http://openaccess.thecvf.com/content_CVPR_2019/papers/Speciale_Privacy_Preserving_Image-Based_Localization_CVPR_2019_paper.pdf)] Privacy Preserving Image-Based Localization. [__`pos.`__ __`oth.`__]
- [[CVPR](http://openaccess.thecvf.com/content_CVPR_2019/html/Chang_Argoverse_3D_Tracking_and_Forecasting_With_Rich_Maps_CVPR_2019_paper.html)] Argoverse: 3D Tracking and Forecasting With Rich Maps.[__`tra.`__ __`aut.`__]
- [[CVPR](http://openaccess.thecvf.com/content_CVPR_2019/papers/Giancola_Leveraging_Shape_Completion_for_3D_Siamese_Tracking_CVPR_2019_paper.pdf)] Leveraging Shape Completion for 3D Siamese Tracking. [[pytorch](https://github.com/SilvioGiancola/ShapeCompletion3DTracking)] [__`tra.`__ ]
- [[CVPRW](http://openaccess.thecvf.com/content_CVPRW_2019/papers/WAD/Paigwar_Attentional_PointNet_for_3D-Object_Detection_in_Point_Clouds_CVPRW_2019_paper.pdf)] Attentional PointNet for 3D-Object Detection in Point Clouds. [[pytorch](https://github.com/anshulpaigwar/Attentional-PointNet)] [__`cls.`__ __`det.`__ __`aut.`__]
- [[CVPR](http://openaccess.thecvf.com/content_CVPR_2019/papers/Deng_3D_Local_Features_for_Direct_Pairwise_Registration_CVPR_2019_paper.pdf)] 3D Local Features for Direct Pairwise Registration. [__`reg.`__]
- [[CVPR](http://openaccess.thecvf.com/content_CVPR_2019/papers/Dovrat_Learning_to_Sample_CVPR_2019_paper.pdf)] Learning to Sample. [[tensorflow](https://github.com/orendv/learning_to_sample)] [__`cls.`__ __`rec.`__]
- [[CVPR](http://openaccess.thecvf.com/content_CVPR_2019/papers/Pittaluga_Revealing_Scenes_by_Inverting_Structure_From_Motion_Reconstructions_CVPR_2019_paper.pdf)] Revealing Scenes by Inverting Structure from Motion Reconstructions. [[code](https://github.com/francescopittaluga/invsfm)] [__`rec.`__]
- [[CVPR](http://openaccess.thecvf.com/content_CVPR_2019/papers/Qiu_DeepLiDAR_Deep_Surface_Normal_Guided_Depth_Prediction_for_Outdoor_Scene_CVPR_2019_paper.pdf)] DeepLiDAR: Deep Surface Normal Guided Depth Prediction for Outdoor Scene from Sparse LiDAR Data and Single Color Image. [[pytorch](https://github.com/JiaxiongQ/DeepLiDAR)] [__`dep.`__]
- [[CVPR](http://openaccess.thecvf.com/content_CVPR_2019/papers/Gu_HPLFlowNet_Hierarchical_Permutohedral_Lattice_FlowNet_for_Scene_Flow_Estimation_on_CVPR_2019_paper.pdf)] HPLFlowNet: Hierarchical Permutohedral Lattice FlowNet for Scene Flow Estimation on Large-scale Point Clouds. [[pytorch](https://github.com/laoreja/HPLFlowNet)] [__`oth.`__]
-
- [[ICCV](https://arxiv.org/abs/1904.09664v1)] Deep Hough Voting for 3D Object Detection in Point Clouds. [[pytorch](https://github.com/facebookresearch/votenet)] [[tensorflow](https://github.com/qq456cvb/VoteNet)] [__`det.`__] :fire:
- [[ICCV](https://arxiv.org/abs/1904.03751)] DeepGCNs: Can GCNs Go as Deep as CNNs? [[tensorflow](https://github.com/lightaime/deep_gcns)] [[pytorch]](https://github.com/lightaime/deep_gcns_torch) [__`seg.`__] :fire:
- [[ICCV](https://arxiv.org/pdf/1907.10844.pdf)] PU-GAN: a Point Cloud Upsampling Adversarial Network. [[tensorflow](https://github.com/liruihui/PU-GAN)] [__`oth.`__]
- [[ICCV](https://arxiv.org/pdf/1812.07050.pdf)] 3D Point Cloud Learning for Large-scale Environment Analysis and Place Recognition. [__`rel.`__ __`oth.`__]
- [[ICCV](https://arxiv.org/pdf/1906.12320.pdf)] PointFlow: 3D Point Cloud Generation with Continuous Normalizing Flows. [[pytorch](https://github.com/stevenygd/PointFlow)] [__`oth.`__]
- [[ICCV](https://arxiv.org/pdf/1907.12704.pdf)] Multi-Angle Point Cloud-VAE: Unsupervised Feature Learning for 3D Point Clouds from Multiple Angles by Joint Self-Reconstruction and Half-to-Half Prediction. [__`oth.`__]
- [[ICCV](https://drive.google.com/file/d/11GJzouV6jt_aOpvrJ8l3J5x_R_-m-Lg8/view)] SO-HandNet: Self-Organizing Network for 3D Hand Pose Estimation with Semi-supervised Learning. [[code](https://github.com/TerenceCYJ/SO-HandNet)] [__`pos.`__]
- [[ICCV](https://arxiv.org/abs/1812.11017)] DUP-Net: Denoiser and Upsampler Network for 3D Adversarial Point Clouds Defense. [__`oth.`__]
- [[ICCV](https://arxiv.org/abs/1908.04616)] Revisiting Point Cloud Classification: A New Benchmark Dataset and Classification Model on Real-World Data. [__`cls.`__ __`dat.`__] [[code](https://github.com/hkust-vgd/scanobjectnn)] [[dataset](https://hkust-vgd.github.io/scanobjectnn/)]
- [[ICCV](https://arxiv.org/abs/1904.08889)] KPConv: Flexible and Deformable Convolution for Point Clouds. [[tensorflow](https://github.com/HuguesTHOMAS/KPConv)] [__`cls.`__ __`seg.`__] :fire:
- [[ICCV](https://arxiv.org/pdf/1908.06295.pdf)] ShellNet: Efficient Point Cloud Convolutional Neural Networks using Concentric Shells Statistics. [[project](https://hkust-vgd.github.io/shellnet/)] [__`seg.`__]
- [[ICCV](https://arxiv.org/pdf/1908.04422.pdf)] Point-Based Multi-View Stereo Network. [[pytorch](https://github.com/callmeray/PointMVSNet)] [__`rec.`__]
- [[ICCV](https://arxiv.org/abs/1909.03669)] DensePoint: Learning Densely Contextual Representation for Efficient Point Cloud Processing. [[pytorch](https://github.com/Yochengliu/DensePoint)] [__`cls.`__ __`seg.`__ __`oth.`__]
- [[ICCV](https://arxiv.org/abs/1905.04153v2)] DeepICP: An End-to-End Deep Neural Network for 3D Point Cloud Registration. [__`reg.`__]
- [[ICCV](https://arxiv.org/pdf/1905.06292.pdf)] 3D Point Cloud Generative Adversarial Network Based on Tree Structured Graph Convolutions. [[pytorch](https://github.com/seowok/TreeGAN)] [__`oth.`__]
- [[ICCV](https://arxiv.org/pdf/1909.10469.pdf)] Hierarchical Point-Edge Interaction Network for Point Cloud Semantic Segmentation. [__`seg.`__]
- [[ICCV](http://openaccess.thecvf.com/content_ICCV_2019/papers/Spezialetti_Learning_an_Effective_Equivariant_3D_Descriptor_Without_Supervision_ICCV_2019_paper.pdf)] Learning an Effective Equivariant 3D Descriptor Without Supervision. [__`oth.`__]
- [[ICCV](http://openaccess.thecvf.com/content_ICCV_2019/html/Choy_Fully_Convolutional_Geometric_Features_ICCV_2019_paper.html)] Fully Convolutional Geometric Features. [[pytorch](https://github.com/chrischoy/FCGF)] [__`reg.`__]
- [[ICCV](https://arxiv.org/pdf/1812.07050.pdf)] LPD-Net: 3D Point Cloud Learning for Large-Scale Place Recognition and Environment Analysis. [__`oth.`__ __`aut.`__]
- [[ICCV](http://openaccess.thecvf.com/content_ICCV_2019/papers/Hermosilla_Total_Denoising_Unsupervised_Learning_of_3D_Point_Cloud_Cleaning_ICCV_2019_paper.pdf)] Total Denoising: Unsupervised Learning of 3D Point Cloud Cleaning. [[tensorflow](https://github.com/phermosilla/TotalDenoising)] [__`oth.`__]
- [[ICCV](https://arxiv.org/abs/1904.00229)] USIP: Unsupervised Stable Interest Point Detection from 3D Point Clouds. [[pytorch](https://github.com/lijx10/USIP)] [__`oth.`__]
- [[ICCV](http://openaccess.thecvf.com/content_ICCV_2019/papers/Mao_Interpolated_Convolutional_Networks_for_3D_Point_Cloud_Understanding_ICCV_2019_paper.pdf)] Interpolated Convolutional Networks for 3D Point Cloud Understanding. [__`cls.`__ __`seg.`__]
- [[ICCV](http://openaccess.thecvf.com/content_ICCV_2019/papers/Zheng_PointCloud_Saliency_Maps_ICCV_2019_paper.pdf)] PointCloud Saliency Maps. [[code](https://github.com/tianzheng4/PointCloud-Saliency-Maps)] [__`oth.`__]
- [[ICCV](https://arxiv.org/pdf/1907.10471.pdf)] STD: Sparse-to-Dense 3D Object Detector for Point Cloud. [__`det.`__ __`oth.`__]
- [[ICCV](http://openaccess.thecvf.com/content_ICCV_2019/papers/Golyanik_Accelerated_Gravitational_Point_Set_Alignment_With_Altered_Physical_Laws_ICCV_2019_paper.pdf)] Accelerated Gravitational Point Set Alignment with Altered Physical Laws. [__`reg.`__]
- [[ICCV](http://openaccess.thecvf.com/content_ICCV_2019/papers/Wang_Deep_Closest_Point_Learning_Representations_for_Point_Cloud_Registration_ICCV_2019_paper.pdf)] Deep Closest Point: Learning Representations for Point Cloud Registration. [__`reg.`__]
- [[ICCV](http://openaccess.thecvf.com/content_ICCV_2019/papers/Prokudin_Efficient_Learning_on_Point_Clouds_With_Basis_Point_Sets_ICCV_2019_paper.pdf)] Efficient Learning on Point Clouds with Basis Point Sets. [[code](https://github.com/sergeyprokudin/bps)] [__`cls.`__ __`reg.`__]
- [[ICCV](http://openaccess.thecvf.com/content_ICCV_2019/papers/Dai_PointAE_Point_Auto-Encoder_for_3D_Statistical_Shape_and_Texture_Modelling_ICCV_2019_paper.pdf)] PointAE: Point Auto-encoder for 3D Statistical Shape and Texture Modelling. [__`rec.`__]
- [[ICCV](http://openaccess.thecvf.com/content_ICCV_2019/papers/Jiang_Skeleton-Aware_3D_Human_Shape_Reconstruction_From_Point_Clouds_ICCV_2019_paper.pdf)] Skeleton-Aware 3D Human Shape Reconstruction From Point Clouds. [__`rec.`__]
- [[ICCV](http://openaccess.thecvf.com/content_ICCV_2019/papers/Liu_Dynamic_Points_Agglomeration_for_Hierarchical_Point_Sets_Learning_ICCV_2019_paper.pdf)] Dynamic Points Agglomeration for Hierarchical Point Sets Learning. [[pytorch](https://github.com/yuyi1005/DPAM)] [__`cls.`__ __`seg.`__]
- [[ICCV](http://openaccess.thecvf.com/content_ICCV_2019/papers/Hassani_Unsupervised_Multi-Task_Feature_Learning_on_Point_Clouds_ICCV_2019_paper.pdf)] Unsupervised Multi-Task Feature Learning on Point Clouds. [__`cls.`__ __`seg.`__]
- [[ICCV](http://openaccess.thecvf.com/content_ICCV_2019/papers/Meng_VV-Net_Voxel_VAE_Net_With_Group_Convolutions_for_Point_Cloud_ICCV_2019_paper.pdf)] VV-NET: Voxel VAE Net with Group Convolutions for Point Cloud Segmentation. [[tensorflow](https://github.com/xianyuMeng/VV-Net-Voxel-VAE-Net-with-Group-Convolutions-for-Point-Cloud-Segmentation)] [__`seg.`__]
- [[ICCV](http://openaccess.thecvf.com/content_ICCV_2019/papers/Nguyen_GraphX-Convolution_for_Point_Cloud_Deformation_in_2D-to-3D_Conversion_ICCV_2019_paper.pdf)] GraphX-Convolution for Point Cloud Deformation in 2D-to-3D Conversion. [[pytorch](https://github.com/justanhduc/graphx-conv)] [__`rec.`__]
- [[ICCV](http://openaccess.thecvf.com/content_ICCV_2019/papers/Liu_MeteorNet_Deep_Learning_on_Dynamic_3D_Point_Cloud_Sequences_ICCV_2019_paper.pdf)] MeteorNet: Deep Learning on Dynamic 3D Point Cloud Sequences. [[code](https://github.com/xingyul/meteornet)] [__`cls.`__ __`seg.`__ __`oth.`__]
- [[ICCV](https://arxiv.org/abs/1908.02990)] Fast Point R-CNN. [__`det.`__ __`aut.`__]
- [[ICCV](http://openaccess.thecvf.com/content_ICCV_2019/papers/Zhou_Robust_Variational_Bayesian_Point_Set_Registration_ICCV_2019_paper.pdf)] Robust Variational Bayesian Point Set Registration. [__`reg.`__]
- [[ICCV](http://openaccess.thecvf.com/content_ICCV_2019/papers/Mehr_DiscoNet_Shapes_Learning_on_Disconnected_Manifolds_for_3D_Editing_ICCV_2019_paper.pdf)] DiscoNet: Shapes Learning on Disconnected Manifolds for 3D Editing. [__`rec.`__ __`oth.`__]
- [[ICCV](http://openaccess.thecvf.com/content_ICCV_2019/papers/Spezialetti_Learning_an_Effective_Equivariant_3D_Descriptor_Without_Supervision_ICCV_2019_paper.pdf)] Learning an Effective Equivariant 3D Descriptor Without Supervision. [__`oth.`__]
- [[ICCV](http://openaccess.thecvf.com/content_ICCV_2019/papers/Lahoud_3D_Instance_Segmentation_via_Multi-Task_Metric_Learning_ICCV_2019_paper.pdf)] 3D Instance Segmentation via Multi-Task Metric Learning. [[code](https://sites.google.com/view/3d-instance-mtml)] [__`seg.`__]
- [[ICCV](http://openaccess.thecvf.com/content_ICCV_2019/papers/Liu_3D_Face_Modeling_From_Diverse_Raw_Scan_Data_ICCV_2019_paper.pdf)] 3D Face Modeling From Diverse Raw Scan Data. [__`rec.`__]
- [[ICCVW](https://arxiv.org/abs/1909.12249)] Range Adaptation for 3D Object Detection in LiDAR. [__`det.`__ __`aut.`__]
-
- [[NeurIPS](https://arxiv.org/pdf/1901.08396.pdf)] Self-Supervised Deep Learning on Point Clouds by Reconstructing Space. [__`cls.`__ __`oth.`__]
- [[NeurIPS](https://arxiv.org/abs/1906.01140)] Learning Object Bounding Boxes for 3D Instance Segmentation on Point Clouds. [[tensorflow](https://github.com/Yang7879/3D-BoNet)] [__`det.`__ __`seg.`__]
- [[NeurIPS](http://papers.nips.cc/paper/8706-exploiting-local-and-global-structure-for-point-cloud-semantic-segmentation-with-contextual-point-representations.pdf)] Exploiting Local and Global Structure for Point Cloud Semantic Segmentation with Contextual Point Representations. [[tensorflow](https://github.com/fly519/ELGS)] [__`seg.`__]
- [[NeurIPS](https://arxiv.org/pdf/1907.03739.pdf)] Point-Voxel CNN for Efficient 3D Deep Learning. [__`det.`__ __`seg.`__ __`aut.`__]
- [[NeurIPS](http://papers.nips.cc/paper/8940-pointdan-a-multi-scale-3d-domain-adaption-network-for-point-cloud-representation.pdf)] PointDAN: A Multi-Scale 3D Domain Adaption Network for Point Cloud Representation. [[code](https://github.com/canqin001/PointDAN)] [__`cls.`__ __`oth.`__]
-
- [[ICLR](https://openreview.net/forum?id=SJeXSo09FQ)] Learning Localized Generative Models for 3D Point Clouds via Graph Convolution. [__`oth.`__]
-
- [[ICMLW](https://arxiv.org/abs/1905.07290)] LiDAR Sensor modeling and Data augmentation with GANs for Autonomous driving. [__`det.`__ __`oth.`__ __`aut.`__]
-
- [[AAAI](https://arxiv.org/abs/1811.11731)] CAPNet: Continuous Approximation Projection For 3D Point Cloud Reconstruction Using 2D Supervision. [[code](https://github.com/val-iisc/capnet)] [__`rec.`__] 
- [[AAAI](https://arxiv.org/abs/1811.02565)] Point2Sequence: Learning the Shape Representation of 3D Point Clouds with an Attention-based Sequence to Sequence Network. [[tensorflow](https://github.com/liuxinhai/Point2Sequence)] [__`cls.`__ __`seg.`__]
- [[AAAI](https://par.nsf.gov/biblio/10086163)] Point Cloud Processing via Recurrent Set Encoding. [__`cls.`__]
- [[AAAI](https://arxiv.org/abs/1812.00333)] PVRNet: Point-View Relation Neural Network for 3D Shape Recognition. [[pytorch](https://github.com/Hxyou/PVRNet)] [__`cls.`__ __`rel.`__]
- [[AAAI](http://gaoyue.org/paper/HGNN.pdf)] Hypergraph Neural Networks. [[pytorch](https://github.com/iMoonLab/HGNN)] [__`cls.`__]
-
- [[TOG](https://arxiv.org/abs/1801.07829)] Dynamic Graph CNN for Learning on Point Clouds. [[tensorflow](https://github.com/WangYueFt/dgcnn)][[pytorch](https://github.com/WangYueFt/dgcnn)] [__`cls.`__ __`seg.`__] :fire: :star:
- [[TOG](https://arxiv.org/pdf/1903.10170.pdf)] LOGAN: Unpaired Shape Transform in Latent Overcomplete Space. [[tensorflow](https://github.com/kangxue/LOGAN)] [__`oth.`__]
- [[SIGGRAPH Asia](https://arxiv.org/abs/1908.00575v1)] StructureNet: Hierarchical Graph Networks for 3D Shape Generation. [__`seg.`__ __`oth.`__]
-
- [[MM](https://dl.acm.org/citation.cfm?id=3343031.3351009)] MMJN: Multi-Modal Joint Networks for 3D Shape Recognition. [__`cls.`__ __`rel.`__]
- [[MM](https://dl.acm.org/citation.cfm?id=3351061)] 3D Point Cloud Geometry Compression on Deep Learning. [__`oth.`__]
- [[MM](https://dl.acm.org/citation.cfm?id=3351042)] SRINet: Learning Strictly Rotation-Invariant Representations for Point Cloud Classification and Segmentation. [[tensorflow](https://github.com/tasx0823/SRINet)] [__`cls.`__ __`seg.`__]
- [[MM](https://dl.acm.org/citation.cfm?id=3350960)] L2G Auto-encoder: Understanding Point Clouds by Local-to-Global Reconstruction with Hierarchical Self-Attention. [__`cls.`__ __`rel.`__]
- [[MM](https://dl.acm.org/citation.cfm?id=3351076)] Ground-Aware Point Cloud Semantic Segmentation for Autonomous Driving. [[code](https://github.com/Jaiy/Ground-aware-Seg)] [__`seg.`__ __`aut.`__]
-
- [[ICME](https://arxiv.org/abs/1908.08996)] Justlookup: One Millisecond Deep Feature Extraction for Point Clouds By Lookup Tables. [__`cls.`__ __`rel.`__]
-
- [[ICASSP](https://arxiv.org/abs/1904.04427)] 3D Point Cloud Denoising via Deep Neural Network based Local Surface Estimation. [[code](https://github.com/chaojingduan/Neural-Projection)] [__`oth.`__]
-
- [[BMVC](https://arxiv.org/abs/1907.06371)] Mitigating the Hubness Problem for Zero-Shot Learning of 3D Objects. [__`cls.`__]
-
- [[ICRA](https://arxiv.org/abs/1904.00319)] Discrete Rotation Equivariance for Point Cloud Recognition. [[pytorch](https://github.com/lijx10/rot-equ-net)] [__`cls.`__]
- [[ICRA](https://arxiv.org/abs/1809.08495)] SqueezeSegV2: Improved Model Structure and Unsupervised Domain Adaptation for Road-Object Segmentation from a LiDAR Point Cloud. [[tensorflow](https://github.com/xuanyuzhou98/SqueezeSegV2)] [__`seg.`__ __`aut.`__]
- [[ICRA](https://www.ais.uni-bonn.de/papers/ICRA_2019_Razlaw.pdf)] Detection and Tracking of Small Objects in Sparse 3D Laser Range Data. [__`det.`__ __`tra.`__ __`aut.`__]
- [[ICRA](https://arxiv.org/abs/1905.02553)] Oriented Point Sampling for Plane Detection in Unorganized Point Clouds. [__`det.`__ __`seg.`__]
- [[ICRA](https://ras.papercept.net/conferences/conferences/ICRA19/program/ICRA19_ContentListWeb_1.html)] Point Cloud Compression for 3D LiDAR Sensor Using Recurrent Neural Network with Residual Blocks. [[pytorch](https://github.com/ChenxiTU/Point-cloud-compression-by-RNN)] [__`oth.`__]
- [[ICRA](https://arxiv.org/abs/1809.06065)] Focal Loss in 3D Object Detection. [[code](https://github.com/pyun-ram/FL3D)] [__`det.`__ __`aut.`__]
- [[ICRA](https://arxiv.org/abs/1809.06267)] PointNetGPD: Detecting Grasp Configurations from Point Sets. [[pytorch](https://github.com/lianghongzhuo/PointNetGPD)] [__`det.`__ __`seg.`__]
- [[ICRA](https://arxiv.org/abs/1904.09742)] 2D3D-MatchNet: Learning to Match Keypoints across 2D Image and 3D Point Cloud. [__`oth.`__]
- [[ICRA](https://ras.papercept.net/conferences/conferences/ICRA19/program/ICRA19_ContentListWeb_2.html)] Speeding up Iterative Closest Point Using Stochastic Gradient Descent. [__`oth.`__]
- [[ICRA](https://ras.papercept.net/conferences/conferences/ICRA19/program/ICRA19_ContentListWeb_2.html)] Uncertainty Estimation for Projecting Lidar Points Onto Camera Images for Moving Platforms. [__`oth.`__]
- [[ICRA](https://ras.papercept.net/conferences/conferences/ICRA19/program/ICRA19_ContentListWeb_2.html)] SEG-VoxelNet for 3D Vehicle Detection from RGB and LiDAR Data. [__`det.`__ __`aut.`__]
- [[ICRA](https://arxiv.org/abs/1903.06405v1)] BLVD: Building A Large-scale 5D Semantics Benchmark for Autonomous Driving. [[project](https://github.com/VCCIV/BLVD)] [__`dat.`__ __`det.`__ __`tra.`__ __`aut.`__ __`oth.`__]
- [[ICRA](https://ras.papercept.net/conferences/conferences/ICRA19/program/ICRA19_ContentListWeb_2.html)] A Fast and Robust 3D Person Detector and Posture Estimator for Mobile Robotic Applications. [__`det.`__]
- [[ICRA](https://arpg.colorado.edu/papers/hmrf_icp.pdf)] Robust low-overlap 3-D point cloud registration for outlier rejection. [[matlab](https://github.com/JStech/ICP)] [__`reg.`__]
- [[ICRA](https://ras.papercept.net/conferences/conferences/ICRA19/program/ICRA19_ContentListWeb_3.html)] Robust 3D Object Classification by Combining Point Pair Features and Graph Convolution. [__`cls.`__ __`seg.`__]
- [[ICRA](https://ras.papercept.net/conferences/conferences/ICRA19/program/ICRA19_ContentListWeb_3.html)] Hierarchical Depthwise Graph Convolutional Neural Network for 3D Semantic Segmentation of Point Clouds. [__`seg.`__]
- [[ICRA](https://ras.papercept.net/conferences/conferences/ICRA19/program/ICRA19_ContentListWeb_3.html)] Robust Generalized Point Set Registration Using Inhomogeneous Hybrid Mixture Models Via Expectation. [__`reg.`__]
- [[ICRA](https://arxiv.org/abs/1902.07511)] Dense 3D Visual Mapping via Semantic Simplification. [__`oth.`__]
- [[ICRA](https://arxiv.org/abs/1904.01649)] MVX-Net: Multimodal VoxelNet for 3D Object Detection. [__`det.`__ __`aut.`__]
- [[ICRA](https://export.arxiv.org/abs/1810.01470)] CELLO-3D: Estimating the Covariance of ICP in the Real World. [__`reg.`__]
-
- [[IROS](https://www.researchgate.net/publication/334720713_EPN_Edge-Aware_PointNet_for_Object_Recognition_from_Multi-View_25D_Point_Clouds)] EPN: Edge-Aware PointNet for Object Recognition from Multi-View 2.5D Point Clouds. [[tensorflow](https://github.com/Merium88/Edge-Aware-PointNet)] [__`cls.`__ __`det.`__]
- [[IROS](https://arxiv.org/pdf/1904.13030.pdf)] SeqLPD: Sequence Matching Enhanced Loop-Closure Detection Based on Large-Scale Point Cloud Description for Self-Driving Vehicles. [__`oth.`__] [__`aut.`__]
- [[IROS](https://arxiv.org/pdf/1909.01643v1.pdf)] PASS3D: Precise and Accelerated Semantic Segmentation for 3D Point Cloud. [__`seg.`__ __`aut.`__]
-
- [[IV](https://arxiv.org/abs/1906.10964)] End-to-End 3D-PointCloud Semantic Segmentation for Autonomous Driving. [__`seg.`__] [__`aut.`__]
-
- [[Eurographics Workshop](https://arxiv.org/abs/1904.02375)] Generalizing Discrete Convolutions for Unstructured Point Clouds. [[pytorch](https://github.com/aboulch/ConvPoint)] [__`cls.`__ __`seg.`__]
-
- [[WACV](https://arxiv.org/abs/1811.02191)] 3DCapsule: Extending the Capsule Architecture to Classify 3D Point Clouds. [__`cls.`__]
-
- [[3DV](https://arxiv.org/pdf/1908.06297.pdf)] Rotation Invariant Convolutions for 3D Point Clouds Deep Learning. [[project](https://hkust-vgd.github.io/riconv/)] [__`cls.`__ __`seg.`__]
- [[3DV](https://arxiv.org/abs/1906.11555)] Effective Rotation-invariant Point CNN with Spherical Harmonics kernels. [[tensorflow](https://github.com/adrienPoulenard/SPHnet)] [__`cls.`__ __`seg.`__ __`oth.`__]
-
- [[TVCG](https://arxiv.org/pdf/1907.13538.pdf)] LassoNet: Deep Lasso-Selection of 3D Point Clouds. [[project](https://lassonet.github.io/)] [__`oth.`__]
-
- [[arXiv](https://arxiv.org/abs/1901.02532)] Fast 3D Line Segment Detection From Unorganized Point Cloud. [__`det.`__]
- [[arXiv](https://arxiv.org/abs/1812.01687)] Point-Cloud Saliency Maps. [[tensorflow](https://github.com/tianzheng4/PointCloud-Saliency-Maps)] [__`cls.`__ __`oth.`__]
- [[arXiv](https://export.arxiv.org/abs/1901.03006)] Extending Adversarial Attacks and Defenses to Deep 3D Point Cloud Classifiers. [[code](https://github.com/Daniel-Liu-c0deb0t/3D-Neural-Network-Adversarial-Attacks)] [__`oth.`__]
- [[arxiv](https://arxiv.org/abs/1901.08396)] Context Prediction for Unsupervised Deep Learning on Point Clouds. [__`cls.`__ __`seg.`__]
- [[arXiv](http://export.arxiv.org/abs/1901.09280)] Points2Pix: 3D Point-Cloud to Image Translation using conditional Generative Adversarial Networks. [__`oth.`__]
- [[arXiv](http://export.arxiv.org/abs/1901.09394)] NeuralSampler: Euclidean Point Cloud Auto-Encoder and Sampler. [__`cls.`__ __`oth.`__]
- [[arXiv](https://arxiv.org/abs/1902.05247)] 3D Graph Embedding Learning with a Structure-aware Loss Function for Point Cloud Semantic Instance Segmentation. [__`seg.`__]
- [[arXiv](https://arxiv.org/abs/1902.10272)] Zero-shot Learning of 3D Point Cloud Objects. [[code](https://github.com/alichr/Zero-shot-Learning-of-3D-Point-Cloud-Objects)] [__`cls.`__]
- [[arXiv](https://arxiv.org/abs/1903.09847)] Monocular 3D Object Detection with Pseudo-LiDAR Point Cloud. [__`det.`__ __`aut.`__]
- [[arXiv](https://arxiv.org/abs/1903.01695)] Real-time Multiple People Hand Localization in 4D Point Clouds. [__`det.`__ __`oth.`__]
- [[arXiv](https://arxiv.org/abs/1903.02858)] Variational Graph Methods for Efficient Point Cloud Sparsification. [__`oth.`__]
- [[arXiv](https://arxiv.org/abs/1903.05807)] Neural Style Transfer for Point Clouds. [__`oth.`__]
- [[arXiv](https://arxiv.org/abs/1903.07918)] OREOS: Oriented Recognition of 3D Point Clouds in Outdoor Scenarios. [__`pos.`__ __`oth.`__]
- [[arXiv](https://arxiv.org/abs/1903.10750)] FVNet: 3D Front-View Proposal Generation for Real-Time Object Detection from Point Clouds. [[code](https://github.com/LordLiang/FVNet)] [__`det.`__ __`aut.`__]
- [[arXiv](https://arxiv.org/abs/1904.00069)] Unpaired Point Cloud Completion on Real Scans using Adversarial Training. [__`oth.`__]
- [[arXiv](https://arxiv.org/abs/1904.00230)] MortonNet: Self-Supervised Learning of Local Features in 3D Point Clouds. [__`cls.`__ __`seg.`__]
- [[arXiv](https://arxiv.org/abs/1904.00817)] DeepPoint3D: Learning Discriminative Local Descriptors using Deep Metric Learning on 3D Point Clouds. [__`cls.`__ __`rel.`__ __`oth.`__]
- [[arXiv](https://arxiv.org/abs/1904.07537)] Complexer-YOLO: Real-Time 3D Object Detection and Tracking on Semantic Point Clouds. [[pytorch](https://github.com/AI-liu/Complex-YOLO)] [__`det.`__ __`tra.`__ __`aut.`__] :fire:
- [[arXiv](https://arxiv.org/abs/1904.10795)] Graph-based Inpainting for 3D Dynamic Point Clouds. [__`oth.`__]
- [[arXiv](https://arxiv.org/abs/1903.11027)] nuScenes: A multimodal dataset for autonomous driving. [[link](https://www.nuscenes.org/overview)] [__`dat.`__ __`det.`__ __`tra.`__ __`aut.`__]
- [[arXiv](https://arxiv.org/abs/1901.08373)] 3D Backbone Network for 3D Object Detection. [[code](https://github.com/Benzlxs/tDBN)] [__`det.`__ __`aut.`__]
- [[arXiv](https://arxiv.org/abs/1811.07605v3)] Adversarial Autoencoders for Compact Representations of 3D Point Clouds. [[pytorch](https://github.com/MaciejZamorski/3d-AAE)] [__`rel.`__ __`oth.`__]
- [[arXiv](https://arxiv.org/pdf/1904.10014.pdf)] Linked Dynamic Graph CNN: Learning on Point Cloud via Linking Hierarchical Features. [__`cls.`__ __`seg.`__]
- [[arXiv](https://arxiv.org/abs/1905.08705)] GAPNet: Graph Attention based Point Neural Network for Exploiting Local Feature of Point Cloud. [[tensorflow](https://github.com/FrankCAN/GAPNet)] [__`cls.`__ __`seg.`__]
- [[arXiv](https://arxiv.org/abs/1906.01140)] Learning Object Bounding Boxes for 3D Instance Segmentation on Point Clouds. [[tensorflow](https://github.com/Yang7879/3D-BoNet)] [__`det.`__ __`seg.`__]
- [[arXiv](https://export.arxiv.org/abs/1906.04173)] Differentiable Surface Splatting for Point-based Geometry Processing. [[pytorch](https://github.com/yifita/DSS)] [__`oth.`__]
- [[arXiv](https://arxiv.org/abs/1906.10887)] Spatial Transformer for 3D Points. [__`seg.`__]
- [[arXiv](https://arxiv.org/abs/1907.03739)] Point-Voxel CNN for Efficient 3D Deep Learning. [__`seg.`__ __`det.`__ __`aut.`__]
- [[arXiv](https://arxiv.org/pdf/1907.02545.pdf)] Attentive Context Normalization for Robust Permutation-Equivariant Learning. [__`cls.`__]
- [[arXiv](https://arxiv.org/abs/1906.08240)] Neural Point-Based Graphics. [[project](https://dmitryulyanov.github.io/neural_point_based_graphics)] [__`oth.`__] 
- [[arXiv](https://arxiv.org/pdf/1908.02111.pdf)] Point Cloud Super Resolution with Adversarial Residual Graph Networks. [__`oth.`__] [[tensorflow](https://github.com/wuhuikai/PointCloudSuperResolution)]
- [[arXiv](https://arxiv.org/pdf/1908.10209.pdf)] Blended Convolution and Synthesis for Efficient Discrimination of 3D Shapes. [__`cls.`__ __`rel.`__]
- [[arXiv](https://arxiv.org/pdf/1908.11069v1.pdf)] StarNet: Targeted Computation for Object Detection in Point Clouds. [[tensorflow](https://github.com/tensorflow/lingvo)] [__`det.`__]
- [[arXiv](https://arxiv.org/pdf/1903.10168.pdf)] Efficient Tracking Proposals using 2D-3D Siamese Networks on LIDAR. [__`tra.`__]
- [[arXiv](https://arxiv.org/pdf/1905.07650v1.pdf)] SAWNet: A Spatially Aware Deep Neural Network for 3D Point Cloud Processing. [[tensorflow](https://github.com/balwantraikekutte/SAWNet)] [__`cls.`__ __`seg.`__]
- [[arXiv](https://arxiv.org/abs/1907.03670)] Part-A^2 Net: 3D Part-Aware and Aggregation Neural Network for Object Detection from Point Cloud. [__`det.`__ __`aut.`__]
- [[arXiv](https://arxiv.org/pdf/1906.03299.pdf)] PyramNet: Point Cloud Pyramid Attention Network and Graph Embedding Module for Classification and Segmentation. [__`cls.`__ __`seg.`__]
- [[arXiv](https://arxiv.org/pdf/1910.08287.pdf)] PointRNN: Point Recurrent Neural Network for Moving Point Cloud Processing. [[tensorflow](https://github.com/hehefan/PointRNN)] [__`tra.`__ __`oth.`__ __`aut.`__]
- [[arXiv](https://arxiv.org/abs/1907.09798)] PointAtrousGraph: Deep Hierarchical Encoder-Decoder with Point Atrous Convolution for Unorganized 3D Points. [[tensorflow](https://github.com/paul007pl/PointAtrousGraph)] [__`cls.`__ __`seg.`__]
- [[arXiv](https://arxiv.org/pdf/1907.05279.pdf)] Tranquil Clouds: Neural Networks for Learning Temporally Coherent Features in Point Clouds. [__`oth.`__]
- [[arXiv](https://arxiv.org/pdf/1911.09040.pdf)] 3D-Rotation-Equivariant Quaternion Neural Networks. [__`cls.`__ __`rec.`__]
- [[arXiv](https://arxiv.org/pdf/1908.11026.pdf)] Point2SpatialCapsule: Aggregating Features and Spatial Relationships of Local Regions on Point Clouds using Spatial-aware Capsules. [__`cls.`__ __`rel.`__ __`seg.`__]
- [[arXiv](https://arxiv.org/abs/1911.12885)] Geometric Feedback Network for Point Cloud Classification. [__`cls.`__]
- [[arXiv](https://arxiv.org/abs/1912.00195v1)] SGAS: Sequential Greedy Architecture Search. [[project](https://sites.google.com/kaust.edu.sa/sgas)] [[code](https://github.com/lightaime/sgas)] [__`cls.`__]
- [[arXiv](https://arxiv.org/abs/1912.00202)] Relation Graph Network for 3D Object Detection in Point Clouds. [__`det.`__]
- [[arXiv](https://arxiv.org/pdf/1907.13079.pdf)] Deformable Filter Convolution for Point Cloud Reasoning. [__`seg.`__ __`det.`__ __`aut.`__]
- [[arXiv](https://arxiv.org/pdf/1912.03264.pdf)] PU-GCN: Point Cloud Upsampling via Graph Convolutional Network. [[project](https://sites.google.com/kaust.edu.sa/pugcn)] [__`oth.`__]
- [[arXiv](https://arxiv.org/pdf/1911.11098.pdf)] StructEdit: Learning Structural Shape Variations. [[project](https://github.com/daerduoCarey/structedit)] [__`rec.`__]
- [[arXiv](https://arxiv.org/pdf/1912.02984v1.pdf)] Grid-GCN for Fast and Scalable Point Cloud Learning. [__`seg.`__ __`cls.`__]
- [[arXiv](https://arxiv.org/pdf/1911.10150.pdf)] PointPainting: Sequential Fusion for 3D Object Detection. [__`seg.`__ __`det.`__]
- [[arXiv](https://arxiv.org/pdf/1912.07161.pdf)] Transductive Zero-Shot Learning for 3D Point Cloud Classification. [__`cls.`__]
- [[arXiv](https://arxiv.org/pdf/1912.10644.pdf)] Geometry Sharing Network for 3D Point Cloud Classification and Segmentation. [[pytorch](https://github.com/MingyeXu/GS-Net)] [__`cls.`__ __`seg.`__]
- [[arvix](https://arxiv.org/abs/1912.12033)] Deep Learning for 3D Point Clouds: A Survey. [[code](https://github.com/QingyongHu/SoTA-Point-Cloud)] [__`cls.`__ __`det.`__ __`tra.`__ __`seg.`__]
- [[arXiv](https://arxiv.org/pdf/1912.01800v1.pdf)] Spectral-GANs for High-Resolution 3D Point-cloud Generation. [__`rec.`__ __`oth.`__]
- [[arXiv](https://arxiv.org/pdf/1909.12663.pdf)] Point Attention Network for Semantic Segmentation of 3D Point Clouds. [__`seg.`__]
- [[arXiv](https://arxiv.org/pdf/1909.07137v1.pdf)] PLIN: A Network for Pseudo-LiDAR Point Cloud Interpolation. [__`oth.`__]
- [[arXiv](https://arxiv.org/abs/1904.08159)] 3D Object Recognition with Ensemble Learning --- A Study of Point Cloud-Based Deep Learning Models. [__`cls.`__ __`det.`__]

---
## 2020
- [[AAAI](https://arxiv.org/abs/1912.00280)] Morphing and Sampling Network for Dense Point Cloud Completion. [[pytorch](https://github.com/Colin97/MSN-Point-Cloud-Completion)] [__`oth.`__]
- [[AAAI](https://arxiv.org/pdf/1912.05163.pdf)] TANet: Robust 3D Object Detection from Point Clouds with Triple Attention. [[code](https://github.com/happinesslz/TANet)] [__`det.`__ __`aut.`__]
- [[AAAI](https://arxiv.org/abs/1912.10775)] Point2Node: Correlation Learning of Dynamic-Node for Point Cloud Feature Modeling. [__`seg.`__ __`cls.`__]
- [[AAAI](https://arxiv.org/abs/1811.09361)] PRIN: Pointwise Rotation-Invariant Network. [__`seg.`__ __`cls.`__]
- [[AAAI](https://www.aaai.org/Papers/AAAI/2020GB/AAAI-WuW.2180.pdf)] SK-Net: Deep Learning on Point Cloud via End-to-end Discovery of Spatial Keypoints. [__`oth`__]
-
- [[CVPR](https://arxiv.org/pdf/1911.11236.pdf)] RandLA-Net: Efficient Semantic Segmentation of Large-Scale Point Clouds. [[tensorflow](https://github.com/QingyongHu/RandLA-Net)] [__`seg.`__] 
- [[CVPR](https://arxiv.org/abs/2001.05119)] Learning multiview 3D point cloud registration. [[code](https://github.com/zgojcic/3D_multiview_reg)] [__`reg.`__]
- [[CVPR](https://arxiv.org/pdf/2003.00410.pdf)] PF-Net: Point Fractal Network for 3D Point Cloud Completion. [[pytorch](https://github.com/zztianzz/PF-Net-Point-Fractal-Network.git)] [__`oth.`__]
- [[CVPR](https://arxiv.org/abs/2001.10692)] ImVoteNet: Boosting 3D Object Detection in Point Clouds with Image Votes. [__`det.`__]
- [[CVPR](https://arxiv.org/pdf/2003.06233.pdf)] Fusion-Aware Point Convolution for Online Semantic 3D Scene Segmentation. [[pytorch](https://github.com/jzhzhang/FusionAwareConv)] [__`seg.`__] 
- [[CVPR](https://arxiv.org/pdf/1903.10297.pdf)] AdaCoSeg: Adaptive Shape Co-Segmentation with Group Consistency Loss. [__`seg.`__]
- [CVPR] Structure Aware Single-Stage 3D Object Detection from Point Cloud. [__`det.`__]
- 
- [[WACV](https://arxiv.org/pdf/1912.08487.pdf)] FuseSeg: LiDAR Point Cloud Segmentation Fusing Multi-Modal Data. [__`seg.`__ __`aut.`__]
- [[WACV](http://openaccess.thecvf.com/content_WACV_2020/papers/Ma_Global_Context_Reasoning_for_Semantic_Segmentation_of_3D_Point_Clouds_WACV_2020_paper.pdf)] Global Context Reasoning for Semantic Segmentation of 3D Point Clouds. [__`seg.`__]
- [[WACV](http://openaccess.thecvf.com/content_WACV_2020/papers/Chen_PonitPoseNet_Point_Pose_Network_for_Robust_6D_Object_Pose_Estimation_WACV_2020_paper.pdf)] PointPoseNet: Point Pose Network for Robust 6D Object Pose Estimation. [__`oth.`__]
-
- [[arXiv](https://arxiv.org/pdf/2003.06537.pdf)] OccuSeg: Occupancy-aware 3D Instance Segmentation. [__`seg.`__]
- [[arXiv](https://arxiv.org/pdf/2003.07356.pdf)] Scan2Plan: Efficient Floorplan Generation from 3D Scans of Indoor Scenes. [__`oth.`__]
- [[arXiv](https://arxiv.org/pdf/2003.06754.pdf)] MotionNet: Joint Perception and Motion Prediction for Autonomous Driving Based on Bird's Eye View Maps. [__`oth.`__]
- [[arXiv](https://arxiv.org/pdf/2003.07717.pdf)] Multimodal Shape Completion via Conditional Generative Adversarial Networks. [__`oth.`__]
- [[arXiv](https://arxiv.org/ftp/arxiv/papers/2002/2002.12573.pdf)] MANet: Multimodal Attention Network based Point-View fusion for 3D Shape Recognition. [__`cls.`__]
- [[arXiv](https://arxiv.org/pdf/2002.08239.pdf)] siaNMS: Non-Maximum Suppression with Siamese Networks for Multi-Camera 3D Object Detection. [__`det.`__]
- [[arXiv](https://arxiv.org/pdf/2003.03653.pdf)] SalsaNext: Fast Semantic Segmentation of LiDAR Point Clouds for Autonomous Driving. [__`seg.`__]
- [[arXiv](https://arxiv.org/pdf/2003.05982.pdf)] LaserFlow: Efficient and Probabilistic Object Detection and Motion Forecasting. [__`det.`__ __`oth.`__]
- [[arXiv](https://arxiv.org/pdf/2003.06233.pdf)] Feature Fusion Network Based on Attention Mechanism for 3D Semantic Segmentation of Point Clouds. [__`seg.`__]
- [[arXiv](https://arxiv.org/pdf/2003.05505.pdf)] Confidence Guided Stereo 3D Object Detection with Split Depth Estimation. [__`det.`__]
- [[arXiv](https://arxiv.org/pdf/2003.05593.pdf)] Learning to Segment 3D Point Clouds in 2D Image Space. [__`seg`__]
- [[arXiv](https://arxiv.org/pdf/2003.05199.pdf)] Self-supervised Point Set Local Descriptors for Point Cloud Registration. [__`reg.`__]
- [[arXiv](https://arxiv.org/pdf/2003.05410.pdf)] How Powerful Are Randomly Initialized Pointcloud Set Functions?. [__`cls.`__]
- [[arXiv](https://arxiv.org/pdf/2003.05420.pdf)] Bi-Directional Attention for Joint Instance and Semantic Segmentation in Point Clouds. [__`seg.`__]
- [[arXiv](https://arxiv.org/pdf/2003.03164.pdf)] D3Feat: Joint Learning of Dense Detection and Description of 3D Local Features. [__`cls`__]
- [[arXiv](https://arxiv.org/pdf/2003.02392.pdf)] PointLoc: Deep Pose Regressor for LiDAR Point Cloud Localization. [__`oth.`__]
- [[arXiv](https://arxiv.org/pdf/2003.00888.pdf)] 3D Object Detection From LiDAR Data Using Distance Dependent Feature Extraction. [__`det.`__]
- [[arXiv](https://arxiv.org/pdf/2003.01251.pdf)] Point-GNN: Graph Neural Network for 3D Object Detection in a Point Cloud. [[tensorflow](https://github.com/WeijingShi/Point-GNN)][__`det.`__]
- [[arXiv](https://arxiv.org/pdf/2003.00186.pdf)] HVNet: Hybrid Voxel Network for LiDAR Based 3D Object Detection. [__`det`__]
- [[arXiv](https://arxiv.org/pdf/2003.00529.pdf)] ZoomNet: Part-Aware Adaptive Zooming Neural Network for 3D Object Detection. [__`det.`__]
- [[arXiv](https://arxiv.org/pdf/2003.00492.pdf)] PointASNL: Robust Point Clouds Processing using Nonlocal Neural Networks with Adaptive Sampling. [__`cls.`__]
- [[arXiv](https://arxiv.org/pdf/2003.00601.pdf)] 3D Point Cloud Processing and Learning for Autonomous Driving. [__`oth.`__]
- [[arXiv](https://arxiv.org/pdf/2002.03281.pdf)] PointHop++: A Lightweight Learning Model on Point Sets for 3D Classification. [__`cls.`__]
-
- [[ACIIDS](https://link.springer.com/chapter/10.1007/978-3-030-41964-6_41)] Semi-supervised Representation Learning for 3D Point Clouds. [__`oth.`__]
-
- [[CG](https://www.sciencedirect.com/science/article/abs/pii/S0097849320300224)] ConvPoint: Continuous convolutions for point cloud processing. [__`oth.`__]
-
- [[ISPRS](https://www.sciencedirect.com/science/article/abs/pii/S0924271620300605)] Deep point embedding for urban classification using ALS point clouds: A new perspective from local to global. [__`oth.`__]
-
- [[Master Thesis](https://pdfs.semanticscholar.org/4303/8a62b3e3b2f44d7a9cc50ff69e7586a758cc.pdf)] Neighborhood Pooling in Graph Neural Networks for 3D and 4D Semantic Segmentation. [__'seg.'__]


<h1> 

```diff
- Datasets
```

</h1>

- [[KITTI](http://www.cvlibs.net/datasets/kitti/)] The KITTI Vision Benchmark Suite. [__`det.`__]
- [[ModelNet](http://modelnet.cs.princeton.edu/)] The Princeton ModelNet . [__`cls.`__]
- [[ShapeNet](https://www.shapenet.org/)]  A collaborative dataset between researchers at Princeton, Stanford and TTIC. [__`seg.`__]
- [[PartNet](https://shapenet.org/download/parts)] The PartNet dataset provides fine grained part annotation of objects in ShapeNetCore. [__`seg.`__]
- [[PartNet](http://kevinkaixu.net/projects/partnet.html)] PartNet benchmark from Nanjing University and National University of Defense Technology. [__`seg.`__]
- [[S3DIS](http://buildingparser.stanford.edu/dataset.html#Download)] The Stanford Large-Scale 3D Indoor Spaces Dataset. [__`seg.`__]
- [[ScanNet](http://www.scan-net.org/)] Richly-annotated 3D Reconstructions of Indoor Scenes. [__`cls.`__ __`seg.`__]
- [[Stanford 3D](https://graphics.stanford.edu/data/3Dscanrep/)] The Stanford 3D Scanning Repository. [__`reg.`__]
- [[UWA Dataset](http://staffhome.ecm.uwa.edu.au/~00053650/databases.html)] . [__`cls.`__ __`seg.`__ __`reg.`__]
- [[Princeton Shape Benchmark](http://shape.cs.princeton.edu/benchmark/)] The Princeton Shape Benchmark.
- [[SYDNEY URBAN OBJECTS DATASET](http://www.acfr.usyd.edu.au/papers/SydneyUrbanObjectsDataset.shtml)] This dataset contains a variety of common urban road objects scanned with a Velodyne HDL-64E LIDAR, collected in the CBD of Sydney, Australia. There are 631 individual scans of objects across classes of vehicles, pedestrians, signs and trees. [__`cls.`__ __`match.`__]
- [[ASL Datasets Repository(ETH)](https://projects.asl.ethz.ch/datasets/doku.php?id=home)] This site is dedicated to provide datasets for the Robotics community with the aim to facilitate result evaluations and comparisons. [__`cls.`__ __`match.`__ __`reg.`__ __`det`__]
- [[Large-Scale Point Cloud Classification Benchmark(ETH)](http://www.semantic3d.net/)] This benchmark closes the gap and provides a large labelled 3D point cloud data set of natural scenes with over 4 billion points in total. [__`cls.`__]
- [[Robotic 3D Scan Repository](http://asrl.utias.utoronto.ca/datasets/3dmap/)] The Canadian Planetary Emulation Terrain 3D Mapping Dataset is a collection of three-dimensional laser scans gathered at two unique planetary analogue rover test facilities in Canada.  
- [[Radish](http://radish.sourceforge.net/)] The Robotics Data Set Repository (Radish for short) provides a collection of standard robotics data sets.
- [[IQmulus & TerraMobilita Contest](http://data.ign.fr/benchmarks/UrbanAnalysis/#)] The database contains 3D MLS data from a dense urban environment in Paris (France), composed of 300 million points. The acquisition was made in January 2013. [__`cls.`__ __`seg.`__ __`det.`__]
- [[Oakland 3-D Point Cloud Dataset](http://www.cs.cmu.edu/~vmr/datasets/oakland_3d/cvpr09/doc/)] This repository contains labeled 3-D point cloud laser data collected from a moving platform in a urban environment.
- [[Robotic 3D Scan Repository](http://kos.informatik.uni-osnabrueck.de/3Dscans/)] This repository provides 3D point clouds from robotic experiments，log files of robot runs and standard 3D data sets for the robotics community.
- [[Ford Campus Vision and Lidar Data Set](http://robots.engin.umich.edu/SoftwareData/Ford)] The dataset is collected by an autonomous ground vehicle testbed, based upon a modified Ford F-250 pickup truck. 
- [[The Stanford Track Collection](https://cs.stanford.edu/people/teichman/stc/)] This dataset contains about 14,000 labeled tracks of objects as observed in natural street scenes by a Velodyne HDL-64E S2 LIDAR.
- [[PASCAL3D+](http://cvgl.stanford.edu/projects/pascal3d.html)] Beyond PASCAL: A Benchmark for 3D Object Detection in the Wild. [__`pos.`__ __`det.`__]
- [[3D MNIST](https://www.kaggle.com/daavoo/3d-mnist)] The aim of this dataset is to provide a simple way to get started with 3D computer vision problems such as 3D shape recognition. [__`cls.`__]
- [[WAD](http://wad.ai/2019/challenge.html)] [[ApolloScape](http://apolloscape.auto/tracking.html)] The datasets are provided by Baidu Inc. [__`tra.`__ __`seg.`__ __`det.`__]
- [[nuScenes](https://d3u7q4379vrm7e.cloudfront.net/object-detection)] The nuScenes dataset is a large-scale autonomous driving dataset.
- [[PreSIL](https://uwaterloo.ca/waterloo-intelligent-systems-engineering-lab/projects/precise-synthetic-image-and-lidar-presil-dataset-autonomous)] Depth information, semantic segmentation (images), point-wise segmentation (point clouds), ground point labels (point clouds), and detailed annotations for all vehicles and people. [[paper](https://arxiv.org/abs/1905.00160)] [__`det.`__ __`aut.`__]
- [[3D Match](http://3dmatch.cs.princeton.edu/)] Keypoint Matching Benchmark, Geometric Registration Benchmark, RGB-D Reconstruction Datasets. [__`reg.`__ __`rec.`__ __`oth.`__]
- [[BLVD](https://github.com/VCCIV/BLVD)] (a) 3D detection, (b) 4D tracking, (c) 5D interactive event recognition and (d) 5D intention prediction. [[ICRA 2019 paper](https://arxiv.org/abs/1903.06405v1)] [__`det.`__ __`tra.`__ __`aut.`__ __`oth.`__]
- [[PedX](https://arxiv.org/abs/1809.03605)] 3D Pose Estimation of Pedestrians, more than 5,000 pairs of high-resolution (12MP) stereo images and LiDAR data along with providing 2D and 3D labels of pedestrians. [[ICRA 2019 paper](https://arxiv.org/abs/1809.03605)] [__`pos.`__ __`aut.`__]
- [[H3D](https://usa.honda-ri.com/H3D)] Full-surround 3D multi-object detection and tracking dataset. [[ICRA 2019 paper](https://arxiv.org/abs/1903.01568)] [__`det.`__ __`tra.`__ __`aut.`__]
- [[Argoverse BY ARGO AI]](https://www.argoverse.org/) Two public datasets (3D Tracking and Motion Forecasting) supported by highly detailed maps to test, experiment, and teach self-driving vehicles how to understand the world around them.[[CVPR 2019 paper](http://openaccess.thecvf.com/content_CVPR_2019/html/Chang_Argoverse_3D_Tracking_and_Forecasting_With_Rich_Maps_CVPR_2019_paper.html)][__`tra.`__ __`aut.`__]
- [[Matterport3D](https://niessner.github.io/Matterport/)] RGB-D: 10,800 panoramic views from 194,400 RGB-D images. Annotations: surface reconstructions, camera poses, and 2D and 3D semantic segmentations. Keypoint matching, view overlap prediction, normal prediction from color, semantic segmentation, and scene classification. [[3DV 2017 paper](https://arxiv.org/abs/1709.06158)] [[code](https://github.com/niessner/Matterport)] [[blog](https://matterport.com/blog/2017/09/20/announcing-matterport3d-research-dataset/)]
- [[SynthCity](https://arxiv.org/abs/1907.04758)] SynthCity is a 367.9M point synthetic full colour Mobile Laser Scanning point cloud. Nine categories. [__`seg.`__ __`aut.`__]
- [[Lyft Level 5](https://level5.lyft.com/dataset/?source=post_page)] Include high quality, human-labelled 3D bounding boxes of traffic agents, an underlying HD spatial semantic map. [__`det.`__ __`seg.`__ __`aut.`__]
- [[SemanticKITTI](http://semantic-kitti.org)] Sequential Semantic Segmentation, 28 classes, for autonomous driving. All sequences of KITTI odometry labeled. [[ICCV 2019 paper](https://arxiv.org/abs/1904.01416)] [__`seg.`__ __`oth.`__ __`aut.`__]
- [[NPM3D](http://npm3d.fr/paris-lille-3d)] The Paris-Lille-3D  has been produced by a Mobile Laser System (MLS) in two different cities in France (Paris and Lille). [__`seg.`__] 
- [[The Waymo Open Dataset](https://waymo.com/open/)] The Waymo Open Dataset is comprised of high resolution sensor data collected by Waymo self-driving cars in a wide variety of conditions. [__`det.`__]
- [[A*3D: An Autonomous Driving Dataset in Challeging Environments](https://github.com/I2RDL2/ASTAR-3D)] A*3D: An Autonomous Driving Dataset in Challeging Environments. [__`det.`__]
- [[PointDA-10 Dataset](https://github.com/canqin001/PointDAN)] Domain Adaptation for point clouds.
- [[Oxford Robotcar](https://robotcar-dataset.robots.ox.ac.uk/)] The dataset captures many different combinations of weather, traffic and pedestrians. [__`cls.`__ __`det.`__ __`rec.`__]
- [[WHU-TLS BENCHMARK](http://3s.whu.edu.cn/ybs/en/benchmark.htm)] WHU-TLS benchmark dataset. [__`reg.`__]
