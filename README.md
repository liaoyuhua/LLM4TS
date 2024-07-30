<div align='center'>

English | [简体中文](README_zh.md)

# LLM4TS: Large Language & Foundation Models for Time Series

</div>

This project collects the papers and codes of Large Language Models (LLMs) and Foundation Models (FMs) for Time Series (TS). Hope this project can help you to understand the LLMs and FMs for TS.


## 🦙 LLMs for Time Series

*After the success of BERT, GPT, and other LLMs in NLP, some researchers have proposed to apply LLMs to Time Series (TS) tasks. They fintune the LLMs on TS datasets and achieve state-of-the-art results.*

* PromptCast: A New Prompt-based Learning Paradigm for Time Series Forecasting Hao, in *arXiv* 2022. [\[Paper\]](https://arxiv.org/abs/2210.08964)
* One Fits All: Power General Time Series Analysis by Pretrained LM, in *arXiv* 2023. [\[Paper\]](https://arxiv.org/abs/2302.11939)
* Temporal Data Meets LLM -- Explainable Financial Time Series Forecasting, in *arXiv* 2023. [\[Paper\]](https://arxiv.org/abs/2306.11025)
* TEST: Text Prototype Aligned Embedding to Activate LLM's Ability for Time Series. [\[Paper\]](https://arxiv.org/abs/2308.08241)
* LLM4TS: Two-Stage Fine-Tuning for Time-Series Forecasting with Pre-Trained LLMs. [\[Paper\]](https://arxiv.org/abs/2308.08469)

* The first step is the hardest: Pitfalls of Representing and Tokenizing Temporal Data for Large Language Models. [\[Paper\]](https://arxiv.org/abs/2309.06236)

* Large Language Models Are Zero-Shot Time Series Forecasters. [\[Paper\]](https://arxiv.org/abs/2310.07820)

* TEMPO: Prompt-based Generative Pre-trained Transformer for Time Series Forecasting. [\[Paper\]](https://arxiv.org/abs/2310.04948)

* Time-LLM: Time Series Forecasting by Reprogramming Large Language Models. [\[Paper\]](https://arxiv.org/abs/2310.01728)

* S2IP-LLM: Semantic Space Informed Prompt Learning with LLM for Time Series Forecasting. [\[Paper\]](https://arxiv.org/pdf/2403.05798.pdf)

* Time Series Forecasting with LLMs: Understanding and Enhancing Model Capabilities. [\[Paper\]](https://arxiv.org/abs/2402.10835)

### 📍 Survey

* Large Models for Time Series and Spatio-Temporal Data: A Survey and Outlook. [\[Survey\]](https://arxiv.org/abs/2310.10196)

* Position Paper: What Can Large Language Models Tell Us about Time Series Analysis. [\[Survey\]](https://arxiv.org/abs/2402.02713)

* Foundation Models for Time Series Analysis: A Tutorial and Survey. [\[Survey\]](https://arxiv.org/abs/2403.14735)

* Are Language Models Actually Useful for Time Series Forecasting? [\[Survey\]](https://arxiv.org/abs/2406.16964)


### 📍 Similar Things
* Large Language Models are Few-Shot Health Learners, in *arXiv* 2023. [\[Paper\]](https://arxiv.org/abs/2305.15525)

* Frozen Language Model Helps ECG Zero-Shot Learning, in *arXiv* 2023.[\[Paper\]](https://arxiv.org/abs/2303.12311)


## 🧱 Foundation Models for Time Series
*Recently, some kinds of Foundation Models (FMs) for Time Series (TS) have been proposed. These FMs aims to learn the representation of Time Series from large datasets and then transfer the representation to downstream tasks. Compared with TS-LLMs, these methods do not depend on the pretrained LLMs.*

### 📍 Data

* **LOTSA** [\[Paper\]](https://arxiv.org/abs/2402.02592) [\[GitHub\]](https://github.com/SalesforceAIResearch/uni2ts?tab=readme-ov-file)

* **Timeseries-PILE** [\[Paper\]](https://arxiv.org/abs/2402.03885) [\[GitHub\]](https://github.com/moment-timeseries-foundation-model/moment)

* Towards Foundation Time Series Model: To Synthesize Or Not To Synthesize? [\[Paper\]](https://arxiv.org/abs/2403.02534)

### 📍 Models

* Tiny Time Mixers (TTMs): Fast Pretrained Models for Enhanced Zero/Few-Shot Forecasting of Multivariate Time Series. [\[Paper\]](https://arxiv.org/abs/2401.03955)

* A decoder-only foundation model for time-series forecasting. [\[Paper\]](https://arxiv.org/abs/2310.10688)

* TimeGPT-1. [\[Paper\]](https://arxiv.org/abs/2310.03589?ref=emergentmind)

* Lag-Llama: Towards Foundation Models for Time Series Forecasting. [\[Paper\]](https://arxiv.org/abs/2310.08278)

* Unified Training of Universal Time Series Forecasting Transformers. [\[Paper\]](https://arxiv.org/abs/2402.02592)

* MOMENT: A Family of Open Time-series Foundation Models. [\[Paper\]](https://arxiv.org/abs/2402.03885)

* Chronos: Learning the Language of Time Series. [\[Paper\]](https://arxiv.org/abs/2403.07815) [\[GitHub\]](https://github.com/amazon-science/chronos-forecasting)

* ForecastPFN: Synthetically-Trained Zero-Shot Forecasting. [\[Paper\]](https://arxiv.org/abs/2311.01933) [\[GitHub\]](https://github.com/abacusai/ForecastPFN)

### 📍 Findings

* Scaling Law for Time Series Forecasting. [\[Paper\]](https://arxiv.org/abs/2405.15124)

* Only the Curve Shape Matters: Training Foundation Models for Zero-Shot Multivariate Time Series Forecasting through Next Curve Shape Prediction. [\[Paper\]](https://www.arxiv.org/abs/2402.07570)

### 📍 Surveys

* Foundation Models for Time Series Analysis: A Tutorial and Survey. [\[Survey\]](https://arxiv.org/abs/2403.14735)


## 🔗 Related Fields
*Here, some related fields are listed. These fields are not the main focus of this project, but they are also important for understanding how LLMs are applied to other fields rather than NLP and FMs in specific fields are developed.*

### 📍 PreTrained Time Series
* A Survey on Time-Series Pre-Trained Models, in *arXiv* 2023. [\[Paper\]](https://arxiv.org/abs/2305.10716)
* Transfer learning for Time Series Forecasting. [\[GitHub\]](https://github.com/Nixtla/transfer-learning-time-series)
* TST: A transformer-based framework for multi- variate time series representation learning. [\[Paper\]](https://arxiv.org/abs/2010.02803)
* Ti-mae: Self-supervised masked time series autoencoders. [\[Paper\]](https://arxiv.org/abs/2301.08871)
* SimMTM: A Simple Pre-Training Framework for Masked Time-Series Modeling. [\[Paper\]](https://arxiv.org/pdf/2302.00861.pdf)

* Cost: Contrastive learning of disentangled seasonal-trend rep- resentations for time series forecasting.[\[Paper\]](https://arxiv.org/abs/2202.01575)

* TS2Vec: Towards Universal Representation of Time Series. [\[Paper\]](https://arxiv.org/abs/2106.10466)

### 📍 LLM for Recommendation Systems
* Recommendation as Language Processing (RLP): A Unified Pretrain, Personalized Prompt & Predict Paradigm (P5), in *arXiv* 2022. [\[Paper\]](https://arxiv.org/abs/2203.13366)
* LLM4Rec. [\[GitHub\]](https://github.com/WLiK/LLM4Rec)


### 📍 LLM/FM for Tabular Data
* AnyPredict: Foundation Model for Tabular Prediction, in *arXiv* 2023. [\[Paper\]](https://arxiv.org/abs/2305.12081)
* XTab: Cross-table Pretraining for Tabular Transformers, in *ICML* 2023. [\[Paper\]](https://arxiv.org/abs/2305.06090)

### 📍 LLM in Production (LLMOps)
* Awesome-LLMOps. [\[GitHub\]](https://github.com/tensorchord/Awesome-LLMOps)
