---
course_id: 6-042j-mathematics-for-computer-science-spring-2015
layout: course_section
parent_title: '4.6 Deviation: Markov & Chebyshev Bounds'
title: '4.6 Deviation: Markov & Chebyshev Bounds'
type: course
uid: 719c67c20cf18d4d1d43176b0d540c1b

---

*   [<Variance: Video]({{< baseurl >}}/sections/probability/tp13-2/vertical-0646c16ad916)
*   [4.6.1Deviation From The Mean: Video]({{< baseurl >}}/sections/probability/tp13-2)
*   [4.6.2Don't Expect the Expectation]({{< baseurl >}}/sections/probability/tp13-2/vertical-18d81b8ca2e1)
*   [4.6.3Markov Bounds: Video]({{< baseurl >}}/sections/probability/tp13-2/vertical-8307292b80cb)
*   [4.6.4Markov Bound]({{< baseurl >}}/sections/probability/tp13-2/vertical-ecd276750fa8)
*   [4.6.5Chebyshev Bounds: Video]({{< baseurl >}}/sections/probability/tp13-2/vertical-49f940bfd8d6)
*   [4.6.6Inside the TA's Brain]({{< baseurl >}}/sections/probability/tp13-2/vertical-82fa33baa07e)
*   [4.6.7Variance: Video]({{< baseurl >}}/sections/probability/tp13-2/vertical-0646c16ad916)
*   [4.6.8Practice with Variance]({{< baseurl >}}/sections/probability/tp13-2/vertical-1b1a945bfd78)
*   [4.6.9Flipping Coins]({{< baseurl >}}/sections/probability/tp13-2/vertical-871f95303dd6)
*   [4.6.10Practice with Bounds]({{< baseurl >}}/sections/probability/tp13-2/vertical-00ed1bc2728f)
*   [4.6.11Implications of Expectation]({{< baseurl >}}/sections/probability/tp13-2/vertical-4699d069607e)
*   [\>Flipping Coins]({{< baseurl >}}/sections/probability/tp13-2/vertical-871f95303dd6)

Variance
--------

  

1.  What is the maximum variance of an indicator variable?
    
    Exercise 1
    
    &nbsp;Numerical Response&nbsp;
    
    \\(p(1-p)\\) maximized for \\(p=0.5\\).
    
  
3.  Given independent random variables \\(X\\) and \\(Y\\), what is \\(Var(aX + bY + c)\\)?
    
    Exercise 2
    
    &nbsp;Var(X) + Var(Y)a\*Var(X)b\*Var(Y)a\*Var(X) + b\*Var(Y) + ca^2\*Var(X) + b^2\*Var(Y)a^2\*Var(X) + b^2\*Var(Y) + c^2 a^2\*Var(X) + b^2\*Var(Y)&nbsp;
    
    *   \\(Var(X+a)=Var(X)\\) for any constant \\(a\\).
    *   \\(Var(aX)=a^2Var(X)\\) for any constant \\(a\\).
    *   \\(Var(X+Y)=Var(X)+Var(Y)\\) for independent random variables \\(X\\) and \\(Y\\).
    
    Applying those three rules we get that \\(Var(aX + bY + c)=a^2\\cdot Var(X) + b^2\\cdot Var(Y)\\)
    
    CheckShow Answer
    

*   [BackVariance: Video]({{< baseurl >}}/sections/probability/tp13-2/vertical-0646c16ad916)
*   [ContinueFlipping Coins]({{< baseurl >}}/sections/probability/tp13-2/vertical-871f95303dd6)