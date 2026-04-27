# Daily Reflection Decision Tree – Write-up

## 1. Overview

This project is a deterministic reflection tool designed to help employees analyze their day through a structured sequence of questions. The system follows a decision-tree approach where each answer leads to a predefined next step, ensuring consistency, predictability, and clarity.

The goal of the system is not to judge the user, but to guide them toward greater self-awareness by reflecting on their actions, mindset, and perspective.

---

## 2. Design Approach

I designed the tree as a guided conversation rather than a survey. The flow begins with a simple, intuitive question about the user’s day and gradually moves deeper into their behavior and thought patterns.

The structure is organized around three psychological axes:
1. Locus (Control)
2. Contribution (Giving vs Expecting)
3. Radius (Self vs Others)

Each axis builds on the previous one, creating a natural progression from personal awareness to broader perspective.

---

## 3. Axis Design

### Axis 1: Locus (Victim vs Victor)

This axis is based on the concept of Locus of Control.

The questions are designed to identify whether the user:
- Sees themselves as having control over outcomes (internal locus)
- Attributes outcomes primarily to external factors (external locus)

Example:
- “I adapted” → internal path
- “I felt stuck” → external path

The reflection gently highlights the user’s level of agency without assigning blame, encouraging awareness rather than judgment.

---

### Axis 2: Contribution (Giving vs Entitlement)

This axis explores whether the user’s focus was on:
- Contributing to others
- Expecting recognition or focusing on what they received

The questions encourage reflection on behaviors such as:
- Helping teammates
- Taking initiative beyond assigned tasks
- Attitude toward collaboration

The reflection emphasizes the importance of contribution while maintaining a neutral and supportive tone.

---

### Axis 3: Radius (Self vs Others)

This axis measures the breadth of the user’s perspective.

It identifies whether the user’s thinking was:
- Self-focused
- Or inclusive of team members, colleagues, or customers

The goal is to gently expand awareness beyond self-centered thinking and encourage a more outward, purpose-driven perspective.

---

## 4. Branching Logic

The system uses fully deterministic branching:
- Each question has fixed options
- Each option maps to a predefined path

A decision node is used after the first question:
- “Productive/Mixed” → routes to an agency-focused path
- “Tough/Frustrating” → routes to a challenge-focused path

This ensures:
- Consistent outputs for identical inputs
- Transparency and auditability of the system

---

## 5. Reflection Design

Each reflection is crafted to:
- Be neutral and non-judgmental
- Encourage self-thinking rather than provide instructions
- Feel like a conversation rather than an evaluation

The tone is intentionally calm and reflective, helping the user think without feeling judged.

---

## 6. Trade-offs

During design, I made the following trade-offs:

- **Simplicity over complexity:**  
  Limited the number of questions to avoid overwhelming the user.

- **Clarity over depth:**  
  Focused on clear and understandable flows rather than covering every possible scenario.

- **Determinism over flexibility:**  
  Avoided free-text input to maintain structure, consistency, and reliability.

---

## 7. What I Would Improve

With more time, I would:
- Add deeper branching for more personalized experiences
- Use accumulated signals to generate more contextual summaries
- Refine reflections based on multiple prior answers
- Build a working interface (CLI or web-based) for interaction

---

## 8. Conclusion

This decision tree demonstrates how abstract psychological concepts can be translated into structured, navigable systems. By guiding users through fixed but meaningful choices, the tool enables consistent and insightful reflection.

The project highlights the ability to design deterministic systems that support human thinking without relying on AI at runtime.