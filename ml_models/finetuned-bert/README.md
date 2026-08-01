---
tags:
  - sentence-transformers
  - sentence-similarity
  - feature-extraction
  - generated_from_trainer
  - dataset_size:224
  - loss:CosineSimilarityLoss
base_model: sentence-transformers/all-mpnet-base-v2
widget:
  - source_sentence:
      "Data Scientist with 7 years of professional experience. Skilled
      in Python, Pandas, TensorFlow, SQL, Machine Learning, NLP, Scikit-learn. Worked
      on enterprise applications, collaborated with Agile teams, improved application
      performance, wrote clean and maintainable code, participated in code reviews,
      and delivered production-ready solutions. Education: B.Sc. Computer Science. Certification:
      Docker Certified Associate. Strong communication, leadership, and analytical skills."
    sentences:
      - We are hiring a AI Engineer. Responsibilities include designing, developing, testing,
        and maintaining software systems. Required skills include RAG, PyTorch, Python,
        LangChain, LLMs. Candidates should be comfortable working in Agile environments,
        collaborating with cross-functional teams, solving complex problems, and delivering
        high-quality software.
      - We are hiring a Data Scientist. Responsibilities include designing, developing,
        testing, and maintaining software systems. Required skills include Scikit-learn,
        Pandas, SQL, Communication, Problem Solving. Candidates should be comfortable
        working in Agile environments, collaborating with cross-functional teams, solving
        complex problems, and delivering high-quality software.
      - We are hiring a Data Analyst. Responsibilities include designing, developing,
        testing, and maintaining software systems. Required skills include SQL, Power
        BI, Tableau, Python, Excel. Candidates should be comfortable working in Agile
        environments, collaborating with cross-functional teams, solving complex problems,
        and delivering high-quality software.
  - source_sentence:
      "Full Stack Developer with 9 years of professional experience.
      Skilled in React, Node.js, MongoDB, Express, JavaScript, Docker, AWS. Worked on
      enterprise applications, collaborated with Agile teams, improved application performance,
      wrote clean and maintainable code, participated in code reviews, and delivered
      production-ready solutions. Education: B.E. Information Technology. Certification:
      Microsoft Azure Fundamentals. Strong communication, leadership, and analytical
      skills."
    sentences:
      - We are hiring a Business Analyst. Responsibilities include designing, developing,
        testing, and maintaining software systems. Required skills include Python, Git,
        PostgreSQL, AWS, FastAPI. Candidates should be comfortable working in Agile environments,
        collaborating with cross-functional teams, solving complex problems, and delivering
        high-quality software.
      - We are hiring a Software Engineer. Responsibilities include designing, developing,
        testing, and maintaining software systems. Required skills include Git, Docker,
        Java, Python, SQL. Candidates should be comfortable working in Agile environments,
        collaborating with cross-functional teams, solving complex problems, and delivering
        high-quality software.
      - We are hiring a Cybersecurity Analyst. Responsibilities include designing, developing,
        testing, and maintaining software systems. Required skills include Security Audits,
        Burp Suite, Python, Communication, Problem Solving. Candidates should be comfortable
        working in Agile environments, collaborating with cross-functional teams, solving
        complex problems, and delivering high-quality software.
  - source_sentence:
      "Data Analyst with 0 years of professional experience. Skilled
      in SQL, Power BI, Excel, Tableau, Python. Worked on enterprise applications, collaborated
      with Agile teams, improved application performance, wrote clean and maintainable
      code, participated in code reviews, and delivered production-ready solutions.
      Education: B.E. Information Technology. Certification: Microsoft Azure Fundamentals.
      Strong communication, leadership, and analytical skills."
    sentences:
      - We are hiring a Data Analyst. Responsibilities include designing, developing,
        testing, and maintaining software systems. Required skills include Excel, Python,
        Power BI, Communication, Problem Solving. Candidates should be comfortable working
        in Agile environments, collaborating with cross-functional teams, solving complex
        problems, and delivering high-quality software.
      - We are hiring a Backend Developer. Responsibilities include designing, developing,
        testing, and maintaining software systems. Required skills include Git, Docker,
        FastAPI, Communication, Problem Solving. Candidates should be comfortable working
        in Agile environments, collaborating with cross-functional teams, solving complex
        problems, and delivering high-quality software.
      - We are hiring a DevOps Engineer. Responsibilities include designing, developing,
        testing, and maintaining software systems. Required skills include Jenkins, Terraform,
        CI/CD, Linux, Kubernetes. Candidates should be comfortable working in Agile environments,
        collaborating with cross-functional teams, solving complex problems, and delivering
        high-quality software.
  - source_sentence:
      "Software Engineer with 5 years of professional experience. Skilled
      in Python, Java, Git, Docker, AWS, REST APIs, SQL. Worked on enterprise applications,
      collaborated with Agile teams, improved application performance, wrote clean and
      maintainable code, participated in code reviews, and delivered production-ready
      solutions. Education: B.Tech in Computer Science. Certification: Microsoft Azure
      Fundamentals. Strong communication, leadership, and analytical skills."
    sentences:
      - We are hiring a Software Engineer. Responsibilities include designing, developing,
        testing, and maintaining software systems. Required skills include NLP, Scikit-learn,
        Machine Learning, SQL, TensorFlow. Candidates should be comfortable working in
        Agile environments, collaborating with cross-functional teams, solving complex
        problems, and delivering high-quality software.
      - We are hiring a Frontend Developer. Responsibilities include designing, developing,
        testing, and maintaining software systems. Required skills include HTML, React,
        CSS, Redux, REST APIs. Candidates should be comfortable working in Agile environments,
        collaborating with cross-functional teams, solving complex problems, and delivering
        high-quality software.
      - We are hiring a Cybersecurity Analyst. Responsibilities include designing, developing,
        testing, and maintaining software systems. Required skills include SIEM, Python,
        Wireshark, Burp Suite, Linux. Candidates should be comfortable working in Agile
        environments, collaborating with cross-functional teams, solving complex problems,
        and delivering high-quality software.
  - source_sentence:
      "Cybersecurity Analyst with 5 years of professional experience.
      Skilled in SIEM, Wireshark, Linux, Python, Burp Suite, Security Audits. Worked
      on enterprise applications, collaborated with Agile teams, improved application
      performance, wrote clean and maintainable code, participated in code reviews,
      and delivered production-ready solutions. Education: B.E. Information Technology.
      Certification: Docker Certified Associate. Strong communication, leadership, and
      analytical skills."
    sentences:
      - We are hiring a Data Scientist. Responsibilities include designing, developing,
        testing, and maintaining software systems. Required skills include Pandas, Scikit-learn,
        Python, Communication, Problem Solving. Candidates should be comfortable working
        in Agile environments, collaborating with cross-functional teams, solving complex
        problems, and delivering high-quality software.
      - We are hiring a Backend Developer. Responsibilities include designing, developing,
        testing, and maintaining software systems. Required skills include Python, FastAPI,
        PostgreSQL, Docker, Redis. Candidates should be comfortable working in Agile environments,
        collaborating with cross-functional teams, solving complex problems, and delivering
        high-quality software.
      - We are hiring a Cybersecurity Analyst. Responsibilities include designing, developing,
        testing, and maintaining software systems. Required skills include Python, Burp
        Suite, Security Audits, Communication, Problem Solving. Candidates should be comfortable
        working in Agile environments, collaborating with cross-functional teams, solving
        complex problems, and delivering high-quality software.
