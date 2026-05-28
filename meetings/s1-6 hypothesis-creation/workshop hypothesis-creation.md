# **Do Quantum**: Hypothesis Creation

# Whats
1. Find your Focus
2. Narrow your Focus
3. Phrase your Focus

# Hows
1. Find: What topics do you think are interesting?
   - Familiarity: What do I or my teammates already know about?
     + Even if you don't know much specifically about quantum, remember that it is a very interdisciplinary field.
     + There's lots of low-hanging fruit, and places where outside knowledge is useful.
   - What is interesting to you?
     + Genuine interest will give you an easier time getting started and overcoming challenges.
   - What is picking up steam?
     + There is a lot of velocity in quantum research.
       Many labs and researchers are shifting focus onto quantum, publishing papers, and developing methods more frequently.
       Some areas move fast because they are accessible, or a primary focus of large research organizations.
       You can approximate velocity by looking for publications within the past time frames: one year, five years, a decade.
     + If you're an opportunist, check out recent publications and find future work sections.
       Sometimes, there are good questions that the authors did not have the time, focus, or skill to pursue.
   - How can I find a specific topic?
     There's a lot of research and people have worked to categorize and catalog it all by type and subject.
     + arXiv Categories: https://arxiv.org/category_taxonomy
     + Mathematics Subject Classiciation (MSC): https://zbmath.org/classification
     + Association for Computing Machinery (ACM) Computing Classification System (CCS): https://dl.acm.org/ccs

2. Narrow: How do you want to pursue your topic?
   - What concepts and variables do you want to focus on? What is uninteresting and what is unimportant?
     Narrowing down your idea to contain only parts that are relevant to your scope helps you create a feasible project.
   - Future work sections of papers:
     When papers describe questions in their future work sections, they can be very related within the perspective of the question answered by the current paper.
     However, there are other ways to view and test the same question. Think about it!
   - What's ongoing work? With which people or resources do you want to work?

3. Phrase: What do you want to test about it?
   - Variables
     In science: Independent, Dependent, Control, Constant
     In distributions: Random, Correlated, Confounding, Independent
   - Testable, Cause --> Effect
     Is there a clear input-output scenario?
     If you want to see if some property changes, how can you control the input to describe your property as an output? 
   - Feasibility
     What can you realistically work on? Can you simulate it, or define a model?


# Example Questions
- Hypothesis Templates
    Cause --> Effect: "Increasing A by X causes Y to change by D."
    Null/Alternative: "H0: A has no effect on Y. H1: A changes Y by D."
    Comparative: "Method A outperforms B on metric M by D under conditions C."
  Examples:
    1. "Adding depolarizing noise at rate r increases readout error rate by ≥2% on a 5-qubit superconducting device (measured bit-flip frequency)."
    2. "Using pulse-shaping reduces gate infidelity by ≥0.5% compared to Gaussian pulses (measured randomized benchmarking error)."

- Experimental-design checklist
    Define IV/DV, controls, constants, metrics, and process.
    Specify measurement metric(s) and thresholds.
    Number of trials / repetitions and randomization plan.
    Analysis method (stat test, CI, effect size).
    Hardware vs. simulation plan and fallback if hardware unavailable.

- Feasibility & resources
    Estimate time, compute, and access needs (simulator/API/hardware credits).
    List necessary software/tools (e.g., Qiskit/PennyLane/SDKs).
    Safety/ethics considerations (data sharing, proprietary hardware limits).

- Common pitfalls & mitigation
    Overly broad aims: require numeric target and narrow population.
    Confounded variables: add controls or orthogonalize factors.
    Measurement noise: increase repetitions or use bootstrap/bootstrapped CIs.
    Non-reproducible hardware results: include simulator baselines and seed protocols.