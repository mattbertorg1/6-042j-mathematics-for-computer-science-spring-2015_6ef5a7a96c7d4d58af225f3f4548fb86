---
course_id: 6-042j-mathematics-for-computer-science-spring-2015
layout: course_section
parent_title: 1.10 Recursive Definition
title: 1.10 Recursive Definition
type: course
uid: 07b69d15ceb477f320edfe861b5c21fc

---

*   [<Recursive Definition]({{< baseurl >}}/sections/proofs/recursive-definition)
*   [1.10.1Recursive Data: Video]({{< baseurl >}}/sections/proofs/recursive-definition)
*   [1.10.2Matching Parentheses]({{< baseurl >}}/sections/proofs/recursive-definition/matching-parentheses)
*   [1.10.3Functions of F18]({{< baseurl >}}/sections/proofs/recursive-definition/functions-of-f18)
*   [1.10.4Structural Induction: Video]({{< baseurl >}}/sections/proofs/recursive-definition/structural-induction-video)
*   [1.10.5Structural Induction: Definition]({{< baseurl >}}/sections/proofs/recursive-definition/structural-induction-definition)
*   [1.10.6Counting Cases]({{< baseurl >}}/sections/proofs/recursive-definition/counting-cases)
*   [1.10.7Recursive Functions: Video]({{< baseurl >}}/sections/proofs/recursive-definition/recursive-functions-video)
*   [\>Functions of F18]({{< baseurl >}}/sections/proofs/recursive-definition/functions-of-f18)

Matching Parentheses
--------------------

  

Which of the following are true about \\(M\\), the set of matched parentheses strings?

Exercise 1

&nbsp;No string in \\(M\\) can start with a right parenthesis.&nbsp;

&nbsp;Every string in \\(M\\) must start with a left parentheses.&nbsp;

&nbsp;\\(M\\) is an infinite set.&nbsp;

&nbsp;Every string in \\(M\\) must have even length. &nbsp;

For any string of length greater than \\(0\\), if it starts with a right parenthesis, it is immediately unmatched. The empty string also vacuously satisfies this statement.

The empty string is a counterexample.

There are a variety of ways to show \\(M\\) is infinite. For example, for any proposed longest string, simply append "()" to the end.

In order for a string to be matched, its length must be a multiple of 2, for pairs of left and right parentheses. Note that the empty string has length 0 which is also even.

CheckShow Answer

*   [BackRecursive Definition]({{< baseurl >}}/sections/proofs/recursive-definition)
*   [ContinueFunctions of F18]({{< baseurl >}}/sections/proofs/recursive-definition/functions-of-f18)