---
course_id: 6-042j-mathematics-for-computer-science-spring-2015
layout: course_section
parent_title: 2.1  GCDs
title: 2.1  GCDs
type: course
uid: 6a0a922fd84dea6eafee260f26d8c991

---

*   [<Divisors]({{< baseurl >}}/sections/structures/tp5-1/vertical-70eb5a2913c0)
*   [2.1.1GCDs & Linear Combinations: Video]({{< baseurl >}}/sections/structures/tp5-1)
*   [2.1.2Euclidean Algorithm: Video]({{< baseurl >}}/sections/structures/tp5-1/euclidean-algorithm-video)
*   [2.1.3Run Euclid Run]({{< baseurl >}}/sections/structures/tp5-1/vertical-b30047e37cc7)
*   [2.1.4Pulverizer: Video]({{< baseurl >}}/sections/structures/tp5-1/pulverizer-video)
*   [2.1.5GCDs I]({{< baseurl >}}/sections/structures/tp5-1/vertical-d1904394a7b7)
*   [2.1.6Revisiting Die Hard: Video]({{< baseurl >}}/sections/structures/tp5-1/revisiting-die-hard-video)
*   [2.1.7Prime Factorization: Video]({{< baseurl >}}/sections/structures/tp5-1/prime-factorization-video)
*   [2.1.8Unique Primes]({{< baseurl >}}/sections/structures/tp5-1/vertical-abe126e3ad2c)
*   [2.1.9Divisors]({{< baseurl >}}/sections/structures/tp5-1/vertical-70eb5a2913c0)
*   [2.1.10GCDs II]({{< baseurl >}}/sections/structures/tp5-1/vertical-912ad2b397a4)
*   [\> Congruences]({{< baseurl >}}/sections/structures/tp5-2)

GCDs II
-------

Compute the GCD of the following two numbers:

  

\\(x=17^{88}\\cdot 31^5\\cdot 37^2\\cdot 59^{1000} \\\\ y=19^{9^{22}}\\cdot 37^{12}\\cdot 53^{3678}\\cdot 59^{29}\\)

Use \\(^\\) for exponentiation and \\(\*\\) for multiplication in your answer.

Exercise 1

&nbsp;Numerical Response&nbsp;

To get the GCD of two numbers: iterate over all primes that appear in both factorizations; raise each of them to the _smallest_ of its two exponents; then multiply the resulting powers.

By the way, if in this procedure you replace the _smallest_ with the _greatest_, the return value will be the LCM (least common multiple) of the two numbers.

CheckShow Answer

*   [BackDivisors]({{< baseurl >}}/sections/structures/tp5-1/vertical-70eb5a2913c0)
*   [Continue Congruences]({{< baseurl >}}/sections/structures/tp5-2)