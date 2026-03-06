# Module 6: AI, Robotics & Ethics

**Inspired by Disney Pixar's *Hoppers* (2026)**

| | |
|---|---|
| **Grade Band** | 9-12 |
| **Duration** | 3 class periods (45-50 minutes each) |
| **Subject Areas** | Computer Science, Engineering, Ethics, Biology |
| **Developed by** | ModelIt! K12 in partnership with the University of Nebraska-Lincoln |

---

## NGSS Standards Alignment

| Standard | Description |
|----------|-------------|
| **HS-ETS1-3** | Evaluate a solution to a complex real-world problem based on prioritized criteria and trade-offs that account for a range of constraints, including cost, safety, reliability, and aesthetics, as well as possible social, cultural, and environmental impacts. |
| **HS-ETS1-1** | Analyze a major global challenge to specify qualitative and quantitative criteria and constraints for solutions that account for societal needs and wants. |
| **HS-LS1-2** | Develop and use a model to illustrate the hierarchical organization of interacting systems that provide specific functions within multicellular organisms. |

**Additional Standards:** This module integrates interdisciplinary ethics standards appropriate for high school technology, philosophy, and social studies courses. It supports the CSTA K-12 Computer Science Standards related to the impacts of computing (3A-IC-24, 3A-IC-25).

**Science and Engineering Practices:** Engaging in Argument from Evidence, Constructing Explanations and Designing Solutions, Developing and Using Models

**Crosscutting Concepts:** Systems and System Models, Cause and Effect, Structure and Function

---

## Learning Objectives

By the end of this module, students will be able to:

1. Build a computational decision model that evaluates a technology (consciousness transfer, autonomous robotics, or AI-animal interaction) against multiple ethical criteria simultaneously.
2. Analyze how changing the weight of different ethical criteria in a model changes the recommended outcome, demonstrating that ethical decisions involve trade-offs, not single right answers.
3. Use simulation data to construct an evidence-based argument about the ethical boundaries of a specific technology application.
4. Compare at least two ethical frameworks (utilitarian, rights-based, virtue-based) by modeling how each produces different recommendations for the same scenario.
5. Evaluate real-world AI and robotics applications using criteria developed through their modeling activities.

---

## Connection to *Hoppers*

The central technology in *Hoppers* is extraordinary: scientists transfer human consciousness into robotic animals, allowing people to live as beavers, birds, and fish. The film plays this for wonder and comedy, but it quietly raises questions that real scientists, engineers, and ethicists are already debating.

If we could build a machine that lets you experience life as another species, should we? Who decides which animals get robotic doubles? What happens to the animal's autonomy when a human is "driving" a robot that looks, sounds, and smells like a member of their colony? And if the technology works — if the robotic beaver is indistinguishable from a real one — does that robot have any rights?

These are not hypothetical questions for a distant future. Autonomous robots already interact with wild animal populations. AI systems already make decisions that affect ecosystems. Brain-computer interfaces are already in human clinical trials. In this module, students use computational modeling to explore the ethical dimensions of these technologies — not to find the "right" answer, but to understand how ethical reasoning works and why thoughtful people can disagree.

---

## Materials Needed

- Computers or tablets with internet access (1 per student or pair)
- Access to Cell Collective or equivalent computational modeling platform (or spreadsheet software for the decision model)
- Student handouts (embedded in procedure below)
- Projector/display for class discussions
- Whiteboard or chart paper
- Index cards or sticky notes (for ethical framework sorting activity)
- Optional: printed scenario cards for the Elaborate activity

---

## Lesson Procedure (5E Model)

### Day 1: Engage and Explore

#### Engage (15 minutes)

**The Hopper Dilemma**

Present students with this scenario:

> "You are on the ethics review board at Beaverton University. The hopping technology works — humans can transfer their consciousness into robotic animals and interact with real wildlife. A research team wants approval for three projects. You have to decide: approve, approve with conditions, or deny."

**Project A — Beaver Communication Study**
A researcher wants to hop into a robotic beaver and join a real beaver colony to study their communication and social structure from the inside. The robotic beaver is indistinguishable from a real one. The colony will not know a human is among them.

**Project B — Endangered Species Protection**
Wildlife managers want to hop into robotic wolves and lead a real wolf pack away from a ranching area to prevent lethal removal. The robot wolf would take on the alpha role temporarily.

