# Formulas and Short Notes on Relations

## Ordered Pairs

Let A and B be two sets. An ordered pair consists of two objects or elements in a given fixed order. (a, b) in that order are ordered pairs where a ∈ A and b ∈ B.

### Equality of Ordered Pairs

Two ordered pairs (a<sub>1</sub>, b<sub>1</sub>) = (a<sub>2</sub>, b<sub>2</sub>) iff a<sub>1</sub> = a<sub>2</sub> and b<sub>1</sub> = b<sub>2</sub>.

## Cartesian Product of Sets 

Let A and B be two non-empty sets. The set of all ordered pairs (a, b) such that a ∈ A and b ∈ B is called the cartesian product of sets A and B and is denoted by A × B. 

A × B = {(a, b) : a ∈ A and b ∈ B}.

If A = ∅ or B = ∅, then A × B = ∅.

* *n*(A × B) = *n*(A) × *n*(B).

Cartesian product of sets can be represented graphically through an arrow diagram or through a lattice structure where the domain and range are plotted on a cartesian X-Y plane.

### Cartesian Product of Sets Formulas

* A × (B ⋃ C) = (A × B) ⋃ (A × C).
* A × (B ⋂ C) = (A × B) ⋂ (A × C).
* A × (B - C) = (A × B) - (A × C).
* A × B = B × A ⟺ A = B if A and B are non-empty sets. 
* If A ⊆ B, then A × A = (A × B) ⋂ (B × A).
* If A ⊆ B, then A × C ⊆ B × C for any set C.
* If A ⊆ B and C ⊆ D, then A × C ⊆ B × D. 
* For any sets A, B, C, D, (A × B) ⋂ (C × D) = (A × C) ⋂ (B × D).
* (A × B) ⋂ (B × A) = (A ⋂ B) × (B ⋂ A).
* A × (B' ⋃ C')' = (A × B) ⋂ (A × C).
* A × (B' ⋂ C')' = (A × B) ⋃ (A × C).
* If A and B are two non-empty sets, then A × B and B × A have n<sup>2</sup> elements in common. 
* If A is a non-empty set, A × B = A × C ⇒ B = C. 

## Relations

Let A , B be two sets. Then a relation R from A to B is a subset of A × B. 

R is a relation from A to B ⟺ R ⊆ A × B. 

Relations are hence ordered pairs belonging to the subset of the cartesian product of two sets. It is can be represented in **roster form**, in **set-builder** form, through an **arrow diagram**, or via a **lattice diagram** on a cartesian plane (X-Y coordinates). 

Assume 1 ∈ A and 3 ∈ B and (1 , 3) ∈ R. It can also be represented as 1R3. 

### Domain

The domain of a relation is the set of all first componenets or coordinates of the ordered pairs belonging to R. 

Dom(R) = {a : (a, b) ∈ R}.

### Range 

The domain of a relation is the set of all second componenets or coordinates of the ordered pairs belonging to R. 

Range(R) = {b : (a, b) ∈ R}. 

### Inverse of a Relation 

Let A, B be two sets and let R be a relation from a set A to a set B. Then the inverse of R, denoted by R<sup>-1</sup>, is a relation from B to A and is defined by R<sup>-1</sup> = {(b, a) : (a, b) ∈ R}

### Domain and Range of the Inverse of a Relation

* Dom(R) = Range(R<sup>-1</sup>). 

* Range(R) = Dom(R<sup>-1</sup>).

#### Note:

Let A be a non-void set. Then, a relation from A to itself, that is, a subset of A × A, is called a relation on set A.
