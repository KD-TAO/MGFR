
# MGFR: **Overcoming False Illusions in Real-World Face Restoration with Multi-Modal Guided Diffusion Model**

Keda Tao, [Jinjin Gu*](https://www.jasongt.com/), [Yulun Zhang](http://yulunzhang.com/),  Xiucheng Wang and Nan Cheng, "Overcoming False Illusions in Real-World Face Restoration with Multi-Modal Guided Diffusion Model"

<p align="center">    <img src="fig/M.png" style="border-radius: 15px"></p>

[arXiv](https://arxiv.org/abs/2410.04161) [Reface-HQ](https://drive.google.com/file/d/1EUQlRCZaoG9eKMoJ8mWaHW5kqvhL0elY/view?usp=sharing)

#### 🔥🔥🔥 News

- **2025-1-22:** Our paper has been accepted by ICLR 2025 (Spotlight)!.
- **2025-4-22:** The new dataset we proposed-Reface-HQ-has been released.
  
---

> **Abstract:** We introduce a novel Multi-modal Guided Real-World Face Restoration (MGFR) technique designed to improve the quality of facial image restoration from low-quality inputs. Leveraging a blend of attribute text prompts, high-quality reference images, and identity information, MGFR can mitigate the generation of false facial attributes and identities often associated with generative face restoration methods. By incorporating a dual-control adapter and a two-stage training strategy, our method effectively utilizes multi-modal prior information for targeted restoration tasks. We also present the Reface-HQ dataset, comprising over 21,000 high-resolution facial images across 4800 identities, to address the need for reference face training images. Our approach achieves superior visual quality in restoring facial details under severe degradation and allows for controlled restoration processes, enhancing the accuracy of identity preservation and attribute correction. Including negative quality samples and attribute prompts in the training further refines the model's ability to generate detailed and perceptually accurate images.

## ⚒️ TODO

* [x] Release Reface-HQ dataset.
* [ ] Release code and pretrained models.

## :sparkles: Reface-HQ Dataset
We introduce a novel, high-quality dataset tailored for reference-based face image restoration tasks, which is now publicly accessible. The dataset comprises face images from over 4,800 unique identities, offering an expanded pool of training samples at higher image resolutions.
### Download
- [Reface-HQ](https://drive.google.com/file/d/1EUQlRCZaoG9eKMoJ8mWaHW5kqvhL0elY/view?usp=sharing) [Reface-Test](https://drive.google.com/file/d/196UvnatfexBw97SZ7OXXFKQ_XIJ4jl7O/view?usp=sharing)
<p align="center">    <img src="fig/D.png" style="border-radius: 15px"></p>

## :eyes: Visual Results
### Face Restoration

<p align="center">    <img src="fig/R1.png" style="border-radius: 15px"></p>

<p align="center">    <img src="fig/R2.png" style="border-radius: 15px"></p>

## Acknowledgement

This project is based on [ControlNet](https://github.com/lllyasviel/ControlNet). Thanks for their awesome work.

## Contact

If you have any questions, please feel free to contact with me at KD.TAO@outlook.com
