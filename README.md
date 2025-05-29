# Evaluating-the-Openness-of-Impactful-AI-Models-with-a-Focus-on-LLMs
It includes the first paper I wrote in my undergraduate years. 
This paper is indexed in KCI (Korea Citation Index).

Based on your paper about evaluating the openness of AI models, here's a comprehensive README structure for your GitHub repository:

# Evaluating the Openness of Impactful AI Models with a Focus on LLMs

## Overview

This repository contains the research framework and evaluation results for assessing the openness of influential AI models, with a particular focus on Large Language Models (LLMs). Our study proposes a comprehensive framework to quantify AI model openness and evaluates high-impact models including those developed by Korean companies.

## Key Contributions

1. **Comprehensive Openness Evaluation Framework**: We propose a multi-dimensional framework that evaluates AI model openness across four key areas:
   - Model Basic Openness
   - Accessibility and Reproducibility
   - Training Methodology Openness
   - Data Openness

2. **Extensive Model Evaluation**: Analysis of influential open-source and closed-source AI models, including Korean domestic models

3. **Performance-Openness Correlation Analysis**: Investigation of the relationship between model openness and performance across different benchmarks (GPQA, MMLU, Elo)

## Key Findings

- **Llama series**, despite being widely perceived as open-source, ranks outside the top 5 in all evaluation criteria
- **Gemma-2 and Gemma-3** consistently outrank Llama models in openness across all evaluation methods
- **Korean models** show relatively lower openness compared to international counterparts
- **Negative correlation** observed between openness and performance, particularly on high-difficulty benchmarks

## Evaluation Framework

### Model Basic Openness (6 components)
- Weights
- Code 
- License 
- Research papers
- Architecture
- Tokenizer 

### Accessibility and Reproducibility (3 components)
- Hardware
- Software
- API 

### Training Methodology Openness (3 components)
- Pre-training
- Fine-tuning 
- Reinforcement learning

### Data Openness (4 components)
- Pre-training
- Fine-tuning 
- Reinforcement learning
- Data filtering

## Model Rankings

Our evaluation reveals significant gaps between perceived and actual openness levels:

**Top Open Models:**
1. Gemma-2,BloomZ
2. DeepSeek V3
3. Phi-4
4. Gemma-3
5. Qwen2.5

**Notable Findings:**
- Some models labeled as "open-source" rank lower than closed-source models in actual openness
- Korean model Kanana performs best among domestic models
- Significant variation in rankings based on different  weighting schemes

## Performance vs. Openness Analysis

Our correlation analysis across three benchmarks reveals:

- **GPQA**: Strong negative correlation (-0.55) - higher openness associated with lower performance
- **MMLU**: Weak correlation (-0.08) - little relationship between openness and performance  
- **Elo**: Moderate negative correlation (-0.24) - slight negative relationship

## Methodology

Our evaluation methodology incorporates:
- **OSI's Open Source AI Definition (OSAID)** compliance
- **Multi-dimensional scoring** across 16 evaluation criteria
- **Weighted scoring systems** reflecting different openness perspectives
- **Quantitative correlation analysis** with performance benchmarks

## Impact and Applications

This framework can be used for:
- **Policy Development**: Informing AI governance and regulation
- **Research Planning**: Selecting appropriate models for academic research
- **Industry Assessment**: Evaluating vendor claims about model openness
- **Community Building**: Promoting transparency in AI development

## 📚 Citation

If you use this framework or findings in your research, please cite:

*I will notice that as soon as possible*

## Acknowledgments

This research was supported by Sejong University's internal research funding in 2024.

---

**Note**: This research provides a systematic approach to evaluating AI model openness and highlights the importance of transparency in AI development. We encourage the community to adopt and extend this framework for broader AI governance initiatives.