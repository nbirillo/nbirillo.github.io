---
title: "Out of the BLEU: How Should We Assess Quality of the Code Generation Models?"
authors: '<i>Mikhail Evtikhiev, Egor Bogomolov, Yaroslav Sokolov, and Timofey Bryksin</i>'
status: "published"
collection: publications
permalink: /publications/2023-09-01-code-generation-metrics
date: 2023-09-01
venue: "<b>Journal of Systems and Software</b>"
paperurl: 'https://doi.org/10.1016/j.jss.2023.111741'
pdf: 'https://arxiv.org/abs/2208.03133'
level: 'Q1'
counter_id: 'J2'
data: 'https://github.com/JetBrains-Research/codegen-metrics'
abstract: "<p><b>Abstract</b>. In recent years, researchers have created and introduced a significant number of various code generation models. As human evaluation of every new model version is unfeasible, the community adopted automatic evaluation metrics such as BLEU to approximate the results of human judgement. These metrics originate from the machine translation domain and it is unclear whether they are applicable for the code generation tasks and how well they agree with the human evaluation on this task. There are also other metrics, CodeBLEU and RUBY, developed to estimate the similarity of code, that take into account the properties of source code. However, for these metrics there are hardly any studies on their agreement with the human evaluation. Despite all that, minimal differences in the metric scores have been used in recent papers to claim superiority of some code generation models over the others.</p><p>In this paper, we present a study on the applicability of six metrics -- BLEU, ROUGE-L, METEOR, ChrF, CodeBLEU, and RUBY -- for evaluation of code generation models. We conduct a study on two different code generation datasets and use human annotators to assess the quality of all models run on these datasets. The results indicate that for the CoNaLa dataset of Python one-liners, none of the metrics can correctly emulate human judgement on which model is better with >95% certainty if the difference in model scores is less than 5 points. For the HearthStone dataset, which consists of classes of a particular structure, a difference in model scores of at least 2 points is enough to claim the superiority of one model over the other. Our findings suggest that the ChrF metric is a better fit for the evaluation of code generation models than the commonly used BLEU and CodeBLEU. Yet, finding a metric for code generation that closely agrees with humans requires additional work.</p>"
j1: 'true'
j1venue: "<b>ASE'23</b>"
j1level: 'A*'
---