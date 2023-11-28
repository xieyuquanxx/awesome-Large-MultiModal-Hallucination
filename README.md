# Large MultiModal Model Hallucination😵

LMM hallucination refers to occasional instances where LMMs generate content that appears plausible but deviates from or conflicts with the provided image. 
LMMs tend to rely more on their own parametric knowledge than on provided visual features, causing them to respond with guesses and generate multimodal hallucinations.

In the MLLM community, we've developed methods for detecting, evaluating, and mitigating hallucinations👍.

---

## Detecting
1. **FDPO**: Detecting and Preventing Hallucinations in Large Vision Language Models, (Gunjal et al. 2023)
     - [![Static Badge](https://img.shields.io/badge/2308.06394-red?logo=arxiv)](https://arxiv.org/abs/2308.06394)  ![Static Badge](https://img.shields.io/badge/not_release-black?logo=github)
2. **HaELM** : Evaluation and Analysis of Hallucination in Large Vision-Language Models, (Wang et al. 2023a)
   - [![Static Badge](https://img.shields.io/badge/2308.15126-red?logo=arxiv)](https://arxiv.org/abs/2308.15126)   [![](https://img.shields.io/badge/HaELM-black?logo=github)](https://github.com/junyangwang0410/HaELM)
   - An automatic MLLM hallucination detection framework, Train LLM to detect
3. **HallE-Switch** : Rethinking and Controlling Object Existence Hallucinations in Large Vision-Language Models for Detailed Caption, (Zhai et al. 2023)
   - [![Static Badge](https://img.shields.io/badge/2310.01779-red?logo=arxiv)](https://arxiv.org/pdf/2310.01779v1.pdf) ![Static Badge](https://img.shields.io/badge/not_release-black?logo=github)

## Evaluating

1. **POPE**: Evaluating Object Hallucination in Large Vision-Language Models, (Li et al. EMNLP 2023)
   - [![Static Badge](https://img.shields.io/badge/2305.10355-red?logo=arxiv)](https://arxiv.org/abs/2305.10355) [![](https://img.shields.io/badge/POPE-black?logo=github)](https://github.com/AoiDragon/POPE)
   - Discriminative Task: Object Existence, 3k * 3 VQA pairs
   - LLM-free
2. **HaELM** : Evaluation and Analysis of Hallucination in Large Vision-Language Models, (Wang et al. 2023a)
   - [![Static Badge](https://img.shields.io/badge/2308.15126-red?logo=arxiv)](https://arxiv.org/abs/2308.15126)   [![](https://img.shields.io/badge/HaELM-black?logo=github)](https://github.com/junyangwang0410/HaELM)
   - Discriminative Task, 1500 VQA pairs
3. **HallusionBench** : An Image-Context Reasoning Benchmark Challenging for GPT-4V(ision), LLaVA-1.5, and Other Multi-modality Model, (Liu et al. 2023)
    - [![Static Badge](https://img.shields.io/badge/2310.14566-red?logo=arxiv)](https://arxiv.org/abs/2310.14566)  [![](https://img.shields.io/badge/HallusionBench-black?logo=github)](https://github.com/tianyi-lab/HallusionBench)
   - Image Reasoning Task, 200 VQA pairs
4. **HallE-Switch** : Rethinking and Controlling Object Existence Hallucinations in Large Vision-Language Models for Detailed Caption, (Zhai et al. 2023)
   - [![Static Badge](https://img.shields.io/badge/2310.01779-red?logo=arxiv)](https://arxiv.org/pdf/2310.01779) ![Static Badge](https://img.shields.io/badge/not_release-black?logo=github)
   - Discriminative Task: Object Existence
5. **NOPE**: Negative Object Presence Evaluation (NOPE) to Measure Object Hallucination in Vision-Language Models, (Lovenia et al.)
   - [![Static Badge](https://img.shields.io/badge/2310.05338-red?logo=arxiv)](https://arxiv.org/abs/2310.05338) ![Static Badge](https://img.shields.io/badge/not_release-black?logo=github)
6. **Bingo** : Holistic Analysis of Hallucination in GPT-4V(ision): Bias and Interference Challenges, (Cui et al.)
   - [![Static Badge](https://img.shields.io/badge/2311.03287-red?logo=arxiv)](https://arxiv.org/pdf/2311.03287) [![](https://img.shields.io/badge/Bingo-black?logo=github)](https://github.com/gzcch/Bingo)
7. **FaithScore** : Evaluating Hallucinations in Large Vision-Language Models, (Jing et al.)
   - [![Static Badge](https://img.shields.io/badge/2311.01477-red?logo=arxiv)](https://arxiv.org/pdf/2311.01477)  [![](https://img.shields.io/badge/FaithScore-black?logo=github)](https://github.com/bcdnlp/faithscore)
   - Generative Task: Object Existence, Attribute, Relationship, 180 VQA pairs
   - open-end find-grained evaluation, need other models to help evaluation
8. **AMBER** : An LLM-free Multi-dimensional Benchmark for MLLMs Hallucination Evaluation, (Wang et al.)
    - [![Static Badge](https://img.shields.io/badge/2311.07397-red?logo=arxiv)](https://arxiv.org/pdf/2311.07397)  [![](https://img.shields.io/badge/AMBER-black?logo=github)](https://github.com/junyangwang0410/amber)
    - Discriminative Task: Object Existence, Attribute, Relationship
    - Generative Task: Object Existence
    - LLM-free

---

## Mitigating

1. **LRV-Instruction** : Mitigating Hallucination in Large Multi-Modal Models via Robust Instruction Tuning, (Liu et al.)
   - [![Static Badge](https://img.shields.io/badge/2306.14565-red?logo=arxiv)](http://arxiv.org/abs/2306.14565)  [![](https://img.shields.io/badge/LRV--Instruction-black?logo=github)](https://github.com/FuxiaoLiu/LRV-Instruction)
   - [dataset] propose an instruction-tuning dataset which include both postive and negative sample
   - GAIVE: evaluation approch which use GPT-4
2. **LURE** : Analyzing and Mitigating Object Hallucination in Large Vision-Language Models, (Zhou et al. 2023b)
   - [![Static Badge](https://img.shields.io/badge/2310.00754-red?logo=arxiv)](https://arxiv.org/pdf/2310.00754) [![](https://img.shields.io/badge/LURE-black?logo=github)](https://github.com/YiyangZhou/LURE)
   -  [revision] train a revision model to detect and correct hallucinated objects in base model’s response. 
3. **HallE-Switch** : Rethinking and Controlling Object Existence Hallucinations in Large Vision-Language Models for Detailed Caption, (Zhai et al. 2023)
   - [![Static Badge](https://img.shields.io/badge/2310.01779-red?logo=arxiv)](https://arxiv.org/pdf/2310.01779)  ![Static Badge](https://img.shields.io/badge/not_release-black?logo=github)
4. **Woodpecker** : Hallucination Correction for Multimodal Large Language Models, (Yin et al.)
   - [![Static Badge](https://img.shields.io/badge/2310.16045-red?logo=arxiv)](https://arxiv.org/abs/2310.16045) [![](https://img.shields.io/badge/Woodpecker-black?logo=github)](https://github.com/BradyFU/Woodpecker)
   - [revision] post-hoc correction
   - need other pretrained visual models
5. **LLaVA-RLHF** : Aligning Large Multimodal Models with Factually Augmented RLHF, (Sun et al.)
   - [![Static Badge](https://img.shields.io/badge/2309.14525-red?logo=arxiv)](https://arxiv.org/abs/2309.14525) [![](https://img.shields.io/badge/LLaVA--RLHF-black?logo=github)](https://github.com/llava-rlhf/LLaVA-RLHF)
   - [RLHF] the first LMM trained with RLHF
   - propose benchmark: MMHal-Bench
6. **Volcano** : Mitigating Multimodal Hallucination through Self-Feedback Guided Revision, (Lee et al.)
   - [![Static Badge](https://img.shields.io/badge/2311.07362-red?logo=arxiv)](https://arxiv.org/abs/2311.07362) [![](https://img.shields.io/badge/Volcano-black?logo=github)](https://github.com/kaistAI/Volcano)
   - self-feedback, according to self-generate natural language feedback to self-revise response
7. **HalluciDoctor**: Mitigating Hallucinatory Toxicity in Visual Instruction Data， (Yu et al.)
   - [![Static Badge](https://img.shields.io/badge/2311.07362-red?logo=arxiv)](https://arxiv.org/abs/2311.13614) [![](https://img.shields.io/badge/HalluciDoctor-black?logo=github)](https://github.com/Yuqifan1117/HalluciDoctor)
