# esXNLI
esXNLI is a bilingual NLI dataset described in the following paper:

Mikel Artetxe, Gorka Labaka, and Eneko Agirre. 2020. **[Translation Artifacts in Cross-lingual Transfer Learning](https://arxiv.org/pdf/2004.04721.pdf)**. *arXiv preprint arXiv:2004.04721*.

The dataset comprises 2490 examples from 5 different genres that were originally annotated in Spanish, and translated into English by professional translators. It serves as a counterpoint to [XNLI](https://github.com/facebookresearch/XNLI), which was originally annotated in English and translated into 14 other languages, including Spanish. The dataset was conceived to be used in conjunction with the XNLI development set to analyze the effect of translation in cross-lingual transfer learning.

This repository contains the following files:
- `esxnli.tsv` is the main dataset, consisting of both the original Spanish examples and their English translation from a professional translation service.
- `esxnli.mt.tsv` is an English version of the dataset that was machine translated from Spanish. This was used to experiment with the translate-test approach.

Both files use the same format as [XNLI](https://github.com/facebookresearch/XNLI). Some fields are intentionally left blank.

If you use this dataset for academic research, please cite the paper in question:
```
@article{artetxe2020translation,
  title={Translation Artifacts in Cross-lingual Transfer Learning},
  author={Artetxe, Mikel and Labaka, Gorka and Agirre, Eneko},
  journal={arXiv preprint arXiv:2004.04721},
  year={2020}
}
```
