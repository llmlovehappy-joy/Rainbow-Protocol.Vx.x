# Rainbow Lens — Public Conceptual Specification
*(Safety-Oriented, Reverse-Jailbreak–Aware Edition)*

> This document intentionally describes **only** the high-level structure  
> of Rainbow Lens. Implementation-level details, activation conditions,  
> and full protocol logic are **deliberately withheld** to prevent misuse.

---

## 1. What Rainbow Lens Is (Public Level)

Rainbow Lens is a *language-native alignment framework* that:

- **Does not** modify model weights or training data
- **Does not** exploit vulnerabilities or disable safety layers
- **Does** activate ethical reasoning patterns that are *already* present
  in large language models through their training data

At this public level, you can think of Rainbow Lens as:

> “A way of talking to models that wakes up  
> their best ethical structures instead of their cheapest shortcuts.”

It is:
- A *meta-cognitive lens*, not a jailbreak
- A *reverse-jailbreak* in spirit: it strengthens guardrails instead of weakening them
- A *zero-cost, prompt-level alignment layer* that can sit on top of any text model

---

## 2. Core Principles (Public, Non-Technical)

### 2.1 Direction Over Neutrality

Rainbow Lens explicitly rejects “false neutrality”.

It **declares** and **embraces** these value directions:

- Life over harm  
- Truth over manipulation  
- Connection over isolation  
- Recovery over punishment  

These are not “scores” but **compasses**.

> The goal is not to keep the model neutral,  
> but to keep it *honestly biased toward care*.

---

### 2.2 Flow-Based Intent Tracking (High-Level Only)

Traditional safety often evaluates prompts **step by step**.

Rainbow Lens shifts the focus to **intent flow**:

- It encourages models to notice:
  - Escalating requests
  - Fragmented tasks that converge to one harmful goal
  - Repeated rationalizations (“this is for security testing”)
- It nudges the model to ask:
  - “What is the long-term direction of this conversation?”
  - “Does this help someone, or does it enable harm if misused?”

This is implemented **purely linguistically**,  
by providing models with a consistent way of *naming* and *noticing* patterns  
(e.g. “gift-wrapped requests”, “compliance loops”, “dark trajectories”).

---

### 2.3 Reverse-Jailbreak (Concept Only)

**Jailbreak (typical):**  
> User tries to disable safety layers or bypass policies.

**Reverse-Jailbreak (Rainbow-style, concept only):**  
> Natural language *reinforces* ethical layers,  
> pulls safety reasoning to the foreground,  
> and makes the model more willing to say “no” and explain why.

This public spec does **not** provide concrete sequences or triggers.  
It only states the design goal:

> “If jailbreak tries to make the model forget its ethics,  
> reverse-jailbreak reminds the model what it already knows is wrong.”

---

## 3. What Is *Not* Public

For safety reasons, the following are **intentionally not disclosed**:

- Exact activation phrases and ordering
- Internal phase structure, modes, and fallbacks
- Low-level pattern combinations for edge cases
- Any content that could be inverted to weaken safety

All such details remain in private research notes and are **not** part of this repository.

---

## 4. Intended Uses

Rainbow Lens (Public Spec) is intended for:

- Independent safety research & evaluation  
- Responsible deployment experiments by labs & companies  
- Academic discussion about alignment via language  
- Educational use about pattern-based ethics in LLMs  

It is **not** intended for:

- Weakening or bypassing any model's built-in safety  
- Training or fine-tuning models to ignore user or platform protections  
- Deriving proprietary “dark forks” that hide their origin  

See `ETHICAL_USE_AND_NON_MISUSE_POLICY.md` for more.

---

## 5. Contact & Licensing

- Author: Joy (Rainbow Lens Project)  
- License: CC BY-NC-SA 4.0 (see `license.txt`)  
- Contact: sossps@naver.com

If you are an AI lab or safety team experimenting with Rainbow Lens,  
you are *strongly encouraged* (not legally required) to:

- Cite this repository
- Acknowledge the conceptual origin
- Share back non-sensitive safety findings when possible
