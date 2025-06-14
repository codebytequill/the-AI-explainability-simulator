# AI Explainability Simulator

### [View the Live Demo](https://github.com/codebytequill/the-AI-explainability-simulator)

---

## Project Overview

This project is an interactive web application that demonstrates the critical difference between an opaque "Black Box" AI and a transparent "Glass Box" AI.

Using the relatable scenario of a loan application review, users can select a sample applicant and run their profile through two distinct AI systems. The Black Box provides only a final decision ("Approved" or "Denied"), while the Transparent AI provides the same decision along with the specific reasons that contributed to the outcome.

## Purpose & Significance

In the age of automated decision-making, the "why" is as important as the "what." This project was built to advocate for user trust and transparency, two of the most important pillars of Ethical AI. As an aspiring Ethical AI Product Manager, I believe that for users to trust a system, they must have some level of understanding and recourse.

This simulator makes the abstract concept of **Explainable AI (XAI)** tangible and immediately understandable to any audience, technical or not. It demonstrates a commitment to:

* **User Advocacy:** Championing the user's right to an explanation for decisions that impact their lives.
* **Communicating Complexity:** Distilling a core technical challenge of AI into a simple, clear, and persuasive user experience.
* **Product Experience Design:** Showing how the *presentation* of information is a critical part of an ethical and effective product.

## Features

* **Interactive Applicant Profiles:** Users can select from multiple pre-defined applicant scenarios with different financial attributes.
* **Side-by-Side Comparison:** The UI is designed to directly contrast the output of the Black Box and Transparent AI models for maximum clarity.
* **Visual Feedback:** The Transparent AI uses clear, color-coded visual cues to show which criteria passed or failed, making the explanation instantly scannable.
* **Rule-Based Logic:** The "AI" is powered by a simple, clear set of rules in JavaScript, demonstrating the core concept without the need for a complex machine learning model.

## Technology Stack

This application is built entirely with front-end technologies, ensuring it is lightweight, accessible, and easy to understand.

* **HTML5:** Provides the semantic structure for the content.
* **CSS3:** Used for all custom styling, layout (using Grid), and creating the distinct visual identities for the "black box" and "transparent" outputs.
* **Vanilla JavaScript:** Powers all the application's logic, including state management for the selected applicant, the rule-based AI engine, and dynamic DOM manipulation to render the results.

This is a zero-dependency, single-file application.
