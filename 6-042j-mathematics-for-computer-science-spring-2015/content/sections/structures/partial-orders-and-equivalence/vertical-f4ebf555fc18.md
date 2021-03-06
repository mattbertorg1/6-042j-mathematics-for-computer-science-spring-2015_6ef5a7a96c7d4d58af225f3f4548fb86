---
course_id: 6-042j-mathematics-for-computer-science-spring-2015
layout: course_section
parent_title: 2.7 Partial Orders and Equivalence
title: 2.7 Partial Orders and Equivalence
type: course
uid: 8db7161bcd487d105925ec9b93051cad

---

*   [<Partial Orders and Equivalence]({{< baseurl >}}/sections/structures/partial-orders-and-equivalence)
*   [2.7.1Partial Orders: Video]({{< baseurl >}}/sections/structures/partial-orders-and-equivalence)
*   [2.7.2Population Partial Order]({{< baseurl >}}/sections/structures/partial-orders-and-equivalence/vertical-f4ebf555fc18)
*   [2.7.3Representing Partial Orders As Subset Relations: Video]({{< baseurl >}}/sections/structures/partial-orders-and-equivalence/vertical-a604c5db7bb5)
*   [2.7.4Equivalence Relations: Video]({{< baseurl >}}/sections/structures/partial-orders-and-equivalence/vertical-c6c01eb0d061)
*   [2.7.5Relational Properties]({{< baseurl >}}/sections/structures/partial-orders-and-equivalence/vertical-6ea0ba8a2d05)
*   [2.7.6Properties Of Relations]({{< baseurl >}}/sections/structures/partial-orders-and-equivalence/vertical-d7f7704d23b4)
*   [2.7.7Equivalence Relations & Partial Orders]({{< baseurl >}}/sections/structures/partial-orders-and-equivalence/vertical-d757201744eb)
*   [\>Representing Partial Orders As Subset Relations: Video]({{< baseurl >}}/sections/structures/partial-orders-and-equivalence/vertical-a604c5db7bb5)

Population Partial Order
------------------------

  

In a population of 10 people, let \\(R \\) be the "older than" relation and \\(T \\) be the "taller than" relation.

1.  Which of the following properties guarantee that \\(R \\) will be a linear order?
    
    Exercise 1
    
    &nbsp;There is a unique oldest personThere are at most two people with the same ageNo two people are the same ageThere is an age that no one hasSome person appears twice in the list No two people are the same age&nbsp;
    
  
3.  Assume both \\(R \\) and \\(T \\) are linear orders. Which properties are **guaranteed** to be true for the product relation \\(R \\times T \\)?
    
    Exercise 2
    
    &nbsp; symmetric &nbsp;
    
    &nbsp; antisymmetric &nbsp;
    
    &nbsp; asymmetric &nbsp;
    
    &nbsp; reflexive &nbsp;
    
    &nbsp; transitive &nbsp;
    
    &nbsp; acyclic &nbsp;
    
    &nbsp; linear &nbsp;
    
    Not **symmetric** because two distinct people cannot both be older and taller than each other.
    
    Not **reflexive** because a person cannot be older/taller than himself.
    
    Not **linear** because if person \\(A \\) is older than person \\(B \\) but \\(B \\) is taller than \\(A \\), then \\(A\\) and \\(B\\) are incomparable.
    
    CheckShow Answer
    
  

*   [BackPartial Orders and Equivalence]({{< baseurl >}}/sections/structures/partial-orders-and-equivalence)
*   [ContinueRepresenting Partial Orders As Subset Relations: Video]({{< baseurl >}}/sections/structures/partial-orders-and-equivalence/vertical-a604c5db7bb5)