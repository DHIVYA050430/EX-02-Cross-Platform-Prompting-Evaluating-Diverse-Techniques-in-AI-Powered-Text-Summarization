# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## Name:DIVYA E
## Reg no: 212223230050
## AIM
To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

## Scenario:
You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

Accuracy

Coherence

Simplicity

Speed

User experience

## Algorithm:
## Output:
## Zero-shot Prompts:
## Definition:
**Zero‑shot prompting** is a technique where a Large Language Model (LLM) is given a task instruction **without any prior examples** of how to complete that task. The model relies entirely on its pre‑trained knowledge and general language understanding to generate a response.
## Prompt:To generate an article on "The Basics of Blockchain Technology" in 500 words and provide an information about the sources and summerise it.
## ChatGpt:

**The Basics of Blockchain Technology**

Blockchain is a decentralized and secure digital ledger that records transactions across multiple systems. It uses cryptographic techniques to ensure data integrity and prevents unauthorized changes. Key features include decentralization, transparency, and immutability. Consensus mechanisms like Proof of Work and Proof of Stake validate transactions. While blockchain is widely known for powering cryptocurrencies, it also has applications in healthcare, supply chains, and smart contracts. Despite challenges like scalability and energy usage, blockchain continues to evolve and has the potential to revolutionize various industries by eliminating intermediaries and improving trust in digital transactions.Blockchain is a decentralized and secure digital ledger that records transactions across multiple systems. It uses cryptographic techniques to ensure data integrity and prevents unauthorized changes. Key features include decentralization, transparency, and immutability. Consensus mechanisms like Proof of Work and Proof of Stake validate transactions. While blockchain is widely known for powering cryptocurrencies, it also has applications in healthcare, supply chains, and smart contracts. Despite challenges like scalability and energy usage, blockchain continues to evolve and has the potential to revolutionize various industries by eliminating intermediaries and improving trust in digital transactions.

## Deepseek:

**The Basics of Blockchain Technology**
Blockchain is a decentralized, tamper-resistant digital ledger where data blocks are cryptographically chained together. Key features include decentralization, transparency, and immutability. Consensus mechanisms like Proof of Work (PoW) or Proof of Stake (PoS) validate transactions without central authorities. Beyond cryptocurrencies, blockchain enables smart contracts, supply chain tracking, and secure data sharing. Challenges remain in energy use, scalability, and regulation. Sources include Nakamoto's Bitcoin white paper, Antonopoulos’ Mastering Bitcoin, Buterin’s Ethereum paper, NIST guidelines, IBM’s enterprise overview, and an IEEE survey—all confirming blockchain’s role as a trustless, decentralized system with ongoing technical trade-offs.

## Gemni:
**The Basics of Blockchain Technology**

Blockchain technology is a decentralized, immutable ledger system that records transactions across a peer-to-peer network without the need for a central authority. By grouping data into "blocks" secured by cryptographic hashes, it ensures that once information is recorded, it cannot be altered or deleted, fostering transparency and trust. Modern networks utilize consensus mechanisms to validate data and employ smart contracts to automate complex agreements. Since its inception with Bitcoin, the technology has evolved into a robust infrastructure for institutional finance and supply chains, offering a highly secure, transparent, and efficient alternative to traditional centralized databases.

## Evaluation Table

| AI Platform   | Accuracy | Coherence | Simplicity | Speed | User Experience | Comments                                                              | Final Grade |
| ------------- | -------- | --------- | ---------- | ----- | --------------- | --------------------------------------------------------------------- | ----------- |
| **ChatGPT**   | 9/10     | 9/10      | 9/10       | 10/10 | 9/10            | Clear, simple, concise; easy for undergraduates to read               | **A**       |
| **Deepseek**    | 10/10    | 9/10      | 8/10       | 9/10  | 8/10            | Very detailed and accurate and easy to understand. | **A-**      |
| **Gemni** | 9/10     | 9/10      | 9/10       | 9/10  | 9/10            | Good explanation, slightly longer sentences; still understandable     | **A**       |

