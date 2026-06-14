# Prompt Engineering Internship – Week 1 Project 3

## Context-Anchored Answering (RAG Basics)

### Overview

This project demonstrates the principles of Retrieval-Augmented Generation (RAG) by forcing an LLM to answer questions only from a provided reference document.

The system operates as a Closed-Book AI and must never use outside knowledge.

---

## Objective

To prevent hallucinations by restricting the model to a provided reference text and requiring citations for every answer.

---

## Prompt Engineering Techniques Used

### 1. Context Injection

A reference document is supplied inside the prompt.

### 2. Negative Constraints

If the answer is not present in the reference text, the model must reply:

Information Not Found

### 3. Citation Enforcement

Every answer must include the paragraph number from the source document.

### 4. Hallucination Prevention

The model is forbidden from using external knowledge.

---

## Files Included

* Instruction.txt
* Prompt_Text.txt
* Reference_Document.txt
* Example1_Question.txt
* Example1_Answer.txt
* Example2_Question.txt
* Example2_Answer.txt
* Final_Test_Question.txt
* Final_Test_Answer.txt

---

## Conclusion

This project demonstrates how context anchoring and strict constraints improve factual accuracy and reduce hallucinations in AI systems.
