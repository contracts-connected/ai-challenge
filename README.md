# Technical Test – AI Contract Risk Analysis Agent

## Objective

This test challenges you to build a small AI-powered system capable of analyzing contract documents and identifying
potential risks. The goal is to evaluate your ability to design a lightweight AI pipeline, implement document processing
logic, and deliver a minimal but functional user interface.

This assessment is designed to be completed in **no more than 4 hours**.

---

## What You Need to Build

### 1. Contract Risk Detection Agent

Create an AI-driven process (or rule-based hybrid) that can:

* Read an uploaded contract (PDF or text)
* Extract relevant clauses or sections
* Detect potential risks such as:

    * Missing insurance requirements
    * Uncapped liability
    * Vague payment terms
    * Broad indemnification clauses
    * Missing termination terms
    * Ambiguous scope of work
* Return:

    * A list of identified risks
    * A brief explanation for each risk
    * *(Optional bonus)* Suggested remediation or revision

**You may use any programming language or AI framework.**

---

### 2. Simple User Interface

Build a minimal UI that allows the evaluator to:

* Upload a contract file
* Trigger the analysis
* View the results clearly

The UI can be simple (even a single-page form), but it must:

* Accept a file upload
* Display the list of detected risks and explanations
* Handle errors gracefully

Any stack is acceptable (React, Vue, Next.js).

---

## Deliverables

You must submit:

1. **Repository link** (GitHub, GitLab, etc.) containing:

    * Source code
    * README with setup instructions and architecture overview
2. **Working version:** local runnable project, Dockerized service, or hosted demo.
3. **Short technical note** explaining your approach, assumptions, limitations, and what you would improve with more
   time.

---

## Evaluation Criteria

Your submission will be evaluated based on the following:

### Technical Implementation (40%)

* Code clarity, structure, and maintainability
* Good use of LLMs and parsing logic
* Accuracy of risk detection

### User Interface (20%)

* Ease of use
* Clear presentation of results

### Reasoning Quality (20%)

* Quality and relevance of explanations
* Ability to justify findings

### Product Thinking (20%)

* Practicality and usability of the solution
* Extensibility for real-world usage

---


Good luck, and we look forward to reviewing your submission!
