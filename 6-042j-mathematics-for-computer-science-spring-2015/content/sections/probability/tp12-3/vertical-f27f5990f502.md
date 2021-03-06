---
course_id: 6-042j-mathematics-for-computer-science-spring-2015
layout: course_section
parent_title: 4.4 Random Variables, Density Functions
title: 4.4 Random Variables, Density Functions
type: course
uid: e0649a8f87adc6b9ff43ef4494e94f2b

---

*   [<PDF to CDF]({{< baseurl >}}/sections/probability/tp12-3/vertical-0527081b6af3)
*   [4.4.1Bigger Number Game: Video]({{< baseurl >}}/sections/probability/tp12-3)
*   [4.4.2Random Variables: Independence: Video]({{< baseurl >}}/sections/probability/tp12-3/vertical-af2ad400f984)
*   [4.4.3Odd Heads and Matches]({{< baseurl >}}/sections/probability/tp12-3/vertical-12926a05d1ba)
*   [4.4.4Random Variables: Uniform & Binomial: Video]({{< baseurl >}}/sections/probability/tp12-3/vertical-c596d4103fc3)
*   [4.4.5Late For A Date]({{< baseurl >}}/sections/probability/tp12-3/vertical-5a2c58463701)
*   [4.4.6A Random Number]({{< baseurl >}}/sections/probability/tp12-3/vertical-fd04358ad7c2)
*   [4.4.7PDF to CDF]({{< baseurl >}}/sections/probability/tp12-3/vertical-0527081b6af3)
*   [4.4.8Dice And Coin Game]({{< baseurl >}}/sections/probability/tp12-3/vertical-f27f5990f502)
*   [\>Expectation]({{< baseurl >}}/sections/probability/tp13-1)

Dice And Coin Game
------------------

  

A fair die is tossed and its outcome is denoted by \\(X\\). After that, we toss an independent fair coin \\(X\\) times and count the number of heads. Let \\(Y\\) denote the number of heads. Please answer as a fraciton in the form of x/y.

1.  What is \\(\\Pr\[Y=4\]\\)?
    
    Exercise 1
    
    &nbsp;Numerical Response&nbsp;
    
    Conditioning on \\(X = k\\) for \\(k = 1, \\ldots, 6\\), \\(Y\\) has a binomial distribution with parameters \\((k, \\frac{1}{2})\\). By the Law of Total Probability, \\(\\Pr\[Y=4\]=\\sum\_{k=1}^6\\Pr\[Y=4|X=k\]\\Pr\[X=k\]=\\frac{1}{6}\\left(\\frac{1}{2^4}+\\binom{5}{4}\\frac{1}{2^5}+\\binom{6}{4}\\frac{1}{2^6}\\right)=\\frac{29}{384}\\).
    
  
3.  What is \\(\\Pr\[X=5\\;|\\;Y=4\]\\)?
    
    Exercise 2
    
    &nbsp;Numerical Response&nbsp;
    
    By Bayes Rule, \\(\\Pr\[X=5\\;|\\;Y=4\]=\\frac{\\Pr\[Y=4\\;|\\;X=5\]\\Pr\[X=5\]}{\\Pr\[Y=4\]}\\). Since \\(\\Pr\[Y=4\\;|\\;X=5\]=\\binom{5}{4}\\frac{1}{2^5}\\), it follows that \\(\\Pr\[X=5\\;|\\;Y=4\]=\\frac{\\binom{5}{4}\\frac{1}{2^5}\\cdot\\frac{1}{6}}{\\frac{29}{384}}=\\frac{10}{29}\\).
    
    CheckShow Answer
    

*   [BackPDF to CDF]({{< baseurl >}}/sections/probability/tp12-3/vertical-0527081b6af3)
*   [ContinueExpectation]({{< baseurl >}}/sections/probability/tp13-1)