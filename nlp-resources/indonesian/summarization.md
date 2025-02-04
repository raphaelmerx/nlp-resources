---
title: "Indonesian Text Summarization"
subtitle: "Model and its Dataset for Indonesian Text Summarization"
excerpt: "The task of producing a shorter version of one or several documents that preserves most of the input's meaning"
date: 2021-06-01
author: "Wilson Wongso, Steven Limcorn and AI-Research.id team"
draft: false
layout: list-sidebar
images:
- /blog/assets/css-grid-thumbnail.png
series:
- huggingface jax flax event
tags:
- GPT-2
- T5
- BERT
- BART
- Language Model
categories:
# layout options: single or single-sidebar
layout: single-sidebar
---

# 

## Models
| Name                                     | Description                                                                                                                                                            | Author                      | Link                                                                                 |
|------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------|--------------------------------------------------------------------------------------|
| Indonesian T5 Summarization Base Model   | t5-base-indonesian-summarization-cased model is based on t5-base-bahasa-summarization-cased by huseinzol05, finetuned using id_liputan6 dataset.                       | Cahya Wirawan               | [HuggingFace](https://huggingface.co/cahya/t5-base-indonesian-summarization-cased)   |
| Indonesian BERT2GPT Summarization Model  | bert2gpt-indonesian-summarization model is based on cahya/bert-base-indonesian-1.5G and cahya/gpt2-small-indonesian-522Mby cahya, finetuned using id_liputan6 dataset. | Cahya Wirawan               | [HuggingFace](https://huggingface.co/cahya/bert2gpt-indonesian-summarization)        |
| Indonesian BERT2BERT Summarization Model | bert2bert-indonesian-summarization model is based on cahya/bert-base-indonesian-1.5G by cahya, finetuned using id_liputan6 dataset.                                    | Cahya Wirawan               | [HuggingFace](https://huggingface.co/cahya/bert2bert-indonesian-summarization)       |
| Indonesian T5 Summarization Small Model  | t5-small-indonesian-summarization-cased model is based on t5-small-bahasa-summarization-cased by huseinzol05, finetuned using indosum dataset.                         | Panggi Libersa Jasri Akadol | [HuggingFace](https://huggingface.co/panggi/t5-small-indonesian-summarization-cased) |
| Indonesian T5 Summarization Base Model   | t5-base-indonesian-summarization-cased model is based on t5-base-bahasa-summarization-cased by huseinzol05, finetuned using indosum dataset.                           | Panggi Libersa Jasri Akadol | [HuggingFace](https://huggingface.co/panggi/t5-base-indonesian-summarization-cased)  |

## Datasets
| Name       | Description                                                                                                                                                                                                                                                                                                                                                                                                             | Author                                                                                                                                                          | Link                                                            |
|------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------|
| WikiLingua | A large-scale, multilingual dataset for the evaluation of crosslingual abstractive summarization systems. Authors extracted article and summary pairs in 18 languages from WikiHow, a high quality, collaborative resource of how-to guides on a diverse set of topics written by human authors.                                                                                                                        | Faisal Ladhak, Esin Durmus, Claire Cardie and Kathleen McKeown                                                                                                  | [HuggingFace](https://huggingface.co/datasets/wiki_lingua)      |
| Liputan6   | A large-scale Indonesian summarization dataset. Authors harvested articles from an online news portal, and obtain 215,827 document-summary pairs.                                                                                                                                                                                                                                                                       | Fajri Koto and Jey Han Lau and Timothy Baldwin                                                                                                                  | [HuggingFace](https://huggingface.co/datasets/id_liputan6)      |
| XLSum      | A comprehensive and diverse dataset comprising 1.35 million professionally annotated article-summary pairs from BBC, extracted using a set of carefully designed heuristics. The dataset covers 45 languages ranging from low to high-resource, for many of which no public dataset is currently available. XL-Sum is highly abstractive, concise, and of high quality, as indicated by human and intrinsic evaluation. | Hasan, Tahmid and Bhattacharjee, Abhik and Islam, Md. Saiful and Mubasshir, Kazi and Li, Yuan-Fang and Kang, Yong-Bin and Rahman, M. Sohel and Shahriyar, Rifat | [HuggingFace](https://huggingface.co/datasets/csebuetnlp/xlsum) |
