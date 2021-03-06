---
course_id: 6-042j-mathematics-for-computer-science-spring-2015
layout: course_section
parent_title: 2.6 Directed Acyclic Graphs (DAGs) & Scheduling
title: 2.6 Directed Acyclic Graphs (DAGs) & Scheduling
type: course
uid: 011a1e95b575d2f709fa03443fdeb584

---

*   [<Processor Time Bounds]({{< baseurl >}}/sections/structures/tp7-1/vertical-a69125071411)
*   [2.6.1DAGs: Video]({{< baseurl >}}/sections/structures/tp7-1)
*   [2.6.2DAGs]({{< baseurl >}}/sections/structures/tp7-1/vertical-dcde59c77eab)
*   [2.6.3Scheduling: Video]({{< baseurl >}}/sections/structures/tp7-1/vertical-0b187f2dedb6)
*   [2.6.4Scheduling Prerequisites]({{< baseurl >}}/sections/structures/tp7-1/vertical-cb2dbc0f9d11)
*   [2.6.5Time versus Processors: Video]({{< baseurl >}}/sections/structures/tp7-1/vertical-ce9e54c9d251)
*   [2.6.6Processor Time Bounds]({{< baseurl >}}/sections/structures/tp7-1/vertical-a69125071411)
*   [2.6.7The Divisibility DAG]({{< baseurl >}}/sections/structures/tp7-1/vertical-839e7a19a176)
*   [\>Partial Orders and Equivalence]({{< baseurl >}}/sections/structures/partial-orders-and-equivalence)

The Divisibility DAG
--------------------

  

![](/courses/electrical-engineering-and-computer-science/6-042j-mathematics-for-computer-science-spring-2015/structures/tp7-1/vertical-839e7a19a176/divi2.gif)

In the above DAG for the divisibility relation on \\(\\{1, \\ldots, 12\\}\\), there is an upward path from \\(a\\) to \\(b\\) iff \\(a\\) divides \\(b\\). If \\(24\\) was added as a vertex, what is the minimum number of edges that must be added to the DAG to represent divisibility on \\(\\{1, \\ldots, 12, 24\\}\\)?

Exercise 1

&nbsp;Text Response&nbsp; Answer:2

Edges from 8 and 12 to 24 are all that are needed.

CheckShow Answer

*   [BackProcessor Time Bounds]({{< baseurl >}}/sections/structures/tp7-1/vertical-a69125071411)
*   [ContinuePartial Orders and Equivalence]({{< baseurl >}}/sections/structures/partial-orders-and-equivalence)