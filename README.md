# Awesome Anomaly Detection in Medical Images
A curated list of awesome anomaly detection works in medical imaging, inspired by the other awesome-* initiatives.

For a complete list of anomaly detection in general computer vision, please visit [awesome anomaly detection](https://github.com/hoya012/awesome-anomaly-detection).

--- Last updated: Aug. 10, 2020 ---

To complement or correct it, please contact me at **zhoukang [at] shanghaitech [dot] edu [dot] cn** or send a pull request.

## Overview
- [Deep learning based methods](#deep-learning-based-methods)
  * [Brain MRI](#brain-mri)
  * [Brain CT](#brain-ct)
  * [Retinal OCT](#retinal-oct)
  * [Retinal fundus](#retinal-fundus)
  * [Chest X-Ray in CT](#chest-x-ray-in-ct)
  * [Other modalities](#other-modalities)
- [Non-deep learning based methods](#non-deep-learning-based-methods)
  * [Brain MRI](#brain-mri-1)
- [Some works that related to anomaly detection](#some-works-that-related-to-anomaly-detection)
- [Not yet public (MICCAI 2020)](#not-yet-public)

# Deep learning based methods
## Brain MRI
- [Alex _et. al._] [Generative adversarial networks for brain lesion detection] [Medical Imaging 2017: Image Processing] [[google scholar]](https://scholar.google.at/scholar?q=Generative+adversarial+networks+for+brain+lesion+detection&hl=zh-CN&as_sdt=0&as_vis=1&oi=scholart) [[pdf]](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/10133/1/Generative-adversarial-networks-for-brain-lesion-detection/10.1117/12.2254487.full?SSO=1)
- [Chen _et. al._] [Unsupervised Detection of Lesions in Brain MRI using constrained adversarial auto-encoders] [MIDL'18] [[google scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Unsupervised+Detection+of+Lesions+in+Brain+MRI+using+constrained+adversarial+auto-encoders&btnG=) [[pdf]](https://arxiv.org/abs/1806.04972)
- [Chen _et. al._] [Deep generative models in the real-world: An open challenge from medical imaging] [arxiv, 2018] [[google scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Deep+generative+models+in+the+real-world%3A+An+open+challenge+from+medical+imaging&btnG=) [[pdf]](https://arxiv.org/abs/1806.05452)
- [Chen _et. al._] [Unsupervised lesion detection via image restoration with a normative prior] [MIA, 2020] [[google scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Unsupervised+lesion+detection+via+image+restoration+with+a+normative+prior&btnG=) [[pdf]](https://www.sciencedirect.com/science/article/pii/S1361841520300773)
- [Baur _et. al._] [Deep Autoencoding Models for Unsupervised Anomaly Segmentation in Brain MR Images] [MICCAI'18 workshop] [[google scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Deep+Autoencoding+Models+for+Unsupervised+Anomaly+Segmentation+in+Brain+MR+Images&btnG=) [[pdf]](https://link.springer.com/chapter/10.1007/978-3-030-11723-8_16)
- [Baur _et. al._] [Fusing unsupervised and supervised deep learning for white matter lesion segmentation] [MIDL'19] [[google scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Fusing+Unsupervised+and+Supervised+Deep+Learning+for+White+Matter+Lesion+Segmentation&btnG=) [[pdf]](https://openreview.net/forum?id=ryxNhZGlxV)
- [Baur _et. al._] [Bayesian Skip-Autoencoders for Unsupervised Hyperintense Anomaly Detection in High Resolution Brain Mri] [ISBI'20] [[google scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Bayesian+Skip-Autoencoders+for+Unsupervised+Hyperintense+Anomaly+Detection+in+High+Resolution+Brain+Mri&btnG=) [[pdf]](https://ieeexplore.ieee.org/abstract/document/9098686/)
- [Baur _et. al._] [Autoencoders for Unsupervised Anomaly Segmentation in Brain MR Images: A Comparative Study] [arxiv, 2020] [[google scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Autoencoders+for+Unsupervised+Anomaly+Segmentation+in+Brain+MR+Images%3A+A+Comparative+Study&btnG=) [[pdf]](https://arxiv.org/abs/2004.03271)
- [Baur _et. al._] [Scale-Space Autoencoders for Unsupervised Anomaly Segmentation in Brain MRI] [MICCAI'20] [[google scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Scale-Space+Autoencoders+for+Unsupervised+Anomaly+Segmentation+in+Brain+MRI&btnG=) [[pdf]](https://arxiv.org/abs/2006.12852)
- [Zimmerer _et. al._] [Context-encoding Variational Autoencoder for Unsupervised Anomaly Detection] [MIDL'19] [[google scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Context-encoding+Variational+Autoencoder+for+Unsupervised+Anomaly+Detection&btnG=) [[pdf]](https://openreview.net/forum?id=BylLiVXptV)
- [Zimmerer _et. al._] [Unsupervised Anomaly Localization using Variational Auto-Encoders] [MICCAI'19] [[google scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Unsupervised+Anomaly+Localization+using+Variational+Auto-Encoders&btnG=) [[pdf]](https://link.springer.com/chapter/10.1007/978-3-030-32251-9_32)
- [Zimmerer _et. al._] [High-and Low-level image component decomposition using VAEs for improved reconstruction and anomaly detection] [arxiv, 2019] [[google scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=High-and+Low-level+image+component+decomposition+using+VAEs+for+improved+reconstruction+and+anomaly+detection&btnG=) [[pdf]](https://arxiv.org/abs/1911.12161)
- [Han _et. al._] [MADGAN: unsupervised Medical Anomaly Detection GAN using multiple adjacent brain MRI slice reconstruction] [arxiv, 2020] [[google scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=MADGAN%3A+unsupervised+Medical+Anomaly+Detection+GAN+using+multiple+adjacent+brain+MRI+slice+reconstruction&btnG=) [[pdf]](https://arxiv.org/abs/2007.13559)
- [Zhou _et. al._] [Unsupervised anomaly localization using VAE and beta-VAE] [arxiv, 2020] [[google scholar]](https://scholar.google.at/scholar?hl=zh-CN&as_sdt=0%2C5&as_vis=1&q=Unsupervised+anomaly+localization+using+VAE+and+beta-VAE&btnG=) [[pdf]](https://arxiv.org/abs/2005.10686)

## Brain CT
- [Pawlowski _et. al._] [Unsupervised lesion detection in brain CT using bayesian convolutional autoencoders] [MIDL'18] [[google scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Unsupervised+lesion+detection+in+brain+CT+using+bayesian+convolutional+autoencoders&btnG=) [[pdf]](https://openreview.net/forum?id=S1hpzoisz)

## Retinal OCT
- [Schlegl _et. al._] [Unsupervised Anomaly Detection with Generative Adversarial Networks to Guide Marker Discovery (**AnoGAN**)] [IPMI'17] [[google scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Unsupervised+Anomaly+Detection+with+Generative+Adversarial+Networks+to+Guide+Marker+Discovery&btnG=) [[pdf]](https://optima.meduniwien.ac.at/fileadmin/PublicationPDFs/2017_schlegl_arxiv.pdf)[[unofficial code]](https://github.com/LeeDoYup/AnoGAN-tf)
- [Schlegl _et. al._] [f-AnoGAN: Fast unsupervised anomaly detection with generative adversarial networks] [MIA, 2019] [[google scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=f-AnoGAN%3A+Fast+unsupervised+anomaly+detection+with+generative+adversarial+networks&btnG=) [[pdf]](https://www.sciencedirect.com/science/article/abs/pii/S1361841518302640)[[code]](https://github.com/tSchlegl/f-AnoGAN)
- [Seebock _et. al._] [Exploiting Epistemic Uncertainty of Anatomy Segmentation for Anomaly Detection in Retinal OCT] [TMI, 2019] [[google scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=xploiting+Epistemic+Uncertainty+of+Anatomy+Segmentation+for+Anomaly+Detection+in+Retinal+OCT&btnG=) [[pdf]](https://ieeexplore.ieee.org/abstract/document/8727461)
- [Zhang _et. al._] [Memory-Augmented Anomaly Generative Adversarial Network for Retinal OCT Images Screening] [ISBI'20] [[google scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Memory-Augmented+Anomaly+Generative+Adversarial+Network+for+Retinal+OCT+Images+Screening&btnG=) [[pdf]](https://ieeexplore.ieee.org/abstract/document/9098717)
- [Zhou _et. al._] [Sparse-GAN: Sparsity-constrained Generative Adversarial Network for Anomaly Detection in Retinal OCT Image] [ISBI'20] [[google scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Sparse-GAN%3A+Sparsity-constrained+Generative+Adversarial+Network+for+Anomaly+Detection+in+Retinal+OCT+Image&btnG=) [[pdf]](https://ieeexplore.ieee.org/abstract/document/9098374)
- [Zhou _et. al._] [Encoding Structure-Texture Relation with P-Net for Anomaly Detection in Retinal Images] [ECCV'20] [[pdf]](http://zhoukang.pro/paper/2020_ECCV_pnet.pdf.pdf)[[code]](https://github.com/ClancyZhou/P_Net_Anomaly_Detection)

## Retinal fundus
- [Zhou _et. al._] [Encoding Structure-Texture Relation with P-Net for Anomaly Detection in Retinal Images] [ECCV'20] [[pdf]](http://zhoukang.pro/paper/2020_ECCV_pnet.pdf.pdf)[[code]](https://github.com/ClancyZhou/P_Net_Anomaly_Detection)

## Chest X-Ray in CT
- [Tang _et. al._] [Abnormal Chest X-ray Identification With Generative Adversarial One-Class Classifier] [ISBI'19] [[google scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Abnormal+Chest+X-ray+Identification+With+Generative+Adversarial+One-Class+Classifier&btnG=) [[pdf]](https://arxiv.org/abs/1903.02040)
- [Zhang _et. al._] [Viral Pneumonia Screening on Chest X-ray Images Using Confidence-Aware Anomaly Detection] [arxiv, 2020] [[google scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Viral+Pneumonia+Screening+on+Chest+X-ray+Images+Using+Confidence-Aware+Anomaly+Detection&btnG=) [[pdf]](https://arxiv.org/abs/2003.12338)
- [Wolleb _et. al._] [DeScarGAN: Disease-Specific Anomaly Detection with Weak Supervision] [MICCAI'20] [[google scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=DeScarGAN%3A+Disease-Specific+Anomaly+Detection+with+Weak+Supervision&btnG=) [[pdf]](https://arxiv.org/abs/2007.14118)[[code]](https://github.com/JuliaWolleb/DeScarGAN)

## Other modalities
- [Tian _et. al._] [Few-Shot Anomaly Detection for Polyp Frames from Colonoscopy] [MICCAI'20] [[google scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Few-Shot+Anomaly+Detection+for+Polyp+Frames+from+Colonoscopy&btnG=) [[pdf]](https://arxiv.org/abs/2006.14811)[[code]](https://github.com/tianyu0207/FSAD-Net)

# Non-deep learning based methods
## Brain MRI
- [Chen _et. al._] [Unsupervised Lesion Detection with Locally Gaussian Approximation] [MLMI'19] [[google scholar]](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=Unsupervised+Lesion+Detection+with+Locally+Gaussian+Approximation&btnG=) [[pdf]](https://link.springer.com/chapter/10.1007/978-3-030-32692-0_41)

# Some works that related to anomaly detection
- [Zhang _et. al._] [Cascaded Generative and Discriminative Learning for Microcalcification Detection in Breast Mammograms] [ICCV'19] [[google scholar]](https://scholar.google.at/scholar?hl=zh-CN&as_sdt=0%2C5&as_vis=1&q=Cascaded+Generative+and+Discriminative+Learning+for+Microcalcification+Detection+in+Breast+Mammograms&btnG=) [[pdf]](https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhang_Cascaded_Generative_and_Discriminative_Learning_for_Microcalcification_Detection_in_Breast_CVPR_2019_paper.pdf)
- [Siddiquee _et. al._] [Learning Fixed Points in Generative Adversarial Networks: From Image-to-Image Translation to Disease Detection and Localization] [ICCV'19] [[google scholar]](https://scholar.google.at/scholar?hl=zh-CN&as_sdt=0%2C5&as_vis=1&q=Learning+Fixed+Points+in+Generative+Adversarial+Networks%3A+From+Image-to-Image+Translation+to+Disease+Detection+and+Localization&btnG=) [[pdf]](https://openaccess.thecvf.com/content_ICCV_2019/papers/Siddiquee_Learning_Fixed_Points_in_Generative_Adversarial_Networks_From_Image-to-Image_Translation_ICCV_2019_paper.pdf)

# Not yet public
- [SteGANomaly: Inhibiting CycleGAN Steganography for Unsupervised Anomaly Detection in Brain MRI] [MICCAI'20]
- [SALAD: Self-Supervised Aggregation Learning for Anomaly Detection on X-Rays] [MICCAI'20]
- [Robust Layer Segmentation against Complex Retinal Abnormalities for en face OCTA Generation] [MICCAI'20]
- [Abnormality Detection on Chest X-ray Using Uncertainty Prediction Auto-Encoders] [MICCAI'20]
 