<div align='center'>

[English](README.md) | 简体中文

# LLM4TS: Large Language Models for Time Series

</div>

这个项目收集了大型语言模型（LLMs）和基础模型（FMs）在时间序列（TS）方面的论文和代码。希望这个项目能帮助你理解LLMs和FMs在时间序列方面的应用。

## 🦙 大语言模型与时间序列

*在BERT、GPT和其他LLMs在自然语言处理领域取得成功后，一些研究者提出将LLMs应用于时间序列（TS）任务。他们在TS数据集上对LLMs进行微调，并取得了SOTA结果。*

* PromptCast: A New Prompt-based Learning Paradigm for Time Series Forecasting Hao, in *arXiv* 2022. [\[Paper\]](https://arxiv.org/abs/2210.08964)
* One Fits All: Power General Time Series Analysis by Pretrained LM, in *arXiv* 2023. [\[Paper\]](https://arxiv.org/abs/2302.11939)
* Temporal Data Meets LLM -- Explainable Financial Time Series Forecasting, in *arXiv* 2023. [\[Paper\]](https://arxiv.org/abs/2306.11025)
* TEST: Text Prototype Aligned Embedding to Activate LLM's Ability for Time Series. [\[Paper\]](https://arxiv.org/abs/2308.08241)
* LLM4TS: Two-Stage Fine-Tuning for Time-Series Forecasting with Pre-Trained LLMs. [\[Paper\]](https://arxiv.org/abs/2308.08469)

* The first step is the hardest: Pitfalls of Representing and Tokenizing Temporal Data for Large Language Models. [\[Paper\]](https://arxiv.org/abs/2309.06236)

* Large Language Models Are Zero-Shot Time Series Forecasters. [\[Paper\]](https://arxiv.org/abs/2310.07820)

* TEMPO: Prompt-based Generative Pre-trained Transformer for Time Series Forecasting. [\[Paper\]](https://arxiv.org/abs/2310.04948)

* Time-LLM: Time Series Forecasting by Reprogramming Large Language Models. [\[Paper\]](https://arxiv.org/abs/2310.01728)

### 📍 综述

* Large Models for Time Series and Spatio-Temporal Data: A Survey and Outlook. [\[Survey\]](https://arxiv.org/abs/2310.10196)

* Position Paper: What Can Large Language Models Tell Us about Time Series Analysis. [\[Survey\]](https://arxiv.org/abs/2402.02713)

* Foundation Models for Time Series Analysis: A Tutorial and Survey [\[Survey\]](https://arxiv.org/abs/2403.14735)

### 📍 类似的工作
* Large Language Models are Few-Shot Health Learners, in *arXiv* 2023. [\[Paper\]](https://arxiv.org/abs/2305.15525)

* Frozen Language Model Helps ECG Zero-Shot Learning, in *arXiv* 2023.[\[Paper\]](https://arxiv.org/abs/2303.12311)

## 🧱 基座模型与时间序列

*最近，一些时间序列（TS）的基座模型（FMs）被提出。这些FMs旨在从大型数据集中学习时间序列的表示，并将表示转移到下游任务中。与TS-LLM相比，这些方法不依赖预训练的LLMs。*

* Tiny Time Mixers (TTMs): Fast Pretrained Models for Enhanced Zero/Few-Shot Forecasting of Multivariate Time Series. [\[Paper\]](https://arxiv.org/abs/2401.03955)

* A decoder-only foundation model for time-series forecasting. [\[Paper\]](https://arxiv.org/abs/2310.10688)

* TimeGPT-1. [\[Paper\]](https://arxiv.org/abs/2310.03589?ref=emergentmind)

* Lag-Llama: Towards Foundation Models for Time Series Forecasting. [\[Paper\]](https://arxiv.org/abs/2310.08278)

* Unified Training of Universal Time Series Forecasting Transformers. [\[Paper\]](https://arxiv.org/abs/2402.02592)

* MOMENT: A Family of Open Time-series Foundation Models. [\[Paper\]](https://arxiv.org/abs/2402.03885)

## 🔗 相关领域
*这里列出了一些相关领域。这些领域并非本项目的主要关注点，但它们对于理解LLMs如何应用于除了NLP之外的其他领域，以及其他特定领域如何构建基座模型也很重要。*

### 📍 预训练时间序列模型
* A Survey on Time-Series Pre-Trained Models, in *arXiv* 2023. [\[Paper\]](https://arxiv.org/abs/2305.10716)
* Transfer learning for Time Series Forecasting. [\[GitHub\]](https://github.com/Nixtla/transfer-learning-time-series)
* TST: A transformer-based framework for multi- variate time series representation learning. [\[Paper\]](https://arxiv.org/abs/2010.02803)
* Ti-mae: Self-supervised masked time series autoencoders. [\[Paper\]](https://arxiv.org/abs/2301.08871)
* SimMTM: A Simple Pre-Training Framework for Masked Time-Series Modeling. [\[Paper\]](https://arxiv.org/pdf/2302.00861.pdf)

* Cost: Contrastive learning of disentangled seasonal-trend rep- resentations for time series forecasting.[\[Paper\]](https://arxiv.org/abs/2202.01575)

* TS2Vec: Towards Universal Representation of Time Series. [\[Paper\]](https://arxiv.org/abs/2106.10466)

### 📍 大语言模型与推荐系统
* Recommendation as Language Processing (RLP): A Unified Pretrain, Personalized Prompt & Predict Paradigm (P5), in *arXiv* 2022. [\[Paper\]](https://arxiv.org/abs/2203.13366)
* LLM4Rec. [\[GitHub\]](https://github.com/WLiK/LLM4Rec)


### 📍 基座模型与表格数据
* AnyPredict: Foundation Model for Tabular Prediction, in *arXiv* 2023. [\[Paper\]](https://arxiv.org/abs/2305.12081)
* XTab: Cross-table Pretraining for Tabular Transformers, in *ICML* 2023. [\[Paper\]](https://arxiv.org/abs/2305.06090)

### 📍 LLMOps
* Awesome-LLMOps. [\[GitHub\]](https://github.com/tensorchord/Awesome-LLMOps)
