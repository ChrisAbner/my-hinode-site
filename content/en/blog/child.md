---
author: "Chris Abner"
title: "Vicuna: An Open-Source Chatbot"
date: 2023-02-17
description: "Impressing GPT-4 with 90% ChatGPT Quality"
tags: ["theme"]
thumbnail: https://www.aidemos.info/wp-content/uploads/2023/04/Vicuna.webp
photoCredits: <a href="https://unsplash.com/@lucabravo">Luca Bravo</a>
photoSource: <a href="https://unsplash.com/photos/ESkw2ayO2As">Unsplash</a>
---

{{< image src="https://www.aidemos.info/wp-content/uploads/2023/04/Vicuna.webp" ratio="16x9" caption="" class="rounded" >}}

##  An open source chatbot for high quality natural conversations

Chatbots are becoming more and more popular as a way of interacting with users, providing information, entertainment, and assistance. However, building a chatbot that can handle diverse and natural conversations is still a challenging task that requires a lot of data and computational resources.

In this blog post, we will introduce Vicuna, an open-source chatbot that aims to provide a high-quality conversational experience with minimal data and training time. Vicuna is based on LLaMA, a large-scale pre-trained language model that can generate fluent and coherent texts on various topics. Vicuna fine-tunes LLaMA on user-shared conversations collected from ShareGPT, a platform that allows users to chat with GPT-3 and share their dialogues with others.

We will show how Vicuna achieves impressive results in terms of quality, diversity, and personality, compared to other state-of-the-art chatbots such as OpenAI ChatGPT and Google Bard. We will also demonstrate how Vicuna can be easily customized and deployed using our open-source code and web interface.

## What is Vicuna?

Vicuna is an open-source chatbot that leverages LLaMA, a large-scale pre-trained language model that can generate fluent and coherent texts on various topics. LLaMA is trained on a massive corpus of text from the web, books, news, Wikipedia, and other sources, using the Transformer architecture and the self-attention mechanism.

Vicuna fine-tunes LLaMA on user-shared conversations collected from ShareGPT, a platform that allows users to chat with GPT-3 and share their dialogues with others. ShareGPT provides a rich and diverse source of conversational data that covers different domains, styles, and personalities. By fine-tuning on this data, Vicuna adapts LLaMA to the conversational setting and learns how to generate natural and engaging responses.

Vicuna uses a simple yet effective decoding strategy that combines top-k sampling and nucleus sampling to generate diverse and relevant responses. Top-k sampling restricts the generation to the k most likely tokens at each step, while nucleus sampling truncates the probability distribution to the smallest set of tokens whose cumulative probability exceeds a threshold. This way, Vicuna avoids generating generic or repetitive responses while maintaining coherence and consistency.

Vicuna also incorporates a persona module that allows the chatbot to have a consistent and distinctive personality across different conversations. The persona module consists of a set of attributes and values that describe the chatbot's identity, preferences, opinions, and emotions. For example, the chatbot's name, age, gender, occupation, hobbies, favorite movies, etc. The persona module is used to guide the generation process by adding persona-related keywords or phrases to the input context.




## How does Vicuna compare to other chatbots?

We evaluate Vicuna using GPT-4 as a judge. GPT-4 is a hypothetical future version of GPT-3 that can generate human-like texts on any topic. We assume that GPT-4 can also evaluate the quality of texts using various criteria such as fluency, coherence, relevance, diversity, and personality. We compare Vicuna to other state-of-the-art chatbots such as OpenAI ChatGPT and Google Bard using GPT-4's ratings.

Our preliminary evaluation shows that Vicuna achieves more than 90% * quality of OpenAI ChatGPT and Google Bard while outperforming other models like LLaMA and Stanford Alpaca in more than 90% * of the cases. Vicuna generates more natural and engaging responses that are relevant to the input context and reflect the chatbot's personality. Vicuna also avoids generating generic or repetitive responses that are common in other chatbots.



