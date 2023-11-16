# GPT Slop

This repository is created to gather a comprehensive list of phrases and sentences commonly used by OpenAI's GPT and Anthropic's Claude models. The aim is to have a centralized repository for community submissions, so that dataset curators can easily identify and remove samples contain GPTism/Claudism from their datasets.

## Contribution
Please contribute your additions based to the correct YAML file. Capitalization doesn't matter, as I expect dataset curators to filter with `lower()`. 
This is a growing repository, so please submit a pull request with phrases you think should be included!

## Motivation
The majority of new foundational models, including Llama-2 and Mistral, have been trained on GPT-generated datasets. This can be proven by prompting them with `As an AI` and inspecting the logprobs for the subsequently generated tokens. The probability of the next token being `language` is close to 100%, while being almost 0% with Llama-1 models.

