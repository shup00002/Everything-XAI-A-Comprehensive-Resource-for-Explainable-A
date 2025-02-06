# Everything-XAI-A-Comprehensive-Resource-for-Explainable-A
A comprehensive, community-driven resource for Explainable AI (XAI), model interpretability, and ML transparency.  Contributions welcome!
# Comprehensive XAI (Explainable AI) Resource List
---

## Table of Contents
1. [Popular & Comprehensive XAI Libraries](#popular--comprehensive-xai-libraries)
2. [Additional XAI Resources & Curated Lists](#additional-xai-resources--curated-lists)
3. [Notes](#notes)

---

## Popular & Comprehensive XAI Libraries

- [**OmniXAI (Salesforce)**](https://github.com/salesforce/OmniXAI)  
  A unified and extensible Python library for explainable AI, covering local and global explanations across tabular, vision, and NLP models. Offers a consistent API and built-in visualization tools.

- [**IBM AI Explainability 360 (AIX360)**](https://github.com/IBM/AIX360)  
  A diverse toolkit of algorithms for local and global explainability, interpretable models, counterfactual analysis, and fairness-focused methods. Includes tutorials and example notebooks.

- [**Captum (PyTorch, Meta)**](https://github.com/pytorch/captum)  
  Deep-learning-focused interpretability library offering gradient-based explanations (Integrated Gradients, DeepLIFT, GradientSHAP, Occlusion, etc.) for PyTorch models. Provides easy-to-use APIs and visualization utilities.

- [**InterpretML (Microsoft)**](https://github.com/interpretml/interpret)  
  A unified framework combining glass-box models (e.g., Explainable Boosting Machines) and black-box explanation techniques (LIME, SHAP). Offers an interactive dashboard for model interpretability.

- [**SHAP (SHapley Additive exPlanations)**](https://github.com/slundberg/shap)  
  A game-theoretic approach to explain each prediction. Provides model-agnostic and model-specific explainers for tree-based models, deep learning, and more. Visualizations like force plots, dependence plots, and summary plots are well-established.

- [**LIME (Local Interpretable Model-Agnostic Explanations)**](https://github.com/marcotcr/lime)  
  One of the earliest model-agnostic techniques for generating local explanations by approximating a complex model with a simpler, interpretable one in the neighborhood of each prediction.

- [**Alibi (SeldonIO)**](https://github.com/SeldonIO/alibi)  
  A suite of algorithms for explaining ML models, including Anchors (high-precision local rules), counterfactual explanations, contrastive explanations, and prototypes. Often used in production with Seldon Core.

- [**DALEX**](https://github.com/ModelOriented/DALEX)  
  A cross-language ecosystem (R and Python) for explaining ML models. Includes methods like variable importance, partial dependence plots, local explanations (e.g., LIME, SHAP), and interactive dashboards.

- [**Eli5**](https://github.com/TeamHG-Memex/eli5)  
  A straightforward library to visualize and debug ML models (scikit-learn, XGBoost, LightGBM, etc.). Supports feature importance, permutation importance, and partial dependence for quick local and global insights.

- [**Skater**](https://github.com/datascienceinc/Skater)  
  A Python library for model interpretation, offering global interpretability (feature importance, partial dependence) and local interpretability (LIME-like explanations), plus built-in visualizations.

- [**L2X (“Learning to Explain”)**](https://github.com/Jianbo-Lab/L2X)  
  Focuses on feature selection for local explanations by using mutual information to find the most influential subset of features per prediction, especially relevant for deep models.

- [**Py-Explainer**](https://github.com/temple-learner/Py-Explainer)  
  A library for rule-based local explanations by extracting interpretable rules from complex ML models, emphasizing tabular data explanations.

- [**Anchor (Original Implementation)**](https://github.com/marcotcr/anchor)  
  Original code for the “Anchors” explanation technique (same creator as LIME). Demonstrates how to produce if-then rule-based local explanations.

- [**TorchRay (Facebook Research)**](https://github.com/facebookresearch/TorchRay)  
  A library targeting **computer vision** interpretability in PyTorch: gradient-based saliency, occlusion methods, and feature visualization for CNNs.

- [**tf-explain**](https://github.com/sicara/tf-explain)  
  Interpretability methods for **TensorFlow/Keras** models, including Grad-CAM, Grad-CAM++, and occlusion-based explanations.

- [**keras-vis**](https://github.com/raghakot/keras-vis)  
  A toolkit for visualizing Keras CNNs (saliency maps, Grad-CAM, activation maximization) to help interpret model decisions in computer vision tasks.

- [**Ecco (NLP)**](https://github.com/john-hewitt/ecco)  
  Focused on **transformers** and other NLP models, allowing visualization and interpretation of attention heads, activations, and token importance in large language models.

- [**DAF (Deep AutoFocus)**](https://github.com/alexklibisz/deep-autofocus)  
  A specialized approach for interpretability of CNNs by focusing on salient regions, illustrating domain-specific XAI methods for computer vision.

- [**CEM (Contrastive Explanation Method)**](https://github.com/marcotcr/convince)  
  Provides “pertinent positives” and “pertinent negatives” to explain model decisions by what features are present (and necessary) vs. absent (and sufficient).

---

## Additional XAI Resources & Curated Lists

- [**Awesome Machine Learning Interpretability**](https://github.com/jphall663/awesome-machine-learning-interpretability)  
  A broader “awesome” list of XAI techniques, code, and research papers.

- [**Fairlearn (Microsoft)**](https://github.com/fairlearn/fairlearn)  
  Primarily focuses on **fairness** in AI, but also includes interpretability metrics, bias mitigation algorithms, and an interactive dashboard.

- [**AiExplainability360 Official Website (IBM)**](http://aix360.mybluemix.net)  
  Companion site for AIX360 with tutorials, demos, and in-depth documentation.

- [**Interpretable ML Book (by Christoph Molnar)**](https://github.com/christophM/interpretable-ml-book)  
  A free, in-depth resource covering theory and practice of model interpretability, often cited alongside the libraries above.

---

## Notes

- **Model-Agnostic vs Model-Specific**:  
  Some libraries (SHAP, LIME) can explain nearly any model, while others (Captum, tf-explain) specialize in certain frameworks (PyTorch, TensorFlow).

- **Local vs Global Explanations**:  
  Local methods explain individual predictions, whereas global methods describe overall model behavior and feature importance.

- **Domain-Specific Tools**:  
  - **Computer Vision**: TorchRay, tf-explain, keras-vis (with Grad-CAM, saliency).  
  - **NLP**: Ecco (visualizing transformers), LIME/SHAP (token-level explanations).  

- **Licenses & Usage**:  
  Most are open-source under MIT, Apache 2.0, or BSD. Check each project’s LICENSE for details on redistribution or modification.


