# Module 4: The Brain-Machine Connection

**Inspired by Disney Pixar's *Hoppers* (2026)**

| | |
|---|---|
| **Grade Band** | 6-10 |
| **Duration** | 3 class periods (45-50 minutes each) |
| **Subject Areas** | Life Science, Neuroscience, Engineering/Technology |
| **Developed by** | ModelIt! K12 in partnership with the University of Nebraska-Lincoln |

---

## NGSS Standards Alignment

| Standard | Description |
|----------|-------------|
| **MS-LS1-8** | Gather and synthesize information that sensory receptors respond to stimuli by sending messages to the brain for immediate behavior or storage as memories. |
| **HS-LS1-2** | Develop and use a model to illustrate the hierarchical organization of interacting systems that provide specific functions within multicellular organisms. |
| **MS-ETS1-4** | Develop a model to generate data for iterative testing and modification of a proposed object, tool, or process such that an optimal design can be achieved. |

**Science and Engineering Practices:** Developing and Using Models, Analyzing and Interpreting Data, Constructing Explanations

**Crosscutting Concepts:** Systems and System Models, Cause and Effect, Structure and Function

---

## Learning Objectives

By the end of this module, students will be able to:

1. Build a computational model of a sensory signal pathway that demonstrates how the brain processes different types of sensory input.
2. Compare sensory capabilities across at least three species using data-driven analysis in a simulation environment.
3. Explain how brain-computer interfaces (BCIs) translate neural signals into machine commands using input-output modeling.
4. Run simulations that model signal strength, processing speed, and feedback loops in sensory systems.
5. Evaluate the potential and limitations of current BCI technology using evidence from their models.

---

## Connection to *Hoppers*

In *Hoppers*, scientists at Beaverton University build robotic animals so lifelike that humans can "hop" their consciousness into them — experiencing the world through a beaver's whiskers, a bird's ultraviolet vision, or a fish's lateral line. But how would that actually work? How does a beaver's brain process the feeling of water rushing past its fur differently than how your brain processes the same sensation through your fingertips?

In this module, students explore the real science behind the brain-machine connection. They build computational models of sensory pathways, compare how different species process the same stimuli, and investigate how real-world brain-computer interfaces are already helping people interact with machines using only their thoughts.

---

## Materials Needed

- Computers or tablets with internet access (1 per student or pair)
- Access to Cell Collective or equivalent computational modeling platform
- Student handouts (provided below in procedure)
- Projector/display for class demonstrations
- Whiteboard or chart paper
- Optional: simple circuit kit (LED, battery, wire) for physical analogy
- Optional: blindfolds and textured objects for sensory exploration warm-up

---

## Lesson Procedure (5E Model)

### Day 1: Engage and Explore

#### Engage (10 minutes)

**The Hopper Challenge**

Pose this question to the class:

> "In *Hoppers*, a person can 'hop' into a robotic beaver and suddenly feel water through whiskers, hear sounds underwater, and sense magnetic fields. What would your brain need to do differently to process a beaver's senses instead of your own?"

Show a brief clip or images from the film depicting the consciousness transfer moment. Then facilitate a quick Think-Pair-Share:

- **Think** (1 min): What senses do you rely on most? What senses might a beaver rely on most?
- **Pair** (2 min): Compare answers with a partner. Where do human and beaver senses overlap? Where do they differ?
- **Share** (3 min): Collect responses on the board. Categorize into: senses humans and beavers share, senses that differ, and senses that are unique to one or the other.

**Teacher tip:** Students often forget about less obvious senses like proprioception (body position), thermoception (temperature), or magnetoception (magnetic fields). Prompt them if needed.

#### Explore (35 minutes)

**Activity: Mapping the Sensory Signal Pathway**

Students work in pairs to build a computational model of a basic sensory signal pathway.

**Step 1 — Introduce the Modeling Platform (10 min)**

Walk students through the computational modeling environment (Cell Collective or equivalent). Demonstrate:
- How to create nodes (components) in a model
- How to define relationships between nodes (arrows/connections)
- How to set input values and run a simulation

**Step 2 — Build a Basic Sensory Pathway Model (25 min)**

Students construct a model with these components:

| Node | Role | Type |
|------|------|------|
| Stimulus | Environmental input (e.g., touch, light, sound) | Input variable |
| Sensory Receptor | Detects stimulus and converts to signal | Processing node |
| Sensory Neuron | Transmits signal toward brain | Relay node |
| Brain Processing Center | Interprets signal, determines response | Processing node |
| Motor Neuron | Carries response signal to muscles | Relay node |
| Response | Physical action taken | Output variable |

Students should:
1. Create all six nodes and connect them in sequence
2. Add a "Signal Strength" variable (scale of 0-10) as an input parameter
3. Add a "Processing Speed" variable that can be adjusted
4. Run the simulation with different signal strength values
5. Record observations: What happens when signal strength is low (1-2) vs. high (8-10)?

