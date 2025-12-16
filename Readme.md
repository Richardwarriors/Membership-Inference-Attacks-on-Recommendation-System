# 📘 **Membership Inference Attacks on Recommender Systems (RecSys) – Literature Repository**

A curated, up-to-date collection of **membership inference attacks (MIAs)** and **defense mechanisms** for **recommender systems**.

This repository accompanies our survey paper and aims to help researchers, practitioners, and students quickly navigate existing work on privacy risks in RecSys.
Papers are grouped based on their publication type, datasets, attack setting, model family, and targeted recommendation task.

We continuously update this repository and welcome contributions from the community.

----

## 🔗 **Paper Link (Survey)**

> *[Membership Inference Attacks on Recommender Systems: A Comprehensive Survey](https://richardwarriors.github.io/RecSys_MIA_overview.pdf)*
> (*under review ACM computer survey.*)

If this repository is helpful, please consider citing the survey above.

---

## 📚 **What This Repository Contains**

* ✔ A complete list of **published and preprint papers** on **RecSys MIAs**

* ✔ Links to **original papers**, **official code**, and **reproduction repositories**

* ✔ Categorization by
  
  * attack type (user-level, interaction-level, social-level)
  * adversarial knowledge (white-box, black-box)

* ✔ Summary tables for quick comparison

* ✔ Defense and mitigation techniques

---

# 📘 **Membership Inference Attacks on Recommender Systems (RecSys) – Literature Repository**

This repository maintains a comprehensive and continuously updated list of **membership inference attacks (MIAs)** and **defenses** in **Recommender Systems (RecSys)**.
It accompanies our survey on RecSys MIAs and is intended to support researchers, practitioners, and students working on privacy threats in recommendation systems.

---

## 🔗 **Quick Links**

### Attack papers sorted by year

| [2025](#attack-papers-2025) | [2024](#attack-papers-2024) | [2023](#attack-papers-2023) | [2022](#attack-papers-2022) | [2021](#attack-papers-2021) | 

### Defense papers sorted by year

| [2025](#defense-papers-2025) | [2024](#defense-papers-2024) | [2023](#defense-papers-2023)| [2022](#defense-papers-2022) | [2021](#defense-papers-2021) |

---

# 🔥 **Membership Inference Attack**

---

# 🟦 **Attack Papers 2025**

<a name="attack-papers-2025"></a>

| Year | Title                                                                                | Attack Target     | Adversarial Knowledge | Target Model                                 | Venue  | Paper Link                                          | Code Link                                 |
| ---- | ------------------------------------------------------------------------------------ | ----------------- | --------------------- | -------------------------------------------- | ------ | --------------------------------------------------- | ----------------------------------------- |
| 2025 | *RecPS: Privacy Risk Scoring for Recommender Systems*                                | Interaction-level | White-box             | ⭐ Matrix-Factorization based & Graph-based ⭐ | RecSys | [https://dl.acm.org/doi/10.1145/3705328.3748052](#) | [https://github.com/RhincodonE/RsLiRA](#) |
| 2025 | *Social Relation-Level Privacy Risks and Preservation in Social Recommender Systems* | Social-level      | Black-box             | ⭐ Graph-based ⭐                              | SIGIR  | [https://dl.acm.org/doi/10.1145/3726302.3730086](#) | [https://github.com/XuHao-bit/SMIA](#)    |

---

# 🟦 **Attack Papers 2024**

<a name="attack-papers-2024"></a>

| Year | Title                                                                                                     | Attack Target     | Adversarial Knowledge | Target Model                                      | Venue | Paper Link                                          | Code Link                                                 |
| ---- | --------------------------------------------------------------------------------------------------------- | ----------------- | --------------------- | ------------------------------------------------- | ----- | --------------------------------------------------- | --------------------------------------------------------- |
| 2024 | *Shadow-Free Membership Inference Attacks: Recommender Systems Are More Vulnerable Than You Thought*      | User-level        | Black-box             | ⭐ Matrix-Factorization based & Sequential-based ⭐ | IJCAI | [https://arxiv.org/abs/2405.07018](#)               | [https://github.com/XiaoxiaoChi-code/shadow-free-MIAs](#) |
| 2024 | *Interaction-level Membership Inference Attack against Recommender Systems with Long-tailed Distribution* | Interaction-level | Black-box             | ⭐ Graph-based ⭐                                   | CIKM  | [https://dl.acm.org/doi/10.1145/3627673.3679804](#) | [https://github.com/dzhong2/MINER](#)                     |

---

# 🟦 **Attack Papers 2023**

<a name="attack-papers-2023"></a>

| Year | Title                                                                                 | Attack Target     | Adversarial Knowledge | Target Model         | Venue | Paper Link                                          | Code Link |
| ---- | ------------------------------------------------------------------------------------- | ----------------- | --------------------- | -------------------- | ----- | --------------------------------------------------- | --------- |
| 2023 | *Interaction-level membership inference attack against federated recommender systems* | Interaction-level | White-box             | \                    | WWW   | [https://arxiv.org/abs/2301.10964](#)               | [Link](#) |
| 2023 | *Membership inference attacks against sequential recommender systems*                 | User-level        | Black-box             | ⭐ Sequential-based ⭐ | WWW   | [https://dl.acm.org/doi/10.1145/3543507.3583447](#) | [Link](#) |

---

# 🟦 **Attack Papers 2022**

<a name="attack-papers-2023"></a>

| Year | Title                                                                             | Attack Target | Adversarial Knowledge | Target Model         | Venue | Paper Link                            | Code Link                                       |
| ---- | --------------------------------------------------------------------------------- | ------------- | --------------------- | -------------------- | ----- | ------------------------------------- | ----------------------------------------------- |
| 2022 | *Debiasing learning for membership inference attacks against recommender systems* | User-level    | Black-box             | ⭐ Sequential-based ⭐ | KDD   | [https://arxiv.org/abs/2206.12401](#) | [https://github.com/WZH-NLP/DL-MIA-KDD-2022](#) |

---

# 🟦 **Attack Papers 2021**

<a name="attack-papers-2023"></a>

| Year | Title                                                      | Attack Target | Adversarial Knowledge | Target Model                   | Venue | Paper Link                            | Code Link                                  |
| ---- | ---------------------------------------------------------- | ------------- | --------------------- | ------------------------------ | ----- | ------------------------------------- | ------------------------------------------ |
| 2021 | *Membership inference attacks against recommender systems* | User-level    | Black-box             | ⭐ Matrix-Factorization based ⭐ | CCS   | [https://arxiv.org/abs/2109.08045](#) | [https://github.com/minxingzhang/MIARS](#) |

---

# 🛡️ **Defense Papers**

### (Give them a similar structure: year → title → defense strategy → target model → venue → links)

# 🟦 **Defence Papers 2025**

<a name="attack-papers-2025"></a>

| Year | Title                                                                                | Defense Type                      | Venue  | Paper Link                                          | Code Link                                 |
| ---- | ------------------------------------------------------------------------------------ | --------------------------------- | ------ | --------------------------------------------------- | ----------------------------------------- |
| 2025 | *RecPS: Privacy Risk Scoring for Recommender Systems*                                | Privacy Risk Score                | RecSys | [https://dl.acm.org/doi/10.1145/3705328.3748052](#) | [https://github.com/RhincodonE/RsLiRA](#) |
| 2025 | *Social Relation-Level Privacy Risks and Preservation in Social Recommender Systems* | Differency Privacy&Regularization | SIGIR  | [https://dl.acm.org/doi/10.1145/3726302.3730086](#) | [https://github.com/XuHao-bit/SMIA](#)    |

---

# 🟦 **Defence Papers 2024**

<a name="attack-papers-2024"></a>

| Year | Title                                                                                                     | Defense Type                      | Venue    | Paper Link                                          | Code Link                              |
| ---- | --------------------------------------------------------------------------------------------------------- | --------------------------------- | -------- | --------------------------------------------------- | -------------------------------------- |
| 2024 | *Recommendation Unlearning via Influence Function*                                                        | Approximate Unlearning            | ACM TORS | [https://dl.acm.org/doi/10.1145/3701763](#)         | [https://github.com/baiyimeng/IFRU](#) |
| 2024 | *Interaction-level Membership Inference Attack against Recommender Systems with Long-tailed Distribution* | Differency Privacy&Regularization | CIKM     | [https://dl.acm.org/doi/10.1145/3627673.3679804](#) | [https://github.com/dzhong2/MINER](#)  |

* * *

# 🟦 **Defence Papers 2023**

<a name="attack-papers-2023"></a>

| Year | Title                                                                                    | Defense Type           | Venue        | Paper Link                                                                                                            | Code Link                                                               |
| ---- | ---------------------------------------------------------------------------------------- | ---------------------- | ------------ | --------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------- |
| 2023 | *Forgetting User Preference in Recommendation Systems with Label-Flipping*               | Approximate Unlearning | IEEE BigData | [https://ieeexplore.ieee.org/document/10386603](#)                                                                    | [Link](#)                                                               |
| 2023 | *UltraRE: Enhancing RecEraser for Recommendation Unlearning via Error Decomposition*     | Exact Unlearning       | NeurIPS      | [https://proceedings.neurips.cc/paper_files/paper/2023/file/29a0ea49a103a233b17c0705cdeccb66-Paper-Conference.pdf](#) | [https://github.com/ZhangYizhao/UltraRE](#) |
| 2023 | *Selective and collaborative influence function for efficient recommendation unlearning* | Approximate Unlearning | ESWA         | https://arxiv.org/abs/2203.11491                                                                                      | [Link](#)                                                               |
| 2023 | *Closed-form Machine Unlearning for Matrix Factorization*                                | Approximate Unlearning | CIKM         | https://dl.acm.org/doi/10.1145/3583780.3614811                                                                        | [Link](#)                                                               |
| 2023 | *Interaction-level Membership Inference Attack Against Federated Recommender Systems*    | Differency Privacy     | WWW          | https://arxiv.org/abs/2301.10964                                                                                      | [Link](#)                                                               |

* * *

# 🟦 **Defence Papers 2022**

<a name="attack-papers-2022"></a>

| Year | Title                                                                                    | Defense Type           | Venue  | Paper Link                                          | Code Link                                                      |
| ---- | ---------------------------------------------------------------------------------------- | ---------------------- | ------ | --------------------------------------------------- | -------------------------------------------------------------- |
| 2022 | *Recommendation unlearning*                                                              | Exact Unlearning       | WWW    | [https://dl.acm.org/doi/10.1145/3485447.3511997](#) | [https://github.com/chenchongthu/Recommendation-Unlearning](#) |
| 2022 | *Making Recommender Systems Forget: Learning and Unlearning for Erasable Recommendation* | Exact Unlearning       | KBS    | [https://arxiv.org/abs/2203.11491](#)               | [Link](#)                                                      |
| 2022 | *Forgetting Fast in Recommender Systems*                                                 | Approximate Unlearning | RecSys | https://arxiv.org/abs/2208.06875                    | [Link](#)                                                      |

* * * 

# 🟦 **Defence Papers 2021**

<a name="attack-papers-2021"></a>

| Year | Title                                                      | Defense Type             | Venue | Paper Link                            | Code Link                                  |
| ---- | ---------------------------------------------------------- | ------------------------ | ----- | ------------------------------------- | ------------------------------------------ |
| 2021 | *Membership inference attacks against recommender systems* | Popularity Randomization | CCS   | [https://arxiv.org/abs/2109.08045](#) | [https://github.com/minxingzhang/MIARS](#) |



## 🤝 **Contributing**

We welcome:

* New paper links
* Missing code repositories
* Improved categorization
* Reproductions or benchmarks
* Future work suggestions

To add a paper, simply open a PR or submit an issue with:

```
[Paper Title]
Authors:
Conference/Year:
Paper Link:
Code Link (if available):
Category:
```

---

## 📬 **Contact**

If you would like your paper or code to be added or updated (especially preprints with later publication), please open an issue or email the maintainers.

---

## ⭐ **Citation**

If you use this repository in your research, please cite our survey:

```bibtex
@misc{he2025membershipinferenceattacksrecommender,
      title={Membership Inference Attacks on Recommender System: A Survey}, 
      author={Jiajie He and Xintong Chen and Xinyang Fang and Min-Chun Chen and Yuechun Gu and Keke Chen},
      year={2025},
      eprint={2509.11080},
      archivePrefix={arXiv},
      primaryClass={cs.IR},
      url={https://arxiv.org/abs/2509.11080}, 
}
```

---

## 🛠 Maintainers

* [Richard He]
* [Ruby Chen]
* [Michale Chen]
* [Freya Fang]

---
