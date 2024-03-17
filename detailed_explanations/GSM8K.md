# GSM8K benchmark/metric

Dataset provided by OpenAI containing *'8500  high quality linguistically diverse grade school math word problems'*. The dataset was created new from scratch by crowdsourced workers. OpenAI estimates that in the paper *'less than 2
percent of problems contain breaking errors'*.

1. [Problem domain](#Problem-domain)
2. [When to consider this benchmark?](#When-to-consider-this-benchmark?)
3. [Resources](#Resources)

## Problem domain

The problem domain is the mulit-step mathematical reasoning on mathematical problems inside a text corpus. The benchmark poses a challenge to models as they need to identify the correct task to solve, what calculations steps need to be done to solve the task and then apply theses steps to yield a final answer.

The task formulation is in the form of , solving them requires simple Algebra.

Example task:
```
John Doe did 48 commits in June, and then half as many commits in July. How many commits did John altogether in June and July?
``` 

## When to consider this benchmark?

Models performing well on this benchmark migth be well suited on your problems if the solutions need
- multi-step mathematical reasoning
- mathematical concepts beyond simple Algebra

On a meta level models doing well on this benchmark might be good at
- extracting numerical information from a text corpus

## Resources

- [Link to paper on arXiv](https://arxiv.org/abs/2110.14168)
- [Link to full dataset](https://github.com/openai/grade-school-math)
- Part of the [open LLM leaderboard](https://huggingface.co/spaces/HuggingFaceH4/open_llm_leaderboard) on HuggingFace
