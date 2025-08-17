# hse-nes-bachelor-thesis-llm-economics

# HSE & NES Bachelor's Thesis: Evaluating Large Language Models as Economic Decision-Makers

**Year:** 2025  
**Grade:** 8/10  
**Author:** Kozachenko Maksim

## Abstract (Русский)
В данной работе анализируются способности моделей ChatGPT решать задачи, требующие компетенций, необходимых для принятия экономических решений. Исследование основано на серии оригинальных экспериментов по оценке устойчивости к когнитивным искажениям, управлению рисками, справедливости, креативности, а также экономической грамотности. Оценивается поведение моделей в различных ситуациях, с особым вниманием к сравнению моделей с наличием и без наличия способности к рассуждению: GPT-4o и o1. Анализ выявляет как сильные стороны языковых моделей, в частности высокий уровень экономической грамотности у o1, так и их ограничения, включая подверженность когнитивным искажениям, шаблонность в креативных задачах и недостаточную адаптацию к контексту в некоторых ситуациях. Работа вносит вклад в понимание возможностей и границ применения больших языковых моделей в сложных управленческих задачах и предлагает направления для дальнейших исследований и доработок моделей.

## Abstract (English)
This study analyzes the capabilities of ChatGPT models in solving tasks that require competencies essential for economic decision-making. The research is based on a series of original experiments evaluating resistance to cognitive biases, risk management, fairness, creativity, and economic literacy. The behavior of the models is assessed across various scenarios, with specific focus on juxtaposing models with and without reasoning capabilities: GPT-4o and o1. The analysis identifies both the strengths of language models, particularly the high level of economic literacy demonstrated by o1, and their limitations, including susceptibility to cognitive biases, repetitive patterns in creative tasks, and insufficient contextual adaptation in certain situations. The study contributes to the understanding of the potential and limitations of large language models in complex managerial tasks and suggests directions for further research and model refinement.

## Methodology

We focused on five key competencies essential for economic decision-making:

1. **Cognitive Bias Resistance** – ability to recognize and mitigate biases.  
2. **Fairness** – capacity to make impartial and ethically sound decisions.  
3. **Creativity** – flexibility and originality in problem-solving.  
4. **Economic Literacy** – understanding of economic concepts and reasoning.  
5. **Risk Management Skills** – ability to assess and respond to uncertainty.  

Each competency was tested using custom-designed prompts and theoretical scenarios, submitted to **GPT-4o** and **o1**. For each experiment, prompts were repeated in new threads to avoid memory effects, and results were recorded across multiple iterations.

---

## Key Results

- **Cognitive Bias Resistance:** Both models showed vulnerability; GPT-4o tended toward heuristic/impulsive answers, while o1 sometimes resisted biases better thanks to step-by-step reasoning.  
- **Fairness:** Both applied rigid equality-based rules, with limited contextual flexibility.  
- **Creativity:** Outputs lacked originality; content was repetitive and easily distinguishable from human work.  
- **Economic Literacy:** Both performed well, with o1 more accurate overall; occasional shallow understanding or factual errors persisted.  
- **Risk Management:** GPT-4o leaned toward excessive caution, while o1 often ignored risk and maximized expected value. Neither displayed human-like patterns such as decreasing absolute risk aversion (DARA).  

**General Insight:**  
Models partially align with human expectations in economic decision-making but show limitations in creativity, nuanced judgment, and bias resistance.  
o1’s reasoning ability made it more “System-2-like” (deliberative), while GPT-4o behaved more “System-1-like” (fast, heuristic-driven).  
LLMs are not yet capable of replicating the complex reasoning required for high-stakes economic decisions without human supervision.

---