## Few-shot:
## Definition:
**Few-shot** prompting is a technique where you give an AI model a few examples of a task before asking it to perform a similar task.
These examples help the model understand the pattern, format, or style of the expected answer.
## Prompt:
"Here are examples of summaries for technical articles. Example 1 Mini Article: “Bitcoin uses blockchain technology to allow peer-to-peer payments without banks. Each transaction is stored in a public ledger that anyone can verify.” Example 2 Mini Article: “Smart contracts are programs stored on a blockchain. They run automatically when certain conditions are met, reducing the need for intermediaries in business deals.”
Summerise and give it in 100 words.
## ChatGpt:
**The Basics of Blockchain Technology**
Blockchain technology enables secure and decentralized digital transactions without relying on intermediaries like banks. It works by recording transactions in a public ledger that is transparent and accessible to all participants. Cryptographic methods ensure that the data remains secure and tamper-proof. One key application is cryptocurrency, such as Bitcoin, which allows peer-to-peer payments. Another important feature is smart contracts, which are self-executing programs that automatically perform actions when specific conditions are met. These innovations reduce costs, increase efficiency, and improve trust in digital systems, making blockchain a powerful tool for modern technological and business applications.
## Deepseek:

**The Basics of Blockchain Technology**
Bitcoin uses blockchain to enable peer-to-peer payments without banks, storing every transaction on a public, verifiable ledger. Separately, smart contracts are self-executing programs stored on a blockchain; they trigger automatically when predefined conditions are met, reducing or eliminating intermediaries like lawyers or brokers in business deals. Together, these examples illustrate two core uses of blockchain technology: first, as a decentralized payment system (Bitcoin), and second, as a programmable automation tool (smart contracts). Both leverage blockchain’s transparency, immutability, and trustlessness to streamline processes that traditionally required central authorities or third parties.
## Gemni:
**The Basics of Blockchain Technology**
Blockchain technology transforms finance and business by eliminating intermediaries through decentralized ledgers. As demonstrated by Bitcoin, it enables direct peer-to-peer payments, utilizing a public record that ensures transparency and security without requiring traditional banks. Beyond currency, the technology supports smart contracts—automated programs that execute transactions only when specific conditions are met. Together, these innovations reduce the need for middlemen, cut costs, and streamline complex deals. By replacing central authorities with cryptographic verification and automated code, blockchain creates a high-trust environment for global digital exchange, making it a foundational tool for the modern digital economy.

## EVALUATION TABLE

| AI Platform   | Accuracy (10) | Coherence (10) | Simplicity (10) | Speed (10) | User Experience (10) | Comments                                                                                          | Final Grade |
| ------------- | ------------- | -------------- | --------------- | ---------- | -------------------- | ------------------------------------------------------------------------------------------------- | ----------- |
| **ChatGPT**   | 10            | 10             | 10              | 10         | 10                   | Clear, concise, and very easy for undergraduates to understand                                    | **A**       |
| **Deepseek**    | 10            | 9              | 9               | 9          | 9                    | Extremely accurate and detailed, slightly technical; longer sentences may be harder for beginners | **A-**      |
| **Gemni** | 10            | 10             | 9               | 9          | 10                   | Accurate, coherent, slightly longer sentences, still readable; excellent user experience          | **A**       |


## Chain-of-thought:
## Definition:
 **Chain-of-thought** prompting is a technique where an AI model is encouraged to show its step-by-step reasoning while solving a problem.
It helps in understanding how the answer is derived, especially for complex tasks like math, logic, or problem-solving.
## Prompt:
"Let's think step-by-step. First, explain how blockchain works, then summarize its key applications." 
Finally give its summerization in 100 words.

## ChatGpt:
**The Basics of Blockchain Technology**
Blockchain is a decentralized technology that records transactions securely across a distributed network of computers. It works by grouping transactions into blocks that are linked using cryptographic hashes, ensuring data integrity and immutability. Transactions are verified through consensus mechanisms, eliminating the need for central authorities. Blockchain is best known for powering cryptocurrencies like Bitcoin, enabling secure peer-to-peer transactions. It also supports smart contracts, which automate processes without intermediaries. Beyond finance, blockchain is used in supply chain management, healthcare, digital identity, and voting systems. Its transparency, security, and efficiency make it a transformative technology with wide-ranging applications.
## Deepseek:

**The Basics of Blockchain Technology**
Blockchain is a decentralized digital ledger where data is grouped into cryptographically linked blocks. Consensus mechanisms like Proof of Work validate new entries without a central authority, making the system transparent and tamper-resistant. Key applications include cryptocurrencies (peer-to-peer payments), smart contracts (self-executing agreements), supply chain tracking, secure medical records, digital identity management, and fraud-proof voting. Each use case eliminates intermediaries while improving trust and auditability. Despite challenges like energy use and scalability, blockchain transforms how value, data, and agreements are managed online—offering a foundational shift toward decentralized, verifiable systems across finance, healthcare, logistics, and governance.
## Gemni:
**The Basics of Blockchain Technology**
Blockchain is a decentralized ledger that records data through a secure, step-by-step process of transaction initiation, network verification, and cryptographic "chaining." By grouping transactions into blocks linked by unique hashes, it ensures that data is immutable and transparent without needing a central authority. In 2026, its applications have expanded into "invisible infrastructure," powering everything from instant global finance (DeFi) and the tokenization of real-world assets to providing an audit trail for AI. Ultimately, blockchain replaces traditional middlemen with automated trust, making digital exchanges faster, cheaper, and significantly more secure for users worldwide.

