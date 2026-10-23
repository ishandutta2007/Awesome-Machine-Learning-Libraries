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

- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## Sector Overview & Market Dynamics

The global machine learning platforms and Automated Machine Learning (AutoML) market is estimated at **$3.7B–$6.8B for AutoML** (and **$135B+ for the broader ML platform ecosystem**) in 2026, advancing at a compound annual growth rate (CAGR) exceeding 35%. The sector exhibits a bifurcated market structure: it is **highly concentrated** at the core cloud infrastructure and compute layer dominated by hyperscalers (Microsoft, Alphabet, and Amazon), yet **moderately fragmented** across specialized enterprise AutoML, automated feature engineering, and predictive analytics vendors.

## SaaS/Hosted Platforms

| Product | Company Scale (Valuation / Revenue) | Description | Pricing | Free Tier Limit |
| :--- | :--- | :--- | :--- | :--- |
| **[Azure Automated ML](https://azure.microsoft.com/en-us/products/machine-learning/automatedml)** | **~$3.1T Market Cap** (Microsoft parent; $245B+ ARR) | Microsoft's AutoML service within Azure Machine Learning. | **$0.02/hour** compute entry (pay-as-you-go; AutoML software tools included with Azure ML compute). | **$200 credit** (30-day trial) + free monthly quota of select Azure services (e.g., 750 hours of B1s VMs for 12 months). |
| **[Google Cloud AutoML](https://cloud.google.com/automl)** | **~$2.1T Market Cap** (Alphabet parent; $350B+ revenue) | Google's managed AutoML for tabular, vision, and text workflows. | **$21.50/hour** for tabular model training ($0.056/hour for minimal Vertex AI compute endpoints). | **$300 free credits** (valid for 90 days) across GCP services; no permanent free AutoML training. |
| **[AWS SageMaker](https://aws.amazon.com/sagemaker/)** | **~$2.0T Market Cap** (Amazon parent; AWS $105B+ ARR) | End-to-end ML platform with built-in algorithms, AutoML (Autopilot), and deployment. | **$0.05/hour** (entry compute via `ml.t3.medium` instances; pay-as-you-go). | **2-month free trial**: 250 hours/month of `ml.t2.medium`/`ml.t3.medium` notebooks, 50 hours of `ml.m4.xlarge` training, and 125 hours of `ml.m4.xlarge` hosting. |
| **[DataRobot](https://www.datarobot.com/)** | **$6.3B Valuation** ($225M–$285M ARR) | Automated ML platform with AutoML, MLOps, and generative AI capabilities. | **~$40,000/year** entry-level enterprise tier (~$3,333/month equivalent via custom contract). | **14-day free trial** with full platform capabilities upon sales verification; no permanent free tier. |
| **[Dataiku](https://www.dataiku.com/)** | **$3.7B Valuation** ($350M+ ARR) | Collaborative data science platform with visual and code-based workflows. | **~$4,000/month** (~$48,000/year entry commercial package). | **14-day Cloud Trial** (5 users, 4 CPUs, 32 GB compute) or **Free Edition** on-premises (limited to 3 users, community support). |
| **[H2O.ai](https://h2o.ai/)** | **$1.7B Valuation** (~$75M ARR) | Enterprise AI platform with Driverless AI (AutoML) and the open-source H2O-3 library. | **$250,000/year** starting enterprise license via cloud marketplaces. | **21-day free trial** of Driverless AI; or permanent **H2O-3 Open Source** (100% free under Apache 2.0). |
| **[Pecan AI](https://www.pecan.ai/)** | **$117M Funding** (~$10M ARR) | Predictive analytics platform focused on revenue and customer lifecycle predictions. | **~$950/month** entry-level prediction plan (Starter tier billed annually). | **14-day guided proof-of-concept / sandbox trial** via sales demo; no permanent free tier. |
| **[dotData](https://dotdata.com/)** | **$74.6M Funding** (~$15M–$25M ARR est.) | Automated feature engineering and predictive analytics platform. | **¥50,000/month** (~$330/month) for dotData Insight Lite (Japanese SMB tier). | **14-day evaluated trial / pilot** upon request; no permanent free tier. |
| **[Akkio](https://www.akkio.com/)** | **$60M Valuation** ($18M total funding) | AI-native analytics and predictive modeling platform for agencies. | **$49/month** (Starter self-serve plan; scaling to enterprise packages). | **14-day free trial** (access to core predictive models and data connectors; no credit card required). |
| **[BigML](https://bigml.com/)** | **$6.6M Funding** (~$5M–$10M ARR) | Machine learning platform with a focus on ease of use and private deployments. | **$30/month** (Standard plan; 64 MB task size, 2 parallel tasks). | **Free forever plan**: max **16 MB** dataset/task size, max 2 parallel tasks, unlimited non-commercial runs. |

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
