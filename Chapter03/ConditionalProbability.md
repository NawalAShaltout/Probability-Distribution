# Conditional Probability 

## Outlines


## The Conditional Probability
**- Conditional probability** is the probability of an event occurring given that another event has already occurred. It is fundamental in probability theory and statistics, helping us refine predictions based on new information.  
    - **The formula for conditional probability is:**  
       $$P(A|B) = \frac{P(A ∩ B)}{P(B)}$$   
    - `P(A|B)`: Probability of event `A` occurring given event `B` has occurred.  
    
    - `P(A ∩ B)`: Probability of both `A` and `B` occurring.
    
    - `P(B)`: Probability of event `B` occurring.
--- 
## Key Rules
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


      

