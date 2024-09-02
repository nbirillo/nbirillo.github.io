---
title: "Smart Caching for Efficient Functional Dependency Discovery"
authors: '<i>Anastasiia Birillo and Nikita Bobrov</i>'
status: "published"
collection: publications
permalink: /publications/2019-09-11-smart-caching
date: 2019-09-11
venue: "the proceedings of <b>ADBIS'19</b>"
level: 'C'
paperurl: 'https://doi.org/10.1007/978-3-030-30278-8_7'
counter_id: 'C2'
abstract: '<p><b>Abstract</b>. Functional dependency (FD) is a concept for describing regularities in data, that traditionally was used for schema normalization. Recently, a different problem has emerged: for a given dataset, find FDs that are contained in it. Efficient FD discovery is of great importance due to FD usage in many tasks such as data cleaning, schema recovery, and query optimization.</p><p>In this paper we consider a particular class of FD discovery algorithms that rely on partition intersection. We present a simple approach for caching intermediate results that are generated during run times of these algorithms. Our approach is essentially a heuristic that selects which partitions to cache based on measures of disorder in data. For this purpose, we adopt such well-known measures as Entropy and Gini Impurity, and propose a novel one—Inverted Entropy. Our approach has a negligible computational overhead, and can be used with a number of FD discovery algorithms, both exact and approximate. Our experiments demonstrate that our heuristic allows to decrease algorithm run times by up to 40% while simultaneously requiring up to an order of magnitude less space compared to the state-of-the-art caching approaches.</p>'
---