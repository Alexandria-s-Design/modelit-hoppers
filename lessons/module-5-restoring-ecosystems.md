# Module 5: Restoring Ecosystems — The Beaver Solution

**Inspired by Disney Pixar's *Hoppers* (2026)**

| | |
|---|---|
| **Grade Band** | 8-12 |
| **Duration** | 3 class periods (45-50 minutes each) |
| **Subject Areas** | Environmental Science, Ecology, Data Analysis, Earth Science |
| **Developed by** | ModelIt! K12 in partnership with the University of Nebraska-Lincoln |

---

## NGSS Standards Alignment

| Standard | Description |
|----------|-------------|
| **HS-LS2-6** | Evaluate claims, evidence, and reasoning that the complex interactions in ecosystems maintain relatively consistent numbers and types of organisms in stable conditions, but changing conditions may result in a new ecosystem. |
| **HS-LS2-7** | Design, evaluate, and refine a solution for reducing the impacts of human activities on the environment and biodiversity. |
| **HS-ESS3-4** | Evaluate or refine a technological solution that reduces impacts of human activities on natural systems. |
| **HS-LS2-2** | Use mathematical representations to support and revise explanations based on evidence about factors affecting biodiversity and populations in ecosystems. |

**Science and Engineering Practices:** Analyzing and Interpreting Data, Using Mathematics and Computational Thinking, Engaging in Argument from Evidence, Developing and Using Models

**Crosscutting Concepts:** Cause and Effect, Stability and Change, Systems and System Models

---

## Learning Objectives

By the end of this module, students will be able to:

1. Build and run a computational ecosystem model that simulates the cascading effects of beaver reintroduction on a degraded watershed.
2. Analyze real research data on beaver-created wetlands and wildfire resilience to support evidence-based claims.
3. Use simulation data to compare ecosystem outcomes with and without beaver activity over multiple time scales.
4. Evaluate beaver reintroduction as a nature-based engineering solution by weighing ecological benefits, costs, and trade-offs using model outputs.
5. Construct a data-supported argument for or against beaver reintroduction in a specific real-world scenario.

---

## Connection to *Hoppers*

In *Hoppers*, the scientists at Beaverton University don't just study beavers from the outside — they "hop" into robotic beavers and experience firsthand how these animals transform landscapes. They feel the current change as a dam goes up. They watch a barren stream bank become a thriving wetland in fast-forward. The film's science consultant, Dr. Emily Fairfax, spent a decade studying exactly this phenomenon: how beavers create green, fire-resistant oases in landscapes devastated by drought and wildfire.

In this module, students step into the role of ecosystem scientists. They won't hop into a robotic beaver, but they will build computational models that reveal the same truth the film celebrates — that a single species, given the chance, can engineer an entire ecosystem back to health.

---

## Materials Needed

- Computers or tablets with internet access (1 per student or pair)
- Access to Cell Collective or equivalent computational modeling platform
- Spreadsheet software (Google Sheets, Excel, or equivalent)
- Student data packet (printable or digital — see Data Sets below)
- Projector/display for class data analysis
- Whiteboard or large chart paper for class data compilation
- Colored pencils or markers (for hand-drawn model diagrams on Day 1)
- Optional: printed satellite images of beaver-modified landscapes

### Data Sets Referenced

The following data concepts are used in student activities. Teachers should prepare simplified data tables based on published research:

- Vegetation greenness (NDVI) in beaver-dammed vs. undammed stream reaches during drought
- Stream temperature data upstream vs. downstream of beaver dams
- Species diversity counts in restored vs. unrestored riparian areas
- Water table depth measurements near and far from beaver ponds

*Note: Simplified and classroom-appropriate data tables are embedded in the lesson procedures below. These are based on patterns documented in published ecohydrology research, adapted for educational use.*

---

## Lesson Procedure (5E Model)

### Day 1: Engage and Explore

#### Engage (15 minutes)

**The Satellite View**

Display two satellite/aerial images side by side (or describe them if images are unavailable):

- **Image A:** A drought-stricken Western U.S. stream corridor. Brown, dry vegetation. Narrow, incised stream channel. Minimal tree canopy.
- **Image B:** The same region, but a section where beavers have built dams. Bright green vegetation. Wide, marshy wetlands. Dense riparian forest. Ponds visible.

