FROM vllm/vllm-openai:v0.6.4

ENTRYPOINT ["vllm",  "serve", "BAAI/bge-multilingual-gemma2", "--tokenizer=BAAI/bge-multilingual-gemma2", "--task=embedding"]
