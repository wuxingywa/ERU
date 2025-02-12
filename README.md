# Elastic Robust Unlearning of Specific Knowledge in Large Language Models

This is the code repository for the paper ***Elastic Robust Unlearning of Specific Knowledge in Large Language Models*.**

![1](https://github.com/wuxingywa/ERU/blob/main/ERU.png)

## Abstract

LLM unlearning aims to remove sensitive or harmful information within the model, thus reducing the potential risk of generating unexpected information. However, existing Preference Optimization (PO)-based unlearning methods suffer two limitations. First, their rigid reward setting limits the effect of unlearning. Second, the lack of robustness causes unlearned information to reappear. To remedy these two weaknesses, we present a novel LLM unlearning optimization framework, namely Elastic Robust Unlearning (ERU), to efficiently and robustly remove specific knowledge from LLMs. We design an elastic reward setting instead of the rigid reward setting to enhance the unlearning effect. Meanwhile, we propose latent-space adversarial training into the unlearning process to trigger specific failure patterns for enhancing the robustness of the unlearned model in multiple scenarios. Experimental results show that ERU can improve the unlearning effectiveness significantly while maintaining a high utility performance. Especially, in the WMDP-Bio benchmark, ERU shows a 11.1% improvement over the second-best method, and maintains 83% performance even under 1,000 sample fine-tuned retraining attacks, significantly better than the baseline method.