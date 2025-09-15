# Python Screening Task 3 – Research Plan

This repository contains my research plan for **Python Screening Task 3: Evaluating Open Source Models for Student Competence Analysis**.  
The goal of this task is to explore open-source AI models and evaluate their potential to analyze Python code, identify misconceptions, generate meaningful prompts, and support deeper student learning.  

## Research Plan

My approach to evaluate open-source models that can be used to analyze student competence in Python. My focus will be on models that don’t just check code correctness but also give meaningful feedback to help students learn better. I’ll start with models trained specifically on code, such as **CodeLlama-7B-Python**, and compare them with educational tools like Open Education Analytics. To test their usefulness, I’ll create a dataset of Python code covering beginner to advanced levels, including intentional mistakes (syntax errors, logic bugs, and common misconceptions like variable scope issues or incorrect loops). Each model will be judged on how well it </br> 
(1) understands Python code structurally and logically, </br> 
(2) generates prompts that push students to think conceptually rather than just fix syntax,</br> 
(3) spots reasoning gaps and misconceptions, and</br> 
(4) provides feedback that encourages deeper learning without simply handing out solutions. 
For validation, I’ll benchmark using datasets like HumanEval-Python and also ask experts to review the generated prompts through the lens of **Bloom’s taxonomy**.

---

## Reasoning  

- **What makes a model suitable for high-level competence analysis?**  
  It should go beyond syntax checking and demonstrate true conceptual understanding of Python, while also being able to identify misconceptions and reasoning gaps.  

- **How would you test whether a model generates meaningful prompts?**  
  I would check prompts against **Bloom’s taxonomy**, ensure they target real misconceptions, and validate them with Python educators for depth and relevance.  

- **What trade-offs might exist between accuracy, interpretability, and cost?**  
  Large models may be highly accurate but expensive and less interpretable. Smaller models are cheaper and easier to use but may miss subtle reasoning errors.  

- **Why did you choose the model you evaluated, and what are its strengths or limitations?**  
  I chose **CodeLlama-7B-Python** because it is Python-focused, open-source, and accessible. Its strengths are domain-specific training and flexibility. Its limitations are less explicit pedagogical alignment and possible inconsistency, which can be mitigated with fine-tuning and evaluation frameworks.  

---

## Setup Instructions  

To view this project:  

1. Clone the repo:  
   ```bash
   git clone https://github.com/Pritam216/python-screening-task3.git
   cd python-screening-task3
   ```
 ---
## References  

- [Code Llama (Meta)](https://huggingface.co/codellama)  
- [HumanEval Dataset (OpenAI)](https://github.com/openai/human-eval)  
- [DeepEval: Evaluation Framework](https://github.com/confident-ai/deepeval)  
- [Bloom’s Taxonomy Overview (Vanderbilt University)](https://cft.vanderbilt.edu/guides-sub-pages/blooms-taxonomy/)  
- [Educational Data Mining Society](https://educationaldatamining.org/)  
- [scikit-learn: Machine Learning in Python](https://scikit-learn.org/stable/)  

 ---