Ask students:

> "These two images are from the same region, during the same drought, in the same year. What is different, and what could explain the difference?"

Allow 3-4 minutes of open discussion. Students will likely guess irrigation, rainfall differences, or human intervention. Then reveal: the difference is beavers.

**Key framing for the module:**

> "Dr. Emily Fairfax, the scientist who consulted on *Hoppers*, discovered something remarkable: beaver-dammed areas stayed green and moist even when everything around them dried out and burned. In her research, she found that beaver ponds raised water tables, cooled stream temperatures, and created firebreaks — all without any human engineering. Today, we're going to model how that works."

#### Explore (30 minutes)

**Activity: Building the Beaver Ecosystem Model**

Students work in pairs to construct a computational model of a stream ecosystem with and without beaver activity.

**Step 1 — Identify System Components (10 min)**

As a class, brainstorm the key components of a stream/riparian ecosystem. Teacher guides students to identify these nodes for their model:

| Node | Description | Type |
|------|-------------|------|
| Precipitation | Rainfall/snowmelt input | Input variable |
| Stream Flow | Water volume moving through channel | Dynamic variable |
| Beaver Dams (present/absent) | Toggle: are beavers in the system? | Control variable (0 or 1) |
| Ponded Water | Water stored behind dams | Dynamic variable |
| Water Table Depth | Groundwater level | Dynamic variable |
| Riparian Vegetation | Plant growth along stream | Dynamic variable |
| Soil Moisture | Water content in surrounding soil | Dynamic variable |
| Stream Temperature | Water temperature | Dynamic variable |
| Aquatic Biodiversity | Number/diversity of aquatic species | Output variable |
| Wildfire Vulnerability | How susceptible the area is to fire | Output variable |

**Step 2 — Define Relationships (10 min)**

Students draw connections between nodes. Guide them to establish these key relationships:

- Precipitation **increases** Stream Flow
- Beaver Dams **increase** Ponded Water (when present)
- Ponded Water **raises** Water Table Depth
- Higher Water Table **increases** Soil Moisture
- Higher Soil Moisture **increases** Riparian Vegetation
- More Riparian Vegetation **decreases** Stream Temperature (shade)
- Lower Stream Temperature **increases** Aquatic Biodiversity
- Higher Soil Moisture **decreases** Wildfire Vulnerability
- More Riparian Vegetation **decreases** Wildfire Vulnerability
- Riparian Vegetation **increases** Ponded Water (roots trap sediment, reinforce dams) — this is a **positive feedback loop**

**Step 3 — Build in the Modeling Platform (10 min)**

Students translate their diagram into the computational modeling platform, creating nodes and connections. Set initial variable ranges:

- Precipitation: 0-10 (0 = severe drought, 10 = heavy rain)
- Beaver Dams: 0 (absent) or 1 (present)
- All other variables: start at 5 (moderate baseline)

Students should have a working model by the end of Day 1. If time is short, completing the build can extend into Day 2.

---

### Day 2: Explore (continued) and Explain

#### Explore Continued (25 minutes)

**Activity: Running the Drought Simulation**

Students use their models to simulate two scenarios and collect data.

**Scenario A — Drought Without Beavers**
- Set Precipitation to 2 (drought conditions)
- Set Beaver Dams to 0 (absent)
- Run simulation for 10 time steps (representing 10 years)
- Record values for: Water Table Depth, Riparian Vegetation, Stream Temperature, Aquatic Biodiversity, Wildfire Vulnerability

**Scenario B — Drought With Beavers**
- Set Precipitation to 2 (same drought)
- Set Beaver Dams to 1 (present)
- Run simulation for 10 time steps
- Record the same variables

Students organize results into a comparison table:

| Variable | Year 1 (No Beaver) | Year 5 (No Beaver) | Year 10 (No Beaver) | Year 1 (Beaver) | Year 5 (Beaver) | Year 10 (Beaver) |
|----------|---|---|---|---|---|---|
| Water Table Depth | | | | | | |
| Riparian Vegetation | | | | | | |
| Stream Temperature | | | | | | |
| Aquatic Biodiversity | | | | | | |
| Wildfire Vulnerability | | | | | | |

