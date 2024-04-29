---
title: "Awards"
sidebar: mydoc_sidebar
permalink: CONCUR_awards.html
toc: false 
folder: mydoc
---

### The Test of Time Award

For the period 2004-2007, the CONCUR Test of Time Award has been awarded to the papers:

- **Stephen D. Brookes**. A semantics for concurrent separation logic, published in CONCUR 2004
https://doi.org/10.1007/978-3-540-28644-8_2

- **Peter W. O’Hearn**. Resources, concurrency and local reasoning, published in CONCUR 2004
https://doi.org/10.1007/978-3-540-28644-8_4

At the turn of the millennium, the quest for Hoare-style logics for imperative programs with pointers and aliasing
was considered to be one of the most difficult challenges for program verification. The proposals available by then
were often too complex to handle even simple examples, much less the kind of software routinely found in
industrial code bases. This state of affairs changed when Reynolds, O'Hearn, Istiaq and Yang invented Separation
Logic (SL).
In his LICS 2002 paper, Reynolds cites unpublished preliminary work by O'Hearn aiming to extend SL to shared
state concurrent programs. The key idea was that "as program variables are syntactically partitioned into groups
owned by different processes and resources, so the heap should be similarly partitioned by separating
conjunctions in the proof of the program". He also adds: "Unfortunately, at this writing, there is no proof that
O’Hearn’s inference rules are sound".

These difficulties were elegantly overcome by the two invited Concur 2004 papers introducing Concurrent
Separation Logic (CSL), authored respectively by O'Hearn and Brookes. In his Concur 2004 paper "Resources,
Concurrency, and Local Reasoning", O'Hearn eloquently expounds how the underlying principles of separation
logic would naturally embrace the world of concurrent programs with shared state and basic synchronization
primitives. While introducing CSL and its proof rules, O'Hearn presents remarkably simple proofs for numerous
challenging examples, highlighting the practicality of the logic's abstractions. Moreover, he motivates and details a
general method for designing CSL proofs based on the intuitive concepts of separation, resource ownership, and
resource ownership transfer.

The soundness of CSL was at the time solved after a key suggestion of Brookes, by requiring shared resource
invariants to be "precise", that is, expressed by assertions that uniquely identify a well-delimited part of the heap.
In his Concur 2004 paper, "A Semantics for Concurrent Separation Logic", Brookes develops a novel action-trace
semantics for the basic concurrent programming language of CSL, which permits the first proof of soundness for
CSL. Brookes' semantics was also the first race-sensitive denotational model for concurrent programs, a
construction of independent interest, and essential to proving the famous "no races" theorem for CSL. This
collection of contributions was crucial to establish CSL as the most prominent approach for reasoning about
concurrent shared state programs until today.

The Concur 2004 papers by O'Hearn and Brookes frequently refer to each other, and are delightful to read as a
whole; it is very fortunate that they appeared in the same edition of Concur. Since then, CSL has been a constant
source of inspiration for the scientific community, motivating many theoretical and practical developments
important to tackle increasingly sophisticated real-world concurrent shared state programming scenarios including
higher-order languages, storable locks, expressive permissions mechanisms, fine-grained concurrency, weak
memory concurrency, verification of type systems (e.g., Rust), linearizability, program refinement, crash safety,
non-interference, and incorrectness logic. CSL has been adapted as part of mature research tools such as Verifast,
Viper, Iris, VST, and F*, and it has been used in an industrial setting for among others the verification of concurrent
data structures and micro-kernels/hypervisors.

We congratulate Brookes and O'Hearn for this lasting contribution to the scientific community!


### Interview with the winners
TBD
