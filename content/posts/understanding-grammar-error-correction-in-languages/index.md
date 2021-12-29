---
author: "Nihar Sanda"
title: "Understanding Grammar Error Correction in Morphologically Rich Languages"
date: "2021-12-28"
description: "Understanding the research paper on grammar error correction in morphologically rich languages especially in Russian Languages"
tags: ["NLP", "ML", "AI"]
categories: ["technology"]

# cover:
#   image: "1.png"
#   relative: true # To use relative path for cover image, used in hugo Page-bundles
---

In this article we will be discussing the research paper on grammar error correction in morphologically rich languages especially in Russian Languages. The research paper is titled: `The Grammar Error Correction in Morphologically Rich Languages: The Case of Russian` and it is published in the Journal of Language Technology. The research paper is available [here](https://aclanthology.org/Q19-1001.pdf)


Rozovskaya and Roth 2019, uses a corpus of the Russian Learner Corpus of Academic Writing (RULEC, 560K 
words) which is written by students in United States learning Russian.

Russian language is termed as "Morphologically Rich Language" (MRL's). The dataset included essays from 12 foreign and 5 heritage Russian speakers which was annotated by 2 native Russian speakers. The essays were annotated and each error was assigned a type which led to the development of error classification schema that addresses errors in morphology, syntax, and word usage, and takes into account linguistic properties of the Russian language.

The approaches experimented in the paper are:
1. Learner-trained classifiers: Error-specific classifiers trained on learner data
2. Minimal-supervision classifiers: Error-specific classifiers trained on learner and native data with minimal supervision
3. Phrase-based machine translation system
