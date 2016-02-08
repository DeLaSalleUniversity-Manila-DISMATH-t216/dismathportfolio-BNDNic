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
- Double Negation Law
- Commutative Law
- Associative Law
- Distributive Law
- De Morgan's Law
- Absorption Law
- Negation Law

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

##Week 3

#####Methods of Proof

- We were introduced to the Methods of Proof.

The Methods of Proof are:
- Direct Proof
  1. Assume p is TRUE
  2. Show that q is also TRUE based on step 1
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

##Week 4

#####Methods of Proof 

- Proof by Equivalence
  1. p ↔ q ≡ (p → q) → (q → p)

#####Mathematical Induction 

- The Basis Step is proving the given statement for the first natural number.
- The Inductive Step is proving that the given statement for any one natural number implies the given statement for the next natural number.
