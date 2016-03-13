# dismathportfolio-BNDNic
dismathportfolio-BNDNic created by Classroom for GitHub

##Week 1

#####Orientation

- I was introduced to the course Discrete Mathematics (DISMATH).
- Some applications were introduced and we had an example of what to expect from the course because of the Knights and Knaves problem. 

#####Logical Operations

| Logical Symbol  | Logical Operator      | Short Hand  | Logical Expression  |
| :---------------: |:---------------------:| :----------:|:--------------------:|
|   ¬     | Negation              | not         | ¬p    |
|   ∧     | Conjunction           | and         | p ∧ q |
|  v    | Disjunction           | or          | p v q  |
|   ⊕     | Exclusive Disjunction | xor         | p ⊕ q |
|   →     | Conditional           | if, then    | p → q |
|  ↔     | Biconditional         | iff         | p ↔ q |

#####Truth Table

- Truth table using T (True) and F (False)

| p | q | p ∧ q | p v q | p ⊕ q | p → q | p ↔ q |    
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| F | F | F | F | F | T | T |
| F | T | F | T | T | T | F |
| T | F | F | T | T | F | F |
| T | T | T | T | F | T | T |

- Truth table using 1 (True) and 0 (False)

| p | q | p ∧ q | p v q | p ⊕ q | p → q | p ↔ q |    
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
| 0 | 0 | 0 | 0 | 0 | 1 | 1 |
| 0 | 1 | 0 | 1 | 1 | 1 | 0 |
| 1 | 0 | 0 | 1 | 1 | 0 | 0 |
| 1 | 1 | 1 | 1 | 0 | 1 | 1 |

######Propositional Logic

I learned that when p → q, 
- its q → p is called converse
- its ¬p → ¬q is called inverse
- and its ¬q → ¬p is called contrapositive

##Week 2

#####Logical Equivalences

- I learned about the 10 Logical Equivalences that are used to simplify complicated logical expressions.

The 10 Logical Equivalences are:
- Identity Law
- Domination Law
- Idempotent Law
- Negation Law
- Double Negation Law
- Commutative Law
- Associative Law
- Distributive Law
- De Morgan's Law
- Absorption Law

##Week 3

- The discussion about logical equivalences was continued.
- Existential and Universal quantifiers were introduced to us.
- We were also introduced to a statement which is always true and it is called a Tautology 

##Week 4

#####Rules of Inference

- The class was given the assignment about proving if Superman exists and the rules of inference was what we were supposed to use in answering the assignment.
- It is also used in proving or testing the validity of a given argument.

The Rules of Inference are:
- Modus Ponens
- Modus Tollens
- Hypothetical Syllogism
- Disjunctive Syllogism
- Addition
- Simplification
- Conjunction
- Resolution

#####Methods of Proof

- We were introduced to the Methods of Proof.

The Method of Proof that was discussed is:
- Direct Proof
  1. Assume p is TRUE
  2. Show that q is also TRUE based on step 1

##Week 5

#####Methods of Proof

The next Method of Proof that were discussed are:
- Proof by Contraposition (Indirect)
  1. Assume ¬q ≡ T
  2. Show that ¬p is also TRUE based on step 1 
- Vacuous and Trivial Proof
  1. If ¬p is FALSE then p→q must be TRUE 
    ¬p
    ∴p→q
  2. If q is TRUE then p→q must also be TRUE 
    q
    ∴p→q
- Proof by Contradiction
  1. Assume that the Premise is NOT TRUE
  2. Show that step 1 will end up in a Contradiction
- Proof by Equivalence
  1. p ↔ q ≡ (p → q) → (q → p)

##Week 6

- The lesson about proving was continued and more examples were given to our class to help us understand more on proving statements and premises.

#####Mathematical Induction 

- Mathematical Induction was introduced to us this week.
- The Basis Step is proving the given statement for the first natural number.
- The Inductive Step is proving that the given statement for any one natural number implies the given statement for the next natural number.

##Week 7

- Mathematical induction examples were given to us just like prove P(n) = 1+3+5+...+(2n+1) = n^2
- Recursive/Inductive Definition was also introduced to us, this is not anymore a proof but it still has a basis step and a recursive step.
- An algorithm that solves a problem by reducing it to an instance of the same problem with smaller input is called a Recursive Algorithm.
- Program correctness and Program verification were also taught to the class.
- And power series was introduced to the class.

##Week 8

- Functions, also called mappings or transformations was discussed to us.
- Domain and Range were discussed to the class.
- Range and Codomain were compared and differentiated.

#####Types of Functions

1. One-to-one Function (injective)
-  This is a function that never assign the same value to two different domain elements.
2. Onto Function (surjective)
- This is a function with equal range and codomain.
3. One-to-one correspondence (bijection).

- Algorithm was introduced to the class.
- A high-level description of an algorithm that uses the structural conventions of a programming language is called a pseudo code, and it is intended for human reading.

#####Preconditions and Postconditions

- Preconditions and postconditions were also taught to the class. 
- Preconditions are statements that describe valid input. 
- Postconditions are conditions that the output should satisfy.

- The properties of algorithm are:
1. Input
2. Output
3. Definitness
4. Correctness
5. Finitness
6. Generality

- Two ways of searching algorithms were taught to us. 
- The linear search sample program is a one by one search tool. 
- Binary search algorithm is a little faster than linear search.

##Week 9

- Binary search was discussed to the class.
- Iteration is needed when we are doing pseudo codes and it is a big help if we want to make sure that what we are doing is correct.
- Bubble sort algorithm was taught to the class. It sorts numbers according to order and this is arranged by comparing adjacent elements.
- Insertion sort algorithm was discussed. The first element and the second element are compared to one another and if the second element is smaller than the first element, place it before the first element. This goes on until everything is arranged.
- Greedy Algorithm was discussed. At each step, it selects the best choice.
- And growth of functions was discussed. This is described using the Big-O notation.
