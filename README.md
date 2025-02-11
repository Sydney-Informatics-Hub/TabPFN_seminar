# AI-Powered Tabular Modeling with TabPFN

**Author:** Sebastian Haan, The University of Sydney

This repository accompanies a seminar on TabPFN, a novel approach to tabular data modeling leveraging artificial intelligence. TabPFN (**Tabular Prior-data Fitted Network**) represents a **major change** in how we approach tabular data. It uses **in-context learning to autonomously discover highly efficient algorithms**, often outperforming traditional methods on datasets with up to 10,000 samples and 500 features.


## Notebooks

This repository includes the following Jupyter notebooks to help you get started with TabPFN:

-   **TabPFN_Intro.ipynb**: Basic usage for classification and regression tasks. This notebook will guide you through the fundamental steps of applying TabPFN to your own tabular datasets. 
-   **TabPFN_UncertaintyEval.ipynb**: Testing the accuracy of predictive probabilities and quantiles. Learn how to evaluate the uncertainty estimates provided by TabPFN, crucial for risk assessment and decision-making.
-   **TabPFN_Insights.ipynb**: Explain model predictions with SHAP (Shapley Additive Explanations) and Feature Selection. Discover how to interpret TabPFN's predictions and gain insights into the most important features driving its decisions.
- **TabPFGen.ipynb**: Generate high-quality synthetic tabular data for regression and classification using energy modeling and TabPFN.

To use these notebooks, you can use Google Colaboratory (Colab) which provides a free cloud-based environment for running Python code, including Jupyter notebooks.


## References

https://www.nature.com/articles/s41586-024-08328-6 

https://arxiv.org/pdf/2207.01848v6 

[https://github.com/PriorLabs/TabPFN](https://github.com/PriorLabs/TabPFN)

