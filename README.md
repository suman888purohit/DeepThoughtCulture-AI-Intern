# DeepThoughtCulture-AI-Intern
# 🌳 Daily Reflection Decision Tree

## 📌 Overview

This project is a deterministic reflection system designed to help employees analyze their day through a structured sequence of questions.

The system uses a decision-tree approach where:
- Each question has fixed options
- Each option leads to a predefined path
- The same inputs always produce the same outputs

The goal is to guide users toward self-awareness without using AI at runtime.

---

## 🧠 Core Concept

The reflection flow is built around three psychological axes:

### 1. Locus (Control)
- Internal (taking responsibility)
- External (blaming circumstances)

### 2. Contribution (Giving vs Expecting)
- Contribution mindset
- Entitlement mindset

### 3. Radius (Self vs Others)
- Self-focused thinking
- Broader perspective (team, colleagues, customers)

---

## 🌲 Tree Structure

The system follows this flow:

Start → Axis 1 → Axis 2 → Axis 3 → Summary → End

- Axis 1 analyzes control and response to situations  
- Axis 2 evaluates contribution and mindset toward work  
- Axis 3 expands perspective beyond self  

---

## 📂 Project Files

- `reflection-tree.tsv` → Main decision tree structure  
- `tree-diagram.png` → Visual flow of the tree  
- `write-up.md` → Design explanation and reasoning  

---

## ⚙️ How It Works

- The tree is fully deterministic  
- No AI or LLM is used at runtime  
- All logic is encoded in structured data  
- Reflections are predefined and triggered based on user choices  

---

## 🤖 Use of AI

AI tools were used only during the design phase to:
- Explore question ideas  
- Improve clarity of options  
- Validate logical flow  

The final system itself does not depend on AI.

---

## 🔒 Guardrails Against Hallucination

- No runtime AI usage  
- Fixed decision paths  
- Predefined reflections  
- Structured data ensures consistency  

---

## 🚀 Future Improvements

- Add deeper branching for personalization  
- Improve summary using accumulated signals  
- Build a CLI or web-based interface  

---

## 📎 Submission

This repository contains Part A of the assignment (Deterministic Decision Tree).

Voice note submission is shared separately via Google Drive link.

---

## 🙌 Conclusion

This project demonstrates how structured thinking and psychological concepts can be transformed into deterministic systems that guide meaningful reflection.