**Project C — Entertainment Experience**
A theme park wants to license the technology so visitors can "hop" into robotic dolphins and swim with a wild pod for 30 minutes as an educational attraction.

Give students 3 minutes to individually write their initial decision for each project (approve / conditions / deny) and one sentence of reasoning. Then poll the class — show of hands for each project. Record the results. There will be disagreement; that is the point.

Ask: "We all looked at the same three projects, but we came to different conclusions. Why? What values or priorities led you to different decisions?"

This sets up the core insight of the module: ethical decisions depend on which criteria you prioritize, and computational modeling can help us see those trade-offs clearly.

#### Explore (30 minutes)

**Activity: Building an Ethical Decision Model**

Students build a computational model that evaluates technology proposals against multiple ethical criteria.

**Step 1 — Define Ethical Criteria (10 min)**

Through guided class discussion, establish the criteria that should factor into evaluating any new technology that interacts with living systems. Students should identify criteria such as:

| Criterion | Description | Scale |
|---|---|---|
| Scientific Benefit | Does the technology advance understanding of the natural world? | 0-10 |
| Animal Welfare | Does the technology avoid harm to or disruption of animal lives and behaviors? | 0-10 |
| Human Safety | Does the technology pose risks to human participants? | 0-10 |
| Ecological Impact | Does the technology benefit, harm, or have neutral effects on ecosystems? | 0-10 |
| Consent & Autonomy | Can all affected parties (human and animal) meaningfully consent? | 0-10 |
| Reversibility | Can the effects of the technology be undone if problems arise? | 0-10 |
| Equity & Access | Who benefits and who bears the risks? Is access fair? | 0-10 |
| Precedent | What does approving this enable in the future? Slippery slope concerns? | 0-10 |

**Step 2 — Build the Decision Model (20 min)**

Students create a weighted decision model in the computational modeling platform (or in a spreadsheet if the platform is better suited to dynamic systems). The model structure:

**Inputs:**
- Score for each criterion (0-10) for a given technology proposal
- Weight for each criterion (how important it is, 0-1, must sum to 1.0)

**Processing:**
- Weighted score = Score x Weight for each criterion
- Total weighted score = sum of all weighted scores

**Outputs:**
- Overall ethics score (0-10 scale)
- Recommendation threshold: Above 7 = Approve, 4-7 = Approve with conditions, Below 4 = Deny

Students should build this model and then score **Project A (Beaver Communication Study)** from the Engage activity. Each pair assigns their own scores based on their reasoning.

**Key modeling insight:** Students will notice that the same project can receive very different overall scores depending on how the criteria are weighted. A student who weights Animal Welfare at 0.3 and Scientific Benefit at 0.1 will reach a different conclusion than one who reverses those weights.

---

### Day 2: Explore (continued) and Explain

#### Explore Continued (20 minutes)

**Activity: Ethical Frameworks as Weight Profiles**

Introduce three classical ethical frameworks and have students model each as a different set of weights:

**Framework 1: Utilitarian (Greatest Good for the Greatest Number)**
| Criterion | Weight |
|---|---|
| Scientific Benefit | 0.25 |
| Ecological Impact | 0.25 |
| Human Safety | 0.15 |
| Animal Welfare | 0.10 |
| Equity & Access | 0.10 |
| Consent & Autonomy | 0.05 |
| Reversibility | 0.05 |
| Precedent | 0.05 |

**Framework 2: Rights-Based (Protect Individual Rights Above All)**
| Criterion | Weight |
|---|---|
| Consent & Autonomy | 0.30 |
| Animal Welfare | 0.25 |
| Human Safety | 0.20 |
| Reversibility | 0.10 |
| Precedent | 0.10 |
| Scientific Benefit | 0.03 |
| Ecological Impact | 0.02 |
| Equity & Access | 0.00 |

**Framework 3: Virtue Ethics (What Would a Responsible Steward Do?)**
| Criterion | Weight |
|---|---|
| Ecological Impact | 0.20 |
| Animal Welfare | 0.20 |
| Precedent | 0.20 |
| Equity & Access | 0.15 |
| Reversibility | 0.10 |
| Human Safety | 0.10 |
| Consent & Autonomy | 0.03 |
| Scientific Benefit | 0.02 |

