# EuroScipy2023
I attended the 15th European Conference on Python in Science (EuroScipy2023). Here in this repository I summerized the teaching materials (github links) from the workshops I have attended.

## 1. Network Analysis Made Simple
Network analysis tutorial: https://github.com/ericmjl/Network-Analysis-Made-Simple

Project Homepage / Git: github.com/networkx/networkx

Public link to supporting material: https://ericmjl.github.io/Network-Analysis-Made-Simple/
Workshop outline:

### Part 1: Introduction (30 min)

1. Networks of all kinds: biological, transportation, web.
2. Representation of networks, NetworkX data structures
3. Introduction to NetworkX API for modelling and graph operations.

### Part 2: Hubs and Paths (30 min)

1. Finding important nodes; applications
2. Pathfinding algorithms and their applications
3. Hands-on: implementing path-finding algorithms
4. Visualize degree and betweenness centrality distributions.

### Part 3: Speed up your code with NetworkX dispatching (30 min)

1. Quick introduction to GraphBLAS
2. Moving between GraphBLAS and NetworkX.
3. Speed up your NetworkX code by changing one line of code!


## 2. Introduction to Geospatial Machine Learning with SRAI
geopandas-tutorial: https://github.com/jorisvandenbossche/geopandas-tutorial

srai-tutorial: https://github.com/kraina-ai/srai-tutorial 

By the end of the tutorial, attendees will be able to:
1. Install and set up the SRAI library.
2. Use SRAI to download and process geospatial data.
3. Apply various regionalization and embedding techniques to geospatial data.
4. Utilize pre-trained embedding models for clustering and similarity search.
5. Build predictive models on top of SRAI embeddings
6. Pre-train available models from scratch.
7. Understand the potential applications and future enhancements of the SRAI library.

## 3. Introduction to NumPy


## 4. Predictive survival analysis with scikit-learn, scikit-survival and lifelines
Tutorial notebooks: https://vincent-maladiere.github.io/survival-analysis-demo

Here is a tentative agenda:

1. What is time-censored data and why it is a problem to train time-to-event regression models.
2. Single event survival analysis with Kaplan-Meier using scikit-survival.
3. Evaluation of the calibration of survival analysis estimators using the integrated brier score (IBS) metric.
4. Predictive survival analysis modeling with Cox Proportional Hazards, Survival Forests using scikit-survival, GradientBoostedIBS implemented from scratch with scikit-learn.
5. How to use a trained GradientBoostedIBS model to estimate the median survival time and the probability of survival at a fixed time horizon.
6. Inspecting the learned statistical association between input features and survival probabilities using partial dependence plot.

## 5. Introduction to scikit-learn
Workshop Outline:
1. Machine Learning 101 (10 min.)
2. What is scikit-learn? (5 min.)
3. Practical Part (+60 min.)
4. Predictive modeling pipeline
5. Evaluation of models
6. Hyperparameters tuning

Public link to supporting material: https://inria.github.io/scikit-learn-mooc/

Tutorial: https://github.com/StefanieSenger/Talks/blob/main/2023_EuroSciPy/2023_EuroSciPy_Intro_to_scikit-learn_fillout-notebook.ipynb

## 6. Image processing with scikit-image
Tutorial: https://github.com/glemaitre/euroscipy-2023-scikit-image

Workshop Outline:
1. image histogram and contrast
2. image filtering: transformations of an image resulting in a new image of similar size (for example, thresholding, edge enhancement, etc.)
3. image segmentation: partitioning an image into several regions (objects)
4. image descriptors

## 7. Get the best from your scikit-learn classifier: trusted probabilties and optimal binary decision
Github link: https://github.com/scikit-learn/scikit-learn/pull/26120

Scikit-learn does not provide any flexibility to go from "soft" to "hard" predictions: it uses a cut-off point at a confidence score of 0.5 (or 0 when using decision_function) to get class labels. However, optimizing a classifier to get a confidence score close to the true probabilities (i.e. a calibrated classifier) does not guarantee to obtain accurate "hard" predictions using this heuristic. Reversely, training a classifier for an optimum "hard" prediction accuracy (with the cut-off constraint at 0.5) does not guarantee obtaining a calibrated classifier.
In this talk, we will present a new scikit-learn meta-estimator allowing us to get the best of the two worlds: a calibrated classifier providing optimum "hard" predictions.
## 8. Timing and Benchmarking Scientific Python
Github link: https://github.com/Kai-Striega/EuroSciPy-2023-Speech/blob/main/EuroSciPy_Speech.pdf

