---
layout: default
title: DSC 180A Methodology Assignment 4
---

# DSC 180A Methodology Assignment 4

**Name:** Kaijie Zhang  
**Email:** kaz029@ucsd.edu  
**Section:** B08 – Large Language Models in Healthcare  
**Instructors:** Aaron Boussina and Karandeep Singh  

---

## **Q1: What is the most interesting topic covered in your domain this quarter?**

The most intriguing topic this quarter is **Content Rot**.  
I observed that when the context length grows beyond a certain point, adding more content can actually decrease model accuracy instead of improving it.  
This phenomenon opens up a rich line of research for understanding how context composition and retrieval quality affect LLM reasoning.

---

## **Q2: Describe a potential investigation you would like to pursue for your Quarter 2 Project.**

I plan to extend the theme from Quarter 1 by designing and experimenting with **new information retrieval (IR) architectures** aimed at improving the performance of **LLMs as information extractors**.  
My focus will be on building retrieval pipelines that can mitigate content rot and maintain semantic relevance across longer contexts.

---

## **Q3: What is a potential change you’d make to the approach taken in your current Quarter 1 Project?**

Instead of relying solely on conventional **IR/RAG frameworks** as the preprocessing step for the extractor, I will replace them with **custom retrieval strategies** that I design, enabling finer control over context selection and organization before LLM inference.

---

## **Q4: What other techniques would you be interested in using in your project?**

I am interested in exploring **discriminator-based validation modules** to interrogate the initial IR/RAG outputs and in applying **test-time scaling methods** to adaptively improve retrieval accuracy during inference.
