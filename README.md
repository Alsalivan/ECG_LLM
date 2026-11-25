# ECG-LLM: Foundation Model for ECG-Based Cardiac Reasoning

Official repository of the paper **"ECG-LLM: Foundation Model for ECG-Based Cardiac Reasoning"** (Selivanov et al.).

📄 Preprint: [arXiv:2607.16323](https://arxiv.org/abs/2607.16323)

> **Status:** the code is being prepared for release and will be added to this repository.

## Overview

ECG-LLM is an ECG-conditioned large language model that answers free-text cardiovascular questions from a 12-lead ECG alone. It is trained on clinically structured question–answer pairs derived from ECG signals, clinical context, cardiac magnetic resonance (CMR) and echocardiography (ECHO), across four cohorts (679,112 ECG studies from 186,409 patients). The model covers conventional ECG interpretation as well as CMR- and ECHO-derived phenotypes that are not directly visible on a standard ECG.

## Repository contents

This repository will contain the code for:

- **Preprocessing** of the ECG cohorts
- **Question–answer generation** from structured cardiac records
- **Training** (ECG encoder pretraining and ECG-LLM instruction tuning)
- **Inference**
- **Evaluation**

## Data

No patient data are distributed in this repository. The datasets used in the study are available from their providers:

| Dataset | Access |
|---|---|
| UK Biobank | Approved researchers on application: https://www.ukbiobank.ac.uk/enable-your-research/apply-for-access |
| PTB-XL | Open access via PhysioNet: https://doi.org/10.13026/kfzx-aw45 |
| MIMIC-IV-ECG | Open access via PhysioNet: https://doi.org/10.13026/4nqg-sb35 |
| MIMIC-IV | Credentialed access via PhysioNet: https://doi.org/10.13026/kpb9-mt58 |
| EchoNext | Credentialed access via PhysioNet: https://doi.org/10.13026/3ykd-bf14 |

Derived data generated in this study, including the question–answer data and evaluation splits, may be shared where the data-use agreements of the source datasets permit.

## Model weights

Sharing of trained model weights is subject to the licences and data-use agreements of the training data.

## Citation

If you use this work, please cite:

```bibtex
@misc{selivanov2026ecgllmfoundationmodelecgbased,
      title={ECG-LLM: Foundation Model for ECG-Based Cardiac Reasoning},
      author={Alexander Selivanov and Friederike Jungmann and Jan Kehrer and Karl-Ludwig Laugwitz and Eimo Martens and Daniel Rueckert},
      year={2026},
      eprint={2607.16323},
      archivePrefix={arXiv},
      primaryClass={eess.SP},
      url={https://arxiv.org/abs/2607.16323},
}
```

## Contact

Alexander Selivanov, Chair for AI in Healthcare and Medicine, Technical University of Munich (TUM) — alexander.selivanov@tum.de
