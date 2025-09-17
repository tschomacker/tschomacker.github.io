---
title: "LLMs for Easy Language Translation: A Case Study on German Public Authorities Web Pages"
collection: publications
category: conferences
permalink: /publication/2025-09-01-llms-for-easy-language-translation
excerpt: 'This paper examines the use of Large Language Models (LLMs) for the intralingual translation of documents from standard German to German Easy Language (Leichte Sprache).'
date: 2025-09-01
venue: 'Lecture Notes in Computer Science'
#slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://doi.org/10.1007/978-3-032-02813-6_20'
manuscripturl: '../files/2025-09-01-llms-for-easy-language-translation.pdf'
citation: 'Schomacker, T., Tinman, B., Biemann, C., Tropmann-Frick, M. (2026). LLMs for Easy Language Translation: A Case Study on German Public Authorities Web Pages. In: Braun, T., Paaßen, B., Stolzenburg, F. (eds) KI 2025: Advances in Artificial Intelligence. KI 2025. Lecture Notes in Computer Science(), vol 15956. Springer, Cham. <a href="https://doi.org/10.1007/978-3-032-02813-6_20">https://doi.org/10.1007/978-3-032-02813-6_20</a>'
---

This paper examines the use of Large Language Models (LLMs) for the intralingual translation of documents from standard German to German Easy Language (Leichte Sprache). We use open-weight models, from the Llama 3 family, with less than ten billion parameters. Additionally, we employ parameter-efficient fine-tuning (QLoRA) to adapt the LLMs to the requirements of Easy Language. For this purpose, we introduce a new data set (ELGEPA) (Source code to obtain the dataset: github.com/minds-hh/ger-gov-easy-lang), which is a parallel corpus of governmental documents in standard German and Easy Language with additional metadata, obtained from all German federal states and their capitals In our experiments, a fine-tuned Llama 3.1-8B-Instruct model achieved a SARI score of 41 and Flesch Reading Ease of 69. Outperforming GPT-4o and indicating that this type of model can deliver promising text quality in Easy Language.