**Guiding questions:**
- At what time step do the two scenarios begin to diverge significantly?
- Which variable shows the biggest difference between beaver and no-beaver scenarios?
- Can you identify the feedback loop in action? Where does the "beaver effect" compound over time?

**Activity: Comparing Model Output to Research Data**

After running simulations, students compare their model outputs to simplified research data:

**Research Data Table — Vegetation Greenness During Drought (based on NDVI patterns)**

| Location Type | NDVI During Normal Year | NDVI During Drought Year | Change |
|---|---|---|---|
| Stream reach without beaver dams | 0.65 | 0.30 | -54% |
| Stream reach with beaver dams | 0.70 | 0.58 | -17% |
| Upland area (no stream) | 0.45 | 0.15 | -67% |

*NDVI = Normalized Difference Vegetation Index. Values closer to 1.0 indicate denser, greener vegetation. These values are simplified approximations based on patterns in published research.*

**Research Data Table — Stream Temperature**

| Measurement Point | Summer Temp (No Beaver) | Summer Temp (Beaver Reach) |
|---|---|---|
| Upstream of beaver dam complex | 22.5 C | 22.5 C |
| Within beaver pond complex | N/A | 16.8 C |
| Downstream of beaver dam complex | 23.1 C | 18.2 C |

**Discussion questions for data comparison:**
- Does your model's behavior match the patterns in the research data?
- If your model diverges from the research data, what might be missing from your model?
- What does the NDVI data tell us about the "firebreak" effect of beaver ponds?

#### Explain (20 minutes)

**Concept Consolidation: Why Beavers Are Ecosystem Engineers**

Teacher-led discussion connecting student model results to key ecological concepts:

1. **Keystone Species (5 min):** A keystone species has a disproportionately large effect on its ecosystem relative to its abundance. Students' models demonstrated this — toggling a single variable (Beaver Dams: 0 to 1) cascaded through the entire system.

2. **Positive Feedback Loops (5 min):** Highlight the reinforcing loop in their models: Beaver dams create ponds, which raise water tables, which grow vegetation, which stabilizes dams and banks, which creates more ponding. Ask: "Is this loop stable? What could break it?"

3. **Nature-Based Solutions (5 min):** Introduce the concept that ecosystem restoration using natural processes (like beaver reintroduction) is an active area of environmental engineering. Compare cost and effectiveness:

   | Approach | Estimated Cost per Mile | Maintenance | Ecological Co-benefits |
   |---|---|---|---|
   | Concrete stream restoration | $500,000-$1,000,000 | Ongoing, expensive | Minimal |
   | Beaver dam analogs (human-built) | $5,000-$15,000 | Low, some monitoring | Moderate |
   | Beaver reintroduction | $1,000-$5,000 | Self-maintaining | Extensive |

   *Cost estimates are approximate and vary by region and project scope.*

4. **Connecting to *Hoppers* (5 min):** In the film, the scientists "hop" into robotic beavers to understand what drives real beavers to build where they build. The science behind this is real — researchers study beaver dam site selection, flow preferences, and construction behavior to predict where reintroduction will be most effective. Students' models capture the downstream effects; real research also models the beaver's "decision-making."

---

### Day 3: Elaborate and Evaluate

#### Elaborate (25 minutes)

**Activity: The Restoration Decision Model**

Students take on the role of environmental consultants. A county government is considering three approaches to restore a fire-damaged watershed. Students must use their models and the research data to evaluate each option and make a recommendation.

**The Scenario:**

> Pine Creek watershed in a Western U.S. county experienced a severe wildfire two years ago. The riparian zone is degraded, water temperatures are dangerously high for native trout, and the county faces increasing wildfire risk. The county has a budget of $200,000 and wants a solution that will show measurable results within 5 years but remain effective for 20+ years.

**Option 1: Engineered Stream Restoration**
- Install concrete and rock structures to slow water flow
- Plant nursery-grown riparian vegetation
- Cost: $180,000 for 1 mile of stream
- Requires annual maintenance ($15,000/year)
- Immediate but limited ecological benefit

