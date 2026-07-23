# bio2C: A Biomedical Benchmark and Modular RAG Framework for Text2Cypher

This repository collects the bio2C benchmark, code, notebooks, and outputs used for biomedical Text2Cypher experiments. It includes RAG-based pipelines for GPT and LLaMA, along with a fine-tuning pipeline for LLaMA-3-8B.

## Data

- [FTdataset](evaluating_text2cypher/FTdataset) contains the dataset splits used in the evaluation workflow.
- [CypherQueries](evaluating_text2cypher/CypherQueries) contains the reference Cypher queries grouped by task type.
- [NLquestions](evaluating_text2cypher/NLquestions) contains the natural-language questions used in the experiments.
- [Neo4jOutputs](evaluating_text2cypher/Neo4jOutputs) stores the outputs produced during query execution.
- [chroma_db](evaluating_text2cypher/chroma_db) contains the vector database used in the retrieval-oriented experiments.

## Citation

Please cite the following articles if this project was useful for your research:

```bibtex
  @article{Cavalleri2026bio2c,
      title="A Biomedical Benchmark and Modular RAG Framework for Text2Cypher", 
      author="Emanuele Cavalleri and Nada Bou Kanaan and Marco Mesiti",
      ADD PREPRINT WHEN PUBLISHED
  }
```