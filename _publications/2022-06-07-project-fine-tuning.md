---
title: "Assessing Project-Level Fine-Tuning of ML4SE Models"
authors: '<i>Egor Bogomolov, Sergey Zhuravlev, Egor Spirin, and Timofey Bryksin</i>'
status: "preprint"
collection: publications
permalink: /publications/2022-06-07-project-fine-tuning
date: 2022-06-07
venue: "<b>e-Print archive</b>"
pdf: 'https://arxiv.org/abs/2206.03333'
data: 'https://zenodo.org/record/6040745'
counter_id: 'P3'
abstract: "<p><b>Abstract</b>. Machine Learning for Software Engineering (ML4SE) is an actively growing research area that focuses on methods that help programmers in their work. In order to apply the developed methods in practice, they need to achieve reasonable quality in order to help rather than distract developers. While the development of new approaches to code representation and data collection improves the overall quality of the models, it does not take into account the information that we can get from the project at hand.</p><p>In this work, we investigate how the model's quality can be improved if we target a specific project. We develop a framework to assess quality improvements that models can get after fine-tuning for the method name prediction task on a particular project. We evaluate three models of different complexity and compare their quality in three settings: trained on a large dataset of Java projects, further fine-tuned on the data from a particular project, and trained from scratch on this data. We show that per-project fine-tuning can greatly improve the models' quality as they capture the project's domain and naming conventions. We open-source the tool we used for data collection, as well as the code to run the experiments: <a href='https://zenodo.org/record/6040745'>https://zenodo.org/record/6040745</a>.</p>"
---