**Guiding questions for student notebooks:**
- What happens to the response when signal strength drops below a threshold?
- Is the relationship between signal strength and response linear or nonlinear?
- What would happen if the connection between sensory neuron and brain processing center were removed?

---

### Day 2: Explore (continued) and Explain

#### Explore Continued (25 minutes)

**Activity: Cross-Species Sensory Comparison Model**

Students extend their Day 1 model to compare sensory processing across three species: **human**, **beaver**, and **hawk**.

Provide students with this reference data:

| Sensory Capability | Human | Beaver | Red-tailed Hawk |
|---|---|---|---|
| Visual acuity (relative) | 5 | 2 | 10 |
| Underwater hearing | 1 | 8 | 0 |
| Tactile sensitivity (whiskers/touch) | 4 | 9 | 2 |
| Color spectrum range | 6 | 3 | 9 (UV vision) |
| Olfactory sensitivity | 3 | 7 | 1 |
| Night vision | 3 | 6 | 4 |

*Values are relative on a 1-10 scale for modeling purposes. These are simplified for classroom use.*

Students should:
1. Create three parallel sensory pathway models — one for each species
2. Adjust the "Sensory Receptor" sensitivity values based on the data table
3. Run identical stimuli (e.g., "underwater sound at strength 7") through all three models
4. Compare outputs: Which species detects the stimulus? How strong is the response?
5. Create a data table comparing responses across species for at least 3 different stimulus types

**Key modeling moment:** Students should discover that the same stimulus produces dramatically different responses depending on the species' receptor sensitivity — a direct parallel to why "hopping" into a robotic beaver in the film would be a disorienting sensory experience.

#### Explain (20 minutes)

**Class Discussion and Concept Consolidation**

1. **Data Share (8 min):** Each pair presents one finding from their cross-species comparison. Teacher records patterns on the board.

2. **Mini-Lecture: How BCIs Actually Work (12 min):**

   Cover these key concepts, connecting each to students' models:

   - **Neural signals are electrical and chemical** — just like the signal strength variable in their models, real neurons fire with varying intensity
   - **Brain-computer interfaces (BCIs)** read electrical patterns from the brain using electrodes, then translate those patterns into commands for a machine
   - **Real-world BCI applications:**
     - Cochlear implants (sensory input BCIs — the machine sends signals TO the brain)
     - Prosthetic limbs controlled by thought (motor output BCIs — the brain sends signals TO the machine)
     - Communication devices for people with paralysis
   - **The *Hoppers* connection:** The film imagines a two-way BCI — full sensory input FROM the robotic animal AND motor control output TO the robotic animal. Current technology can do pieces of this but not the whole thing yet.

   **Discussion prompt:** "Based on your models, what is the hardest part of building a real-life 'hopping' system? What would need to happen to translate human brain signals into beaver-appropriate motor commands?"

---

### Day 3: Elaborate and Evaluate

#### Elaborate (25 minutes)

**Activity: Design a BCI Signal Translation Model**

Students tackle the core engineering challenge of *Hoppers*: How do you translate signals between a human brain and an animal body?

Students build a new model (or extend their existing one) that includes:

1. **Human Brain Output Node** — generates a motor command (e.g., "move forward")
2. **Signal Translator** — a processing node that converts human motor commands into species-specific commands
3. **Robotic Animal Body** — receives translated commands and produces movement
4. **Sensory Feedback Loop** — the robotic animal's sensors send data back through the translator to the human brain

Key modeling parameters to adjust:
- **Translation accuracy** (0-100%): How well does the translator convert human intent to animal movement?
- **Feedback delay** (milliseconds): How long before sensory data gets back to the human brain?
- **Signal noise** (0-10): Random interference in the translation process

Students run simulations to answer:
- At what translation accuracy does the system become usable? (Find the threshold)
- What happens when feedback delay increases? (Explore lag effects)
- How does signal noise affect the human's ability to control the robotic animal?

**Extension for advanced students:** Add a "learning algorithm" node that improves translation accuracy over time (simulating machine learning adaptation).

#### Evaluate (20 minutes)

**Assessment: The BCI Design Brief**

Students complete an individual written assessment:

1. **Model Explanation (diagram + paragraph):** Draw and label a diagram of your BCI signal translation model. Explain how each component works and why the feedback loop is essential.

2. **Data Analysis (short answer):** Using data from your simulation runs, explain the relationship between translation accuracy and system performance. Include at least two specific data points from your simulations.

3. **Real-World Connection (paragraph):** Choose one real-world BCI application (cochlear implant, prosthetic limb, or communication device). Explain how it relates to the model you built. What components from your model exist in the real device? What components are still missing or limited?

4. **Critical Thinking (paragraph):** In *Hoppers*, the consciousness transfer works perfectly — the human immediately feels and moves as the animal does. Based on your modeling and simulation data, explain why this would be extremely difficult in reality. Identify at least two specific technical challenges your model revealed.

