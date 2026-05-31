# **Do Quantum**: Problem Area Activity

**Purpose**  
Practice analyzing quantum algorithms while gaining background knowledge about a problem area of your choice.
This activity should help you understand why/how quantum algorithms are developed, identify current algorithmic challenges, and learn how to reason about computational systems abstractly and logically.

**Due**  
Wednesday, 07 October @ 11:59 pm

# Instructions

**Goal**
- Identify and explore a quantum algorithm or algorithmic problem area that interests you.
- Organize the algorithm into a logical process from input to output.
- Communicate complex computational ideas as a clear system of steps.
- Identify assumptions or hardware constraints that affect whether the algorithm is useful in practice.

**Steps**
1. Partner up with 1 other student.
   It helps if you align with your partner on interest and find or eliminate potential teammates.
2. Together, identify a quantum algorithm and algorithmic problem area to explore.
   Think about:
      + Theory: What quantum principle(s) does it use?
      + Physical: What does it look like physically? How big are state-of-the-art machines? Where can you see them?
      + Resources: How do they scale? What are the limiting factors?
      + Industry: Who makes them? Who uses them? How many are there? How have they progressed since their invention?
      + Users: How do you use them? How are the programs encoded? What constraints should I know about them?
   Example QPU types:
      + superconducting transmon (JJ)
      + trapped ion
      + neutral atom
      + nitrogen vacancy diamond (NVD)
      + nuclear magnetic resonance (NMR)
3. Describe and number each step in the process that the QPU takes from the input quantum program, to the actual results.
   You may include classical pre-processing, post-processing, hyperparameters, or feedback.
   Label each step and what it does. Is it classical, quantum, or hybrid?
4. Break apart the process into logical steps, and create a final flowchart. There should be more than 4.
5. Identify a problem with the architecture. Circle where it lives in the flowchart.
   Example problems with the architecture:
      + data encoding & embedding
      + noise, error rates & decoherence
      + machine precision
      + classical overhead
   How do these problems manifest? What do the consequences look like for users of that system?
6. **ONCE ACCEPTED** Optionally, look at accepted teams & projects to have a good idea of who else will be at the next meeting.

**Submission**
1. Navigate to the "Activity Folder."  
2. Create a folder for your partnership named: "qpu type: fun name you choose"
3. Upload your diagram into that folder, your accompanying written explanations, and a folder with reference materials.  
4. Link your folder in the submission spreadsheet.
5. Be assessed as a team to know if you’re continuing by Thursday, 08 October @ 11:59 pm.

# Rubric

**High-Level Explanation**
- Clear reasoning that an uninitiated student can follow.
- Reasoning and explanation shows personal understanding, not just copied text.
- Scope & assumptions make sense to understand the flow of the system.

**Logical Break-Down**
- Good labels for each step.
- Each step completely follows from the previous. There should be no mysteries.
- The granularity of each step is neither too coarse nor trivial with clear sequencing.
- Physical or software components can be traced to each step of the system.

**Contextualization**
- Discussion connects reasoning and sources.
- Clear problem identification, labeled on the flowchart.
- The impact analysis of the problem should incorporate how it affects users and outcomes.
- At least one realistic mitigation plan with pros and cons.

**Research & Evidence**
- At least 3 credible sources included: technical documentation, research papers, etc.  
- Connections between references and diagrams are clear.
- Sources are included as documents and can be traced to the origin.

**Submission**
- Folder named correctly: "qpu type: fun name you choose."  
- Materials uploaded by deadline.  
- Organization, clarity, and adherence to instructions.

# Tips
1. Keep your high-level explanation simple. The complexity in the steps should be captured in the break-down of each step.  
2. Think about alternative processes for each step.  
3. Be honest & look past marketing. If users complain about using hardware, there is a reason.  
4. A strong bibliography shows depth, don’t rely only on blogs or Wikipedia.   
5. LLMs are nice for formatting and explanations, but you won't automatically develop an understanding from them.   
6. Some nice flowchart software: Graphviz, Mermaid.js, Lucidchart