Students run all three projects (A, B, and C) through their model using each of the three framework weight profiles. This produces a 3x3 matrix of results:

| | Utilitarian | Rights-Based | Virtue Ethics |
|---|---|---|---|
| Project A (Beaver Study) | | | |
| Project B (Wolf Relocation) | | | |
| Project C (Dolphin Entertainment) | | | |

**Guiding questions:**
- Which project scores highest under each framework? Which scores lowest?
- Is there any project that all three frameworks agree on? (Approve or deny?)
- Which framework is most restrictive? Most permissive?
- Do any projects land in the "approve with conditions" zone under all three? What does that tell you?

#### Explain (25 minutes)

**Class Discussion: What the Models Reveal**

1. **Data Share (10 min):** Each pair shares their 3x3 matrix. Teacher compiles a class-wide summary on the board, noting where there is consensus and where there is disagreement.

2. **Key Concepts (15 min):**

   **a) Ethical frameworks are models too.**
   Just like an ecosystem model simplifies a complex system into interacting variables, an ethical framework simplifies complex moral reasoning into prioritized criteria. Neither is "right" — both are useful tools for thinking.

   **b) Weight matters more than score.**
   Students likely noticed that changing the weights had a bigger impact on outcomes than changing individual scores. This mirrors real ethical debates — disagreements are usually about values (what matters most), not about facts (how well the technology performs on a given criterion).

   **c) The real world uses these models.**
   Introduce real examples of structured ethical evaluation:
   - **Institutional Review Boards (IRBs)** evaluate research proposals involving human subjects using criteria similar to students' models
   - **Environmental Impact Assessments (EIAs)** use weighted criteria to evaluate development projects
   - **AI Ethics Boards** at technology companies use frameworks to evaluate new AI applications
   - **The EU AI Act** categorizes AI applications by risk level — a legislative version of a decision model

   **d) Connection to *Hoppers* and real technology:**
   - **Autonomous wildlife robots** already exist — researchers deploy robotic fish, birds, and insects to study animal behavior. The ethical questions students modeled are already being debated.
   - **Brain-computer interfaces** are in human trials. The question of who should have access and what applications are acceptable is active policy debate.
   - **AI-driven wildlife management** uses algorithms to make decisions about animal populations. Who programs the values? Whose ethical framework gets encoded?

---

### Day 3: Elaborate and Evaluate

#### Elaborate (25 minutes)

**Activity: The Ethics Simulation — Real Technology Scenarios**

Students apply their decision model to real-world technologies that exist today or are in active development. Each pair receives one scenario (or chooses one):

**Scenario 1: Robot Bees for Pollination**
A company has developed autonomous robotic bees to pollinate crops in areas where bee populations have collapsed. The robots are effective but could reduce economic pressure to protect real bee habitats. They also outcompete surviving wild bees for flower access in some field tests.

**Scenario 2: AI Predator Control**
A national park uses AI-powered cameras and drones to track predator movements and automatically deploy non-lethal deterrents (sound, light) when predators approach livestock areas. The system is 94% accurate but has incorrectly targeted non-predator wildlife 6% of the time, causing stress behaviors.

**Scenario 3: Deep-Sea Mining with Autonomous Robots**
A mining company wants to use autonomous underwater robots to extract rare minerals from the deep ocean floor. The minerals are needed for renewable energy batteries. The mining would destroy deep-sea hydrothermal vent ecosystems that host unique species found nowhere else on Earth.

**Scenario 4: Genetic Rescue via AI-Designed Organisms**
Scientists propose using AI to design genetically modified coral that can survive ocean warming and acidification. The modified coral would be released into dying reef systems. Long-term effects on reef ecosystems are unknown, but without intervention, the reefs will die within 20 years.

**Scenario 5: Consciousness Upload for Species Preservation**
A tech company (inspired by the *Hoppers* hopping technology) proposes recording the complete neural patterns of the last living members of critically endangered species into a digital archive. They claim this "digital consciousness" could one day be loaded into robotic bodies to "restore" the species. Critics call it a distraction from real conservation.

**Student task:**

