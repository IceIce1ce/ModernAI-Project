# Modern AI Project

![arch](assets/arch.png)

## 1. Introduction

<!-- [ALGORITHM] -->

```BibTeX
@article{ho2020denoising,
  title={Denoising diffusion probabilistic models},
  author={Ho, Jonathan and Jain, Ajay and Abbeel, Pieter},
  journal={Advances in neural information processing systems},
  volume={33},
  pages={6840--6851},
  year={2020}
}
```

## 2. To install the environment, run the following script:
```shell
pip install -e .
```

## 3. To extract the dataset, run the following script:
```shell
bash scripts/extract_dataset.sh
```

## 4. To train and test the model, run the following scripts:
```shell
bash scripts/train.sh
bash scripts/test.sh
```

## 5. To add Gaussian noise and test a facial image, run the following scripts:
```shell
bash scripts/add_noise.sh
bash scripts/test_face.sh
```

## 6. Contact
If you have any questions, feel free to contact `Chi Tran`
([ctran743@gmail.com](ctran743@gmail.com) or [tdc2000@skku.edu](tdc2000@skku.edu)).