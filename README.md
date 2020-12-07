# NLP-Papers
收集NLP经典的相关论文
EMNLP 2020
1. Question Generation

   https://arxiv.org/pdf/2010.01657.pdf
   
   Abstract：Inquisitive probing questions come naturally to humans in a variety of settings, but is a challenging task for automatic systems. One natural type of      question to ask tries to fill a gap in knowledge during text comprehension, like reading a news article: we might ask about background information, deeper          reasons behind things occurring, or more. Despite recent progress with data-driven approaches, generating such questions is beyond the range of models trained on    existing datasets. We introduce INQUISITIVE, a dataset of ∼19K questions that are elicited while a person is reading through a document. Compared to existing        datasets, INQUISITIVE questions target more towards high-level (semantic and discourse) comprehension of text. We show that readers engage in a series of            pragmatic strategies to seek information. Finally, we evaluate question generation models based on GPT2 (Radford et al., 2019) and show that our model is able to    generate reasonable questions although the task is challenging, and highlight the importance of context to generate INQUISITIVE questions

2. Language Model Pretraining
   1) Probing Pretrained Language Models for Lexical Semantics
   
   https://arxiv.org/abs/2010.05731
   
   2) Tired of Topic Models? Clusters of Pretrained Word Embeddings Make for Fast and Good Topics too!
   
   https://arxiv.org/abs/2004.14914
   
   3) Pretrained Language Model Embryology: The Birth of ALBERT
   
   https://arxiv.org/abs/2010.02480
   
   Abstract: While behaviors of pretrained language models (LMs) have been thoroughly examined, what happened during pretraining is rarely studied. We thus          investigate the developmental process from a set of randomly initialized parameters to a totipotent1 language model, which we refer to as the embryology of a    pretrained language model. Our results show that ALBERT learns to reconstruct and predict tokens of different parts of speech (POS) in different learning        speeds during pretraining. We also find that linguistic knowledge and world knowledge do not generally improve as pretraining proceeds, nor do downstream        tasks’ performance. These findings suggest that knowledge of a pretrained model varies during pretraining, and having more pretrain steps does not necessarily    provide a model with more comprehensive knowledge. We provide source codes and pretrained models to reproduce our results at                          https://github.com/d223302/albert-embryology.
   
   4) 
