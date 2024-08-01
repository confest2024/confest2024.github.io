---
title: "Invited Talks Information"
sidebar: mydoc_sidebar
permalink: invited_talks.html
toc: false 
folder: mydoc
---

# Dr. Corina Pasareanu
[Corina Pasareanu](https://www.andrew.cmu.edu/user/pcorina/){:target="_blank"}

<p align="justify">
<b>Bio:</b> Corina Pasareanu is an ACM Fellow and an IEEE ASE Fellow, working at NASA Ames. She is affiliated with KBR and Carnegie Mellon University's CyLab. Her research interests include model checking, symbolic execution, compositional verification, probabilistic software analysis, autonomy, and security. She is the recipient of several awards, including ETAPS Test of Time Award (2021), ASE Most Influential Paper Award (2018), ESEC/FSE Test of Time Award (2018), ISSTA Retrospective Impact Paper Award (2018), ACM Impact Paper Award (2010), and ICSE 2010 Most Influential Paper Award (2010). She has been serving as Program/General Chair for several conferences including: ICSE 2025, SEFM 2021, FM 2021, ICST 2020, ISSTA 2020, ESEC/FSE 2018, CAV 2015, ISSTA 2014, ASE 2011, and NFM 2009. She is on the steering committees for the ICSE, TACAS and ISSTA conferences. She is currently an associate editor for IEEE TSE and for STTT, Springer Nature.</p>

**Title:** Compositional Verification and Run-time Monitoring for Learning-Enabled Autonomous Systems

<p align="justify">
<b>Abstract:</b> Providing safety guarantees for autonomous systems is difficult as these systems operate in complex environments that require the use of learning-enabled components, such as deep neural networks (DNNs) for visual perception. DNNs are hard to analyze due to their size, lack of formal specifications, and sensitivity to small changes in the environment. We present compositional technigiques for the formal verification of safety properties of such autonomous systems. The main idea is to abstract the hard-to-analyze components of the autonomous system, such as DNN-based perception and environmental dynamics, with either probabilistic or worst-case abstractions. This makes the system amenable to formal analysis using off-the-shelf model checking tools, enabling the derivation of specifications for the behavior of the abstracted components such that system safety is guaranteed. We also discuss how the derived specifications can be used as run-time monitors deployed on the DNN outputs. We illustrate these ideas in a case study from the autonomous airplane domain.</p>

# Dr. Mor Harchol-Balter
[Mor Harchol-Balter](https://www.cs.cmu.edu/~harchol/){:target="_blank"}

<p align="justify">
<b>Bio:</b> Dr. Mor Harchol-Balter is the Bruce J. Nelson Professor of Computer Science at Carnegie Mellon. She received her Ph.D. from U.C. Berkeley in 1996 under the direction of Manuel Blum. She joined CMU in 1999, and served as the Head of the PhD program from 2008-2011. She is the SIG Chair for ACM SIGMETRICS. She is a Fellow of both ACM and IEEE, the NSF CAREER award, and several teaching awards, including the Herbert A. Simon Award and Spira Teaching Award. Mor's work focuses on designing new resource allocation policies, including load balancing policies, power management policies, and scheduling policies, for distributed systems. Mor is heavily involved in the SIGMETRICS / PERFORMANCE research community where she has received many paper awards (INFORMS George Nicholson Prize 22, SIGMETRICS 21, SIGMETRICS 19, PERFORMANCE 18, INFORMS APS 18, EUROSYS 16, MASCOTS 16, MICRO 10, SIGMETRICS 03, ITC 03, SIGMETRICS 96). She is the author of two popular textbooks, both published by Cambridge University Press: Performance Analysis and Design of Computer Systems (2013) and Introduction to Probability for Computing (2024). She is also a recipient of dozens of Industrial Faculty Awards including multiple awards from Google, Microsoft, IBM, EMC, Facebook, Intel, Yahoo!, and Seagate. Mor is best known for her enthusiastic keynote talks and her many PhD students, almost all of whom are professors at top academic institutions.</p>

**Title:** Queueing Models for Today's Data Center Jobs

<p align="justify">
<b>Abstract:</b> Most queueing models assume that a job runs on a single server. But this <I>one-server-per-job</I> model is <I>not</I> a good representation of today's compute jobs.<br>

A typical data center job today occupies multiple cores concurrently, often thousands of cores.  We refer to a job that concurrently occupies multiple cores as a <I>multiserver job</I>.  Unfortunately, very little is known about response time in multiserver job queueing models. We present the first results on response time for multiserver job queueing models. In particular, we propose a new scheduling policy for multiserver jobs, called ServerFilling, and bound its response time.<br>

We also consider today's <I>parallel speedup jobs</I>, which can run on any number of cores, but whose speed depends on the number of cores on which the job is run.  Here it is even more complicated to understand how to best share a limited number of cores among a stream of jobs, each governed by a different speedup function.  We discuss some recent optimality results in this nascent area. </p>

# Dr. Arie Gurfinkel
[Arie Gurfinkel](https://arieg.bitbucket.io/){:target="_blank"}  

<p align="justify">
<b>Bio:</b> Dr. Arie Gurfinkel is a Professor in the Department of Electrical and Computer Engineering with a cross-appointment at the Cheriton School of Computer Science at the University of Waterloo. His research tackles the growing challenge of ensuring the correct operation of complex computer systems as they become smaller, faster, and more integrated into our daily lives. His research focuses on developing methods for automated program analysis, Software Model Checking, automated reasoning, and abstract interpretation to facilitate the development, testing, and verification of these systems. </p>

**Title:** Constrained Horn Clauses for Program Verification and Synthesis

<p align="justify">
<b>Abstract:</b>
First Order Logic (FOL) is a powerful formalism that naturally captures many interesting decision and optimization problems. In recent years,
there has been a tremendous progress in automated logic reasoning tools, such as Boolean SATisfiability Solvers and Satisfiability Modulo Theory solvers. This enabled the use of logic and logic solvers as a universal solution to many problems in Computer Science, in general, and in Program Analysis, in particular. Most new program analysis techniques formalize the desired analysis task in a fragment of FOL, and delegate the analysis to a SAT or an SMT solver.<br>
In this talk, we focus on a fragment of FOL called Constrained Horn Clauses (CHC) and the CHC solver SPACER. CHCs arise in many applications of automated verification. They naturally capture such problems as discovery and verification of inductive invariants; Model Checking of safety properties of finite- and infinite-state systems; safety verification of push-down systems (and their extensions); modular verification of distributed and parameterized systems; type inference, and many others.<br>
Using CHC separates the process of developing a proof methodology (also known as generation of Verification Condition (VC)) from the algorithmic details of deciding whether the VC is correct. Such a flexible design simplifies supporting multiple proof methodologies, multiple languages, and multiple verification tasks with a single framework, without sacrificing performance and scalability.<br>
Bio: Dr. Arie Gurfinkel is a Professor in the Department of Electrical and Computer Engineering at the University of Waterloo. His research is in the areas of Program Analysis, Model Checking, and Automated Reasoning. His research group has led the implementation of award-winning program analysis framework SeaHorn, and award-winning solver for Constrained Horn Clauses, SPACER.

</p>
# Dr. Azalea Raad
[Azalea Raad](https://profiles.imperial.ac.uk/azalea.raad){:target="_blank"}

<p align="justify">
<b>Bio:</b> Dr. Azalea Raad is a Senior Lecturer in the Department of Computing at Imperial College London. As of October 2021,She is a UKRI Future Leader Fellow. Between September 2020 and July 2022 she was a consulting research scientist at Facebook, London. As of September 2022, she is a research consultant at Bloomberg. Her research is in the area of programming languages and verification, spanning several topics including non-volatile memory, persistency semantics, weak memory models, stateless model checking and program logics.</p>


# Dr. Thomas Wies
[Thomas Wies](https://cs.nyu.edu/~wies/){:target="_blank"}

<p align="justify">
<b>Bio:</b> Dr. Thomas Wies is a Professor of Computer Science in the Courant Institute of Mathematical Sciences at New York University. He is recipient of an NSF CAREER Award, an OOPSLA 2014 Best Paper Award, and an ISSRE 2019 Distinguished Paper Award. His research interests are in Programming Languages and Formal Methods with a focus on verification, static analysis, and automated reasoning.</p>

**Title:** Verifying Concurrent Search Structures

<p align="justify">
<b>Abstract:</b> Search structures support the fundamental data storage primitives on key-value pairs: insert a pair, delete by key, search by key, and update the value associated with a key. Concurrent search structures are parallel algorithms to speed access to search structures on multicore and distributed servers. For these data structures to be efficient, the underlying parallel algorithms need to perform fine-grained synchronization between threads. This makes them notoriously difficult to design and implement correctly. Indeed, bugs are routinely found both in actual implementations and in the designs proposed by experts in peer-reviewed publications. Often, these bugs elude testing-based quality control due to complex thread interactions that only manifest after deployment, and under conditions that are difficult to replicate. Given the critical role that concurrent search structures play in today’s software infrastructure, it is therefore highly desirable to verify their correctness using formal methods, preferably in an automated fashion.
<br>
In this talk, I will present a framework for obtaining linearizability proofs for concurrent search structures that are modular, reusable, and amenable to automation. The framework takes advantage of recent advances in local reasoning techniques based on concurrent separation logic. I will provide an overview of these techniques and discuss there use for verifying both lock-based and lock-free concurrent search structures such as concurrent (skip)lists, hash structures, binary search trees, B trees, and log-structured merge trees.
</p>