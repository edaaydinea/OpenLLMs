# Open-source LLMs: Uncensored & secure AI locally with RAG

This comprehensive course focuses on empowering learners with the knowledge and skills to utilize open-source Large Language Models (LLMs) effectively, guiding them from initial setup and foundational concepts to building advanced AI applications. Key areas include local LLM deployment (using LM Studio, Ollama), in-depth prompt engineering, implementing Retrieval Augmented Generation (RAG) with vector databases (AnythingLLM, LlamaIndex), developing AI agents (LangChain, Flowise), and custom model fine-tuning, all while considering hardware needs, data privacy, and security.

[Enroll in the course on Udemy](https://www.udemy.com/course/open-source-llms-uncensored-secure-ai-locally-with-rag/)

## Table of Contents

- [Open-source LLMs: Uncensored \& secure AI locally with RAG](#open-source-llms-uncensored--secure-ai-locally-with-rag)
  - [Table of Contents](#table-of-contents)
  - [Week 1 - Introduction to Open-Source LLMs and Course Overview](#week-1---introduction-to-open-source-llms-and-course-overview)
    - [Day 1: Introduction and Overview](#day-1-introduction-and-overview)
    - [Day 2:  Why Open-Source LLMs? Differences, Advantages, and Disadvantages](#day-2--why-open-source-llms-differences-advantages-and-disadvantages)
    - [Day 3: The Easiest Way to Run Open-Source LLMs Locally \& What You Need](#day-3-the-easiest-way-to-run-open-source-llms-locally--what-you-need)
    - [Day 4: Prompt Engineering for Open-Source LLMs and Their Use in the Cloud](#day-4-prompt-engineering-for-open-source-llms-and-their-use-in-the-cloud)
  - [Week 2 - Advanced Topics in Open-Source LLMs](#week-2---advanced-topics-in-open-source-llms)
    - [Day 5: Function Calling, RAG, and Vector Databases with Open-Source LLMs](#day-5-function-calling-rag-and-vector-databases-with-open-source-llms)
    - [Day 6: Optimizing RAG Apps: Tips for Data Preparation](#day-6-optimizing-rag-apps-tips-for-data-preparation)
    - [Day 7: Local AI Agents with Open-Source LLMs](#day-7-local-ai-agents-with-open-source-llms)
    - [Day 8: Finetuning, Renting GPUs, Open-Source TTS, Finding the BEST LLM \& More Tips](#day-8-finetuning-renting-gpus-open-source-tts-finding-the-best-llm--more-tips)
    - [Day 9: Data Privacy, Security, and What Comes Next?](#day-9-data-privacy-security-and-what-comes-next)

## Week 1 - Introduction to Open-Source LLMs and Course Overview

### Day 1: Introduction and Overview

**What I did today:**

- Introduced the course, focusing on utilizing open-source LLMs for local and secure AI applications.
- Learned about key course areas: local LLM deployment (LM Studio, Ollama), prompt engineering, Retrieval Augmented Generation (RAG) with vector databases (AnythingLLM, LlamaIndex), AI agent development (LangChain, Flowise), and custom model fine-tuning.
- Understood the emphasis on hardware needs, data privacy, and security when working with local LLMs.
- Discussed the course's goal to transform learners into proficient users of LLMs, from basics to advanced topics like AI agents and local model operation.
- Explored the concept of uncensored LLMs (e.g., "Dolphin" fine-tunes) to understand model alignment, bias, and their implications, while prioritizing data privacy.
- Received tips for learning, such as adjusting video playback speed for optimal focus.
- Reviewed a comprehensive list of important links for open-source LLMs, installation tools, RAG resources, AI agents, and more, as detailed in the notebook.

**Resources**:

- [day1.ipynb](./notes/day1.ipynb)

### Day 2:  Why Open-Source LLMs? Differences, Advantages, and Disadvantages

**What I did today:**

- Gained a foundational understanding of Large Language Models (LLMs), including their core architecture (parameter and run files), three-phase training process (pre-training, fine-tuning, RLHF), and the significance of tokenization and context windows.
- Explored methods for discovering and evaluating LLMs, including familiarization with resources like the LMSys Chatbot Arena and Open LLM Leaderboards, and understood how to leverage them for model selection based on human preference and objective benchmarks.
- Critically analyzed the trade-offs between closed-source and open-source LLMs, identifying key disadvantages of closed-source models such as privacy risks, costs, limited customization, vendor lock-in, and the potential for bias and censorship.
- Recognized the substantial advantages of open-source LLMs, particularly focusing on enhanced data privacy through local deployment, cost-effectiveness, full customization capabilities, offline functionality, and freedom from externally imposed biases or restrictions.
- Investigated the capabilities of the newly released open-source model, DeepSeek-R1, noting its reported high performance in reasoning tasks due to "Test-Time Compute" and its permissive MIT license for commercial use, including the availability of distilled versions and a testing API.
- Applied conceptual knowledge by analyzing practical scenarios, such as selecting appropriate LLM types for tasks involving sensitive data, explaining technical concepts to non-technical audiences, and strategizing the validation of LLM-generated code.
- Developed a deeper appreciation for the practical implications of LLM attributes by considering how to leverage specific model features (e.g., DeepSeek-R1's reasoning) for advanced applications like generating reliable unit tests.
- Solidified understanding of how to make informed LLM selections by applying learned principles to choose models for specialized tasks, such as using open-source models for projects requiring domain-specific customization and freedom from content restrictions, like historical text analysis.
- Prepared for practical application by understanding the importance of local LLM deployment for privacy and control, setting the stage for hands-on experience with running open-source models.
- Embraced an action-oriented definition of learning, committing to apply this knowledge to make demonstrably different and more informed LLM choices in future projects, particularly advocating for open-source solutions where data privacy and transparency are paramount.

**Resources**:

- [day2.ipynb](./notes/day2.ipynb)

### Day 3: The Easiest Way to Run Open-Source LLMs Locally & What You Need

**What I did today:**

- Understood the hardware requirements (GPU, VRAM, CPU, RAM) for running LLMs locally and the critical role of **quantization** in making models accessible on consumer-grade hardware.
- Learned to install and use **LM Studio** as a user-friendly platform for downloading and running various open-source LLMs (like Llama 3, Phi-3, Mistral) locally, ensuring data privacy.
- Explored the LM Studio interface for model discovery (GGUF format), selection based on quantization levels (e.g., Q4, Q5, FP16), and configuring **GPU offloading** for optimal performance.
- Practiced interacting with LLMs in LM Studio's AI Chat, adjusting parameters like temperature and context length to tailor model outputs.
- Investigated the concept of censored vs. uncensored LLMs, learning how to find and use "Dolphin" fine-tunes for unfiltered responses, while acknowledging the ethical considerations.
- Identified core LLM use cases, primarily text expansion and summarization, and their applications in programming, education, and data analysis.
- Gained knowledge on enabling and using multimodal **vision models** (e.g., Llava with Llama 3/Phi-3) in LM Studio, including the need for separate vision adapter files, to analyze images locally.
- Delved deeper into GPU offload settings to balance performance and system resources.
- Consolidated learning on strategic model selection, hardware optimization, and practical LM Studio usage.

**Resources**:

- [day3.ipynb](./notes/day3.ipynb)

### Day 4: Prompt Engineering for Open-Source LLMs and Their Use in the Cloud

**What I did today:**

- Explored **HuggingChat** as a user-friendly interface for open-source LLMs, noting its cloud-based accessibility, file upload capabilities, and integrated tools (function calling).
- Learned about **System Prompts** and their importance in guiding LLM behavior across platforms like Hugging Chat, LM Studio, and ChatGPT.
- Understood why **Prompt Engineering** is crucial, illustrated by how LLMs might provide overly complex solutions without specific, human-centric reasoning instructions.
- Grasped the concept of **Semantic Association**, where LLMs activate related terms and concepts based on input words, forming a key principle for effective prompting.
- Studied **Structured Prompts**, which involve defining a modifier (output type), a topic, and additional modifiers (audience, style, length) to tailor LLM outputs.
- Investigated **Instruction Prompting**, including using phrases like "Let's think step by step" or "Take a deep breath" to enhance LLM responses.
- Examined **Role Prompting**, where assigning a persona (e.g., "expert data scientist") improves output specificity by leveraging semantic association.
- Learned about **Shot Prompting** (Zero-Shot, One-Shot, Few-Shot), which involves providing zero to multiple examples to guide the LLM's output style and structure.
- Explored **Reverse Prompt Engineering**, an iterative method to deconstruct existing text to derive a generative prompt that can replicate its style and content.
- Understood **Chain of Thought (CoT) Prompting**, which encourages LLMs to articulate intermediate reasoning steps, improving accuracy for multi-step problems.
- Was introduced to **Tree of Thoughts (ToT) Prompting**, a technique where the LLM explores multiple reasoning paths, evaluates them, and strategically expands promising ones.
- Saw how **Combining Prompting Concepts** (layering role, structured, shot, and enhancer prompts) can produce highly specific and effective LLM outputs.
- Learned about **Creating Custom Assistants** in platforms like Hugging Chat, which involves pre-configuring LLMs with system prompts and roles for specialized tasks.
- Discovered **Groq** and its LPU technology for exceptionally fast inference speeds with open-source LLMs.

**Resources**:

- [Day 4 Notes](./notes/day4.ipynb)

## Week 2 - Advanced Topics in Open-Source LLMs

### Day 5: Function Calling, RAG, and Vector Databases with Open-Source LLMs

**What I did today:**

- Explored the foundational elements and setup process for creating a local Retrieval Augmented Generation (RAG) application.
- Emphasized the importance of understanding concepts like function calling, vector databases, and embedding models.
- Learned about building a private and versatile local system using tools such as LM Studio and Olama.
- Understood how to enable capabilities like searching local files, accessing the internet, generating charts, and integrating text-to-speech, while ensuring maximum data privacy.
- Investigated function calling in LLMs, presenting the LLM as an "operating system" that intelligently delegates tasks to specialized external tools or programs.
- Learned about Retrieval Augmented Generation (RAG) as an efficient method for providing LLMs with additional, specific knowledge.
- Understood the process of installing and configuring AnythingLM to build local AI applications, including those leveraging function calling and RAG.
- Explored how to connect AnythingLM to a locally hosted open-source LLM server, such as one run by LM Studio.
- Learned to build a private, local RAG application using AnythingLM with an LM Studio server, focusing on workspace creation, document ingestion (local files, websites, YouTube transcripts, GitHub repositories), and embedding information into AnythingLM's built-in local vector database (LanceDB).
- Understood how to activate and utilize function calling capabilities, specifically web search, within a local AnythingLM setup by configuring an "agent" in AnythingLM to use an external search API (like SerpDog).
- Explored advanced agent skills in AnythingLM, such as full document summarization and on-the-fly chart generation.
- Delved into advanced configuration settings in AnythingLM, with a particular emphasis on improving Text-to-Speech (TTS) quality through integration with external services like OpenAI.
- Covered the installation of Ollama, managing models through its command-line interface, and connecting Ollama as a local LLM provider to AnythingLM.

**Resources:**

- [Day 5 Notebook](./notes/day5.ipynb)

### Day 6: Optimizing RAG Apps: Tips for Data Preparation

**What I did today:**

- Learned about ChatGPT's "Custom Instructions" feature, which allows users to provide persistent information and response preferences to personalize outputs and improve efficiency.
- Explored Chain of Thought (CoT) prompting, a technique to enhance LLM reasoning by guiding them to articulate intermediate steps, using either few-shot examples or zero-shot instructions like "Let's think step by step."
- Investigated Self-Consistency prompting, which improves answer reliability by generating multiple responses to a query and selecting the most frequent one.
- Understood "Knowledge Creation Prompting" (or Knowledge Generation), where an initial general query primes the LLM with context, enhancing subsequent specific prompts on that topic.
- Delved into Tree of Thought (ToT) prompting, an advanced technique where the LLM generates, evaluates, and expands on diverse ideas in a branching structure to solve complex problems.
- Received an overview of other advanced prompting techniques like Retrieval Augmented Generation (RAG), ART, and APE, with an emphasis on mastering core methods like Tree of Thought for high-stakes tasks.

**Resources:**

- [Day 6 Notebook](./notes/day6.ipynb)

### Day 7: Local AI Agents with Open-Source LLMs

**What I did today:**

- Defined AI agents as interconnected systems of multiple LLMs designed for complex tasks, and explored development frameworks like LangChain, LangGraph, and Flowise.
- Focused on Flowise for its local deployment capabilities and user-friendly interface, suitable for building applications like automated content generation and coding assistants.
- Understood multi-LLM agent architectures, where tasks are divided among specialized LLMs (e.g., planner, researcher, writer) for more robust outcomes.
- Explored the supervisor/sub-expert LLM architecture, where a supervisor LLM coordinates specialized sub-expert LLMs for task decomposition and specialized intelligence.
- Learned about Retrieval Augmented Generation (RAG) for AI agents, enabling them to access external knowledge bases to improve accuracy and relevance.
- Gained practical experience by installing Flowise locally using Node.js and managing Node.js versions with NVM (Node Version Manager) to ensure compatibility (recommending Node.js v20.6.0).
- Navigated the Flowise interface, including the Marketplace for templates, and learned to manage credentials for external services.
- Built a local RAG chatbot using Flowise with a self-hosted Ollama server (Llama 3), covering component setup (chat models, embeddings, vector stores, document loaders) and the critical "upsert" process.
- Created a multi-LLM AI agent in Flowise with a supervisor-worker architecture (Code Writer and Documentation Writer) using local Ollama models, including AI-assisted prompt generation.
- Developed a multi-agent AI system for content creation (web research → blog post → tweet → YouTube titles) using Flowise, local Ollama (Llama 3 with function calling), and SerpAPI for web searches.
- Investigated integrating RAG capabilities into individual worker agents within Flowise and discussed deploying Flowise applications to cloud platforms like Render with persistent disk storage.
- Explored using open-source models from Hugging Face Inference API in Flowise, including API token setup and the importance of model-specific prompt templates, and learned to embed/share chatbots.
- Enhanced Flowise application performance by integrating Groq's high-speed inference API for LLMs like Llama 3, while noting Groq does not provide embedding models.

**Resources:**

- [Day 7 Notebook](./notes/day7.ipynb)

### Day 8: Finetuning, Renting GPUs, Open-Source TTS, Finding the BEST LLM & More Tips

**What I did today:**

- Explored Text-to-Speech (TTS) options, focusing on OpenAI's TTS via Google Colab for its quality and ease of use, while also acknowledging open-source alternatives like Jets.
- Learned about Moshi Moshi, a free, open-source conversational AI, as a tool for casual interaction and experimentation.
- Investigated LLM fine-tuning, discussing platforms like Hugging Face AutoTrain and Google Colab (with Unsloth for Llama 3) for customizing models, while also highlighting the significant costs, data requirements, and potential for increased hallucinations.
- Understood the process of generating custom datasets for fine-tuning (e.g., using ChatGPT) and key training parameters (steps, epochs, loss).
- Received strong cautionary advice regarding the general necessity and effectiveness of fine-tuning, with Retrieval Augmented Generation (RAG) often presented as a more practical alternative.
- Learned how to find and evaluate open-source LLMs using resources like Chatbot Arena and the Open LLM Leaderboard, with Meta's Llama models noted as consistently strong.
- Discussed xAI's Grok, acknowledging its power and open-source nature but noting its current impracticality for local use due to size and lack of quantization, making X platform subscription the primary access route.
- Explored GPU rental services like RunPod (recommending The Bloke's One-Click UI template) and Vast.ai (as Mass Compute) for running large models when local hardware is insufficient.

**Resources:**

- [Day 8 Notebook](./notes/day8.ipynb)

### Day 9: Data Privacy, Security, and What Comes Next?
