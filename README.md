# *(TMM2026) Multi-Proxy Quality-Aware Learning and Classifier Calibration for Few-Shot Incremental Fine-Grained Remote Sensing Classification.

📄 **[IEEE TMM Paper](https://ieeexplore.ieee.org/abstract/document/11466468)**

🚧 **This repository is under construction. Code will be released soon.**

This repository will contain the official implementation of our paper:

> **Multi-Proxy Quality-Aware Learning and Classifier Calibration for Few-Shot Incremental Fine-Grained Remote Sensing Classification**
> IEEE Transactions on Multimedia (TMM), 2026

---

## 🔥 Overview

Few-shot incremental fine-grained remote sensing classification (FSFG-RS) is a challenging problem due to:

* **Severe data scarcity** for novel classes
* **Fine-grained inter-class similarity**
* **Catastrophic forgetting** during incremental updates

To address these issues, we propose a novel framework with:

* **Multi-Proxy Quality-Aware Learning**

  * Introduces multiple proxies to capture intra-class variations
  * Incorporates quality-aware weighting to suppress noisy samples

* **Classifier Calibration Strategy**

  * Mitigates bias between base and novel classes
  * Improves decision boundary alignment under incremental settings

---

## 📊 Status

* [x] Paper published (TMM 2026)
* [ ] Code cleaning
* [ ] Training scripts
* [ ] Pretrained models

---

## 📄 Paper

* IEEE: https://ieeexplore.ieee.org/abstract/document/11466468

---

## 📌 TODO

* [ ] Release training and evaluation code
* [ ] Provide dataset preparation scripts
* [ ] Upload pretrained models
* [ ] Add detailed usage instructions

---

## 🧪 Planned Usage

### Training

```bash
bash tools/train.sh configs/mpqcl_base.py
```

### Incremental Fine-tuning

```bash
bash tools/train.sh configs/mpqcl_incremental.py
```

### Evaluation

```bash
bash tools/test.sh configs/mpqcl_incremental.py checkpoint.pth
```

---

## 📖 Citation

```bibtex
@article{jiang2026multi,
  title={Multi-Proxy Quality-Aware Learning and Classifier Calibration for Few-Shot Incremental Fine-Grained Remote Sensing Classification},
  author={Jiang, Haoran and Zhang, Junjie and Xu, Wenbo and Zeng, Dan and Zhang, Jian},
  journal={IEEE Transactions on Multimedia},
  year={2026},
  publisher={IEEE}
}
```

---

## 📬 Contact

If you have any questions, feel free to open an issue or contact the authors (jianghaoran@shu.edu.cn).