**Option 2: Beaver Dam Analogs (BDAs)**
- Build human-made structures that mimic beaver dams using posts and woven branches
- Designed to attract real beavers to the site over time
- Cost: $10,000 per mile (can treat 20 miles)
- Low maintenance; may need rebuilding after major floods
- Moderate ecological benefit, increasing if beavers colonize

**Option 3: Beaver Reintroduction**
- Relocate beaver families from conflict areas to Pine Creek
- Install temporary fencing to protect infrastructure during establishment
- Cost: $3,000 per beaver family (can relocate 15+ families across watershed)
- Self-maintaining once established
- Extensive ecological benefit but slower initial results; some risk of human-beaver conflict (flooding roads, cutting trees near homes)

**Student task:**

1. Modify their computational model to simulate each of the three options over a 20-year time horizon. Adjust variables to reflect the different approaches:
   - Option 1: Set initial Riparian Vegetation higher, but no Beaver Dams node active. Add a "Maintenance" input that keeps structures functional.
   - Option 2: Start with Beaver Dams at 0.5 (partial), increasing to 1 if beavers colonize (at time step 5).
   - Option 3: Start with Beaver Dams at 1, but set initial Ponded Water lower (beavers take time to build).

2. Run all three scenarios and record outcomes at Year 5, Year 10, and Year 20 for: Wildfire Vulnerability, Aquatic Biodiversity, Stream Temperature, and total estimated cost.

3. Create a summary comparison table or chart.

4. Write a one-page recommendation memo to the county, citing specific model data to support their choice.

#### Evaluate (20 minutes)

**Assessment: Evidence-Based Ecosystem Restoration Proposal**

Students submit their recommendation memo and model data. The memo should include:

1. **Claim:** Which restoration option do you recommend and why? (1-2 sentences)

2. **Evidence:** Present at least three specific data points from your simulations that support your recommendation. Include your comparison table or chart.

3. **Reasoning:** Explain the ecological mechanisms that make your recommended approach effective. Reference the feedback loops and cascading effects visible in your model.

4. **Trade-offs:** Acknowledge at least one disadvantage of your recommended approach and explain why the benefits outweigh it.

5. **Connection to Research:** Reference at least one piece of the research data (NDVI, temperature, or cost data) provided in class and explain how it supports your recommendation.

---

## Computational Modeling Activity Summary

**Core Model:** Stream/Riparian Ecosystem with Beaver Variable
- 10 nodes representing hydrological and ecological components
- Key control variable: Beaver Dams (present/absent)
- Key input: Precipitation level
- Key outputs: Wildfire Vulnerability, Aquatic Biodiversity, Stream Temperature
- Core behavior: Positive feedback loop (beaver dams create conditions that sustain more beaver activity and ecosystem health)

**Simulation Runs:**
- Drought scenario: with and without beavers (10-year horizon)
- Restoration comparison: three management options (20-year horizon)

**Data Analysis:**
- Comparison of model outputs to simplified research data (NDVI, temperature)
- Cost-benefit analysis across restoration approaches

**Platform:** Cell Collective or equivalent computational modeling environment, supplemented with spreadsheet for data analysis and visualization

---

## Assessment Rubric

| Criterion | Excellent (4) | Proficient (3) | Developing (2) | Beginning (1) |
|---|---|---|---|---|
| **Model Construction** | Model includes all required nodes with correct relationships, including feedback loop. Runs accurately across all scenarios. | Model includes most nodes and relationships. Minor errors that do not significantly affect outputs. | Model is incomplete or has relationship errors that affect simulation accuracy. | Model is non-functional or missing major components. |
| **Data Analysis** | Collects complete data from all scenarios. Creates clear comparison tables/charts. Identifies trends and thresholds accurately. | Collects data from most scenarios. Comparison is present but may lack some detail. | Data collection is incomplete. Comparison is superficial or contains errors. | Minimal data collected. No meaningful comparison. |
| **Evidence-Based Argument** | Recommendation is clearly stated with 3+ specific data points from simulations and research. Reasoning explains ecological mechanisms. | Recommendation is stated with some data support. Reasoning addresses mechanisms but may lack depth. | Recommendation is present but weakly supported by data. Reasoning is vague. | No clear recommendation or no data support. |
| **Trade-off Analysis** | Accurately identifies trade-offs for recommended and alternative approaches. Uses model data to weigh pros and cons. | Identifies at least one trade-off. Some connection to model data. | Trade-offs mentioned but not analyzed or connected to data. | No trade-off analysis. |
| **Scientific Communication** | Memo is well-organized, uses scientific vocabulary accurately, and presents data clearly. Would be understandable to a non-scientist decision-maker. | Memo is organized with some scientific vocabulary. Data presentation is adequate. | Memo is disorganized or uses vocabulary inaccurately. Data is present but hard to interpret. | Memo does not address the prompt or lacks coherence. |