Scientific code is often complex, resource-intensive, and sensitive to performance issues, making accurate timing and benchmarking critical for optimising performance and ensuring reproducibility. However, benchmarking scientific code presents several challenges, including variability in input data, hardware and software dependencies, and optimisation trade-offs. In this talk, I discuss the importance of timing and benchmarking for scientific code and outline strategies for addressing these challenges. Specifically, I emphasise the need for representative input data, controlled benchmarking environments, appropriate metrics, and careful documentation of the benchmarking process. By following these strategies, developers can effectively optimise code performance, select efficient algorithms and data structures, and ensure the reliability and reproducibility of scientific computations.

## 9. Solara: A Pure Python, React-style Framework for Scaling Your Data Apps
Github link: https://github.com/widgetti/solara/
Public link to supporting material: https://solara.dev

Solara is a pure Python web framework designed to scale complex applications. Leveraging a React-like API, Solara offers the scalability, component-based coding, and simple state management that have made React a standard for large web applications. Solara uses a pure Python implementation of React, Reacton, to create ipywidgets-based applications that work both in the Jupyter Notebook environment and as standalone web apps with frameworks like FastAPI. This talk will explore the design principles of Solara, illustrate its potential with case studies and live examples, and provide resources for attendees to incorporate Solara into their own projects. Whether you're a researcher developing interactive visualizations or a data scientist building complex web applications, Solara provides a Python-centric solution for scaling your projects effectively.

## 10. Chalk’it: an open-source framework for rapid web applications
Github link: https://github.com/ifpen/chalk-it

Please also visit the templates galleries, that can be explored online using the hosted version of Chalk’it : https://ifpen.github.io/chalk-it/
halk'it is an open-source framework that transforms Python scripts into distributable web app dashboards. It utilizes drag-and-drop widgets to establish an interface linked to a dataflow connecting Python code and various data sources. Chalk'it supports multiple Python graphics libraries, including Plotly, Matplotlib and Folium for interactive mapping and visualization. The framework operates entirely in web browsers using Pyodide. In our presentation, we will showcase Chalk'it, emphasizing its primary features, software architecture, and key applications, with a special focus on geospatial data visualization.

## 11. MLJAR Automated Machine Learning for Humans
Github link: https://github.com/mljar/mljar-supervised

The mljar-supervised is an Automated Machine Learning Python package that works with tabular data. It is designed to save time for a data scientist. It abstracts the common way to preprocess the data, construct the machine learning models, and perform hyper-parameters tuning to find the best model 🏆. It is no black-box as you can see exactly how the ML pipeline is constructed (with a detailed Markdown report for each ML model).

## 12. skrub - is a Python library that facilitates prepping your tables for machine learning.
Github link: https://github.com/skrub-data/skrub

skrub provides tools (TableVectorizer, fuzzy_join...) and encoders (GapEncoder, MinHashEncoder...) for morphological similarities, for which we usually identify three common cases: similarities, typos and variations


## 13. scverse: foundational tools for single-cell omics analysis
Github link: https://scverse.org/packages/

This repository contains the list of scverse ecosystem packages that are displayed on scverse.org. The goal is to increase visibility of ecosystem packages and make it easier for users to find appropriate software. Registered ecosystem packages can also get their own tag to use on the scverse forum for user discussion. Authors of these packages can be added the scverse github organization. In the future, we may also test releases of core packages against the test suites of ecosystem packages.

If a package is part of this list, it means it fulfills certain minimum requirements as outlined below. It does not imply endorsement or that an in-depth review has been performed.

## 14. RNA-seq data normalization in Python
Github link: https://github.com/genialis/RNAnorm

Python implementation of common RNA-seq normalization methods:
•	CPM (Counts per million)
•	FPKM (Fragments per kilobase million)
•	TPM (Transcripts per million)
•	UQ (Upper quartile)
•	CUF (Counts adjusted with UQ factors)
•	TMM (Trimmed mean of M-values)
•	CTF (Counts adjusted with TMM factors)

## 15. caffeine: Covariance Data Frames for Predictive M/EEG Pipelines
Github link: https://github.com/coffeine-labs/coffeine

Coffeine is designed for building biomedical prediction models from M/EEG signals. The library provides a high-level interface facilitating the use of M/EEG covariance matrix as representation of the signal. The methods implemented here make use of tools and concepts implemented in PyRiemann. The API is fully compatible with scikit-learn and naturally integrates with MNE.


