# Luu Gia Huy

**Undergraduate student in Computer Science at the University of Information Technology (UIT), Vietnam National University Ho Chi Minh City** · publishes as *Huy Gia Luu*
Ho Chi Minh City, Vietnam

[Website](https://luvlamnhiu123-ui.github.io/) · [Email](mailto:23520618@gm.uit.edu.vn)

## About

I am a Computer Science student at UIT with a passion for scientific research, especially in artificial intelligence and natural language processing. I have carried out a series of studies on natural language processing tasks, agentic AI, and large language models, in both Vietnamese and English.

Going forward, I will keep doing research that improves performance on natural language processing tasks, especially in multilingual and low-resource settings; that makes LLM agents dependable when they work together; and that makes the evaluation of these systems worthy of trust.

## Research Interests

**Text classification**
- **Overview:** Improving the performance of LLMs on text classification tasks in Vietnamese and English, including implicit sentiment analysis, aspect-based sentiment analysis, and named entity recognition. These tasks are hard because the surface wording often does not match the intended meaning or label, and labelled data and annotation guidelines are limited in low-resource settings.
- **My work and results:** Built the first Vietnamese benchmark for implicit sentiment and developed prompting, fine-tuning, and model-architecture methods that improve how models handle implicit cues. Showed that framing opinion extraction as code generation improves results on Vietnamese benchmarks, measured how far LLM-generated annotations can stand in for human labels, and established the first standardized benchmark of LLMs for Vietnamese named entity recognition.

**Agentic AI**
- **Overview:** Studying how LLM agents delegate, coordinate, and reproduce scientific work, and how to grade them. This covers the protocols between agents and the benchmarks and rubrics that measure what they do.
- **My work and results:** Showed that strict delegation orders make capable agents inherit errors from flawed plans, and that a lightweight verification step catches most faulty plans. Contributed to benchmarks and rubrics for evaluating agents that reproduce research papers.

**LLM evaluation**
- **Overview:** Examining whether the way we evaluate LLMs, especially with LLM judges in multilingual settings, deserves the trust placed in it. The question is what common safeguards actually establish about the independence and validity of a judgment.
- **My work and results:** Showed through audits of published practice that judges from different vendors do not guarantee independent evaluation. Proposed a framework that reports independence and grounding separately.

## Publications

**Published and accepted**

1. Hanhua Hong, Yizhi Li, Jiaoyan Chen, **Huy Gia Luu**, Sophia Ananiadou, Jung-jae Kim, and Chenghua Lin. 2026. Can LLMs Write Reliable Rubrics? A Meta-Evaluation for Experiment Reproduction. In *Findings of the Association for Computational Linguistics: AACL 2026*. To appear.
2. Hanhua Hong, Yizhi Li, **Huy Gia Luu**, Jian Yang, Ming Zhou, and Chenghua Lin. 2026. Overview of the NLPCC 2026 Shared Task 11: Agent-Based Experiment Reproduction from Scientific Papers. In *Proceedings of NLPCC 2026, Shared Tasks*. To appear.
3. **Huy Gia Luu**, Hoang Nguyen Minh, Vu Duc Nguyen, and Dang Van Thin. 2026. Marker-Aligned Subspace Separation for Implicit Sentiment Analysis. In *Proceedings of the International Symposium on Information and Communication Technology (SOICT 2026)*. To appear.
4. **Huy Gia Luu**\* et al. 2026. A Benchmark Evaluation of Named Entity Recognition with Large Language Models in Vietnamese. In *Proceedings of ATAC 2026*. To appear. \*Co-first author. [[PDF]](atac2026-vietnamese-ner-benchmark.pdf)
5. Hoang Nguyen Minh\*, **Huy Gia Luu**\*, and Dang Van Thin. 2026. Investigating the Role of Reasoning Augmentation in Parameter-Efficient Fine-Tuning for Implicit Sentiment Analysis. In *Proceedings of ATAC 2026*. To appear. \*Equal contribution. [[PDF]](atac2026-isa-reasoning-peft.pdf) [[Code]](https://github.com/UIT23520530/atac2026)
6. **Huy Gia Luu** and Dang Van Thin. 2025. Exploring the Power of Large Language Models for Vietnamese Implicit Sentiment Analysis. In *Proceedings of the 18th International Natural Language Generation Conference*, pages 202–214, Hanoi, Vietnam. Association for Computational Linguistics. [[ACL Anthology]](https://aclanthology.org/2025.inlg-main.14/) [[Code]](https://github.com/HuyGiaLuu/ViISA)

**Under review**

7. **Huy Gia Luu**, Hoang Nguyen Minh, and Dang Van Thin. Self-Reflective Contextual Reasoning: A Single-Turn Prompting Strategy for Implicit Sentiment Analysis. Under review at *Vietnam Journal of Computer Science*.
8. **Huy Gia Luu** et al. Structured Code-Style Instruction Tuning for Vietnamese Aspect-Based Sentiment Analysis. Under review at a Springer journal.
9. **Huy Gia Luu** et al. Follow Precisely: Plan Adherence Directives and Flawed-Plan Propagation in Multi-Agent Delegation. Under review at *AAMAS 2027*.
10. **Huy Gia Luu** et al. Different Vendors Do Not Imply Independence: Provenance-Aware Multilingual LLM Evaluation. Under review at *ACL Rolling Review* (October 2026 cycle).

**In preparation**

11. **Huy Gia Luu** et al. Retrieval-Augmented Multi-Agent System for Aspect Category Sentiment Analysis on Vietnamese Reviews. In preparation.

My specific contribution to each study is described on my research homepage: [luvlamnhiu123-ui.github.io](https://luvlamnhiu123-ui.github.io/).

## Education

**University of Information Technology (UIT), Vietnam National University Ho Chi Minh City**
Undergraduate program in Computer Science · 2023 – 2027 (expected)

- **Advisor:** [Dr. Dang Van Thin](https://scholar.google.com/citations?user=5WKo838AAAAJ&hl=en)
- **Graduation thesis:** A Study of Advanced Techniques for Improving Sentiment Analysis Performance with Language Models
  *(Vietnamese title: Nghiên cứu các kỹ thuật nâng cao cải thiện hiệu suất bài toán phân tích cảm xúc với mô hình ngôn ngữ)*

## Research Experience

**Research Assistant, UIT.NLP Research Group**, University of Information Technology, VNU-HCM · 2024 – present
Led by [Assoc. Prof. Ngan Luu-Thuy Nguyen](https://scholar.google.com/citations?user=VoTCbXYAAAAJ&hl=en), under the supervision of [Dr. Dang Van Thin](https://scholar.google.com/citations?user=5WKo838AAAAJ&hl=en).
- Take part in research on improving the performance of sentiment analysis in both Vietnamese and English.

**Research Intern (remote)**, Lab of [Prof. Chenghua Lin](https://chenghua-lin.github.io/) · 2026 – present
- Contribute to research on agentic AI systems that support the reproduction of scientific research.

## Skills

- **Programming and tools:** Python, PyTorch, Git and GitHub, LaTeX, Google Colab
- **NLP and LLM frameworks:** Hugging Face Transformers, PEFT (LoRA and QLoRA), bitsandbytes, seqeval
- **LLM APIs and models:** OpenAI and Azure OpenAI, Google Gemini, open-weight models such as Gemma, LLaMA, Qwen, and DeepSeek
- **Agent frameworks:** LangChain, LangGraph
- **Agents and retrieval:** retrieval-augmented generation with Chroma, multi-agent annotation and debate pipelines, delegation and verification protocols
- **Research methods:** prompt engineering, instruction tuning, benchmark construction, human annotation, rubric-based and LLM-as-a-judge evaluation, bootstrap intervals and McNemar tests
- **Languages:** Vietnamese, English

## Academic Service

- **Reviewer**, NLPCC 2026 Shared Task

## Contact

- **Email:** 23520618@gm.uit.edu.vn
- **Website:** https://luvlamnhiu123-ui.github.io/

*Last updated October 2026.*
