# EX-02 – Cross-Platform Prompting: Evaluating Diverse Techniques in AI-Powered Text Summarization

**Name** DIVYA E
**Register No.:** 212223230050

---

##  AIM
To evaluate and compare the effectiveness of **different prompting techniques** (Zero-shot, Few-shot, Chain-of-Thought, and Role-based) across **multiple AI platforms** (ChatGPT, Gemini, and Perplexity AI) for a common summarization task.

---

##  Scenario
You are part of a **content curation team** for an educational platform that delivers concise summaries of research papers to undergraduate students.  
Your task is to summarize a **500-word technical article** titled:

> **"The Basics of Blockchain Technology"**

using different AI platforms and prompting strategies.  
The goal is to determine which **platform + prompting combination** yields the best summary in terms of:

- **Accuracy** – Captures all essential points correctly  
- **Coherence** – Logical and structured flow  
- **Simplicity** – Easy to understand for students  
- **Speed** – Response time and efficiency  
- **User Experience (UX)** – Readability, usability, and formatting quality  

---

##  Algorithm

1. **Article Selection**  
   Select the technical article *“The Basics of Blockchain Technology”* (approx. 500 words).

2. **Prompting Strategies**  
   Evaluate four prompting approaches:
   - **Zero-shot**: No examples; direct summary request.  
   - **Few-shot**: Provide 2–3 example summaries first.  
   - **Chain-of-Thought (CoT)**: Ask the model to reason step-by-step before summarizing.  
   - **Role-based**: Assign a specific role (e.g., professor, tutor).

3. **Platform Selection**  
   Perform experiments using:  
   - **ChatGPT (OpenAI)**  
   - **Gemini (Google)**  
   - **Perplexity AI**

4. **Execution**  
   - Apply each prompting technique on each platform.  
   - Record summaries and time taken.  
   - Evaluate each output on five metrics.

5. **Evaluation Metrics**
   - Accuracy (1–5)
   - Coherence (1–5)
   - Simplicity (1–5)
   - Speed (1–5)
   - User Experience (1–5)

6. **Scoring & Analysis**
   - Assign scores out of 5 for each criterion.
   - Calculate total score out of 25.
   - Compare across platforms and prompt types.

---

##  Prompts Used

###  Zero-shot Prompt

Summarize the following article titled “The Basics of Blockchain Technology” in 150 words for undergraduate students. Use clear and simple language.


###  Few-shot Prompt

Example 1:

Article: "Introduction to Artificial Intelligence"

Summary: Artificial Intelligence (AI) enables computers to perform tasks requiring human-like intelligence such as learning, reasoning, and problem-solving.

Example 2:

Article: "Cloud Computing Basics"

Summary: Cloud computing provides on-demand access to computing resources like storage and processing power over the internet, enabling scalability and flexibility.


### Chain-of-Thought Prompt

1.Before writing the final summary, break down the key points of the article “The Basics of Blockchain Technology” step-by-step:

2.Identify the main concept and purpose of blockchain.

3.Explain how blockchain works (blocks, nodes, consensus).

4.Mention its uses and advantages.

5.After reasoning through these steps, generate a concise summary suitable for undergraduate readers.

###  Role-based Prompt

You are a university professor explaining “The Basics of Blockchain Technology” to first-year computer science students.
Write a clear and concise summary (about 150 words) that explains the topic in simple language with examples.


---

##  Platforms Used

| Platform | Description |
|-----------|-------------|
| **ChatGPT** | OpenAI’s LLM, strong coherence and reasoning |
| **Gemini** | Google’s LLM, fast responses, concise summaries |
| **Perplexity AI** | Web-integrated AI, accurate factual outputs |

---

## Evaluation

| Platform | Prompt Type | Accuracy | Coherence | Simplicity | Speed | UX | **Total (/25)** |
|-----------|--------------|-----------|------------|-------------|--------|----|----------------|
| ChatGPT | Zero-shot | 4 | 4 | 4 | 5 | 5 | **22** |
| ChatGPT | Few-shot | 5 | 5 | 5 | 4 | 5 | **24** |
| ChatGPT | Chain-of-Thought | 5 | 5 | 4 | 3 | 5 | **22** |
| ChatGPT | Role-based | 5 | 5 | 5 | 4 | 5 | **24** |
| Gemini | Zero-shot | 3 | 3 | 3 | 5 | 4 | **18** |
| Gemini | Few-shot | 4 | 4 | 4 | 4 | 4 | **20** |
| Gemini | Role-based | 4 | 4 | 5 | 4 | 4 | **21** |
| Perplexity | Zero-shot | 4 | 4 | 4 | 5 | 4 | **21** |
| Perplexity | Few-shot | 4 | 4 | 5 | 4 | 4 | **21** |
| Perplexity | Role-based | 5 | 5 | 5 | 4 | 4 | **23** |

---

---

##  Analysis

- **ChatGPT (Few-shot)** and **ChatGPT (Role-based)** achieved the **highest total score (24/25)** due to superior coherence and student-friendly tone.  
- **Perplexity (Role-based)** performed very well, producing structured and factual summaries.  
- **Gemini** had the fastest response time but slightly lower content accuracy.  
- **Chain-of-Thought** prompting produced detailed yet slower responses.  
- **Few-shot** prompting improved contextual understanding across all models.

---

### Key Findings:
- **ChatGPT** provided the most balanced performance overall — accurate, coherent, and well-structured summaries.  
- **Gemini** excelled in **speed**, making it ideal for quick summaries with moderate detail.  
- **Perplexity AI** produced **clear and factual** summaries, particularly strong in **role-based prompts**.  
- **Few-shot prompting** consistently improved summarization quality across all platforms.  

---

##  Final Observation Table

| Criterion | Best Performer | Remarks |
|------------|----------------|----------|
| **Accuracy** | ChatGPT (Few-shot) | High factual consistency |
| **Coherence** | ChatGPT (Role-based) | Logical, fluent structure |
| **Simplicity** | Perplexity (Role-based) | Easy-to-read summaries |
| **Speed** | Gemini (Zero-shot) | Fastest response |
| **User Experience** | ChatGPT | Clean, readable, export-friendly |

---

##  Result

The **best-performing combinations** were:
1. **ChatGPT + Few-shot prompting → 24/25**  
2. **ChatGPT + Role-based prompting → 24/25**  
3. **Perplexity + Role-based prompting → 23/25**

 The experiment successfully demonstrated how prompt engineering techniques influence the quality of AI-generated summaries.  


---
