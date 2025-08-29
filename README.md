# EX-02-Cross-Platform-Prompting-Evaluating-Diverse-Techniques-in-AI-Powered-Text-Summarization

## AIM

To study and compare the performance of various prompting strategies (zero-shot, few-shot, chain-of-thought, and role-based) across multiple AI tools (ChatGPT, Gemini, Claude, Copilot) for the task of **text summarization**. The objective is to examine how each prompting style influences readability, simplicity, and accuracy when condensing technical information.

---

## Scenario

### Step 1: First Summarization

**Task:** Condense a 500-word article on *“The Basics of Blockchain Technology”* into 120–150 words suitable for undergraduate students. The output should be simple, clear, and easy to follow.

**Produced Summary:**
Blockchain is a digital record-keeping system that stores transactions securely and transparently across a network of computers. Unlike centralized systems, blockchain uses decentralization, meaning every participant shares and verifies the data. Each “block” contains transaction details, and the blocks connect together to form a tamper-proof “chain.” Its main characteristics are openness, immutability (records cannot be changed), and safety. Initially created for Bitcoin, blockchain now supports many areas such as finance, supply chain monitoring, and digital identity. It is important because it builds trust among users without the need for middlemen. For students, learning blockchain is essential since it powers many new technologies in finance, governance, and innovation.

---

### Step 2: Simplified & Example-Based Summarization

**Task:** Make the summary easier to understand and add at least two real-world examples of blockchain use.

**Updated Summary:**
Blockchain works like a digital diary that is shared across many computers. Once something is written in it, it cannot be erased or modified, which makes it secure and reliable. Instead of being controlled by one authority, everyone in the network checks and confirms the records, ensuring transparency. The first major use of blockchain was Bitcoin, a digital money system that works without banks. Today, it is also used in supply chains, for instance, to track food from farms to shops, and in healthcare, where patient details can be stored safely and accessed only with permission. Overall, blockchain builds confidence and accuracy in systems where safety and trust are crucial.

---

## Algorithm

1. **Provide Input**: A 500-word article (“The Basics of Blockchain Technology”).
2. **Apply Prompting Styles**:

   * **Zero-Shot Prompting** → Directly request a summary.
   * **Few-Shot Prompting** → Give sample summaries and then ask for another.
   * **Chain-of-Thought Prompting** → Ask the AI to show reasoning before creating the summary.
   * **Role-Based Prompting** → Instruct the AI to act as a *teacher* explaining to undergraduates.
3. **Assess Output** on the basis of:

   * Clarity
   * Simplicity
   * Correctness
   * Use of real-world examples
4. **Refine Output**: Adjust the summary to make it easier to read and add practical applications.
5. **Cross-Platform Testing**: Use the same prompts in ChatGPT, Gemini, Claude, and Copilot, then compare tone, clarity, and accuracy.

---

## Result

<img width="1536" height="672" alt="Gemini_Generated_Image_pju1zjpju1zjpju1" src="https://github.com/user-attachments/assets/06971e30-cdb8-4b3f-940c-dda42e1d1625" />


---
