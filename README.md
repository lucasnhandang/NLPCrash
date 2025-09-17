
# nlp-llm-crash-48h

Structure:
- 01_classification/classification_distilbert.ipynb
- 02_ner/ner_roberta_conll2003.ipynb
- 03_ir_rerank/ir_bi_cross_rerank.ipynb
- 04_sft/sft_trl_minimal.ipynb
- 05_rag_langchain/rag_langchain_minimal.ipynb
- 06_rag_llamaindex/rag_llamaindex_minimal.ipynb
- 07_vllm/vllm_client_openai_compatible.ipynb
- 08_prompt_bank/prompt_bank.md

Run order: 01 → 03 → 05/06 → 04 → 07. GPU recommended for 04/05/06.

Notes:
- Install dependencies cell-by-cell. Replace models with smaller ones if VRAM is limited.
- Internet-required datasets/models are pulled by HF hub. Configure proxies if needed.
