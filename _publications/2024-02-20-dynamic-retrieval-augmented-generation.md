---
title: "Dynamic Retrieval-Augmented Generation"
authors: '<i>Anton Shapkin, Denis Litvinov, Yaroslav Zharov, Egor Bogomolov, Timur Galimzyanov, and Timofey Bryksin</i>'
status: "preprint"
collection: publications
permalink: /publications/2024-02-20-dynamic-retrieval-augmented-generation
date: 2024-02-20
venue: "<b>arXiv</b>"
pdf: 'https://arxiv.org/abs/2312.08976'
counter_id: 'P8'
abstract: "<p><b>Abstract</b>. Current state-of-the-art large language models are effective in generating high-quality text and encapsulating a broad spectrum of world knowledge. These models, however, often hallucinate and lack locally relevant factual data. Retrieval-augmented approaches were introduced to overcome these problems and provide more accurate responses. Typically, the retrieved information is simply appended to the main request, restricting the context window size of the model. We propose a novel approach for the Dynamic Retrieval-Augmented Generation (DRAG), based on the entity-augmented generation, which injects compressed embeddings of the retrieved entities into the generative model. The proposed pipeline was developed for code-generation tasks, yet can be transferred to some domains of natural language processing. To train the model, we collect and publish a new project-level code generation dataset. We use it for the evaluation along with publicly available datasets. Our approach achieves several targets: (1) lifting the length limitations of the context window, saving on the prompt size; (2) allowing huge expansion of the number of retrieval entities available for the context; (3) alleviating the problem of misspelling or failing to find relevant entity names. This allows the model to beat all baselines (except GPT-3.5) with a strong margin.</p>"
---