1. Score their scenario on all 8 ethical criteria (0-10 for each)
2. Run the scenario through all three ethical framework weight profiles
3. Identify which framework produces the highest and lowest scores
4. Determine their own recommendation: Approve, Approve with Conditions, or Deny
5. Write a brief (one paragraph) justification explaining:
   - Which ethical framework most closely aligns with their recommendation
   - Which single criterion was most decisive in their reasoning
   - What conditions they would impose (if applicable)

**Class share (5 min):** Quick round-robin — each pair shares their scenario, recommendation, and the one criterion that mattered most. Class notes patterns across scenarios.

#### Evaluate (20 minutes)

**Assessment: Ethical Analysis Portfolio**

Students complete an individual written assessment with three parts:

**Part 1 — Model Documentation (diagram + explanation)**

Provide a clear representation of your ethical decision model (screenshot, diagram, or formula sheet). Explain:
- What each criterion represents and why it is included
- How the weighting system works
- What the output score means and how it maps to a recommendation

**Part 2 — Comparative Framework Analysis**

Choose one of the three *Hoppers* projects (A, B, or C) from Day 1. Present your model's output for that project under all three ethical frameworks. Then answer:

- Why do the three frameworks produce different recommendations for the same project?
- Which framework do you find most compelling for evaluating technologies that affect animals? Defend your choice with at least two specific reasons.
- Identify one limitation of using a computational model for ethical decision-making. What does the model miss that human judgment captures?

**Part 3 — Real-World Application**

