---
title: "Evaluation of Contrastive Learning with Various Code Representations for Code Clone Detection"
authors: '<i>Maksim Zubkov, Egor Spirin, Egor Bogomolov, and Timofey Bryksin</i>'
status: "preprint"
collection: publications
permalink: /publications/2022-06-17-contrastive-learning-for-semantic-clones
date: 2022-06-17
venue: "<b>e-Print archive</b>"
pdf: 'https://arxiv.org/abs/2206.08726'
data: 'https://zenodo.org/record/6360627'
counter_id: 'P4'
abstract: "<p><b>Abstract</b>. Code clones are pairs of code snippets that implement similar functionality. Clone detection is a fundamental branch of automatic source code comprehension, having many applications in refactoring recommendation, plagiarism detection, and code summarization. A particularly interesting case of clone detection is the detection of semantic clones, i.e., code snippets that have the same functionality but significantly differ in implementation. A promising approach to detecting semantic clones is contrastive learning (CL), a machine learning paradigm popular in computer vision but not yet commonly adopted for code processing.</p><p>Our work aims to evaluate the most popular CL algorithms combined with three source code representations on two tasks. The first task is code clone detection, which we evaluate on the POJ-104 dataset containing implementations of 104 algorithms. The second task is plagiarism detection. To evaluate the models on this task, we introduce CodeTransformator, a tool for transforming source code. We use it to create a dataset that mimics plagiarised code based on competitive programming solutions. We trained nine models for both tasks and compared them with six existing approaches, including traditional tools and modern pre-trained neural models. The results of our evaluation show that proposed models perform diversely in each task, however the performance of the graph-based models is generally above the others. Among CL algorithms, SimCLR and SwAV lead to better results, while Moco is the most robust approach. Our code and trained models are available at <a href='https://doi.org/10.5281/zenodo.6360627'>https://doi.org/10.5281/zenodo.6360627</a>, <a href='https://doi.org/10.5281/zenodo.5596345'>https://doi.org/10.5281/zenodo.5596345</a>.</p>"
---