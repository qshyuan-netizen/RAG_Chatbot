# RAG_Chatbot
Ask AI to answer questions based on a private pdf file; grasp the concept RAG (Retrieval Augmented Generation).

RAG: (user query + contents retrieved from the pdf which are semantically similar) -> LLM -> answer generation.

Use LangChain classes to call open-source models on Hugging Face.

Pdf file used: a specialized technical paper [arxiv.org/pdf/2502.00835](https://arxiv.org/pdf/2502.00835).

**Example Q&A:**
Question:  Who are the authors of the paper "CAIMAN: Causal Action Influence Detection ..."?
Answer: The authors of the paper "CAIMAN: Causal Action Influence Detection for Sample-Efficient Loco-Manipulation" are:

1. Yuanchen Yuan
2. Jin Cheng
3. Núria Armengol Urpí
4. Stelian Coros
