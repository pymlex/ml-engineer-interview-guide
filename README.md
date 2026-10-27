# Подготовка к собеседованию ML-инженера

Последовательный курс. В каждой главе сначала вводятся обозначения и постановка задачи, затем вывод формул и следствия. Читать по порядку.


## Оглавление


1. [Математический базис](chapters/01-math.md) — наблюдения, $\theta$, MLE, априорное и апостериорное распределения, вывод MAP → Ridge и Lasso, CLT, SVD, градиенты
2. [Классическое обучение с учителем](chapters/02-classical-ml.md) — риск, bias–variance, OLS, вывод сигмоиды и LogLoss, регуляризация, метрики, SVM, лес, бустинг
3. [Снижение размерности и кластеризация](chapters/03-dimensionality-clustering.md) — PCA через SVD, LDA, t-SNE, UMAP, K-Means, DBSCAN, HDBSCAN, агломерация
4. [Глубокое обучение](chapters/04-deep-learning.md) — MLP, активации, инициализация, нормализации, оптимайзеры, CNN, ResNet, RNN
5. [Трансформеры](chapters/05-transformers.md) — attention, MHA/MQA/GQA, FlashAttention, PagedAttention, RoPE, Pre-LN, семейства стеков
6. [Инференс, масштаб, выравнивание](chapters/06-llm-ops.md) — prefill и decoding, KV-кэш, квантизация, параллелизм, LoRA, вывод DPO из RLHF
7. [Мультимодальность](chapters/07-multimodality.md) — InfoNCE в CLIP, ViT, мост к LLM, LLaVA, Whisper


Полный список источников: [REFERENCES.md](REFERENCES.md).


## Принцип изложения


Каждый ключевой объект сначала называется и определяется. Формула появляется после постановки. Связки вроде MAP и Ridge или Бернулли и сигмоиды выводятся, а не объявляются.


## Лицензия


GPL-3.0. См. [LICENSE](LICENSE).
