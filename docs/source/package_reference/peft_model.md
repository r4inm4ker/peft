<!--⚠️ Note that this file is in Markdown but contain specific syntax for our doc-builder (similar to MDX) that may not be
rendered properly in your Markdown viewer.
-->

# Models

[`PeftModel`] is the base model class for specifying the base Transformer model and configuration to apply a PEFT method to. The base `PeftModel` contains methods for loading and saving models from the Hub.

## PeftModel

[[autodoc]] PeftModel
    - all

## PeftModelForSequenceClassification

A `PeftModel` for sequence classification tasks.

[[autodoc]] PeftModelForSequenceClassification
    - all

## PeftModelForTokenClassification

A `PeftModel` for token classification tasks.

[[autodoc]] PeftModelForTokenClassification
    - all

## PeftModelForCausalLM

A `PeftModel` for causal language modeling.

[[autodoc]] PeftModelForCausalLM
    - all

## PeftModelForSeq2SeqLM

A `PeftModel` for sequence-to-sequence language modeling.

[[autodoc]] PeftModelForSeq2SeqLM
    - all

## PeftModelForQuestionAnswering

A `PeftModel` for question answering.

[[autodoc]] PeftModelForQuestionAnswering
    - all

## PeftModelForFeatureExtraction

A `PeftModel` for getting extracting features/embeddings from transformer models.

[[autodoc]] PeftModelForFeatureExtraction
    - all

## Utilities

[[autodoc]] get_peft_model