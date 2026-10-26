# CVBL-CCTV-Face Dataset

**CVBL-CCTV-Face Dataset for Real-World Face Enhancement and Recognition in Surveillance**

**Manish Das, Ajay Kumar Yadav, Shiv Ram Dubey, and Satish Kumar Singh**

Computer Vision and Biometrics Lab (CVBL), Indian Institute of Information Technology Allahabad, India.

## Introduction

The **CVBL-CCTV-Face Dataset** is a real-world facial image dataset developed for face enhancement and recognition under challenging CCTV surveillance conditions. Unlike conventional face datasets that primarily contain high-quality or synthetically degraded facial images, the proposed dataset consists of authentic low-quality (LQ) face images captured using an 8MP IP Dome CCTV camera (EW-IP8050D) in unconstrained indoor environments. The corresponding high-quality (HQ) reference images are acquired independently under controlled conditions, resulting in an unpaired dataset without spatial alignment between LQ and HQ images.

The dataset contains **18,376 facial images from 223 unique identities**, comprising 15,662 low-quality CCTV images and 2,714 high-quality reference images. It is provided in two versions: **Version A** contains 8,090 LQ images and 102 HQ images from 102 identities, with one HQ reference per identity, while **Version B** contains 7,572 LQ images and 2,612 HQ images from 130 identities, with 15–25 HQ references per identity. The two versions share nine identities, resulting in 223 unique identities in the complete dataset.

The proposed dataset presents several real-world surveillance challenges, including motion blur, low resolution, illumination variations, sensor noise, partial occlusions, accessories such as caps, non-frontal poses, downward head orientations, and partially visible faces. These naturally occurring degradations make the dataset suitable for evaluating face enhancement, super-resolution, and recognition methods under realistic surveillance conditions.

## Sample Images

![CVBL-CCTV-Face Dataset Samples](CVBL_CCTV_Face_Samples.png)

**Figure 1:** Sample images from the proposed CVBL-CCTV-Face Dataset. The top row shows high-quality (HQ) reference images acquired under controlled conditions, while the bottom row presents corresponding low-quality (LQ) facial images captured using a CCTV camera.

## Challenges in the Dataset

The CVBL-CCTV-Face Dataset includes several challenging facial appearances commonly encountered in real-world surveillance environments:

- **Blurred Faces:** Motion blur and defocus reduce facial clarity and visibility.
- **Occlusions by Accessories:** Caps and other accessories partially obscure important facial features.
- **Partially Visible Faces:** Facial regions are obstructed by doors, walls, or other environmental objects.
- **Pose Variations:** Side-facing and non-frontal faces exhibit significant changes in facial appearance.
- **Downward Head Poses:** Downward-facing subjects obscure important facial landmarks such as the eyes and mouth.

![CVBL-CCTV-Face Dataset Challenges](CVBL_CCTV_Face_Challenges.png)

**Figure 2:** Representative challenges in the proposed CVBL-CCTV-Face Dataset. The rows from top to bottom illustrate blurred faces, faces occluded by caps, partially visible faces, side-facing poses, and downward head poses.

## Download CVBL-CCTV-Face Dataset

To obtain the CVBL-CCTV-Face Dataset, kindly download and complete the **[License Agreement Form](LICENSE_AGREEMENT_CVBL_CCTV_FACE.pdf)** and send the signed form to **srdubey@iiita.ac.in**.

The dataset is available for approved research purposes. The download link will be provided after verification and approval of the license agreement.

Redistribution or unauthorized sharing of the dataset is not permitted.

## Citation

Any research work or publication based directly or indirectly on the CVBL-CCTV-Face Dataset should include the following reference:

M. Das, A. K. Yadav, S. R. Dubey, and S. K. Singh, "CVBL-CCTV-Face Dataset for Real-World Face Enhancement and Recognition in Surveillance", 5th IEEE International Conference on Computer Vision and Machine Intelligence (CVMI), Pune, India, Oct.–Nov. 2026 (Accepted).
