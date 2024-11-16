# Models Documentation

This document provides essential information about generative AI models to help you understand their sources, selection criteria, creators, and classifications.

---

## 1. Where Can I Find the Models?
Models can be sourced from the following repositories and platforms:
- **[Hugging Face Model Hub](https://huggingface.co/models)**: A repository of open-source models across various domains.
- **[OpenAI API](https://platform.openai.com/overview)**: For GPT-based models and more.
- **[Cohere](https://cohere.com/)**: Specializing in text generation and embedding models.
- **[EleutherAI](https://www.eleuther.ai/)**: Open-source alternatives to proprietary language models.
- **[Google AI Model Garden](https://ai.google/models)**: Models for advanced use cases like T5 and BERT.
- **[Meta AI](https://ai.facebook.com/)**: Open LLaMA models and other resources.
- **Custom Training Pipelines**: For creating domain-specific models (set up using frameworks like [TensorFlow](https://www.tensorflow.org/) or [PyTorch](https://pytorch.org/)).

---

## 2. Which Model to Select for My Use Case?
### Factors to Consider:
- **Task Type**: Choose based on [classification](https://huggingface.co/docs/transformers/tasks/classification), [generation](https://huggingface.co/docs/transformers/tasks/text_generation), [summarization](https://huggingface.co/docs/transformers/tasks/summarization), or [embedding](https://www.sbert.net/).
- **Domain-Specific Needs**: Opt for fine-tuned models tailored for specific industries (e.g., [BioBERT](https://huggingface.co/monologg/biobert_v1.1_pubmed) for biomedical data).
- **Size vs. Speed**: Larger models perform better but may have slower inference times ([model comparison here](https://huggingface.co/docs/transformers/benchmarks)).
- **Privacy and Licensing**: Evaluate the permissiveness of open-source licenses ([Hugging Face License Guide](https://huggingface.co/docs/transformers/main/en/transformers_hub#license)).
- **Community Support**: Prefer models with active communities and robust documentation ([Hugging Face Forum](https://discuss.huggingface.co/)).

---

## 3. Where Are Models Downloaded?
Models are typically downloaded and stored locally or in cloud storage, based on the tool or library:
- **[Transformers Library](https://huggingface.co/docs/transformers/installation)**: `$HOME/.cache/huggingface/transformers/`
- **[PyTorch Hub](https://pytorch.org/hub/)**: Local `~/.torch/` cache.
- **Custom Directory**: Specify paths using configuration files in deployment tools ([example guide](https://huggingface.co/docs/transformers/main/en/transformers_hub#offline-mode)).
- **Docker Images**: Containerized model deployments store models in `/models` ([Docker Best Practices](https://docs.docker.com/develop/dev-best-practices/)).

---

## 4. Who Creates These Models?
### Major Contributors:
- **Research Labs**: [OpenAI](https://openai.com/), [DeepMind](https://www.deepmind.com/), [Google AI](https://ai.google/), [Meta AI](https://ai.facebook.com/), [Microsoft Research](https://www.microsoft.com/en-us/research/).
- **Open-Source Communities**: [Hugging Face](https://huggingface.co/), [EleutherAI](https://www.eleuther.ai/), [Cohere](https://cohere.com/).
- **Academia**: Universities and research organizations collaborating on cutting-edge AI (e.g., [Stanford NLP](https://nlp.stanford.edu/)).
- **Individual Developers**: Open-source enthusiasts who share their contributions via platforms like [GitHub](https://github.com/).

---

## 5. Classification of All the Models Out There
### Categories of Models:
1. **Generative Models**: [GPT](https://platform.openai.com/docs/models), [LLaMA](https://ai.facebook.com/blog/large-language-model-llama-meta-ai/), [T5](https://huggingface.co/docs/transformers/model_doc/t5).
2. **Classification Models**: [BERT](https://huggingface.co/docs/transformers/model_doc/bert), [RoBERTa](https://huggingface.co/docs/transformers/model_doc/roberta).
3. **Embedding Models**: [Sentence Transformers](https://www.sbert.net/), [Cohere Embed](https://cohere.com/embed).
4. **Vision Models**: [DALL·E](https://openai.com/dall-e), [Stable Diffusion](https://stability.ai/).
5. **Audio Models**: [Whisper](https://openai.com/whisper), [Wav2Vec](https://huggingface.co/models?search=wav2vec).
6. **Multi-Modal Models**: [CLIP](https://github.com/openai/CLIP), [Flamingo](https://www.deepmind.com/publications/flamingo-a-visual-language-model-for-few-shot-learning).

### Additional Classifications:
- **Pre-trained vs. Fine-tuned Models**: Distinguish between generic pre-trained models and specialized fine-tuned variants ([fine-tuning tutorial](https://huggingface.co/docs/transformers/training)).
- **Open-Source vs. Proprietary**: Models with open licensing versus those requiring paid access ([overview of proprietary models](https://platform.openai.com/docs/models)).

---

This documentation will be updated regularly as new models and features emerge in the field of generative AI.
