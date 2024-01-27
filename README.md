# Large MultiModal Model Hallucination [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

LMM hallucination😵 refers to occasional instances where LMMs generate content that appears plausible but deviates from or conflicts with the provided image. 
LMMs tend to rely more on their own parametric knowledge than on provided visual features, causing them to respond with guesses and generate multimodal hallucinations.

In the MLLM community, we've developed methods for detecting, evaluating, and mitigating hallucinations👍.

---
- [Awesome LMM Hallucination](#large-multiModal-model-hallucination)
     - [Detecting Hallucination](#detecting)
     - [Evaluating Hallucination](#evaluating)
     - [Mitigating Hallucination](#mitigating)

---

## Detecting
1. **FDPO**: Detecting and Preventing Hallucinations in Large Vision Language Models, (Gunjal et al. 2023)
     - [![Static Badge](https://img.shields.io/badge/2308.06394-red?logo=arxiv)](https://arxiv.org/abs/2308.06394)  ![Static Badge](https://img.shields.io/badge/not_release-black?logo=github)
2. **HaELM**: Evaluation and Analysis of Hallucination in Large Vision-Language Models, (Wang et al. 2023a)
   - [![Static Badge](https://img.shields.io/badge/2308.15126-red?logo=arxiv)](https://arxiv.org/abs/2308.15126)   [![](https://img.shields.io/badge/HaELM-black?logo=github)](https://github.com/junyangwang0410/HaELM)
   - An automatic MLLM hallucination detection framework, Train LLM to detect
3. **HallE-Switch**: Rethinking and Controlling Object Existence Hallucinations in Large Vision-Language Models for Detailed Caption, (Zhai et al. 2023)
   - [![Static Badge](https://img.shields.io/badge/2310.01779-red?logo=arxiv)](https://arxiv.org/pdf/2310.01779v1.pdf) [![](https://img.shields.io/badge/HallE_Switch-black?logo=github)](https://github.com/bronyayang/HallE_Switch)

## Evaluating

1. **POPE**: Evaluating Object Hallucination in Large Vision-Language Models, (Li et al. EMNLP 2023)
   - [![Static Badge](https://img.shields.io/badge/2305.10355-red?logo=arxiv)](https://arxiv.org/abs/2305.10355) [![](https://img.shields.io/badge/POPE-black?logo=github)](https://github.com/AoiDragon/POPE)
   - Discriminative Task: Object Existence, 3k * 3 VQA pairs
   - LLM-free
2. **HaELM**: Evaluation and Analysis of Hallucination in Large Vision-Language Models, (Wang et al. 2023a)
   - [![Static Badge](https://img.shields.io/badge/2308.15126-red?logo=arxiv)](https://arxiv.org/abs/2308.15126)   [![](https://img.shields.io/badge/HaELM-black?logo=github)](https://github.com/junyangwang0410/HaELM)
   - Discriminative Task, 1500 VQA pairs
3. **HallusionBench**: An Image-Context Reasoning Benchmark Challenging for GPT-4V(ision), LLaVA-1.5, and Other Multi-modality Model, (Liu et al. 2023)
    - [![Static Badge](https://img.shields.io/badge/2310.14566-red?logo=arxiv)](https://arxiv.org/abs/2310.14566)  [![](https://img.shields.io/badge/HallusionBench-black?logo=github)](https://github.com/tianyi-lab/HallusionBench)
   - Image Reasoning Task, 200 VQA pairs
4. **NOPE**: Negative Object Presence Evaluation (NOPE) to Measure Object Hallucination in Vision-Language Models, (Lovenia et al.)
   - [![Static Badge](https://img.shields.io/badge/2310.05338-red?logo=arxiv)](https://arxiv.org/abs/2310.05338) ![Static Badge](https://img.shields.io/badge/not_release-black?logo=github)
5. **Bingo**: Holistic Analysis of Hallucination in GPT-4V(ision): Bias and Interference Challenges, (Cui et al.)
   - [![Static Badge](https://img.shields.io/badge/2311.03287-red?logo=arxiv)](https://arxiv.org/pdf/2311.03287) [![](https://img.shields.io/badge/Bingo-black?logo=github)](https://github.com/gzcch/Bingo)
6. **FaithScore**: Evaluating Hallucinations in Large Vision-Language Models, (Jing et al.)
   - [![Static Badge](https://img.shields.io/badge/2311.01477-red?logo=arxiv)](https://arxiv.org/pdf/2311.01477)  [![](https://img.shields.io/badge/FaithScore-black?logo=github)](https://github.com/bcdnlp/faithscore)
   - Generative Task: Object Existence, Attribute, Relationship, 180 VQA pairs
   - open-end find-grained evaluation, need other models to help evaluation
7. **AMBER**: An LLM-free Multi-dimensional Benchmark for MLLMs Hallucination Evaluation, (Wang et al.)
    - [![Static Badge](https://img.shields.io/badge/2311.07397-red?logo=arxiv)](https://arxiv.org/pdf/2311.07397)  [![](https://img.shields.io/badge/AMBER-black?logo=github)](https://github.com/junyangwang0410/amber)
    - Discriminative Task: Object Existence, Attribute, Relationship
    - Generative Task: Object Existence
    - LLM-free
8. Behind the Magic, **MERLIM**: Multi-modal Evaluation Benchmark for Large Image-Language Models, (Villa et al.)
    - [![Static Badge](https://img.shields.io/badge/2312.02219-red?logo=arxiv)](https://arxiv.org/abs/2312.02219)  [![](https://img.shields.io/badge/MERLIM--(404_now)-black?logo=github)](https://github.com/ojedaf/MERLIM)


---

## Mitigating

1. **LRV-Instruction**: Mitigating Hallucination in Large Multi-Modal Models via Robust Instruction Tuning, (Liu et al. ICLR2024)
   - [![Static Badge](https://img.shields.io/badge/2306.14565-red?logo=arxiv)](http://arxiv.org/abs/2306.14565)  [![](https://img.shields.io/badge/LRV--Instruction-black?logo=github)](https://github.com/FuxiaoLiu/LRV-Instruction)
   - [dataset] propose an instruction-tuning dataset that includes both positive and negative sample
   - _GAIVE_: evaluation approach which uses GPT-4
2. **LURE**: Analyzing and Mitigating Object Hallucination in Large Vision-Language Models, (Zhou et al. ICLR2024)
   - [![Static Badge](https://img.shields.io/badge/2310.00754-red?logo=arxiv)](https://arxiv.org/pdf/2310.00754) [![](https://img.shields.io/badge/LURE-black?logo=github)](https://github.com/YiyangZhou/LURE) 
   - [post-hoc revision] train a revision model to detect and correct hallucinated objects in the base model’s response. 
3. **HallE-Switch**: Rethinking and Controlling Object Existence Hallucinations in Large Vision-Language Models for Detailed Caption, (Zhai et al. 2023)
   - [![Static Badge](https://img.shields.io/badge/2310.01779-red?logo=arxiv)](https://arxiv.org/pdf/2310.01779)  [![](https://img.shields.io/badge/HallE_Switch-black?logo=github)](https://github.com/bronyayang/HallE_Switch)
   - _CCEval_, a GPT-4 assisted evaluation method tailored for detailed captioning
4. **Woodpecker**: Hallucination Correction for Multimodal Large Language Models, (Yin et al.)
   - [![Static Badge](https://img.shields.io/badge/2310.16045-red?logo=arxiv)](https://arxiv.org/abs/2310.16045) [![](https://img.shields.io/badge/Woodpecker-black?logo=github)](https://github.com/BradyFU/Woodpecker)  [![Static Badge](https://img.shields.io/badge/demo-yellow)](https://f252626b321420bfb1.gradio.live/)
   - [revision] post-hoc correction
   - need other pre-trained visual models
5. **LLaVA-RLHF**: Aligning Large Multimodal Models with Factually Augmented RLHF, (Sun et al.)
   - [![Static Badge](https://img.shields.io/badge/2309.14525-red?logo=arxiv)](https://arxiv.org/abs/2309.14525) [![](https://img.shields.io/badge/LLaVA--RLHF-black?logo=github)](https://github.com/llava-rlhf/LLaVA-RLHF)
   - [RLHF-PPO] the first LMM trained with RLHF
   - propose benchmark: **MMHal-Bench**
6. **Volcano**: Mitigating Multimodal Hallucination through Self-Feedback Guided Revision, (Lee et al.)
   - [![Static Badge](https://img.shields.io/badge/2311.07362-red?logo=arxiv)](https://arxiv.org/abs/2311.07362) [![](https://img.shields.io/badge/Volcano-black?logo=github)](https://github.com/kaistAI/Volcano)
   - self-feedback, according to self-generate natural language feedback to self-revise response
7. **HalluciDoctor**: Mitigating Hallucinatory Toxicity in Visual Instruction Data， (Yu et al.)
   - [![Static Badge](https://img.shields.io/badge/2311.13614-red?logo=arxiv)](https://arxiv.org/abs/2311.13614) [![](https://img.shields.io/badge/HalluciDoctor-black?logo=github)](https://github.com/Yuqifan1117/HalluciDoctor)
8. **VCD**: Mitigating Object Hallucinations in Large Vision-Language Models through Visual Contrastive Decoding, (Leng et al.)
   - [![Static Badge](https://img.shields.io/badge/2311.16922-red?logo=arxiv)](https://arxiv.org/abs/2311.16922) [![](https://img.shields.io/badge/VCD-black?logo=github)](https://github.com/DAMO-NLP-SG/VCD)
   - train-free
9. **HA-DPO**: Beyond Hallucinations: Enhancing LVLMs through Hallucination-Aware Direct Preference Optimization
   - [![Static Badge](https://img.shields.io/badge/2311.16839-red?logo=arxiv)](https://arxiv.org/abs/2311.16839) ![Static Badge](https://img.shields.io/badge/not_release-black?logo=github)
10. Mitigating Hallucination in Visual Language Models with Visual Supervision, (Chen et al.)
    - [![Static Badge](https://img.shields.io/badge/2311.16479-red?logo=arxiv)](https://arxiv.org/abs/2311.16479) ![Static Badge](https://img.shields.io/badge/not_release-black?logo=github)
    - construct a fine-grained vision instruction dataset, **RAI-30k**. It contains multi-modal conversations focusing on specific vision relations in an image.
    - propose a new benchmark: **RAHBench**
    - incorporating SAM in the vision instruction tuning process'
11. **OPERA**: Alleviating Hallucination in Multi-Modal Large Language Models via Over-Trust Penalty and Retrospection-Allocation, (Huang et al.)
    - [![Static Badge](https://img.shields.io/badge/2311.17911-red?logo=arxiv)](https://arxiv.org/abs/2311.17911) [![](https://img.shields.io/badge/OPERA-black?logo=github)](https://github.com/shikiw/OPERA)
12. **FOHE**: Mitigating Fine-Grained Hallucination by Fine-Tuning Large Vision-Language Models with Caption Rewrites, (Wang et al.)
    - [![Static Badge](https://img.shields.io/badge/2312.01701-red?logo=arxiv)](https://arxiv.org/abs/2312.01701) [![](https://img.shields.io/badge/FOHE-black?logo=github)](https://github.com/Anonymousanoy/FOHE)
    - use ChatGPT to post-hoc correction
13. **RLHF-V**: Towards Trustworthy MLLMs via Behavior Alignment from Fine-grained Correctional Human Feedback
    - [![Static Badge](https://img.shields.io/badge/2312.00849-red?logo=arxiv)](https://arxiv.org/abs/2312.00849) [![](https://img.shields.io/badge/RLHF--V-black?logo=github)](https://github.com/RLHF-V/RLHF-V)
    - [RLHF-DPO] 1.4K preference data, natural language feedback
14. **MOCHa**: Multi-Objective Reinforcement Mitigating Caption Hallucinations, (Ben-Kish et al.)
    - [![Static Badge](https://img.shields.io/badge/2312.03631-red?logo=arxiv)](https://arxiv.org/abs/2312.03631) [![](https://img.shields.io/badge/Mocha-black?logo=github)](https://github.com/assafbk/mocha_code)
    - [RLHF]
15. **HACL**: Hallucination Augmented Contrastive Learning for Multimodal Large Language Model, (Jiang et al.)
    - [![Static Badge](https://img.shields.io/badge/2312.06968-red?logo=arxiv)](https://arxiv.org/abs/2312.06968) ![Static Badge](https://img.shields.io/badge/not_release-black?logo=github)
16. **Silkie**: Preference Distillation for Large Visual Language Models, (Li et al.)
    - [![Static Badge](https://img.shields.io/badge/2312.10665-red?logo=arxiv)](https://arxiv.org/abs/2312.10665) [![](https://img.shields.io/badge/Silkie-black?logo=github)](https://github.com/vlf-silkie/VLFeedback)
17. **MMCot**: Multimodal Chain-of-Thought Reasoning in Language Models, (Zhang et al.)
     - [![Static Badge](https://img.shields.io/badge/2302.00923-red?logo=arxiv)](https://arxiv.org/abs/2302.00923) [![](https://img.shields.io/badge/mm--cot-black?logo=github)](https://github.com/amazon-science/mm-cot)
     - [CoT]
18. **KAM-CoT**: Knowledge Augmented Multimodal Chain-of-Thoughts Reasoning, (Mondal et al. AAAI 2024)
    - [![Static Badge](https://img.shields.io/badge/2401.12863-red?logo=arxiv)](https://arxiv.org/abs/2401.12863) ![Static Badge](https://img.shields.io/badge/not_release-black?logo=github)
    - [CoT]