Choose a technology that currently exists (examples: facial recognition, autonomous vehicles, CRISPR gene editing, social media recommendation algorithms, or one from the Day 3 scenarios). Run it through your decision model using the ethical framework you find most compelling. Present:
- Your scores for each criterion (with brief justification for each)
- The weighted total and recommendation
- One paragraph arguing for your recommendation, citing your model data
- One paragraph presenting the strongest counterargument (using a different framework's perspective)

---

## Computational Modeling Activity Summary

**Core Model:** Weighted Multi-Criteria Ethical Decision Model
- 8 input criteria, each scored 0-10
- Weight profile determines criterion importance (weights sum to 1.0)
- Output: Weighted ethics score (0-10) mapped to Approve / Conditions / Deny
- Three preset weight profiles representing Utilitarian, Rights-Based, and Virtue Ethics frameworks
- Students also create their own custom weight profile

**Simulation Runs:**
- 3 fictional *Hoppers*-inspired projects x 3 ethical frameworks = 9 evaluations
- 1 real-world technology scenario x 3 frameworks = 3 evaluations
- 1 student-selected real technology x student's chosen framework = 1 evaluation

**Key Computational Thinking Skills:**
- Parameterization (translating qualitative ethical judgments into quantitative scores)
- Sensitivity analysis (how do changes in weights affect outcomes?)
- Model comparison (same inputs, different parameters, different outputs)
- Model limitations (what can and cannot be captured computationally?)

**Platform:** Cell Collective, spreadsheet software, or any tool that allows weighted calculations and variable adjustment

---

## Assessment Rubric

| Criterion | Excellent (4) | Proficient (3) | Developing (2) | Beginning (1) |
|---|---|---|---|---|
| **Model Construction & Documentation** | Model is fully functional with all 8 criteria, correct weighting, and clear threshold logic. Documentation explains every component. | Model works with most criteria and correct weighting. Documentation covers main components. | Model is partially functional or has weighting errors. Documentation is incomplete. | Model does not function or is missing major components. No meaningful documentation. |
| **Framework Comparison** | Accurately applies all three frameworks. Clearly explains why different frameworks produce different outcomes. Identifies specific criteria that drive divergence. | Applies at least two frameworks correctly. Explains some reasons for different outcomes. | Applies frameworks but with errors in weights or interpretation. Comparison is superficial. | Does not apply multiple frameworks or confuses framework concepts. |
| **Evidence-Based Argument** | Recommendation is clearly stated, supported by specific model data, and addresses counterarguments using an alternative framework. Reasoning is nuanced. | Recommendation is stated with some data support. Counterargument is present but underdeveloped. | Recommendation is present but weakly supported. No meaningful counterargument. | No clear recommendation or no connection to model data. |
| **Ethical Reasoning Quality** | Demonstrates understanding that ethical questions involve legitimate disagreement. Identifies model limitations thoughtfully. Avoids oversimplification. | Shows understanding of multiple perspectives. Some recognition of model limitations. | Treats ethics as having a single right answer. Limited recognition of complexity. | No meaningful engagement with ethical reasoning. |
| **Real-World Application** | Applies model to a real technology with well-justified scores, clear analysis, and insightful connections between model output and real-world implications. | Applies model to a real technology with reasonable scores and adequate analysis. | Application to real technology is superficial or scores are unjustified. | No real-world application or application is disconnected from model. |

---

## Extension Activities

1. **AI Ethics Board Simulation:** Students form a mock ethics board and review a proposal from another group (swap Day 3 scenarios). The board must reach a consensus decision, documenting their deliberation process and the framework they used to resolve disagreements.

2. **Weight Sensitivity Analysis:** Students systematically vary one criterion's weight while holding others constant and graph the effect on the overall score. This teaches sensitivity analysis — identifying which criteria are "tipping point" factors for a given technology.

3. **Historical Case Study:** Students apply their decision model retroactively to a historical technology decision (e.g., DDT use, nuclear power, social media) and compare their model's recommendation to what actually happened. Discuss: Would structured ethical modeling have changed the outcome?

4. **Design Your Own Framework:** Students create a fourth ethical framework with its own weight profile, name it, and write a one-page philosophy statement explaining what values it prioritizes and why. They then run all scenarios through their custom framework and compare results to the three standard frameworks.

5. **Cross-Module Synthesis:** Students revisit the beaver reintroduction decision from Module 5 and run it through their ethical decision model. How does an ecological engineering decision look when evaluated through an ethics lens? Are there ethical concerns with beaver reintroduction that the pure science model did not capture?

6. **Guest Speaker or Interview:** Students prepare questions for a professional who works at the intersection of technology and ethics (a university IRB member, an environmental lawyer, a tech company policy analyst) and conduct an interview exploring how ethical frameworks operate in real institutional settings.

---

## Teacher Notes

- **This is not a philosophy class, and that is fine.** The ethical frameworks are presented as modeling tools — ways to structure thinking — not as philosophical positions students need to master in depth. The goal is for students to see that values can be parameterized, compared, and analyzed, just like any other system variable. Keep the focus on the computational modeling activity and the data it produces.

- **Managing classroom discussions on ethics:** Ethical topics can generate strong opinions. Establish discussion norms before Day 1:
  - We critique ideas, not people
  - "I disagree because..." not "That's wrong"
  - Everyone's reasoning matters, even if we reach different conclusions
  - The model gives us a shared language for comparing viewpoints

- **The model's limitations are a feature, not a bug.** Students should conclude that computational models are powerful tools for ethical analysis but cannot replace human judgment. The model cannot capture emotional nuance, cultural context, or moral intuition. Explicitly discuss this in the Explain phase — it is one of the most important takeaways.

- **Scoring ethics is inherently subjective, and students should know that.** When students assign a "7" to Animal Welfare for a given project, that is a judgment call. Different students will score the same criterion differently for the same project, and that is expected. The model's value is not in producing the "correct" answer but in making the reasoning visible and comparable.

- **Differentiation for grades 9-10 vs. 11-12:** For younger students, reduce to 5-6 criteria (drop Precedent and Equity & Access, which require more abstract thinking) and use only two ethical frameworks. For older students, require the sensitivity analysis extension and ask them to identify which criterion is the "swing vote" for each scenario.

- **Connecting to real careers:** If time allows, briefly mention careers that involve this kind of work: bioethicist, technology policy analyst, environmental impact assessor, IRB coordinator, AI safety researcher. Students who enjoy this module may not realize these are real career paths.

- **Time management:** Day 2 is the most intellectually demanding. The Explain discussion may need to be shortened if students are still working through their 3x3 matrix. Prioritize getting students through at least two of the three framework profiles — the third can be completed as homework.

- **Assessment flexibility:** The three-part portfolio can be completed across Days 2-3 and as homework. Part 1 (model documentation) can be a screenshot with annotations. Part 3 (real-world application) works well as a take-home assignment since students may want to research their chosen technology.

- **The *Hoppers* hook should diminish as the module progresses.** By Day 3, students should be engaging with the real-world implications of AI, robotics, and ethics on their own terms. The film scenario is a fun entry point, but the module's value is in the transferable skill of structured ethical analysis through computational modeling.
