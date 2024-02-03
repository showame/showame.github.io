---
layout: post
title: "Threat Model GPT"
date: 2024-02-03 12:27:56 +0100
categories: AI Security
tags: GPT ThreatModeling
---

# About Threat Model GPT

I've published a GPT for the first time, hurray!

Lately I have been busy with threat modeling, and while doing this I realized how great it would be to have a dedicated assistant, which is why I've built Threat Model GPT.

In the realm of IT, the concept of security often presents itself as a daunting challenge. For many, it remains an elusive aspect of their operations, typically assigned to the already burdened shoulders of security teams. In less fortunate scenarios, it's either indefinitely deferred or neglected altogether.

Recognizing this gap, I was motivated to create Threat Model GPT as a solution aimed at demystifying and simplifying the threat modeling process. My goal was to craft a tool that would empower software engineers and managers alike to efficiently assess and enhance the security framework of their projects. The beauty of leveraging AI in security is its ability to demystify the complexities of cyberspace.

Threat Model GPT is designed with user-friendliness in mind, enabling users to generate [Data Flow Diagrams](https://en.wikipedia.org/wiki/Data_flow_diagram) (DFD) by simply describing the system under examination. This feature supports various diagram modeling languages, including the [Mermaid](https://www.mermaidchart.com/) syntax, offering flexibility to accommodate user preferences. In fact, users are encouraged to specify their preferred language when interacting with the tool to ensure the output meets their expectations. Following the creation and approval of a DFD that accurately represents the system, users can proceed to feed the diagram code into Threat Model GPT and move on with the threat model analysis.

The GPT will interpret the diagram code and initiate a comprehensive analysis with the model of choice. While STRIDE serves as the default model, Threat Model GPT is versatile, allowing for the application of alternative models that best align with the specific needs of the user's project.

A current limitation is that only ChatGPT Plus and higher plans can use the GPT store, but I do hope that in the future OpenAI will consider changing this by extending to the free-tier users. Such a move would democratize the benefits of AI and in this particular case of threat modeling, enabling a wider audience to hone their security skills and practices.

Thank you for reading to the end of this post!

Before moving on with your busy day, and if you have access to the GPT Store, be sure to check out my GPT: [https://chat.openai.com/g/g-aMj6Bj48D-threat-model-gpt](https://chat.openai.com/g/g-aMj6Bj48D-threat-model-gpt)