## EVALUATION TABLE
| **Platform**  | **Accuracy** | **Coherence** | **Simplicity** | **Speed** | **User Experience** | **Average Score (/10)** | **Remarks**                                                                       |
| ------------- | ------------ | ------------- | -------------- | --------- | ------------------- | ----------------------- | --------------------------------------------------------------------------------- |
| **ChatGPT**   | 10           | 10            | 10             | 10        | 10                  | **10.0**                | Very clear, accurate, and student-friendly summary. |
| **Deepseek**    | 10           | 9             | 9              | 9         | 9                   | **9.2**                 | Accurate and detailed, but slightly more technical and wordy.                     |
| **Gemni** | 10           | 10            | 9              | 9         | 10                  | **9.6**                 | Balanced, professional, and coherent. Slightly complex .        |

## Role-Based prompting:
## Definition:
Role-based prompting is a technique where you assign a specific role or identity to the AI before asking a question.
This helps the AI respond in a particular style, tone, or expertise level based on that role (e.g., teacher, engineer, doctor).
## Prompt:
You are an educational content curator for an online learning platform.Your task is to help undergraduate students easily understand technical topics. Read the following 500-word article on “The Basics of Blockchain Technology” and write a simple, clear, and accurate summary (100 words). Use an educational tone, avoid jargon, and focus on clarity and understanding.
## ChatGpt:
**The Basics of Blockchain Technology**
Blockchain is a digital system used to record information securely across many computers instead of one central place. It stores data in blocks that are linked together, forming a chain that cannot be easily changed. Each transaction is verified by a network of computers, ensuring accuracy and trust without needing intermediaries like banks. Blockchain is best known for supporting cryptocurrencies such as Bitcoin, but it is also used in areas like supply chain tracking and digital contracts. Its main advantages are transparency, security, and reliability, making it a valuable technology for modern applications across different industries.
## Deepseek:

**The Basics of Blockchain Technology**
A blockchain is a digital record book shared across many computers. Instead of one person or bank controlling it, everyone in the network has a copy. Information is stored in “blocks,” and each block is linked to the one before it using a unique code. Once added, a block cannot be changed—this makes the system secure and transparent. Blockchain can track money (like Bitcoin), manage contracts, or follow products through a supply chain. It removes the need for middlemen like banks or lawyers. While not perfect (it can use lots of energy), blockchain helps build trust online without a central boss.
## Gemni:
**The Basics of Blockchain Technology**
Blockchain technology acts as a shared digital notebook that records information in a way that is nearly impossible to change. Instead of one bank or company controlling the data, copies are shared across thousands of computers globally.
When a transaction occurs, the network verifies it, bundles it into a "block," and links it to previous entries using a unique digital fingerprint. This creates a permanent, transparent chain. By removing the need for middlemen, blockchain makes digital activities—from sending money to signing contracts—faster, more secure, and accessible to everyone without requiring a central authority.

## EVALUATION TABLE

| **AI Platform** | **Accuracy** | **Coherence** | **Simplicity** | **Speed** | **User Experience** | **Average Score (/10)** | **Remarks**                                                             |
| --------------- | ------------ | ------------- | -------------- | --------- | ------------------- | ----------------------- | ----------------------------------------------------------------------- |
| **ChatGPT**     | 10           | 10            | 10             | 10        | 10                  | **10.0**                | Very clear, simple, and educational tone. |
| **Deepseek**      | 10           | 10            | 9              | 9         | 9                   | **9.4**                 | Accurate and detailed but uses slightly complex phrasing.               |
| **Gemni**   | 10           | 10            | 9              | 9         | 10                  | **9.6**                 | Balanced and informative, slightly more formal tone.  

## Overall Performance:
<img width="562" height="435" alt="image" src="https://github.com/user-attachments/assets/e5e9415d-b476-4499-85df-10c158564402" />

## Result
 The results of this evaluation will be presented in a structured format, providing a clear comparison of the effectiveness of different prompting techniques across the chosen AI platforms for the task of summarizing the technical article on "The Basics of Blockchain Technology."

