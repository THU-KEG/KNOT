
# Untangle the KNOT: Conflicting Knowledge Resolution in Large Language Models

## Overview

This repository contains the KNOT dataset and associated code developed in our research for examining the capability of Large Language Models (LLMs) to resolve conflicts between the knowledge present in their parameters and newly provided external documents. Our study introduces a novel dataset, KNOT, designed to evaluate LLMs' abilities in handling knowledge conflicts across three reasoning levels: Direct Extraction, Explicit Reasoning, and Implicit Reasoning.
## Dataset

The KNOT dataset facilitates the study of conflicting knowledge resolution in LLMs, comprising questions categorized into three types based on the reasoning skills required:

- **KNOT-S**: Focuses on Direct Extraction, where the answer can be directly identified from the conflicting knowledge provided.
- **KNOT-E**: Involves Explicit Reasoning, requiring the model to follow an explicit reasoning path provided in the question.
- **KNOT-I**: Pertains to Implicit Reasoning, necessitating the model to independently infer the reasoning path to find the answer.

### Structure

The dataset is organized into the following files:

- `knot_with_simple_questions.json`: Questions requiring Direct Extraction.
- `knot_with_explicit_questions.json`: Questions necessitating Explicit Reasoning.
- `knot_with_implicit_questions.json`: Questions demanding Implicit Reasoning.


## Citation

If you find this dataset and our research useful in your work, please consider citing our paper:

```bibtex
@inproceedings{liu2024untangle,
  title={Untangle the KNOT: Interweaving Conflicting Knowledge and Reasoning Skills in Large Language Models},
  author={Liu, Yantao and Yao, Zijun and Lv, Xin and Cao, Shulin and Yu, Jifan and Hou, Lei and Li, Juanzi},
  booktitle={Proceedings of the 30th International Conference on Computational Linguistics (COLING 2024)},
  year={2024},
  organization={International Committee on Computational Linguistics}
}
```

## License

This project is licensed under the terms of the GNU General Public License v3.0.


