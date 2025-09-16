# Mathematical Formulas for Sets 

## Special Sets 

Some special sets have designated representation symobology. 

* *N* : for the set of natural numbers.
* *Z* : for the set of all integers.
* *Z<sup>+</sup>* : for the set of all positive integers.
* *W* : for the set of all whole numbers.  
* *Q* : for the set of all rational numbers.
* *Q<sup>+</sup>* : for the set of all positive rational numbers.
* *R* : for the set of all real numbers.
* *R<sup>+</sup>* : for the set of all positive real numbers. 
* *C* : for the set of all complex numbers.
* ∅ : for the set containing no elements, also called the empty set. 

## Two forms of sets

Sets can be represented in Roster form (also called Tabular form) or in Set-builder form. 

Example of Roster form of all vowels in Engglish: {a, e, i, o, u}

Example of Set-builder form of all positive even numbers: {x : x = 2n, n ∈ *N*}

## Set symbology 

* ∈ : Belongs to; a ∈ A ⇒ element a is in set A. 
* ∉ : Not Belongs to; a ∉ A ⇒ element a is not in set A.
* ⊆ : Subset Equal ; A ⊆ B iff a ∈ A ⇒ a ∈ B. 
* ⊂ : Proper subset'
* *n* : Number of elements in a set; *n*(A) is the number of elements in set A.

## Some Results on Subsets

* Every set is a subset of itself.
* The empty set is a subset of every set. 
* The total number of subsets of a finite set containing *n* elements is 2<sup>*n*</sup>. 
* **Two sets A and B are equal if A ⊂ B and B ⊂ A**. In other words, all elements of set A must be in B and all elements of set B must be in set A.
* Two sets are **equivalent** if their cardinal numbers are the same, i.e., *n*(A) = *n*(B)

## Intervals as Subsets of *R*

* [a,b] = {x ∈ *R* : a ≤ x ≤ b} ; square brackets for closed interval.
* (a,b) = {x ∈ *R* : a < x < b} ; round bracket for open interval. 

## Power Sets

Let a be a set. Then the collection or family of all subsets of A is called the power set of A and is denoted by *P*(A).

*P*(A) = {S : S ⊂ A}

## Operation on Sets

### Union of Sets

Let A and B be two sets. The union of A and B is the set of all those elements which belong either to A or to B or both to A and B. 

This is represented as A ⋃ B = {x : x ∈ A **or** x ∈ B}

### Intersection of Sets

Let A and B be two sets. The intersection of A and B is the set of all those elements that belong to both A and B.

This is represented as A ⋂ B = {x : x ∈ A **and** x ∈ B}

### Disjoint Sets

Two sets A and B are said to be disjoint if A ⋂ B = ∅, that is, there are no common elements between the two sets. 

### Difference of Sets

Let A and B be two sets. The difference of A and B, written as A - B, is the set of all those elements of A which do not belong to B. 

A - B = {x : x ∈ A and x ∉ B}

### Symmetric Difference of Two Sets

Let A and B be two sets. The symmetric difference of sets A and B is the set (A - B)⋃(B - A) and is denoted by A Δ B.

### Complement of a Set

Let *U* be the universal set and let A be a set such that A ⊂ *U*. Then the complement of A with respect to U is denoted by A' or A<sup>c</sup> or *U* - A.

## Laws of Algebra of Sets

### Idempotent Laws

For any set A: A ⋃ A = A ;  A ⋂ A = A.

### Identity Laws

For any set A: A ⋃ ∅ = A ; A ⋂ *U* = A.

### Commutative Laws

For any set A and B.

* A ⋃ B = B ⋃ A
* A ⋂ B = B ⋂ A

### Associative Laws

If A, B, and C are any three sets, then 

* (A ⋃ B) ⋃ C = A ⋃ (B ⋃ C)
* A ⋂ (B ⋂ C) = (A ⋂ B) ⋂ C

### Distributive Laws

If A, B, and C are any three sets, then 

* A ⋃ (B ⋂ C) = (A ⋃ B) ⋂ (A ⋃ C)
* A ⋂ (B ⋃ C) = (A ⋂ B) ⋃ (A ⋂ C) 

that is, union and intersection are distributive over intersection and union respectively. 

### De-Morgan's Laws

If A and B are any two sets, then

* (A ⋃ B)' = A' ⋂ B'
* (A ⋂ B)' = A' ⋃ B'

## Operation on Sets Formulas

* A - B = A ⋂ B'
* B - A = B ⋂ A'
* A - B = A ⟺ A ⋂ B = ∅
* (A - B) ⋃ B = A ⋃ B
* (A - B) ⋂ B = ∅
* A ⊆ B ⟺ B' ⊆ A'
* A - (A ⋂ B) = A - B
* (A - B) ⋃ (B - A) = (A ⋃ B) - (A ⋂ B)

### Some More Set Formulas

* (A ⋂ B) ⋃ (A - B) = A
* (A ⋃ B) - A = B - A
* A - (B ⋃ C) = (A - B) ⋂ (A - C)
* A - (B ⋂ C) = (A - B) ⋃ (A - C)
* (A ⋃ B) - C = (A - C) ⋃ (B - C)
* (A ⋂ B) - C = (A - C) ⋂ (B - C)
* A - (B - C) = (A - B) ⋃ (A ⋂ C)
* A ⋂ (B - C) = (A ⋂ B) - (A ⋃ C)
* A ⋂ (B Δ C) = (A ⋂ B) Δ (A ⋂ C)

### Number of Elements in a Set Formulas 

These formulas pertain to finite sets

* *n*(A ⋃ B) = *n*(A) + *n*(B) - *n*(A ⋂ B)
* *n*(A ⋃ B) = *n*(A) + *n*(B) ⟺ A, B are disjoint non-void sets.
* *n*(A - B) = *n*(A) - *n*(A ⋂ B)
* *n*(B - A) = *n*(B) - *n*(A ⋂ B)
* *n*(A Δ B) = No. of elements which belong to exactly one of A or B
             = *n*((A - B) ⋃ (B - A))
             = *n*(A - B) + *n*(B - A)
             = *n*(A) - *n*(A ⋂ B) + *n*(B) - *n*(A ⋂ B)
             = *n*(A) + *n*(B) - 2*n*(A ⋂ B) 
* *n*(A ⋃ B ⋃ C) = *n*(A) + *n*(B) + *n*(C) - *n*(A ⋂ B) - *n*(B ⋂ C) - *n*(A ⋂ C) + *n*(A ⋂ B ⋂ C)
* No. of elements in exactly two of the sets A, B, C = *n*(A ⋂ B) + *n*(B ⋂ C) + -3*n*(A ⋂ B ⋂ C)
* No. of elements ine exactly one of the sets A, B, C = *n*(A) + *n*(B) + *n*(C) - 2*n*(A ⋂ B) - 2*n*(B ⋂ C) - 2*n*(A ⋂ C) + 3*n*(A ⋂ B ⋂ C)
* *n*(A' ⋃ B') = *n*((A ⋂ B)') = *n*(*U*) - *n*(A ⋂ B)
* *n*(A' ⋃ B') = *n*((A ⋃ B)') = *n*(*U*) - *n*(A ⋃ B)
        