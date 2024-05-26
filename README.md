# Massive Text Embedding Benchmark for French Taxation 🤗
[![Python](https://img.shields.io/pypi/pyversions/tensorflow.svg)](https://badge.fury.io/py/tensorflow)
![Maintainer](https://img.shields.io/badge/maintainer-@louisbrulenaudet-blue)
<a target="_blank" href="https://colab.research.google.com/github/louisbrulenaudet/tax-retrieval-benchmark/blob/main/notebook.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

In this notebook, we will explore the process of adding a new task to the Massive Text Embedding Benchmark (MTEB). The MTEB is an open-source framework developed to facilitate the evaluation and benchmarking of multilingual and multi-task models across a diverse set of tasks and languages.

The task we will be integrating is the TaxRetrievalBenchmark, a retrieval task focused on retrieving relevant tax articles or content based on provided queries. This task is particularly useful in the legal and financial domains, where accurate and efficient retrieval of relevant information is crucial.
To add this task to the MTEB framework, we will follow a structured approach:

- Understanding the task: We will start by analyzing the TaxRetrievalBenchmark task, its data format, and the evaluation metrics used to assess model performance.
- Preparing the data: Next, we will preprocess the data from the HuggingFace Hub, converting it to the MTEB format. This step involves organizing the corpus, queries, and relevant document information into the required data structures.
- Implementing the task class: We will then implement the TaxRetrievalBenchmark class, which inherits from the AbsTaskRetrieval class provided by the MTEB framework. This class will encapsulate the task-specific logic, including data loading, metadata management, and evaluation methods.
- Integrating with MTEB: Finally, we will integrate the TaxRetrievalBenchmark class into the MTEB framework, allowing it to be used alongside other tasks for multi-task training and evaluation.

By adding the TaxRetrievalBenchmark task to the MTEB framework, we will contribute to the growing collection of diverse tasks, enabling researchers and practitioners to develop and evaluate multilingual and multi-task models more effectively. This notebook will serve as a practical guide for anyone interested in extending the MTEB framework with new tasks, fostering collaboration and advancing the field of natural language processing.

## Citing this project

If you use this code in your research, please use the following BibTeX entry.

```BibTeX
@misc{louisbrulenaudet2024,
  author =       {Louis Brulé Naudet},
  title =        {Massive Text Embedding Benchmark for French Taxation},
  year =         {2024}
}
```

## Feedback

If you have any feedback, please reach out at [louisbrulenaudet@icloud.com](mailto:louisbrulenaudet@icloud.com).
