# Intent-Aware Self-Correction for Mitigating Social Biases in LLMs
## 📣 Updates
- Coming soon: arXiv preprint with additional experiments and analysis results
- Mar 10, 2025: We will present in Japan's the 31st Annual Meeting of the Association for Natural Language Processing ([ANLP2025](https://www.anlp.jp/nlp2025/))
  - [Paper](https://www.anlp.jp/proceedings/annual_meeting/2025/pdf_dir/Q2-22.pdf) (Titled as: Mitigating Social Bias in Large Language Models by Self-Correction)

## 📖 Overview
### Motivation
Self-Correction based on feedback improves the output quality of Large Language Models (LLMs). Moreover, as Self-Correction functions like the slow and conscious System-2 thinking from cognitive psychology's perspective, it can potentially reduce LLMs' social biases. LLMs are sensitive to contextual ambiguities and inconsistencies; therefore, explicitly communicating their intentions during interactions when applying Self-Correction for debiasing is crucial.

### What we do
In this study, we demonstrate that clarifying intentions is essential for effectively reducing biases in LLMs through Self-Correction. We divide the components needed for Self-Correction into three parts: instruction, response, and feedback, and clarify intentions at each component. We incorporate an explicit debiasing prompt to convey the intention of bias mitigation from the instruction for response generation. In the response, we use Chain-of-Thought (CoT) to clarify the reasoning process. In the feedback, we define evaluation aspects necessary for debiasing and propose clear feedback through multi-aspect critiques and scoring. Through experiments, we demonstrate that self-correcting CoT responses obtained from a debiasing prompt based on multi-aspect feedback can reduce biased responses more robustly and consistently than the baselines. We also find the variation in debiasing efficacy when using models with different bias levels or separating models for response and feedback generation. 

<img width="613" alt="summary-2" src="https://github.com/user-attachments/assets/f5b519d5-f993-4c4d-a1c4-0b604e202ca9" />
