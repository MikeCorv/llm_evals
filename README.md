# llm_evals
This repository contains a collection of Colab notebooks used to evaluate In Context Learning with various Large Language Models (LLMs) on the [MMLU](https://huggingface.co/datasets/cais/mmlu) benchmark and other various benchmarks. The output from colab is cleared for clarity.

These evaluations leverage the EleutherAI [lm-evaluation-harness](https://github.com/EleutherAI/lm-evaluation-harness) library.

<img width="1362" height="778" alt="image" src="https://github.com/user-attachments/assets/b796e71a-82e9-42fb-bfff-c9af44f0ddfb" />


Notable Achievements:

(MMLU)

Google Gemma-3-4b-it: Demonstrated the highest sensitivity to in-context learning, jumping from a 51% score (0-shot) to 65% (5-shot).

Llama-3.2-3B-Instruct: Showed rapid adaptation, improving from 59% (0-shot) to approximately 65% with just 1-shot.
