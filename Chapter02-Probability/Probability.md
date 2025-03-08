# 🎲 Fundamental Concepts of Probability 🎲
 - This section provides an overview of the fundamental concepts of probability, including sample space, events, and various probability relations.

---
## 📚 Content   
  1- [Sample Space](##1.SampleSpace(S))   
  2- [Events](#introduction)   
  3- [Probability theory](#introduction)   
  4- [Probability Rules](#introduction)    
  6- [Examples](#introduction)   

---
### 1. 🌐 Sample Space (S)
  - The sample space is the set of all possible outcomes of an experiment.
  - **Example 01 : Flipping a Coin**
    - If you flip a fair coin, the sample space consists of two possible outcomes:
    
            S = {H, T}
    
  - **Example 02: Rolling a Die**
    - If you roll a fair six-sided die, the sample space consists of six possible outcomes:

           S = {1, 2, 3, 4, 5, 6}

  ---
             
### 2. 🎯 Event (E)
             
  - An event is a subset of the sample space, consisting of one or more outcomes. For instance, getting a Heads in a coin toss is an event.
  - **Example: Flipping a Coin**
    - If you are interested in the event of getting heads when flipping a coin, the event **A** can be represented as:

          A = {H}
    
  - **Example: Rolling a Die**
    - If you are interested in the event of rolling an even number, the event **B** can be represented as:
          
          B = {2, 4, 6}

---

### 3. 📊 Probability of Event (P(A))
  - Probability measures the likelihood of an event occurring. 
  - It is calculated by dividing the number of favorable outcomes **(E)** by the total number of possible outcomes **(S)**:

$$P(E) = \frac{\text{Number of favorable outcomes **(E)**}}{\text{Total number of possible outcomes **(S)**}}$$    

$$P(E) = \frac{|E|}{|S|}$$

  - **Example: Probability of A**
    - $$P(A) = \frac{|A|}{|S|}$$
      
    - $$P(A) = \frac{1}{2} = 0.5$$

  - **Example: Probability of B**
    - $$P(B) = \frac{|B|}{|S|}$$
      
    - $$P(B) = \frac{3}{6} = 0.5$$

  - **Example 03:**
    -  What is the probability of rolling a sum of 7 with two six-sided dice?
     - **Answer:**
       - A --> The combinations to get a sum of 7. **A=** $${(1,6), (2,5), (3,4), (4,3), (5,2),(6,1)}$$.
       - **(S)** $$= 6*6 =36$$.
       - $$P(A)= \( \frac{6}{36} = \frac{1}{6} \)$$.
      
   - **Example 04:**
     - In a class of 20 students, 12 students like math, and 8 like science. If a student is randomly selected, what is the probability that the student likes science ?
      - **Answer:**
        - A --> the student likes science. **|A|** = 8
        - $$P(A) = \( \frac{8}{20} = \frac{4}{10} \)$$.

   - **Example 05:**
     - A box contains 5 red and 3 blue marbles. If two marbles are drawn without replacement, what is the probability that both marbles are red?
      - **Answer:**
        - The probability of drawing the first red marble is **$$P(R1)= \( \frac{5}{8} \)$$**.
        - After drawing the first red marble, there are now 4 red marbles left out of 7 total marbles. So, the probability of drawing the second red marble is **$$P(R2)= \( \frac{4}{7} \)$$**.
        - The probability of both events occurring is
              - $$\( \frac{5}{8} \times \frac{4}{7} = \frac{20}{56} = \frac{5}{14} \)$$.

---
### 4. 📈 AXIOMS OF PROBABILITY
   **1. Non-Negativity Rule**
     - The probability of any event is always between 0 and 1:  
     - **$$\[0 \leq P(E) \leq 1\]$$**     
       - $$\( P(E) = 0 \)$$: The event is impossible. 
       - $$\( P(E) = 1 \)$$: The event is certain.

   **2. Total Probability Rule**
     - The sum of probabilities of all outcomes in the sample space $$\( S \)$$ is 1:  
       - $$\[P(S) = 1 \]$$

   **3. Addition Rule**          
     - For any two events $$\( A \) and \( B \)$$:    
          - $$\[P(A \cup B) = P(A) + P(B) - P(A \cap B)\]$$    
     - If $$\( A \) and \( B \)$$ are **mutually exclusive** (cannot happen simultaneously):   
          - $$\[P(A \cup B) = P(A) + P(B)\]$$  

   **4. Multiplication Rule**    
     - For two events $$\( A \) and \( B \)$$:    
         - If \( A \) and \( B \) are **independent**: $$\[P(A \cap B) = P(A) \cdot P(B)\]$$    
         - If \( A \) and \( B \) are **dependent**: Use conditional probability:  $$\[P(A \cap B) = P(A|B) \cdot P(B)\]$$  
    
   **5. Complement Rule** 
     - The probability of an event $$\( A \)$$ not occurring (complement of \( A \)) is:  
        - $$\[P(A^c) = 1 - P(A)\]$$

  ---

  ### Rules Example01 : 
  - Given the universal set and subsets:
    - Universal Set (\( S \)): {1, 2, 3, 4, 5, 6}
    - Subset \( A \): {1, 2}
    - Subset \( B \): {2, 4, 5}
    - Subset \( C \): {1, 5, 6}
 - Find the following:
    - 1. Complement of **A**
         - $$\[P(A^c) = 1 - P(A)\ = 1 - \frac{2}{6}]$$

 ---
 ### **Example 02**
   - A random sample of 500 people was taken from the 2010 United States Census. Their marital status and race were recorded in the following contingency table using the census labels. A person is randomly chosen from the census data. Find the following.

| Marital Status | American Indian | Black | Asian | White | Two Major Races | Total |
|----------------|------------------|-------|-------|-------|-----------------|-------|
| Divorced       | 0                | 6     | 1     | 30    | 1               | 38    |
| Married        | 1                | 25    | 23    | 156   | 4               | 209   |
| Single         | 2                | 33    | 21    | 155   | 11              | 222   |
| Widowed        | 0                | 7     | 2     | 22    | 0               | 31    |
| Total          | 3                | 71    | 47    | 363   | 16              | 500   
  

   - **a) $$\( P(\text{Single} \cap \text{American Indian}) \)$$ ?**
     
       -The probability that a person is both Single and American Indian is calculated as:
     
       - $$\[ P(\text{Single} \cap \text{American Indian}) = \frac{\text{Number of Single and American Indian}}{\text{Total number of people}} = \frac{2}{500} = 0.004 \]$$

  - **b) $$\( P(\text{Single} \cup \text{American Indian}) \)$$**

      - The probability that a person is either Single or American Indian (or both) is calculated using the union formula:
   
      - $$\[ P(\text{Single} \cup \text{American Indian}) = P(\text{Single}) + P(\text{American Indian}) - P(\text{Single} \cap \text{American Indian}) \]$$
   
      - $$\[ P(\text{Single}) = \frac{222}{500} = 0.444 \]$$
   
      - $$\[ P(\text{American Indian}) = \frac{3}{500} = 0.006 \]$$
   
      - $$\[ P(\text{Single} \cup \text{American Indian}) = 0.444 + 0.006 - 0.004 = 0.446 \]$$
   
 - **c) Probability that the person is Asian or Married?**
   
     - The probability that a person is either Asian or Married is calculated using the union formula:
  
     - $$\[ P(\text{Asian} \cup \text{Married}) = P(\text{Asian}) + P(\text{Married}) - P(\text{Asian} \cap \text{Married}) \]$$
  
     - $$\[ P(\text{Asian}) = \frac{47}{500} = 0.094 \]$$
  
     - $$\[ P(\text{Married}) = \frac{209}{500} = 0.418 \]$$
  
     - $$\[ P(\text{Asian} \cap \text{Married}) = \frac{23}{500} = 0.046 \]$$
  
     - $$\[ P(\text{Asian} \cup \text{Married}) = 0.094 + 0.418 - 0.046 = 0.466 \]$$
  
 - **d) $$\(P(\text{Single} \cap \text{Married})\)$$**
   
     - The probability that a person is both Single and Married is 0 since this is impossible.
     - $$\[ P(\text{Single} \cap \text{Married}) = 0 \]$$

 - **e) $$\( P(\text{Single} \cup \text{Married}) \)$$**
   
     - The probability that a person is either Single or Married is calculated using the union formula:
  
     - $$\[ P(\text{Single} \cup \text{Married}) = P(\text{Single}) + P(\text{Married}) - P(\text{Single} \cap \text{Married}) \]$$
  
     - $$\( P(\text{Single} \cap \text{Married}) = 0 \)$$
  
     - $$\[ P(\text{Single}) = \frac{222}{500} = 0.444 \]$$
  
     - $$\[ P(\text{Married}) = \frac{209}{500} = 0.418 \]$$
  
     - $$\[ P(\text{Single} \cup \text{Married}) = 0.444 + 0.418 = 0.862 \]$$
  
  ---
     
   
  