pipeline_tag: sentence-similarity
library_name: sentence-transformers
metrics:
  - pearson_cosine
  - spearman_cosine
model-index:
  - name: SentenceTransformer based on sentence-transformers/all-mpnet-base-v2
    results:
      - task:
          type: semantic-similarity
          name: Semantic Similarity
        dataset:
          name: ats val
          type: ats-val
        metrics:
          - type: pearson_cosine
            value: 0.9368708181906351
            name: Pearson Cosine
          - type: spearman_cosine
            value: 0.8995955814702428
            name: Spearman Cosine
---

# SentenceTransformer based on sentence-transformers/all-mpnet-base-v2

This is a [sentence-transformers](https://www.SBERT.net) model finetuned from [sentence-transformers/all-mpnet-base-v2](https://huggingface.co/sentence-transformers/all-mpnet-base-v2). It maps sentences & paragraphs to a 768-dimensional dense vector space and can be used for retrieval.

## Model Details

### Model Description

- **Model Type:** Sentence Transformer
- **Base model:** [sentence-transformers/all-mpnet-base-v2](https://huggingface.co/sentence-transformers/all-mpnet-base-v2) <!-- at revision e8c3b32edf5434bc2275fc9bab85f82640a19130 -->
- **Maximum Sequence Length:** 384 tokens
- **Output Dimensionality:** 768 dimensions
- **Similarity Function:** Cosine Similarity
- **Supported Modality:** Text
  <!-- - **Training Dataset:** Unknown -->
  <!-- - **Language:** Unknown -->
  <!-- - **License:** Unknown -->

### Model Sources

- **Documentation:** [Sentence Transformers Documentation](https://sbert.net)
- **Repository:** [Sentence Transformers on GitHub](https://github.com/huggingface/sentence-transformers)
- **Hugging Face:** [Sentence Transformers on Hugging Face](https://huggingface.co/models?library=sentence-transformers)

### Full Model Architecture

```
SentenceTransformer(
  (0): Transformer({'transformer_task': 'feature-extraction', 'modality_config': {'text': {'method': 'forward', 'method_output_name': 'last_hidden_state'}}, 'module_output_name': 'token_embeddings', 'architecture': 'MPNetModel'})
  (1): Pooling({'embedding_dimension': 768, 'pooling_mode': 'mean', 'include_prompt': True})
  (2): Normalize({})
)
```

## Usage

### Direct Usage (Sentence Transformers)

First install the Sentence Transformers library:

```bash
pip install -U sentence-transformers
```

Then you can load this model and run inference.

```python
from sentence_transformers import SentenceTransformer

# Download from the 🤗 Hub
model = SentenceTransformer("sentence_transformers_model_id")
# Run inference
sentences = [
    'Cybersecurity Analyst with 5 years of professional experience. Skilled in SIEM, Wireshark, Linux, Python, Burp Suite, Security Audits. Worked on enterprise applications, collaborated with Agile teams, improved application performance, wrote clean and maintainable code, participated in code reviews, and delivered production-ready solutions. Education: B.E. Information Technology. Certification: Docker Certified Associate. Strong communication, leadership, and analytical skills.',
    'We are hiring a Cybersecurity Analyst. Responsibilities include designing, developing, testing, and maintaining software systems. Required skills include Python, Burp Suite, Security Audits, Communication, Problem Solving. Candidates should be comfortable working in Agile environments, collaborating with cross-functional teams, solving complex problems, and delivering high-quality software.',
    'We are hiring a Data Scientist. Responsibilities include designing, developing, testing, and maintaining software systems. Required skills include Pandas, Scikit-learn, Python, Communication, Problem Solving. Candidates should be comfortable working in Agile environments, collaborating with cross-functional teams, solving complex problems, and delivering high-quality software.',
]
embeddings = model.encode(sentences)
print(embeddings.shape)
# [3, 768]

# Get the similarity scores for the embeddings
similarities = model.similarity(embeddings, embeddings)
print(similarities)
# tensor([[1.0000, 0.7135, 0.1784],
#         [0.7135, 1.0000, 0.4402],
#         [0.1784, 0.4402, 1.0000]])
```

<!--
### Direct Usage (Transformers)

<details><summary>Click to see the direct usage in Transformers</summary>

</details>
-->

<!--
### Downstream Usage (Sentence Transformers)

You can finetune this model on your own dataset.

<details><summary>Click to expand</summary>

</details>
-->

<!--
### Out-of-Scope Use

*List how the model may foreseeably be misused and address what users ought not to do with the model.*
-->

## Evaluation

### Metrics

#### Semantic Similarity

- Dataset: `ats-val`
- Evaluated with [<code>EmbeddingSimilarityEvaluator</code>](https://sbert.net/docs/package_reference/sentence_transformer/evaluation.html#sentence_transformers.sentence_transformer.evaluation.EmbeddingSimilarityEvaluator)

| Metric              | Value      |
| :------------------ | :--------- |
| pearson_cosine      | 0.9369     |
| **spearman_cosine** | **0.8996** |

<!--
## Bias, Risks and Limitations

*What are the known or foreseeable issues stemming from this model? You could also flag here known failure cases or weaknesses of the model.*
-->

<!--
### Recommendations

*What are recommendations with respect to the foreseeable issues? For example, filtering explicit content.*
-->

## Training Details

### Training Dataset

#### Unnamed Dataset

- Size: 224 training samples
- Columns: <code>sentence_0</code>, <code>sentence_1</code>, and <code>label</code>
- Approximate statistics based on the first 100 samples:
  | | sentence_0 | sentence_1 | label |
  |:---------|:-----------------------------------------------------------------------------------|:----------------------------------------------------------------------------------|:-----------------------------------------------------------------|
  | type | string | string | float |
  | modality | text | text | |
  | details | <ul><li>min: 78 tokens</li><li>mean: 89.39 tokens</li><li>max: 96 tokens</li></ul> | <ul><li>min: 64 tokens</li><li>mean: 67.1 tokens</li><li>max: 72 tokens</li></ul> | <ul><li>min: 0.06</li><li>mean: 0.61</li><li>max: 0.99</li></ul> |
- Samples:
  | sentence_0 | sentence_1 | label |
  |:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|:------------------|
  | <code>AI Engineer with 4 years of professional experience. Skilled in LLMs, LangChain, PyTorch, Transformers, Python, RAG. Worked on enterprise applications, collaborated with Agile teams, improved application performance, wrote clean and maintainable code, participated in code reviews, and delivered production-ready solutions. Education: MCA. Certification: AWS Certified Developer. Strong communication, leadership, and analytical skills.</code> | <code>We are hiring a AI Engineer. Responsibilities include designing, developing, testing, and maintaining software systems. Required skills include RAG, LLMs, Python, PyTorch, LangChain. Candidates should be comfortable working in Agile environments, collaborating with cross-functional teams, solving complex problems, and delivering high-quality software.</code> | <code>0.96</code> |
  | <code>AI Engineer with 9 years of professional experience. Skilled in LLMs, LangChain, PyTorch, Transformers, Python, RAG. Worked on enterprise applications, collaborated with Agile teams, improved application performance, wrote clean and maintainable code, participated in code reviews, and delivered production-ready solutions. Education: B.E. Information Technology. Certification: Google Data Analytics. Strong communication, leadership, and analytical skills.</code> | <code>We are hiring a Business Analyst. Responsibilities include designing, developing, testing, and maintaining software systems. Required skills include Power BI, Agile, Excel, Requirements Gathering, SQL. Candidates should be comfortable working in Agile environments, collaborating with cross-functional teams, solving complex problems, and delivering high-quality software.</code> | <code>0.1</code> |
  | <code>Backend Developer with 4 years of professional experience. Skilled in Python, FastAPI, PostgreSQL, Redis, Docker, Git, AWS. Worked on enterprise applications, collaborated with Agile teams, improved application performance, wrote clean and maintainable code, participated in code reviews, and delivered production-ready solutions. Education: B.E. Information Technology. Certification: Google Data Analytics. Strong communication, leadership, and analytical skills.</code> | <code>We are hiring a Backend Developer. Responsibilities include designing, developing, testing, and maintaining software systems. Required skills include Python, Docker, Redis, AWS, Git. Candidates should be comfortable working in Agile environments, collaborating with cross-functional teams, solving complex problems, and delivering high-quality software.</code> | <code>0.86</code> |
- Loss: [<code>CosineSimilarityLoss</code>](https://sbert.net/docs/package_reference/sentence_transformer/losses.html#cosinesimilarityloss) with these parameters:
  ```json
  {
    "loss_fct": "torch.nn.modules.loss.MSELoss",
    "cos_score_transformation": "torch.nn.modules.linear.Identity"
  }
  ```

### Training Hyperparameters

#### Non-Default Hyperparameters

- `per_device_train_batch_size`: 16
- `num_train_epochs`: 10
- `per_device_eval_batch_size`: 16
- `multi_dataset_batch_sampler`: round_robin

#### All Hyperparameters

<details><summary>Click to expand</summary>

- `per_device_train_batch_size`: 16
- `num_train_epochs`: 10
- `max_steps`: -1
- `learning_rate`: 5e-05
- `lr_scheduler_type`: linear
- `lr_scheduler_kwargs`: None
- `warmup_steps`: 0
- `optim`: adamw_torch_fused
- `optim_args`: None
- `weight_decay`: 0.0
- `adam_beta1`: 0.9
- `adam_beta2`: 0.999
- `adam_epsilon`: 1e-08
- `optim_target_modules`: None
- `gradient_accumulation_steps`: 1
- `average_tokens_across_devices`: True
- `max_grad_norm`: 1
- `label_smoothing_factor`: 0.0
- `bf16`: False
- `fp16`: False
- `bf16_full_eval`: False
- `fp16_full_eval`: False
- `tf32`: None
- `gradient_checkpointing`: False
- `gradient_checkpointing_kwargs`: None
- `torch_compile`: False
- `torch_compile_backend`: None
- `torch_compile_mode`: None
- `use_liger_kernel`: False
- `liger_kernel_config`: None
- `use_cache`: False
- `neftune_noise_alpha`: None
- `torch_empty_cache_steps`: None
- `auto_find_batch_size`: False
- `log_on_each_node`: True
- `logging_nan_inf_filter`: True
- `include_num_input_tokens_seen`: no
- `log_level`: passive
- `log_level_replica`: warning
- `disable_tqdm`: False
- `project`: huggingface
- `trackio_space_id`: None
- `trackio_bucket_id`: None
- `trackio_static_space_id`: None
- `per_device_eval_batch_size`: 16
- `prediction_loss_only`: True
- `eval_on_start`: False
- `eval_do_concat_batches`: True
- `eval_use_gather_object`: False
- `eval_accumulation_steps`: None
- `include_for_metrics`: []
- `batch_eval_metrics`: False
- `save_only_model`: False
- `save_on_each_node`: False
- `enable_jit_checkpoint`: False
- `push_to_hub`: False
- `hub_private_repo`: None
- `hub_model_id`: None
- `hub_strategy`: every_save
- `hub_always_push`: False
- `hub_revision`: None
- `load_best_model_at_end`: False
- `ignore_data_skip`: False
- `restore_callback_states_from_checkpoint`: False
- `full_determinism`: False
- `seed`: 42
- `data_seed`: None
- `use_cpu`: False
- `accelerator_config`: {'split_batches': False, 'dispatch_batches': None, 'even_batches': True, 'use_seedable_sampler': True, 'non_blocking': False, 'gradient_accumulation_kwargs': None}
- `parallelism_config`: None
- `dataloader_drop_last`: False
- `dataloader_num_workers`: 0
- `dataloader_pin_memory`: True
- `dataloader_persistent_workers`: False
- `dataloader_prefetch_factor`: None
- `remove_unused_columns`: True
- `label_names`: None
- `train_sampling_strategy`: random
- `length_column_name`: length
- `ddp_find_unused_parameters`: None
- `ddp_bucket_cap_mb`: None
- `ddp_broadcast_buffers`: False
- `ddp_static_graph`: None
- `ddp_backend`: None
- `ddp_timeout`: 1800
- `fsdp`: None
- `fsdp_config`: None
- `deepspeed`: None
- `debug`: []
- `skip_memory_metrics`: True
- `do_predict`: False
- `resume_from_checkpoint`: None
- `warmup_ratio`: None
- `local_rank`: -1
- `prompts`: None
- `batch_sampler`: batch_sampler
- `multi_dataset_batch_sampler`: round_robin
- `router_mapping`: {}
- `learning_rate_mapping`: {}

</details>

### Training Logs

| Epoch | Step | ats-val_spearman_cosine |
| :---: | :--: | :---------------------: |
|  1.0  |  14  |         0.6702          |
|  2.0  |  28  |         0.7176          |
|  3.0  |  42  |         0.7983          |
|  4.0  |  56  |         0.8910          |
|  5.0  |  70  |         0.8971          |
|  6.0  |  84  |         0.8869          |
|  7.0  |  98  |         0.8996          |

### Training Time

- **Training**: 1.3 minutes

### Framework Versions

- Python: 3.12.13
- Sentence Transformers: 5.6.0
- Transformers: 5.13.1
- PyTorch: 2.11.0+cu128
- Accelerate: 1.14.0
- Datasets: 4.0.0
- Tokenizers: 0.22.2

## Citation

### BibTeX

#### Sentence Transformers

```bibtex
@inproceedings{reimers-2019-sentence-bert,
    title = "Sentence-BERT: Sentence Embeddings using Siamese BERT-Networks",
    author = "Reimers, Nils and Gurevych, Iryna",
    booktitle = "Proceedings of the 2019 Conference on Empirical Methods in Natural Language Processing",
    month = "11",
    year = "2019",
    publisher = "Association for Computational Linguistics",
    url = "https://arxiv.org/abs/1908.10084",
}
```

<!--
## Glossary

*Clearly define terms in order to be accessible across audiences.*
-->

<!--
## Model Card Authors

*Lists the people who create the model card, providing recognition and accountability for the detailed work that goes into its construction.*
-->

<!--
## Model Card Contact

*Provides a way for people who have updates to the Model Card, suggestions, or questions, to contact the Model Card authors.*
-->
