# Paper-Reading

## Table of Contents
- [Image-Restoration](#Image-Restoration)
- [Image-Deblur](#Image-Deblur)
- [Image-DefocusDeblur](#Image-DefocusDeblur)
- [Image-SuperResolution](#Image-SuperResolution)


## Image-Restoration
| Paper | Link | Code |
| - | - | - | 
| Multi-Stage Progressive Image Restoration | [CVPR 2021](https://arxiv.org/abs/2102.02808) | [MPRNet](https://github.com/swz30/MPRNet) |
| SwinIR: Image Restoration Using Swin Transformer | [ICCV 2021](https://arxiv.org/abs/2108.10257) | [SwinIR](https://github.com/JingyunLiang/SwinIR) |
| Uformer: A General U-Shaped Transformer for Image Restoration | [CVPR 2022](https://arxiv.org/abs/2106.03106) | [Uformer](https://github.com/ZhendongWang6/Uformer) |
| Restormer: Efficient Transformer for High-Resolution Image Restoration | [CVPR 2022](https://arxiv.org/abs/2111.09881) | [Restormer](https://github.com/swz30/Restormer) |
| Improving Image Restoration by Revisiting Global Information Aggregation | [ECCV 2022](https://arxiv.org/abs/2112.04491)      | [TLC](https://github.com/megvii-research/TLC) |
| Simple Baselines for Image Restoration | [ECCV2022](https://arxiv.org/abs/2407.18046)      | [NAFNet](https://github.com/megvii-research/NAFNet) |
| Revitalizing Convolutional Network for Image Restoration | [TPAMI 2024](https://ieeexplore.ieee.org/abstract/document/10571568) | [ConvIR](https://github.com/c-yn/ConvIR) |
| MambaIR: A Simple Baseline for Image Restoration with State-Space Model | [ECCV 2024](https://arxiv.org/pdf/2411.15269) | [MambaIR](https://github.com/csguoh/MambaIR) |

## Image-Deblur

| Paper | Link | Code |
| - | - | - | 
| Learning a convolutional neural network for non-uniform motion blur removal | [CVPR 2015](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Sun_Learning_a_Convolutional_2015_CVPR_paper.pdf)|[Code 1](http://gr.xjtu.edu.cn/c/document_library/get_file?folderId=2076150&name=DLFE-78101.zip), [Code 2](https://github.com/Sibozhu/MotionBlur-detection-by-CNN) |
| Learning to deblur | [TPAMI 2016](https://arxiv.org/pdf/1406.7444.pdf)|  |
| Deep Multi-scale Convolutional Neural Network for Dynamic Scene Deblurring | [CVPR 2017](https://openaccess.thecvf.com/content_cvpr_2017/papers/Nah_Deep_Multi-Scale_Convolutional_CVPR_2017_paper.pdf) | [DeepDeblur](https://github.com/SeungjunNah/DeepDeblur_release), [GoPro](https://seungjunnah.github.io/Datasets/gopro) |
| Motion blur kernel estimation via deep learning | [TIP 2018](https://ieeexplore.ieee.org/abstract/document/8039224)|[Code & Project page](https://sites.google.com/view/xiangyuxu/deepedge_tip)|
| Dynamic Scene Deblurring Using Spatially Variant Recurrent Neural Networks | [CVPR 2018](http://openaccess.thecvf.com/content_cvpr_2018/html/Zhang_Dynamic_Scene_Deblurring_CVPR_2018_paper.html)|[Code](https://github.com/zhjwustc/cvpr18_rnn_deblur_matcaffe)|
| Scale-recurrent network for deep image deblurring | [CVPR 2018](http://openaccess.thecvf.com/content_cvpr_2018/html/Tao_Scale-Recurrent_Network_for_CVPR_2018_paper.html)|[SRN](https://github.com/jiangsutx/SRN-Deblur) |
|Deblurgan: Blind motion deblurring using conditional adversarial networks | [CVPR 2018](http://openaccess.thecvf.com/content_cvpr_2018/html/Kupyn_DeblurGAN_Blind_Motion_CVPR_2018_paper.html)|[DeblurGAN](https://github.com/KupynOrest/DeblurGAN)|
| Deep Stacked Hierarchical Multi-Patch Network for Image Deblurring| [CVPR2019](http://openaccess.thecvf.com/content_CVPR_2019/html/Zhang_Deep_Stacked_Hierarchical_Multi-Patch_Network_for_Image_Deblurring_CVPR_2019_paper.html)|[DMPHN](https://github.com/HongguangZhang/DMPHN-cvpr19-master)|
|DeblurGAN-v2: Deblurring (Orders-of-Magnitude) Faster and Better| [ICCV 2019](https://arxiv.org/abs/1908.03826)|[DeblurGANv2](https://github.com/TAMU-VITA/DeblurGANv2)|
| Human-Aware Motion Deblurring | [ICCV 2019](https://arxiv.org/pdf/2001.06816)| [HIDE](https://github.com/joanshen0508/HA_deblur) |
|Tell Me Where It is Still Blurry: Adversarial Blurred Region Mining and Refining | [ACM MM 2019](https://www.iis.sinica.edu.tw/papers/liutyng/22871-F.pdf)| |
| Real-World Blur Dataset for Learning and Benchmarking Deblurring Algorithms | [ECCV 2020](https://cg.postech.ac.kr/research/realblur/) | [RealBlur](https://cg.postech.ac.kr/research/realblur/) |
| Rethinking Coarse-to-Fine Approach in Single Image Deblurring | [ICCV 2021](https://arxiv.org/abs/2108.05054) | [MIMO-UNet](https://github.com/chosj95/MIMO-UNet) |
| Deep Residual Fourier Transformation for Single Image Deblurring | [arXiv 2021](https://arxiv.org/abs/2111.11745v1)                        | [DeepRFT-v1](https://github.com/INVOKERer/DeepRFT) |
| Intriguing Findings of Frequency Selection for Image Deblurring | [AAAI 2023](https://ojs.aaai.org/index.php/AAAI/article/view/25281) | [DeepRFT-v1.5](https://github.com/INVOKERer/DeepRFT/tree/AAAI2023) |
| Self-supervised Non-uniform Kernel Estimation with Flow-based Motion Prior for Blind Image Deblurring | [CVPR 2023](https://openaccess.thecvf.com/content/CVPR2023/papers/Fang_Self-Supervised_Non-Uniform_Kernel_Estimation_With_Flow-Based_Motion_Prior_for_Blind_CVPR_2023_paper.pdf) | [UFPNet](https://github.com/Fangzhenxuan/UFPDeblur) |
| Effcient Frequence Domain-based Transformer for High-Quality Image Deblurring | [CVPR 2023](https://openaccess.thecvf.com/content/CVPR2023/papers/Kong_Efficient_Frequency_Domain-Based_Transformers_for_High-Quality_Image_Deblurring_CVPR_2023_paper.pdf) | [FFTformer](https://github.com/kkkls/FFTformer) |
| LoFormer: Local Frequency Transformer for Image Deblurring | [ACM MM 2024](https://arxiv.org/abs/2407.16993)                             | [LoFormer](https://github.com/INVOKERer/LoFormer) |
| Learning Enriched Features via Selective State Spaces Model for Efficient Image Deblurring | [ACM MM 2024](https://arxiv.org/pdf/2403.20106) | [ALGNet](https://github.com/Tombs98/ALGNet)|
| Motion-adaptive Separable Collaborative Filters for Blind Motion Deblurring | [CVPR 2024](https://openaccess.thecvf.com/content/CVPR2024/html/Liu_Motion-adaptive_Separable_Collaborative_Filters_for_Blind_Motion_Deblurring_CVPR_2024_paper.html) | [MISCFilter](https://github.com/ChengxuLiu/MISCFilter) | 
| AdaRevD: Adaptive Patch Exiting Reversible Decoder Pushes the Limit of Image Deblurring | [CVPR 2024](https://arxiv.org/abs/2406.09135)  | [AdaRevD](https://github.com/INVOKERer/AdaRevD) |
| Efficient Visual State Space Model for Image Deblurring | [CVPR 2025](https://arxiv.org/abs/2405.14343) | [EVSSM](https://github.com/kkkls/EVSSM)|

## Image-DefocusDeblur
| Paper | Link | Code |
| - | - | - | 
| Defocus Deblurring Using Dual-Pixel Data | [ECCV 2020](https://arxiv.org/abs/2005.00305) | [DPDD](https://github.com/Abdullah-Abuolaim/defocus-deblurring-dual-pixel)|

## Image-SuperResolution
| Paper | Link | Code |
| - | - | - | 
| ClassSR: A General Framework to Accelerate Super-Resolution Networks by Data Characteristic| [CVPR 2021](https://openaccess.thecvf.com/content/CVPR2021/papers/Kong_ClassSR_A_General_Framework_to_Accelerate_Super-Resolution_Networks_by_Data_CVPR_2021_paper.pdf) | [ClassSR](https://github.com/XPixelGroup/ClassSR) |
| Adaptive Patch Exiting for Scalable Single Image Super-Resolution | [ECCV 2022](https://arxiv.org/abs/2203.11589v2) | [APE-SR](https://github.com/littlepure2333/APE) |
| Transcending the Limit of Local Window: Advanced Super-Resolution Transformer with Adaptive Token Dictionary | [CVPR 2024](https://arxiv.org/abs/2401.08209) | [ATD](https://github.com/LabShuHangGU/Adaptive-Token-Dictionary) |
| GaussianSR: High Fidelity 2D Gaussian Splatting for Arbitrary-Scale Image Super-Resolution | [AAAI 2025](https://arxiv.org/abs/2407.18046) | [GaussianSR](https://github.com/tljxyys/GaussianSR) |