---

## Computational Modeling Activity Summary

**Core Model:** Sensory Signal Pathway
- Nodes: Stimulus, Sensory Receptor, Sensory Neuron, Brain Processing Center, Motor Neuron, Response
- Variables: Signal Strength (input), Processing Speed, Receptor Sensitivity (species-specific)
- Key behavior: Threshold detection, species-specific sensory filtering

**Extended Model:** BCI Signal Translation System
- Additional nodes: Human Brain Output, Signal Translator, Robotic Animal Body, Sensory Feedback Loop
- Variables: Translation Accuracy, Feedback Delay, Signal Noise
- Key behavior: Feedback loops, degradation under noise/delay, threshold performance

**Platform:** Cell Collective or equivalent computational modeling environment

---

## Assessment Rubric

| Criterion | Excellent (4) | Proficient (3) | Developing (2) | Beginning (1) |
|---|---|---|---|---|
| **Model Construction** | Model includes all required nodes, correct connections, and appropriate variable ranges. Runs without errors. | Model includes most nodes and connections. Minor errors in variable setup. | Model is incomplete or has significant connection errors. Runs but produces questionable results. | Model is missing major components or does not run. |
| **Cross-Species Analysis** | Compares all three species with specific data from simulations. Identifies clear patterns and explains biological reasoning. | Compares at least two species with data. Identifies some patterns. | Comparison is vague or lacks supporting data from simulations. | No meaningful comparison attempted. |
| **BCI Understanding** | Accurately explains how BCIs work, connects to model components, and identifies real-world applications with specific examples. | Explains BCI basics and connects to model. Some real-world examples. | Partial understanding of BCIs. Weak connection to model. | Significant misconceptions about BCIs or no connection to model. |
| **Data-Driven Reasoning** | Uses specific simulation data to support all claims. Identifies thresholds and relationships between variables. | Uses some simulation data. Identifies at least one variable relationship. | Limited use of data. Claims are mostly unsupported by simulation results. | No data cited. Claims are opinion-based. |
| **Communication** | Writing is clear, organized, and uses appropriate scientific vocabulary. Diagrams are labeled and accurate. | Writing is mostly clear with some scientific vocabulary. Diagrams present but may lack labels. | Writing is unclear or disorganized. Diagrams incomplete. | Writing does not address the prompts. No diagrams. |

---

## Extension Activities

1. **Research Project — BCIs in Medicine:** Students research a current BCI research project (e.g., Neuralink, BrainGate, cochlear implant advances) and present a 3-minute summary to the class, connecting the real technology to their classroom models.

2. **Sensory Deprivation Modeling:** Students modify their models to simulate what happens when one sensory pathway is blocked (modeling blindness, deafness, etc.) and explore how the brain compensates by increasing sensitivity in other pathways.

3. **Design Challenge — Animal Translator:** Students design (on paper or in the modeling platform) a system that could translate one specific animal sense into a human-understandable signal. For example: How would you let a human "feel" a shark's electroreception?

4. **Cross-Module Connection:** Link to Module 2 (Biomimicry) by having students identify which animal sensory capabilities would be most useful to replicate in a robot designed for search-and-rescue, deep-sea exploration, or wildfire detection.

---

## Teacher Notes

- **Prerequisite knowledge:** Students should have a basic understanding of the nervous system (neurons, brain regions) and the five primary senses. A brief review at the start of Day 1 may be helpful for younger students in the grade band.

- **Differentiation for grades 6-7 vs. 8-10:** For younger students, simplify the cross-species comparison to two species and reduce the BCI translation model to exclude the feedback loop. For older students, add complexity by introducing multiple simultaneous sensory inputs and requiring quantitative analysis of simulation data.

- **Common misconception:** Students often think the brain processes all senses the same way. The cross-species modeling activity directly challenges this by showing how receptor sensitivity determines which stimuli are even detected.

- **Modeling platform notes:** If Cell Collective is not available, this lesson can be adapted for any system dynamics modeling tool (STELLA, NetLogo, or even a well-structured spreadsheet with formulas). The key is that students build the model themselves rather than interacting with a pre-built simulation.

- **Time management:** Day 2 is the most content-heavy. If students need more time on the cross-species comparison model, the Explain mini-lecture can be shortened or moved to the start of Day 3.

- **The *Hoppers* connection is a hook, not the lesson.** Keep film references brief and engaging. The goal is to use the premise to motivate genuine scientific inquiry about sensory processing and neurotechnology. Avoid spending class time on plot details.

- **Sensitivity note:** When discussing BCIs, be aware that some students may have personal connections to assistive technology (hearing aids, cochlear implants, prosthetics). Frame these technologies positively as examples of engineering innovation that improves quality of life.

- **Assessment flexibility:** The written assessment can be completed as homework if class time runs short on Day 3. The model explanation diagram can also be done digitally (screenshot of the model with annotations) rather than hand-drawn.
