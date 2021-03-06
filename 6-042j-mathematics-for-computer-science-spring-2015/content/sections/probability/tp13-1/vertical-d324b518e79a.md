---
course_id: 6-042j-mathematics-for-computer-science-spring-2015
layout: course_section
parent_title: 4.5 Expectation
title: 4.5 Expectation
type: course
uid: f42ae4d89239286f9b723890b787a4ed

---

*   [<Expectation]({{< baseurl >}}/sections/probability/tp13-1)
*   [4.5.1Expectation: Video]({{< baseurl >}}/sections/probability/tp13-1)
*   [4.5.2Uneven Dice]({{< baseurl >}}/sections/probability/tp13-1/vertical-d324b518e79a)
*   [4.5.3Expected Number Of Heads: Video]({{< baseurl >}}/sections/probability/tp13-1/vertical-07d1783f0da3)
*   [4.5.4Expected Number of Heads]({{< baseurl >}}/sections/probability/tp13-1/vertical-932dca21218a)
*   [4.5.5Total Expectation: Video]({{< baseurl >}}/sections/probability/tp13-1/vertical-6913b2097610)
*   [4.5.6Another Dice and Coin Game]({{< baseurl >}}/sections/probability/tp13-1/vertical-3506cf32b49b)
*   [4.5.7Mean Time to Failure: Video]({{< baseurl >}}/sections/probability/tp13-1/vertical-e8dee31ddd76)
*   [4.5.8Three Machines Failing]({{< baseurl >}}/sections/probability/tp13-1/vertical-f2cac6de0392)
*   [4.5.9Linearity of Expectation: Video]({{< baseurl >}}/sections/probability/tp13-1/vertical-49ea207a6233)
*   [4.5.10Fair and Biased Coins]({{< baseurl >}}/sections/probability/tp13-1/vertical-4f20b89f006a)
*   [4.5.11Binomial Board Breaking]({{< baseurl >}}/sections/probability/tp13-1/vertical-49116fd8c065)
*   [4.5.12Great Expectations]({{< baseurl >}}/sections/probability/tp13-1/vertical-88fafb62d4f8)
*   [4.5.13Expectation of a Uniform Distribution]({{< baseurl >}}/sections/probability/tp13-1/vertical-0a1dc9049ff4)
*   [\>Expected Number Of Heads: Video]({{< baseurl >}}/sections/probability/tp13-1/vertical-07d1783f0da3)

Uneven Dice
-----------

  

Say I have a six-sided die that lands on an even number with probability \\(\\frac{1}{4}\\). If it lands on an even number, then it lands on each one with equal probability. The same is true for odd numbers. Find the expected value of this die. Please answer as a decimal with three significant figures.

Exercise 1

&nbsp;Numerical Response&nbsp;

Let \\(R\\) be a random variable for the value of the die roll.  
From the description we know that \\(\\Pr\[R=i\]=\\frac{1}{4}\\cdot\\frac{1}{3}=\\frac{1}{12}\\) for \\(i\\in\\{2, 4, 6\\}\\) and \\(\\Pr\[R=i\]=\\frac{3}{4}\\cdot\\frac{1}{3}=\\frac{1}{4}\\) for \\(i\\in\\{1, 3, 5\\}\\). Then, \\(E\[R\]=\\sum\_{i=1}^6 \\Pr\[R=i\] = 1\\cdot\\frac{1}{4}+2\\cdot\\frac{1}{12}+3\\cdot\\frac{1}{4}+4\\cdot\\frac{1}{12}+5\\cdot\\frac{1}{4}+6\\cdot\\frac{1}{12}=\\frac{13}{4}\\)

CheckShow Answer

*   [BackExpectation]({{< baseurl >}}/sections/probability/tp13-1)
*   [ContinueExpected Number Of Heads: Video]({{< baseurl >}}/sections/probability/tp13-1/vertical-07d1783f0da3)