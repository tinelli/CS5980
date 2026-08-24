---
title: Lectures
type: lectures
---

This page gives highlights of past lectures and provides lecture notes, 
reading assignments, and exercises.
**Greyed out text** (for future lectures) **is tentative and subject to change.**

Chapters and sections in readings are from the textbook, and 
so are the exercises.

#### Aug 25 -- Aug 27

Course introduction and administration.
Introduction to Embedded Systems.
The synchronous model of reactive computation.
Reactive components.

**Notes:**
[Introduction](chap1.pdf) ,
The Synchronous Model [Part I](chap2a.pdf)
<br>
**Readings:**
[Syllabus](../syllabus),
Chap. 1,
Sect. 2.1

<div style="color: #D3D3D3;">

#### Sep 1 -- Sep 3
The Synchronous Model.
Reactive components and their properties.
Deterministic vs. non-deterministic, combinational vs. stateful components.
Event triggered components.
Dividing code reactions into tasks.
Task graphs, await dependencies and schedules.
Parallel composition of components.
Formal definitions.

**Notes:**
The Synchronous Model [Part I](chap2a.pdf) and [Part II](chap2b.pdf)
<br>
**Readings:**
Sect. 2.1 - 2.4
<br>
**Exercises:**
2.1, 2.2, 2.4, 2.5, 2.7, 2.9, 2.12, 2.13

#### Sep 8 -- Sep 10
Parallel composition of components.
Designing synchronous systems.
Bottom-up vs. top-down design.
Synchronous networks.

**Notes:**
The Synchronous Model [Part II](chap2b.pdf) and [Part III](chap2c.pdf)
<br>
**Readings:**
Sect. 2.3–2.4
<br>
**Exercises:**
2.6, 2.15, 2.17

#### Sep 15 -- Sep 17
Safety Requirements.
Transition systems.
Safety properties and invariants.
Verifying invariants.
Inductive strengthening.
Examples of inductive proofs.
Requirement-based design.
Complexity of automated invariant verification.

**Notes:**
Safety Requirements [Part I](chap3a.pdf), [Part II](chap3b.pdf),
and [Part III](chap3c.pdf)
<br>
**Readings:**
Sect. 3.1–3.2; Sect. 3.4 (recommended)
<br>
**Exercises:**
3.1, 3.6, 3.8; exercises in class notes

#### Sep 22 -- Sep 24
Introduction to the Asynchronous Model.
Asynchronous processes: input, output channels, states and tasks.
Executions and interleaving semantics.
Asynchronous parallel composition.
Safety and progress requirements.
Asynchronous design primitives.
Synchronization. Deadlocks.
Shared memory. The mutual exclusion problem.

**Notes:**
The Asynchronous Model [Part I](chap4a.pdf) and [Part II](chap4b.pdf)
<br>
**Readings:**
Sect. 4.1–4.2
<br>
**Exercises:**
4.2, 4.4, 4.5; exercises in class notes

#### Sep 29 -- Oct 1
Fairness assumptions: weak and strong fairness.
Correctness under fairness assumptions.
Asynchronous coordination protocols.
Leader election. Reliable transmission.

**Notes:**
The Asynchronous Model [Part II](chap4b.pdf) and [Part III](chap4c.pdf)
<br>
**Readings:**
Sect. 4.2–4.3 except 4.3.3
<br>
**Exercises:**
Exercises in class notes

#### Oct 5
Midterm I

#### Oct 6 -- Oct 8
More on asynchronous coordination protocols.
The alternating bit protocol.
Wait-free consensus.
Specifying liveness requirements.
Introduction to Linear Temporal Logic: syntax and semantics.

**Notes:**
The Asynchronous Model [Part III](chap4c.pdf),
Liveness Requirements [Part I](chap5a.pdf)
<br>
**Readings:**
Sect. 4.3 except proof of Theorem 4.1, Sect. 5.1

#### Oct 13 -- Oct 15
Derived LTL operators.
Specifying system requirements in LTL. Examples.
LTL equivalences.
LTL specifications.
Encoding fairness assumptions in LTL. Examples.
Correspondence between LTL formulas and Büchi automata. Examples.
Checking LTL properties of reactive systems by reduction to Büchi automata.

**Notes:**
Liveness Requirements [Part I](chap5a.pdf) and [Part II](chap5b.pdf)
<br>
**Readings:**
Sect. 5.1–5.2.1; Sec 5.2.2, 5.2.4 (recommended)
<br>
**Exercises:**
Exercises in class notes


#### Oct 20 -- Oct 22
The timed model.
Clocks.
Motivation and examples.
Formal definition.
Parallel composition.
Modeling imperfect clocks.
Timed based protocols. Examples.

**Notes:**
Timed Model [Part I](chap7a.pdf) and [Part II](chap7b.pdf)
<br>
**Readings:**
Sect. 7.1–2
<br>
**Exercises:**
Exercises in class notes; 7.1, 7.2

#### Oct 27 -- Oct 29
Introduction to dynamical systems.
General concepts and motivation.
Feedback control loops.
Examples of continuous-time components.
Brief recap of derivatives and differential equations.
Continuous-time components: definition and examples.
Sufficient conditions for the existence and uniqueness of executions.

**Notes:**
Dynamical Systems [Part I](chap6a.pdf)
<br>
**Readings:**
Sect. 6.1
<br>
**Exercises:**
6.1

#### Nov 3 -- Nov 5
More on dynamical systems.
The pendulum example.
Equilibria and Stability. Lyapunov and input-output stability.
Linear systems.
Solving linear differential equations.

**Notes:**
Dynamical Systems [Part II](chap6b.pdf) and [Part III](chap6c.pdf)
<br>
**Readings:**
Sect. 6.1, 6.2,
Chap. 2 of [Hefferon](http://joshua.smcvt.edu/linearalgebra/) (as needed)
<br>
**Exercises:**
6.1, 6.4, 6.6

#### Nov 9
Midterm II

#### Nov 10 -- Nov 12
Designing controllers.
Open- and closed-loop controllers.
Stabilizing controllers.
Gain matrix and controllability for linear systems.
PID controllers.
Introduction to hybrid systems.
Hybrid dynamical models: motivation and examples.
Formal definition of hybrid systems.
Executions and composition of hybrid processes.
Zeno behavior. Examples.

**Notes:**
Dynamical Systems [Part IV](chap6d.pdf),
Hybrid Systems [Part I](chap9a.pdf)
<br>
**Readings:**
Sect. 6.3, 9.1
<br>
**Exercises:**
9.2



#### Nov 17 -- Nov 19
Zeno executions, states and processes.
Zeno processes and reachability.
Stability of hybrid systems.
Designing Hybrid Systems. Examples.

**Notes:**
Hybrid Systems [Part I](chap9a.pdf) and [Part II](chap9b.pdf)
<br>
**Readings:**
Sect. 9.1, 9.2
<br>
**Exercises:**
9.5

#### Nov 24 -- Nov 26
No classes. Thanksgiving break.

#### Dec 1 -- Dec 3
<!-- Modeling and checking reactive systems with the Kind 2 model checker.
Modeling examples from the textbook in Kind 2.

**Notes:**
Kind 2 examples: [Miscellaneous](https://kind.cs.uiowa.edu/app/#examples%2FAlur), [Railroad Controller](https://kind.cs.uiowa.edu/app/#examples%2FRailroadController), [Car Cruise Controller](https://kind.cs.uiowa.edu/app/#examples%2FCar)
<br>
**Exercises:**
Experiment with Kind 2 examples [online](https://kind.cs.uiowa.edu/app/) -->

#### Dec 8 -- Dec 10

</div>
