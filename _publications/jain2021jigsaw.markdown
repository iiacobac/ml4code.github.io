---
layout: publication
title: Jigsaw: Large Language Models meet Program Synthesis
authors: Naman Jain, Skanda Vaidyanath, Arun Iyer, Nagarajan Natarajan, Suresh Parthasarathy, Sriram Rajamani, Rahul Sharma
conference: ICSE'22
year: 2021
additional_links:
   - {name: "ArXiV", url: "https://arxiv.org/abs/2112.02969"}
   - {name: "dataset", url: "https://github.com/microsoft/JigsawDataset/"}
   - {name: "media", url: "https://conf.researchr.org/details/icse-2022/icse-2022-papers/178/Jigsaw-Large-Language-Models-meet-Program-Synthesis"}
tags: ["language", "model", "program", "synthesis"]
---
Large pre-trained language models such as GPT-3, Codex, and Google’s language model are now capable of generating code from natural language specifications of programmer intent. We view these developments with a mixture of optimism and caution. On the optimistic side, such large language models have the potential to improve productivity by providing an automated AI pair programmer for every programmer in the world. On the cautionary side, since these large language models do not understand program semantics, they offer no guarantees about quality of the suggested code. In this paper, we present an approach to augment these large language models with post-processing steps based on program analysis and synthesis techniques, that understand the syntax and semantics of programs. Further, we show that such techniques can make use of user feedback and improve with usage. We present our experiences from building and evaluating such a tool Jigsaw, targeted at synthesizing code for using Python Pandas API using multi-modal inputs. Our experience suggests that as these large language models evolve for synthesizing code from intent, Jigsaw has an important role to play in improving the accuracy of the systems.
