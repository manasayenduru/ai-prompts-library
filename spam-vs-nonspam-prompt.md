# 📧 Spam vs Non-Spam Email Classifier

## Zero-Shot, One-Shot & Few-Shot Prompt Engineering System

---

## Overview

This prompt demonstrates how different prompting strategies (Zero-Shot, One-Shot, Few-Shot) affect classification accuracy in an email spam detection task.

It is designed for:

* Prompt engineering education
* LLM behavior comparison
* Classification system design
* AI workflow experimentation

---

## Task Definition

Classify an email into one of two categories:

* **Spam** → Unwanted, promotional, scam, or irrelevant email
* **Not Spam** → Legitimate, important, or personal email

---

# 🧪 1. ZERO-SHOT PROMPT

```text id="zs1"
Classify the following email as Spam or Not Spam.

Return only one label: "Spam" or "Not Spam".

Email:
{input_email}
```

### Behavior

* No examples provided
* Model relies purely on instruction understanding
* Baseline performance

---

# 🧪 2. ONE-SHOT PROMPT

```text id="os1"
Classify emails as Spam or Not Spam.

Example:

Email: "Congratulations! You have won a free iPhone. Click here to claim now."
Label: Spam

Now classify the following email:

Email: {input_email}
```

### Behavior

* One example guides pattern recognition
* Improves boundary clarity
* Reduces ambiguity

---

# 🧪 3. FEW-SHOT PROMPT

```text id="fs1"
Classify emails as Spam or Not Spam.

Examples:

Email: "Congratulations! You have won a free iPhone. Click here to claim now."
Label: Spam

Email: "Your bank account has been locked. Verify your identity immediately."
Label: Spam

Email: "Hi, just confirming our meeting is scheduled for 3 PM tomorrow."
Label: Not Spam

Email: "Please find attached the project report for your review."
Label: Not Spam

Now classify:

Email: {input_email}
```

### Behavior

* Multiple examples define stronger decision boundaries
* Higher consistency and accuracy
* Better handling of edge cases

---

# 📊 Comparison Summary

| Method    | Accuracy | Consistency | Context Understanding      | Best Use Case         |
| --------- | -------- | ----------- | -------------------------- | --------------------- |
| Zero-Shot | Medium   | Low         | Basic                      | Quick tasks           |
| One-Shot  | Good     | Medium      | Better pattern match       | Simple classification |
| Few-Shot  | High     | High        | Strong contextual learning | Production systems    |

---

# 🧠 Key Insight

* Zero-shot = instruction understanding only
* One-shot = pattern introduction
* Few-shot = behavior shaping through examples

---

# 🚀 Practical Applications

This pattern can be extended to:

* Email filtering systems
* Customer support routing
* Fraud detection
* Content moderation
* Inbox prioritization systems

---

# 📌 Prompt Engineering Principle

> The quality of classification improves not by changing the model, but by shaping the context through examples.


