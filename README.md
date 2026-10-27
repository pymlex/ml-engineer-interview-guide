# Подготовка к собеседованию ML-инженера

Читать по порядку. В каждой главе сначала вводятся обозначения и постановка, затем вывод формул и следствия.


1. [Математический базис](chapters/01-math.md) — что такое $x_i$ и $\theta$, MLE, MAP, CLT, SVD, градиенты
2. [Классическое обучение с учителем](chapters/02-classical-ml.md) — риск, OLS, вывод сигмоиды и LogLoss, регуляризация, метрики, SVM, лес, бустинг
3. [Снижение размерности и кластеризация](chapters/03-dimensionality-clustering.md)
4. [Глубокое обучение](chapters/04-deep-learning.md)
5. [Трансформеры](chapters/05-transformers.md)
6. [Инференс, масштаб, выравнивание](chapters/06-llm-ops.md) — KV-кэш, квантизация, параллелизм, вывод DPO из RLHF
7. [Мультимодальность](chapters/07-multimodality.md) — InfoNCE в CLIP, ViT, мост к LLM, Whisper


## Литература

```bibtex
@book{hastie2009elements,
  title={The Elements of Statistical Learning},
  author={Hastie, Trevor and Tibshirani, Robert and Friedman, Jerome},
  year={2009},
  publisher={Springer}
}

@inproceedings{vaswani2017attention,
  title={Attention Is All You Need},
  author={Vaswani, Ashish and others},
  booktitle={NeurIPS},
  year={2017}
}

@inproceedings{dao2022flashattention,
  title={FlashAttention: Fast and Memory-Efficient Exact Attention with IO-Awareness},
  author={Dao, Tri and others},
  booktitle={NeurIPS},
  year={2022}
}

@inproceedings{hu2022lora,
  title={LoRA: Low-Rank Adaptation of Large Language Models},
  author={Hu, Edward J. and others},
  booktitle={ICLR},
  year={2022}
}

@inproceedings{rafailov2023dpo,
  title={Direct Preference Optimization: Your Language Model is Secretly a Reward Model},
  author={Rafailov, Rafael and others},
  booktitle={NeurIPS},
  year={2023}
}

@misc{ml_engineer_interview_guide,
  title={ML Engineer Interview Guide},
  author={Zyukov, Aleks},
  year={2026},
  howpublished={https://github.com/pymlex/ml-engineer-interview-guide},
  note={The project is under GPL-3.0 license.}
}
```

The project is under GPL-3.0 license.