---

## Extension Activities

1. **Real Data Deep Dive:** Access publicly available satellite imagery (Google Earth Engine, Landsat) to examine actual NDVI changes in a beaver-restored watershed. Students compare real remote sensing data to their model predictions.

2. **Stakeholder Debate:** Assign students different stakeholder roles (rancher, town mayor, environmentalist, fishing guide, water utility manager) and hold a structured debate about beaver reintroduction. Each stakeholder must use model data to support their position.

3. **Beaver Dam Analog Design Challenge:** Students design and build a scale model of a beaver dam analog using craft materials, then test it in a stream table or rain gutter to measure its effects on flow rate, sediment capture, and water retention.

4. **Cross-Module Connection:** Link to Module 3 (Ecohydrology) by adding a wildfire event to the model — at time step 5, dramatically reduce Riparian Vegetation and increase Stream Temperature, then observe how quickly the system recovers with vs. without beaver activity.

5. **Letter to a Scientist:** Students write a letter to Dr. Emily Fairfax with a specific question about her beaver research that emerged from their modeling work. Focus on what their model could not capture that her field research could.

---

## Teacher Notes

- **Scientific accuracy note:** The data tables provided in this lesson are simplified approximations based on patterns documented in published ecohydrology research, particularly work on beaver-created refugia during drought and wildfire. They are designed for classroom modeling, not as exact replications of any single study. If students want to explore the primary literature, Dr. Emily Fairfax's published papers on beaver dam-created refugia are accessible and well-written.

- **Differentiation for grades 8-9 vs. 10-12:** For younger students, reduce the number of model nodes (combine Soil Moisture and Water Table Depth into a single "Groundwater" node, for example) and focus the elaboration activity on comparing only two restoration options. For older students, add economic variables to the model (property damage from flooding, firefighting costs saved) and require quantitative cost-benefit analysis in the recommendation memo.

- **The feedback loop is the key concept.** Make sure students can identify and explain the positive feedback loop in their model. This is what makes beaver reintroduction a self-sustaining solution — the loop means beavers create the conditions for their own success, which is fundamentally different from engineered solutions that require ongoing human maintenance.

- **Avoiding oversimplification:** While this lesson presents beaver reintroduction positively (as the research supports), acknowledge that it is not a universal solution. Beavers can cause flooding of roads and agricultural land, cut down valued trees, and create conflicts with landowners. The trade-off analysis in the Elaborate section is designed to address this nuance. Encourage students to grapple with these complexities rather than treating beaver reintroduction as a simple "good vs. bad" narrative.

- **Data literacy focus:** This module emphasizes working with data — both model-generated and research-derived. If students struggle with data interpretation, consider spending additional time on the NDVI and temperature tables before moving to the simulation comparison. The ability to compare model output to empirical data is a critical science practice.

- **Time management:** The Elaborate activity (restoration decision model) is the most time-intensive. If students need more time, the recommendation memo can be assigned as homework. The simulation runs themselves should be completed in class so students can troubleshoot model issues with support.

- **Connection to current events:** Beaver reintroduction programs are active across the Western U.S., U.K., and parts of Europe. Current news articles about these programs can serve as engaging supplementary reading and help students see that the science they are modeling has direct real-world policy implications.

- **ModelIt! approach reminder:** The goal is for students to build and explore models, not to receive a lecture on beaver ecology. Resist the urge to over-explain the science before students have had a chance to discover patterns through their models. The Explain phase should confirm and deepen what students have already begun to figure out.
