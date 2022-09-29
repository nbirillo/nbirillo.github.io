---
title: "Inferring and Applying Type Changes"
authors: '<i>Ameya Ketkar, Oleg Smirnov, Nikolaos Tsantalis, Danny Dig, and Timofey Bryksin</i>'
status: "published"
collection: publications
permalink: /publications/2022-05-08-type-changes
date: 2022-05-08
venue: "proceedings of <b>ICSE'22</b>"
pdf: 'http://users.encs.concordia.ca/~nikolaos/publications/ICSE_2022.pdf'
paperurl: 'https://doi.org/10.1145/3510003.3510115'
tool: 'https://type-change.github.io/index.html'
data: 'https://type-change.github.io/ResultFinalExperimentNew/TypeChangeSummary.html'
video: 'https://www.youtube.com/watch?v=7Xg4yxxwxuI'
counter_id: 'C38'
level: 'A*'
abstract: "<p><b>Abstract</b>. Developers frequently change the type of a program element and update all its references to increase performance, security, or maintainability. Manually performing type changes is tedious, error-prone, and it overwhelms developers. Researchers and tool builders have proposed advanced techniques to assist developers when performing type changes. A major obstacle in using these techniques is that the developer has to manually encode rules for defining the type changes. Handcrafting such rules is difficult and often involves multiple trial-error iterations. Given that open-source repositories contain many examples of type-changes, if we could infer the adaptations, we would eliminate the burden on developers. We introduce TC-Infer, a novel technique that infers rewrite rules that capture the required adaptations from the version histories of open source projects. We then use these rules (expressed in the Comby language) as input to existing type change tools. To evaluate the effectiveness of TC-Infer, we use it to infer 4,931 rules for 605 popular type changes in a corpus of 400K commits. Our results show that TC-Infer deduced rewrite rules for 93% of the most popular type change patterns. Our results also show that the rewrite rules produced by TC-Infer are highly effective at applying type changes (99.2% precision and 93.4% recall). To significantly advance the existing science and tooling we released IntelliTC, an interactive and configurable refactoring plugin for IntelliJ IDEA to perform type changes.</p>"
---