# PrivaT5: A Generative Language Model for Privacy Policies

Welcome to the PrivaT5 repository! This repository hosts the pre-trained PrivaT5 models, designed to enhance understanding and generation of privacy policy content.

## Introduction

This repository contains the models for the paper [PrivaT5: A Generative Language Model for Privacy Policies](https://aclanthology.org/2024.privatenlp-1.16.pdf).

In the digital age, privacy policies are essential for informing users about how their data is collected, used, and shared. Despite their importance, these documents are often lengthy, complex, and difficult to understand for the average user. To address this issue, we introduce PrivaT5, a generative language model based on T5, pre-trained specifically on privacy policy texts. PrivaT5 aims to make privacy policies more accessible and comprehensible.

PrivaT5 leverages the power of continued domain-specific pre-training to excel in privacy policy-related tasks. By building on the T5 architecture and training on a large corpus of privacy policy documents, PrivaT5 offers improved performance and understanding in this niche but critical domain.

## Models

We provide three pre-trained variants of PrivaT5 to cater to different computational needs and performance requirements:

- **PrivaT5-Small:** 60M parameters
- **PrivaT5-Base:** 220M parameters
- **PrivaT5-Large:** 770M parameters

You can download the pre-trained models from the following links:

- [PrivaT5-Small](https://huggingface.co/alzoubi36/priva_t5-small)
- [PrivaT5-Base](https://huggingface.co/alzoubi36/priva_t5-base)
- [PrivaT5-Large](https://huggingface.co/alzoubi36/priva_t5-large)

## Citation

If you use PrivaT5 in your research or application, please cite our paper:

```
@article{alzoubi2024privat5,
  title={PrivaT5: A Generative Language Model for Privacy Policies},
  author={Al Zoubi, Mohammad and Tokala, Santosh T.Y.S.S and Chavez Rosas, Edgar Ricardo and Grabmair, Matthias},
  journal={ACL PrivacyNLP Workshop},
  year={2024}
}
```


## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.