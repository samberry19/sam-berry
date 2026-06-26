---
title: "Differences between protein fitness models can be used to design variants of altered specificity"

authors:
- admin
- Rachelle Gaudet
- Debora S Marks

date: "2026-06-10T00:00:00Z"
doi: "https://doi.org/10.64898/2026.06.10.731299"

publishDate: "2026-06-10T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

publication: In *bioRxiv*
publication_short: In *bioRxiv*

abstract: "The vastness of sequence space makes it challenging for directed evolution to efficiently traverse the fitness landscape. In recent years, unsupervised probabilistic models trained on natural sequences have shown promise for predicting the functional effects of mutations and designing new proteins, leading many to suggest that these models may be useful for guiding directed evolution campaigns toward functional regions of sequence space. However, many directed evolution campaigns are interested in evolving new substrate or ligand specificity, and the behavior of unsupervised sequence models on predicting and designing activity against altered substrates or ligands has not been tested. We have built a curated database of multiplexed functional assay results profiling substrate or ligand specificity and systematically assessed how various popular unsupervised protein fitness models score and design variants that alter selectivity in these datasets. We find that sequence models that learn from the surrounding sequence context, especially protein language models, systematically bias against variants that alter specificity. This bias leads them to design altered-specificity variants at similar or lower rates than random chance. However, we propose a simple strategy to exploit this bias by taking weighted differences of model scores to enrich libraries for altered-specificity variants. These findings and our database should help guide how biologists best use protein fitness models and provide a framework to help machine learning researchers develop a new generation of machine learning models that can better design novelty."

tags: []

featured: false

links:
- name: Preprint
  url: https://www.biorxiv.org/content/10.64898/2026.06.10.731299v1

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---
