mBART Fine-Tuning for Lithuanian Summarization

This repository contains code for fine-tuning Facebook's mBART model on Lithuanian text summarization tasks using the Hugging Face transformers library.
Fine-Tuning Workflow

The fine-tuning process follows these general steps:

Model Configuration: The base facebook/mbart-large-cc25 model is used. Training is configured for multilingual summarization with source and target languages set to Lithuanian (lt_LT).

Training: The model is fine-tuned using Hugging Face's Seq2SeqTrainer with appropriate learning rate, batch size, and warm-up strategy for convergence.

Evaluation: During training, ROUGE scores are used to evaluate summarization quality.

Model Saving: The final model is uploaded to Hugging Face for public use.

Pretrained Lithuanian mBART Summarizer

You can try out the fine-tuned model here:
Arnold001/mbart-lt-summary-phase5 on Hugging Face
