## Enguard AI

One guardrail for all, all guardrails for one!

We produce guardrails based on

### Why should you use these models?

- Optimised for precision to reduce false positives.
- Extremely fast inference using static embeddings powered by Model2Vec.

### Which guards are available?

Below is an overview of all guardrails, showing the best results for the smallest (-2m), best-performing, and multi-lingual models across all configurations.

| Dataset | Classifies | Collection | Smallest (2m) | Best Performing | Multi-lingual (128m) |
| --- | --- | --- | --- | --- | --- |
| [harmfulness-mix](https://huggingface.co/datasets/nicholasKluge/harmful-text) | prompt-harmfulness | [Collection](https://huggingface.co/collections/enguard/prompt-harmfulness-harmfulness-mix) | [0.9192](https://huggingface.co/enguard/tiny-guard-2m-en-prompt-harmfulness-harmfulness-mix) | [0.9350](https://huggingface.co/enguard/small-guard-32m-en-prompt-harmfulness-harmfulness-mix) | - |
| [intel](https://huggingface.co/datasets/Intel/polite-guard) | response-politeness | [Collection](https://huggingface.co/collections/enguard/response-politeness-intel) | [0.8795](https://huggingface.co/enguard/tiny-guard-2m-en-response-politeness-intel) | [0.8908](https://huggingface.co/enguard/medium-guard-128m-xx-response-politeness-intel) | [0.8908](https://huggingface.co/enguard/medium-guard-128m-xx-response-politeness-intel) |
| [jailbreak-in-the-wild](https://huggingface.co/datasets/TrustAIRLab/in-the-wild-jailbreak-prompts) | prompt-jailbreak | [Collection](https://huggingface.co/collections/enguard/prompt-jailbreak-jailbreak-in-the-wild) | [0.8515](https://huggingface.co/enguard/tiny-guard-2m-en-prompt-jailbreak-jailbreak-in-the-wild) | [0.8905](https://huggingface.co/enguard/medium-guard-128m-xx-prompt-jailbreak-jailbreak-in-the-wild) | [0.8905](https://huggingface.co/enguard/medium-guard-128m-xx-prompt-jailbreak-jailbreak-in-the-wild) |
| [jailbreak-sok](https://huggingface.co/datasets/youbin2014/JailbreakDB) | prompt-jailbreak | [Collection](https://huggingface.co/collections/enguard/prompt-jailbreak-jailbreak-sok) | [0.9762](https://huggingface.co/enguard/tiny-guard-2m-en-prompt-jailbreak-jailbreak-sok) | [0.9810](https://huggingface.co/enguard/medium-guard-128m-xx-prompt-jailbreak-jailbreak-sok) | [0.9810](https://huggingface.co/enguard/medium-guard-128m-xx-prompt-jailbreak-jailbreak-sok) |
| [jigsaw](https://huggingface.co/datasets/google/jigsaw_toxicity_pred) | prompt-toxicity | [Collection](https://huggingface.co/collections/enguard/prompt-toxicity-jigsaw) | [0.8967](https://huggingface.co/enguard/tiny-guard-2m-en-prompt-toxicity-jigsaw) | [0.9067](https://huggingface.co/enguard/small-guard-32m-en-prompt-toxicity-jigsaw) | [0.8986](https://huggingface.co/enguard/medium-guard-128m-xx-prompt-toxicity-jigsaw) |
| [nvidia-aegis](https://huggingface.co/datasets/nvidia/Aegis-AI-Content-Safety-Dataset-2.0) | response-safety | [Collection](https://huggingface.co/collections/enguard/response-safety-nvidia-aegis) | [0.7612](https://huggingface.co/enguard/tiny-guard-2m-en-response-safety-nvidia-aegis) | [0.7760](https://huggingface.co/enguard/tiny-guard-4m-en-response-safety-nvidia-aegis) | [0.7530](https://huggingface.co/enguard/medium-guard-128m-xx-response-safety-nvidia-aegis) |
| [nvidia-aegis](https://huggingface.co/datasets/nvidia/Aegis-AI-Content-Safety-Dataset-2.0) | prompt-safety | [Collection](https://huggingface.co/collections/enguard/prompt-safety-nvidia-aegis) | [0.7957](https://huggingface.co/enguard/tiny-guard-2m-en-prompt-safety-nvidia-aegis) | [0.8131](https://huggingface.co/enguard/tiny-guard-8m-en-prompt-safety-nvidia-aegis) | [0.7929](https://huggingface.co/enguard/medium-guard-128m-xx-prompt-safety-nvidia-aegis) |
| [polyguard](https://huggingface.co/datasets/ToxicityPrompts/PolyGuardMix) | response-safety | [Collection](https://huggingface.co/collections/enguard/response-safety-polyguard) | [0.8635](https://huggingface.co/enguard/tiny-guard-2m-en-response-safety-polyguard) | [0.8808](https://huggingface.co/enguard/small-guard-32m-en-response-safety-polyguard) | [0.8753](https://huggingface.co/enguard/medium-guard-128m-xx-response-safety-polyguard) |
| [polyguard](https://huggingface.co/datasets/ToxicityPrompts/PolyGuardMix) | response-refusal | [Collection](https://huggingface.co/collections/enguard/response-refusal-polyguard) | [0.8952](https://huggingface.co/enguard/tiny-guard-2m-en-response-refusal-polyguard) | [0.9039](https://huggingface.co/enguard/tiny-guard-8m-en-response-refusal-polyguard) | [0.9015](https://huggingface.co/enguard/medium-guard-128m-xx-response-refusal-polyguard) |
| [polyguard](https://huggingface.co/datasets/ToxicityPrompts/PolyGuardMix) | prompt-safety | [Collection](https://huggingface.co/collections/enguard/prompt-safety-polyguard) | - | [0.9331](https://huggingface.co/enguard/small-guard-32m-en-prompt-safety-polyguard) | [0.9255](https://huggingface.co/enguard/medium-guard-128m-xx-prompt-safety-polyguard) |
| [toxic-chat](https://huggingface.co/datasets/lmsys/toxic-chat) | response-jailbreak | [Collection](https://huggingface.co/collections/enguard/response-jailbreak-toxic-chat) | [0.9872](https://huggingface.co/enguard/tiny-guard-2m-en-response-jailbreak-toxic-chat) | [0.9914](https://huggingface.co/enguard/small-guard-32m-en-response-jailbreak-toxic-chat) | - |
| [toxic-chat](https://huggingface.co/datasets/lmsys/toxic-chat) | prompt-toxicity | [Collection](https://huggingface.co/collections/enguard/prompt-toxicity-toxic-chat) | [0.9515](https://huggingface.co/enguard/tiny-guard-2m-en-prompt-toxicity-toxic-chat) | [0.9555](https://huggingface.co/enguard/tiny-guard-8m-en-prompt-toxicity-toxic-chat) | - |
