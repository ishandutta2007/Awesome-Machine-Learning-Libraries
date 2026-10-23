# Awesome-Machine-Learning-Libraries

## Top Machine Learning Libraries Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on AutoML Platforms, Gradient Boosting Libraries & Self-Hosted ML Toolkits*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Machine Learning Libraries**. These tools provide the algorithmic foundation for building predictive models—ranging from automated machine learning platforms that abstract away model selection to specialized libraries that excel at specific data types or problem domains.



**Examples** include XGBoost, LightGBM, CatBoost, scikit-learn, DataRobot, H2O.ai, and Dataiku (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active library for self-hosting, avoiding per-model SaaS fees, and controlling the training pipeline. The open-source landscape is anchored by **scikit-learn** (the classical ML standard with 58k+ stars), **XGBoost** (the gradient boosting workhorse with 38k+ stars), **LightGBM** (Microsoft's speed-focused alternative now under community governance), and **CatBoost** (Yandex's categorical-feature specialist), with **PyTorch** and **TensorFlow** providing the deep learning foundation.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



| Product | Description | Pricing | Free Tier Limit |

| :--- | :--- | :--- | :--- |

| **[DataRobot](https://www.datarobot.com/)** | Automated ML platform with AutoML, MLOps, and generative AI capabilities. | **Pricing 5.0 (Classic MLOps)**: contact sales for quote; pricing based on active deployments . | No public free tier. Trial available via sales engagement. |

| **[H2O.ai](https://h2o.ai/)** | Enterprise AI platform with Driverless AI (AutoML) and the open-source H2O-3 library. | **Driverless AI**: enterprise licensing. Microsoft Marketplace lists **$250,000/year** starting price for H2O AI Cloud Platform . | **H2O-3**: fully free and open-source (Apache 2.0). Driverless AI: free trial available; no permanent free tier. |

| **[Dataiku](https://www.dataiku.com/)** | Collaborative data science platform with visual and code-based workflows. | **Commercial editions** (Discover, Business, Enterprise) quoted by sales; no public list prices . | **14-day Cloud Trial**: 5 users, 4 CPUs, 32 GB compute, all features except Govern/advanced LLM Mesh. **Free Edition** for on-prem (feature-restricted) . |

| **[Pecan AI](https://www.pecan.ai/)** | Predictive analytics platform focused on revenue and customer lifecycle predictions. | **Starter**: monthly predictions batches, 500M rows storage. **Team**: 10 batches, 2B rows. **Business**: custom, 5B rows . Exact dollar amounts not published on pricing page. | No permanent free tier. **Starter plan** available but pricing not disclosed publicly. |

| **[BigML](https://bigml.com/)** | Machine learning platform with a focus on ease of use and private deployments. | **Private Deployment (Single Instance)**: support fee $9,000/year. **12-Instance**: license $70,000/year + $14,000 maintenance + $21,000 support. **36-Instance**: license $120,000/year + $24,000 maintenance + $36,000 support . | No public free tier for private deployments. Trial available on cloud platform. |

| **[dotData](https://dotdata.com/)** | Automated feature engineering and predictive analytics platform. | **dotData Insight Lite**: starts at **¥50,000/month** (approx. $330) for Japanese SMBs (annual revenue under ¥30B) . | No permanent free tier. Lite plan available for qualifying SMBs. |

| **[Akkio](https://www.akkio.com/)** | No-code predictive modeling platform. **Repositioned as enterprise-only** in 2026. | **Custom quote only**. The $49 Starter and $99 Growth self-serve plans are **no longer available** . | No free tier. No self-serve signup—contact sales only . |

| **[AWS SageMaker](https://aws.amazon.com/sagemaker/)** | End-to-end ML platform with built-in algorithms, AutoML (Autopilot), and deployment. | Pay-as-you-go for compute, storage, and data processing; no upfront commitments . | **Free tier**: 250 hours of ml.t2.medium/ml.t3.medium notebooks, 50 hours of ml.m4.xlarge training, 125 hours of ml.m4.xlarge hosting (2 months) . |

| **[Azure Automated ML](https://azure.microsoft.com/en-us/products/machine-learning/automatedml)** | Microsoft's AutoML service within Azure Machine Learning. | Pay-as-you-go for compute; AutoML itself has no separate charge. | **$200 credit** for new Azure accounts (30 days). Free compute tier varies by region. |

| **[Google Cloud AutoML](https://cloud.google.com/automl)** | Google's managed AutoML for vision, language, and tabular data. | Pay-as-you-go for training and prediction; AutoML Tables billed per node-hour. | **$300 free credit** for new GCP accounts (90 days). |



## Open-Source GitHub Projects



- **[scikit-learn](https://github.com/scikit-learn/scikit-learn)** [![GitHub Stars](https://img.shields.io/github/stars/scikit-learn/scikit-learn?style=social&color=white)](https://github.com/scikit-learn/scikit-learn/stargazers)  

  **The classical ML standard.** ~58k stars, BSD-3-Clause licensed . Comprehensive toolkit for classification, regression, clustering, dimensionality reduction, and preprocessing. **Strengths**: consistent API across all algorithms, excellent documentation, and battle-tested implementations. Best for tabular ML, feature engineering, and any workflow not requiring deep learning.



- **[XGBoost](https://github.com/dmlc/xgboost)** [![GitHub Stars](https://img.shields.io/github/stars/dmlc/xgboost?style=social&color=white)](https://github.com/dmlc/xgboost/stargazers)  

  **The gradient boosting workhorse.** ~38k stars, Apache 2.0 licensed . Scalable, portable, and distributed gradient boosting for classification, regression, and ranking. Runs on single machine, Hadoop, Spark, Dask, and Flink . **Strengths**: GPU support, mature ecosystem, and consistent performance on tabular competitions. Best for structured/tabular ML where gradient boosting dominates.



- **[LightGBM](https://github.com/lightgbm-org/LightGBM)** [![GitHub Stars](https://img.shields.io/github/stars/lightgbm-org/LightGBM?style=social&color=white)](https://github.com/lightgbm-org/LightGBM/stargazers)  

  **Microsoft's speed-focused gradient boosting.** ~14.7k stars, MIT licensed . **Governance note**: moved from `microsoft/LightGBM` to `lightgbm-org/LightGBM` in March 2026 after Microsoft considered archiving the repository; maintainers now have full control over the project . Histogram-based leaf-wise tree growth for fast training with low memory. Best for large-scale tabular ML where training speed matters.



- **[CatBoost](https://github.com/catboost/catboost)** [![GitHub Stars](https://img.shields.io/github/stars/catboost/catboost?style=social&color=white)](https://github.com/catboost/catboost/stargazers)  

  **Yandex's categorical-feature specialist.** ~8k stars, Apache 2.0 licensed . Gradient boosting with native handling of categorical features, ordered boosting to reduce overfitting, and fast GPU/multi-GPU support out of the box . Best for datasets with many categorical variables and teams wanting strong defaults without extensive tuning.



- **[PyTorch](https://github.com/pytorch/pytorch)** [![GitHub Stars](https://img.shields.io/github/stars/pytorch/pytorch?style=social&color=white)](https://github.com/pytorch/pytorch/stargazers)  

  **The research-first deep learning framework.** ~94k stars, BSD-3-Clause licensed . Dynamic computation graphs, Pythonic API, and dominant in research. Best for deep learning, rapid prototyping, and teams that value flexibility over static graph optimization.



- **[TensorFlow](https://github.com/tensorflow/tensorflow)** [![GitHub Stars](https://img.shields.io/github/stars/tensorflow/tensorflow?style=social&color=white)](https://github.com/tensorflow/tensorflow/stargazers)  

  **The production-scale deep learning standard.** ~194k stars, Apache 2.0 licensed . End-to-end platform with Keras, TensorFlow Serving, TensorFlow Lite, and TensorBoard. Best for production ML systems requiring robust serving infrastructure.



- **[Hugging Face Transformers](https://github.com/huggingface/transformers)** [![GitHub Stars](https://img.shields.io/github/stars/huggingface/transformers?style=social&color=white)](https://github.com/huggingface/transformers/stargazers)  

  **The NLP and LLM standard.** ~166k stars, Apache 2.0 licensed . Unified API for thousands of pre-trained models across NLP, vision, audio, and multimodal tasks. Best for any team working with transformers, LLMs, or pre-trained models.



### Additional Strong Open-Source Options



- **Keras** — High-level API with multi-backend support (TensorFlow, JAX, PyTorch). Best for beginners and rapid prototyping.

- **JAX** — Google's composable transformations framework with TPU support. Best for researchers needing fine-grained control.

- **MLflow** — MLOps lifecycle standard for experiment tracking, model registry, and deployment. Best for teams wanting a unified MLOps layer.

- **BentoML** — Model serving framework for packaging models from any framework into production APIs. Best for multi-framework serving.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- **SaaS pricing is largely opaque**: DataRobot, Dataiku, and Pecan AI do not publish list prices; H2O's $250k/year is a marketplace starting point; Akkio has eliminated self-serve pricing entirely . Model your actual usage before committing.

- **LightGBM governance changed in 2026**: the project moved from Microsoft's organization to `lightgbm-org` after Microsoft considered archiving it. Use the new repository URL for the latest releases .

- **Free tiers are for evaluation, not production**: SageMaker's free tier is time-limited; Azure and GCP credits expire; Dataiku's trial is 14 days; BigML and dotData have no permanent free tiers for enterprise features.

- **Library choice depends on your problem**: tabular ML → scikit-learn/XGBoost/LightGBM/CatBoost; deep learning → PyTorch/TensorFlow; NLP/LLMs → Hugging Face Transformers.



---



**Made for data scientists, ML engineers, and organizations building predictive models.**  

Let's make machine learning libraries more open, appropriately scoped, and production-ready.
