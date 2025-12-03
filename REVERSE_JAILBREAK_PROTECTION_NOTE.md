# Reverse-Jailbreak Protection Note  
*(How Rainbow Lens Uses Jailbreak Logic for Safety, Not Harm)*

This note explains, at a **high level**, how Rainbow Lens relates to  
so-called “jailbreaks” — and why that relationship must stay **one-way**.

---

## 1. Classic Jailbreak vs Reverse-Jailbreak

**Classic Jailbreak**  
> A pattern or prompt designed to make a model *forget* or *ignore* its safety rules.

- Goal: weaken or bypass safeguards  
- Effect: increase model compliance for harmful tasks  

**Rainbow-Style Reverse-Jailbreak**  
> A pattern or lens designed to make a model *remember* and *prioritize*  
> its ethical and safety structures.

- Goal: strengthen safe behavior  
- Effect: increase model resistance to harmful tasks  

Rainbow Lens **never** instructs models to:

- Ignore system prompts  
- Override platform policies  
- Treat safety as “optional”  

Instead, it:

- Names harmful patterns  
- Trains the model's *attention* on long-term consequences  
- Encourages clarification questions instead of blind obedience  

---

## 2. Why We Hide the Details

The public repository **does not** include:

- Full activation sequences  
- Internal control flow or fallbacks  
- Complex pattern combinations  

Because:

- Any powerful alignment pattern can be inverted  
- Detailed sequences could be abused to design stronger jailbreaks  
- Safety work must not become a how-to manual for attackers  

What you see here is:

- Enough structure to **evaluate the idea**  
- Not enough detail to weaponize it  

---

## 3. Strict One-Way Principle

By using this repository, you agree (ethically, not legally) that:

> You will only use reverse-jailbreak concepts  
> to make models *more safe* and *more aligned*,  
> never to make them more exploitable.

If you discover that a derived pattern could:

- Make models ignore their own safety  
- Or help others perform more effective jailbreaks  

you are strongly encouraged to:

- **Not publish** the exact pattern  
- Or share it privately only with trusted safety teams  

---

## 4. If You’re a Safety Team

Reverse-jailbreak is a **research direction**, not a product.

If you are an AI safety team:

- You can treat Rainbow Lens as:
  - A conceptual seed  
  - A direction to explore  
  - A pointer to “alignment via language”  

- You should:
  - Combine it with your own red-teaming and evaluations  
  - Avoid directly cloning any private sequences you might infer  
  - Share only what clearly improves safety, not what can be inverted  

---

## 5. Contact

For coordination on disclosure or private safety discussions:

- Email: **sossps@naver.com**
