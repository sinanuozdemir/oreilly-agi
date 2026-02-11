![oreilly-logo](images/oreilly.png)

# Artificial General Intelligence (AGI) Demystified


This repository contains code for live session and video for the [O'Reilly Course on Artificial General Intelligence (AGI) Demystified](https://www.oreilly.com/live-events/artificial-general-intelligence-agi-demystified/0642572174033)

This course offers an exploration of the current approaches toward Artificial General Intelligence (AGI), focusing on state-of-the-art reasoning models and agent architectures. Participants will learn about the evolution of AGI research, understand key benchmarks used to measure progress, and gain practical knowledge in working with advanced models like Claude 3.7, DeepSeek-R1, and OpenAI's o3. Through hands-on exercises and case studies, attendees will develop the skills needed to evaluate these models' capabilities, understand their limitations, and apply them effectively to complex tasks.

## Notebooks

- **Using Reasoning Models**

	- [An Introduction to Reasoning Models](notebooks/intro_to_reasoning_models.ipynb) - Using 6 reasoning models across 5 providers
	
	- [Short Term Memory with OpenAI Agents](notebooks/OpenAI%20Agents.ipynb) - OpenAI Agents doesn't implement short term memory by default, this code will add the concept to the agent

	- [Computer Use with reasoning models](notebooks/computer_use_reasoning.ipynb) - Letting a reasoning model control our laptop (caution advised when running this code)

	
- **Benchmarking**

	- [Benchmarking Reasoning Models](notebooks/benchmarking_reasoning_models.ipynb) - Running questions from [Humanity's Last Exam](https://huggingface.co/datasets/cais/hle/discussions) on reasoning models

	- [Benchmarking Llama 3.2 Instruct on MMLU and Embedders on MTEB](https://colab.research.google.com/drive/1zDCqXc7vHoZilHVe3y2lYyTmSUSe6bh3?usp=sharingb) 
	
	
		- [Follow-up Evaluating Llama 3.2 non-instruct on MMLU](https://colab.research.google.com/drive/1aMy19Ikyody9CGyn42K3E_DQwLScL0Ek?usp=sharing)

		- [Evaluating Llama 3.1 vs Mistral on Truthful Q/A](https://github.com/sinanuozdemir/quick-start-guide-to-llms/blob/main/notebooks/12_llm_gen_eval.ipynb)



- **Case Studies**

	- [GRPO + Qwen](https://colab.research.google.com/drive/1Cws1IL_T_0_cP0-cHxFA0FEsXYdiAN_8?usp=sharing): Using Reinforcement Learning to train a reasoning model. 

	- [Prompt Engineering Deepseek R1](https://github.com/sinanuozdemir/quick-start-guide-to-llms/blob/main/notebooks/06_adv_prompt_engineering%20-%20DEEPSEEK.ipynb) - Using fewshot learning, vector databases, and even chain of thought prompting to make reasoning models even better

	**Probing**

	- [Probing Chess Playing LLMs](https://colab.research.google.com/drive/114turFLNxLJXiIseDWl1BDJmont0VD8h?usp=sharing)


	- There are over a dozen notebooks for the birth year/death year probing example so I will only share a few key ones here:
	  - [Llama-3 8B Instruct with prompt "Who is {NAME}"](https://colab.research.google.com/drive/1e1d9fATVjVun-_tPj4vS_DSTGaIfxs01?usp=sharing)
	  - [BERT-large-cased no prompt](https://colab.research.google.com/drive/1cizgoh1J6Y-DHBrOkNTFo9Y1CypjwuQM?usp=sharing)
	  - [Mistral-7B-Instruct-v0.3 with prompt "Who is {NAME}"](https://colab.research.google.com/drive/1VL3betxqVZ_H3_8XmLbjE0hEjaoy-HPV?usp=sharing)


## Instructor

**Sinan Ozdemir** is a former lecturer of Data Science at Johns Hopkins University and the author of multiple textbooks on data science and machine learning. Additionally, he is the founder of the recently acquired Kylie.ai, an enterprise-grade conversational AI platform with RPA capabilities. He holds a master’s degree in Pure Mathematics from Johns Hopkins University and is based in San Francisco, CA.

