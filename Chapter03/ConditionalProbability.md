# Conditional Probability 

## 📚 Content   
  1- [The Conditional Probability](##TheConditionalProbability)   
  2- [Key Rules](#KeyRules)   
  3- [Examples](#Examples)   

--- 

## 1️⃣ The Conditional Probability
**- Conditional probability** is the probability of an event occurring given that another event has already occurred. It is fundamental in probability theory and statistics, helping us refine predictions based on new information.  
    - **The formula for conditional probability is:**  
       $$P(A|B) = \frac{P(A ∩ B)}{P(B)}$$   
    - `P(A|B)`: Probability of event `A` occurring given event `B` has occurred.  
    
    - `P(A ∩ B)`: Probability of both `A` and `B` occurring.
    
    - `P(B)`: Probability of event `B` occurring.
--- 
## 2️⃣ Key Rules

### 1. Multiplication Rule  
- The probability of two events occurring together:  
   - P(A ∩ B) = P(B) * P(A|B)  
     **OR**
   - P(A ∩ B) = P(A) * P(B|A)

---
### 2. Law of Total Probability   
   - If `B1, B2, ..., Bn` form a partition of the sample space:
       - P(A) = Σ P(A|Bi) * P(Bi)

--- 
### 3. Bayes' Theorem
   - Bayes' theorem is used for reversing conditional probabilities:
       - P(A|B) = (P(B|A) * P(A)) / P(B)

--- 

### 4. Independent Events 
   - If `A` and `B` are independent, then:
       - P(A|B) = P(A)
       - P(B|A) = P(B)
--- 

## 3️⃣ Examples

### Example 1: Rolling a Die
What is the probability of rolling a `3` given that the outcome is an **odd number**?

**Solution:**
- The odd numbers on a six-sided die are `{1, 3, 5}`—so there are **3 possible outcomes**.
- The probability:
  
    - $$P(3 | Odd) = \frac{P(3 \cap Odd)}{P(Odd)} = \frac{1/6}{3/6} = \frac{1}{3}$$

---

### Example 2: Drawing Cards
A deck of 52 cards contains 26 red cards. What is the probability that a card is a **diamond**, given that it is **red**?

**Solution:**
- There are **26 red cards** (13 diamonds + 13 hearts).
- The probability:
  
   - $$P(Diamond | Red) = \frac{P(Diamond \cap Red)}{P(Red)} = \frac{13/52}{26/52} = \frac{13}{26} = \frac{1}{2}$$

---

### Example 3: Medical Diagnosis (Bayes’ Theorem)
A disease affects **3%** of a population. A medical test correctly detects the disease **90%** of the time, but incorrectly classifies a healthy person as positive **10%** of the time. What is the probability that a person **actually has the disease** given a **positive test result**?

 - Using **Bayes’ theorem**:

     - $$P(D | Positive) = \frac{P(Positive | D) \times P(D)}{P(Positive)}$$
  
     - $$P(D | Positive) = \frac{(0.90 \times 0.03)}{(0.90 \times 0.03) + (0.10 \times 0.97)}$$
  
     - $$P(D | Positive) = \frac{0.027}{0.027 + 0.097} = \frac{0.027}{0.124} \approx 0.2177$$
  
     - So, the probability that a person **actually has the disease given a positive test result is about 21.8%**.

---

### Example 4: Students and Subject Selection
In a class of **100 students**:
  - **40 students** study mathematics.
  - **30 students** study physics.
  - **20 students** study both mathematics and physics.
  - What is the probability that a randomly chosen student studies **physics**, given that they study **mathematics**?

**Solution:**
   - $$P(Physics | Mathematics) = \frac{P(Physics \cap Mathematics)}{P(Mathematics)}$$
   
   - $$P(Physics | Mathematics) = \frac{20/100}{40/100} = \frac{20}{40} = \frac{1}{2}$$
   
   - So, the probability is **50%**.

---
