EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

AIM:

To evaluate and compare the effectiveness of prompting techniques (zero-shot, few-shot, chain-of-thought, role-based) across different AI platforms (e.g., ChatGPT, Gemini, Claude, Copilot) in a specific task: text summarization.

SCENARIO:

You are part of a content curation team for an educational platform that delivers quick summaries of research papers to undergraduate students. Your task is to summarize a 500-word technical article on "The Basics of Blockchain Technology" using multiple AI platforms and prompting strategies.

Your goal is to determine which combination of prompting technique + platform provides the best summary in terms of:

1.Accuracy

2.Coherence

3.Simplicity

4.Speed

5.User experience

OUTPUT:

1.Zero-shot Prompt: "Summarize the article on Blockchain Technology in 100 words."

Platform: ChatGPT
Summary: Blockchain is a decentralized digital ledger that records transactions securely across multiple computers. Each block stores data and links to the previous one, creating a chain. It offers transparency, security, and immutability. Blockchain is widely used in cryptocurrencies, supply chain management, healthcare, and finance. Consensus mechanisms such as Proof of Work and Proof of Stake validate transactions. The technology reduces intermediaries and increases trust among users.

Platform: Gemini
Blockchain technology is a decentralized, digital ledger that records transactions across a network of computers, ensuring that records cannot be altered retroactively. It operates on three core principles: transparency, security, and immutability. Transactions are grouped into "blocks" and linked chronologically using cryptographic hashes, forming a "chain". Because it eliminates the need for central intermediaries like banks, it fosters peer-to-peer trust. While famously the backbone of cryptocurrencies, its applications extend to supply chains, healthcare, and voting systems, providing a robust framework for secure, verifiable data exchange.

Platform: Grok Ai
Blockchain Technology Summary Blockchain is a decentralized, distributed digital ledger that records transactions across a network of computers in a secure, transparent, and immutable way. Data is stored in "blocks" linked chronologically via cryptography, forming an unalterable "chain." Once added and validated through consensus mechanisms (like Proof of Work or Proof of Stake), records cannot be easily altered or deleted. Key features include decentralization (no single authority), transparency (all participants see the same data), security through cryptography, and traceability. Originally introduced with Bitcoin in 2008, it extends far beyond cryptocurrencies to applications in supply chain management, healthcare (secure records), finance (smart contracts), IoT, and more. While promising efficiency, trust, and reduced intermediaries, blockchain faces challenges like scalability, high energy use (in some models), and regulatory hurdles. It represents a foundational shift toward tamper-proof, peer-to-peer systems.

2.Few-shot Prompt: Prompt: Artificial Intelligence helps machines learn patterns from data. Summary: AI enables machines to learn from data.

Text: Blockchain is a decentralized ledger system used to record transactions securely across many computers.

Platform: Chatgpt
Blockchain is a secure distributed system for storing records. Information is organized into linked blocks that cannot be easily modified. It improves security, transparency, and efficiency in many industries such as banking and logistics.

Platform: Gemini
Summary: Blockchain is a decentralized, secure ledger for recording transactions across multiple computers.

Platform: Grok Ai
Summary: Blockchain is a decentralized ledger that securely records transactions across multiple computers.

3.Chain-of-Thought Prompt:

Prompt: Step 1: Identify the key concepts. Step 2: Identify the applications. Step 3: Identify the challenges. Step 4: Create a final summary for students.

Platform: Chatgpt
. Blockchain is a decentralized digital ledger. . Data is stored in blocks linked together. . Transactions are secure and transparent. . Information cannot be easily changed (immutability). . Security and privacy concerns . Regulatory and legal challenges . Blockchain is a decentralized and secure technology that stores transaction records in connected blocks across many computers. It improves transparency and trust and is used in finance, healthcare, and supply chains. However, challenges such as scalability, energy usage, and regulations still need improvement.

Platform: Gemini

Decentralization: A peer-to-peer network where no single entity has control. Immutability: Once data is recorded in a block, it cannot be altered without changing all subsequent blocks. Cryptography: The use of secure hashes to link blocks and verify transactions. Regulation: Legal uncertainties and the lack of a standardized global framework. Complexity: Technical barriers that make it difficult for the general public to adopt or understand. Blockchain is a secure, decentralized ledger technology that records data across a network, making it nearly impossible to hack or alter. By using cryptographic hashes to link blocks of information, it creates a transparent and immutable record. While widely known for powering digital currencies, its potential spans across various industries by removing the need for a central authority. For students, understanding blockchain is essential as it represents a fundamental shift in how digital trust and data integrity are maintained in the modern world.

Platform: Grok Ai

Decentralized Ledger*: A digital record book shared across many computers. No single person or company controls it. Blocks and Chain: Transactions are packed into blocks. These blocks are securely linked one after another like a chain. Immutability: Once information is added, it cannot be easily changed or deleted. Consensus: Special rules (like Proof of Work or Proof of Stake) help all computers agree on which transactions are correct Uses a lot of electricity (in some types) Slow speed when many people use it Rules and laws are still unclear Hard for normal people to understand and use Risk of losing private keys or network attacks It was first used for Bitcoin, but now it helps in tracking goods, automatic contracts, medical records, and more. Even though it has problems like high energy use and slow speed, blockchain is an important new technology that reduces the need for banks or middlemen and creates more trust online.

4.Role-based Prompt:

Prompt: "You are a teacher explaining blockchain to undergraduate students."

Platform: Chatgpt
Summary: Blockchain is like a shared digital notebook where many computers store the same information. Once data is recorded, changing it is difficult. This makes the system secure and useful for applications such as digital payments and record keeping.

Platform: Gemini
As a teacher, think of blockchain as a secure, shared digital ledger that records transactions across a network without a central authority. It uses "blocks" linked in a chronological "chain," ensuring data is transparent, permanent, and tamper-proof for students to trust.

Platform: Grok Ai
"Good morning, class! Blockchain is a shared digital ledger that records transactions across thousands of computers. Once data is added in secure 'blocks,' it cannot be changed. It’s decentralized, transparent, and trustworthy. Used in Bitcoin, supply chains, and smart contracts.

SUMMARY TABLE:

Platform	Accuracy	Coherence	Simplicity	Speed	User Experience
ChatGPT	5	5	4	5	5
Gemini	4	4	5	5	4
Grok Ai	5	4	4	4	4
RESULT: Successfully evaluated and compared the effectiveness of prompting techniques in different AI platforms to test the best balance of accuracy, coherence, simplicity, speed, and user experience for undergraduate-level text summarization
