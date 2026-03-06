# Module 3: Ecohydrology — Follow the Water

**Grade Band:** 6-8
**Duration:** 3 class periods (approximately 50-55 minutes each)
**Subject Area:** Earth Science, Life Science, Environmental Science, Computational Modeling

---

## NGSS Standards Alignment

| Standard | Description |
|----------|-------------|
| MS-ESS2-4 | Develop a model to describe the cycling of water through Earth's systems driven by energy from the sun and the force of gravity. |
| MS-ESS3-3 | Apply scientific principles to design a method for monitoring and minimizing a human impact on the environment. |
| MS-LS2-4 | Construct an argument supported by empirical evidence that changes to physical or biological components of an ecosystem affect populations. |

**Science and Engineering Practices:** Developing and Using Models, Analyzing and Interpreting Data, Constructing Explanations and Designing Solutions, Engaging in Argument from Evidence

**Crosscutting Concepts:** Cause and Effect, Systems and System Models, Stability and Change

---

## Learning Objectives

By the end of this module, students will be able to:

1. Describe how water moves through a watershed and identify the factors that influence its path, speed, and storage.
2. Build a computational watershed model and manipulate variables (land cover, beaver dams, precipitation levels) to observe changes in water distribution.
3. Analyze simulation data to explain how beaver dams increase water retention, reduce peak flooding, and create fire-resistant green corridors.
4. Use model outputs to construct an evidence-based argument about the role of beaver dams in drought resilience and wildfire mitigation.
5. Evaluate the strengths and limitations of their computational model compared to real-world watershed dynamics.

---

## Connection to Disney Pixar's *Hoppers*

One of the most striking scenes in *Hoppers* shows the dramatic contrast between a beaver-dammed landscape — green, lush, and wet even during drought — and the dry, fire-scarred terrain just beyond the wetlands. This is not movie magic. It is real science. Ecohydrologist Dr. Emily Fairfax (whose research inspired the film and whose name appears in a character) has used satellite imagery to show that beaver-dammed areas stay green while surrounding land burns during wildfires. In this lesson, students become ecohydrologists themselves, building computational watershed models to investigate the same question the *Hoppers* scientists explore: **How do beaver dams change where water goes, and can that protect landscapes from drought and fire?**

---

## Materials Needed

- Computers or tablets (1 per pair) with internet access
- ModelIt! Watershed Simulation (web-based modeling tool)
- Student activity packets (3-day series, provided)
- Projector/smartboard
- Printed watershed maps (blank and annotated versions)
- Graph paper or digital graphing tool for data visualization
- Colored pencils (blue, green, brown, red) for watershed mapping
- Optional: satellite image printouts showing beaver dam effects (before/after wildfire images from Dr. Fairfax's research — publicly available)

---

## Lesson Procedure (5E Model)

### Day 1: Engage and Explore

#### Engage (15 minutes)

1. **Satellite Image Analysis:** Display two satellite images side by side (sourced from publicly available research imagery):
   - Image A: A landscape after wildfire — mostly brown and black scorched terrain, with vivid green ribbons along certain stream corridors
   - Image B: The same landscape before the fire — entirely green

   Ask students: *"What do you notice about Image A? Why would some areas stay green while everything around them burned?"*

   Allow 2-3 minutes of quiet observation and note-taking, then open discussion. Guide students toward the answer: the green corridors follow streams where beaver dams stored water and kept the land wet.

2. **Film Connection:** Explain that *Hoppers* showcases this exact phenomenon — beaver-created wetlands that act as natural firebreaks. The film's science consultant, Dr. Emily Fairfax, discovered this pattern through satellite research. Tell students: *"Today you are going to build a computer model of a watershed to investigate the same question Dr. Fairfax studied: How do beaver dams change where water goes?"*

3. **Driving Question:** Post on the board: **"Can beavers make a landscape fireproof?"**

4. **Key Vocabulary:**
   - **Watershed** — An area of land where all water drains to the same outlet (stream, river, lake)
   - **Ecohydrology** — The study of how water and living things interact in ecosystems
   - **Water retention** — How much water a landscape holds onto instead of letting it flow away
   - **Peak flow** — The highest volume of water moving through a point during a storm event
   - **Riparian zone** — The area of vegetation along the banks of a stream or river
   - **Soil moisture** — The amount of water stored in the soil

#### Explore (35-40 minutes)

1. **Watershed Model Orientation (15 minutes):** Using the projector, walk students through the ModelIt! Watershed Simulation:

   **Landscape Panel:**
   - Topographic grid showing elevation, stream channels, and terrain types
   - Land cover layers (forest, grassland, bare soil, urban)
   - Beaver dam placement tool

   **Controls Panel:**
   - Precipitation slider (dry year, average year, wet year, storm event)
   - Season selector (spring snowmelt, summer dry, fall rain, winter)
   - Time controls (step forward, run continuous, reset)

   **Data Dashboard:**
   - Stream flow rate at the watershed outlet (hydrograph)
   - Soil moisture map (color-coded from dry to saturated)
   - Water table depth at selected monitoring points
   - Total water retained in the watershed (percentage of precipitation)

   **Output Visualizations:**
   - Animated water flow across the landscape
   - Time-series hydrograph (flow rate over time)
   - Soil moisture heat map

2. **Baseline Investigation (20-25 minutes):** Students work in pairs. Distribute the Day 1 Activity Packet.

   **Investigation 1 — No Beaver Dams:**
   - Set the landscape to its default state: forested watershed with stream channels, no beaver dams
   - Run a "storm event" precipitation scenario
   - Record on the data sheet:
     - Peak flow rate at the outlet
     - Time to peak flow (how many time steps until the highest flow)
     - Total water retained in the watershed after the storm passes
     - Soil moisture levels at 3 monitoring points (upstream, midstream, downstream)
   - Sketch the hydrograph shape on graph paper

   **Investigation 2 — With Beaver Dams:**
   - Place 3-5 beaver dams along the stream channels (at suggested locations marked on the map)
   - Run the same storm event
   - Record the same measurements
   - Sketch the new hydrograph on the same graph (different color)

   **Quick Analysis Questions (on the worksheet):**
   - How did peak flow change? Higher or lower? By how much?
   - How did time to peak change?
   - How did soil moisture levels change at each monitoring point?
   - Where on the landscape did you see the biggest difference in water distribution?

---

### Day 2: Explain and Elaborate

#### Explain (25 minutes)

1. **Data Sharing and Pattern Recognition (15 minutes):** Create a class data table on the board:

   | Measurement | No Dams (Class Average) | With Dams (Class Average) | Change |
   |-------------|------------------------|--------------------------|--------|
   | Peak flow rate | | | |
   | Time to peak | | | |
   | Water retained (%) | | | |
   | Soil moisture — upstream | | | |
   | Soil moisture — midstream | | | |
   | Soil moisture — downstream | | | |

   Each pair contributes their data. Calculate class averages. Guide discussion:
   - *"What pattern do you see in the peak flow data?"* (Beaver dams reduce peak flow — they spread the water out over time.)
   - *"What happened to the time to peak?"* (It takes longer for water to reach the outlet — dams slow the flow.)
   - *"Where did the retained water go?"* (Into the soil and floodplain areas near the dams — this is what creates wetlands and raises the water table.)

2. **Connecting to the Driving Question (10 minutes):** Now return to the satellite fire images from Day 1. Explain the mechanism:
   - Beaver dams slow water and spread it across the floodplain
   - This raises soil moisture and keeps riparian vegetation green and hydrated
   - During drought, these areas retain moisture longer than surrounding land
   - During wildfire, the wet, green vegetation does not burn as easily — it acts as a natural firebreak
   - This is exactly what Dr. Fairfax's satellite research confirmed

   Students add a written explanation to their activity packet: *"Using your simulation data, explain the chain of cause and effect from beaver dam to fire-resistant landscape."*

#### Elaborate (25-30 minutes)

1. **Scenario Investigation — Drought and Fire Risk:** Students now run a more complex investigation using the Day 2 Activity Packet.

   **Scenario: Three consecutive dry years followed by a wildfire risk assessment.**

   Students set up the following sequence in the simulation:
   - Run 3 cycles of "dry year" precipitation
   - After the 3rd dry year, examine the soil moisture map
   - The simulation calculates a "Fire Vulnerability Index" for each grid cell based on soil moisture and vegetation dryness

   **Configuration A — No beaver dams:**
   - Record the Fire Vulnerability Index at 5 designated landscape points
   - Record total area classified as "high fire risk" (percentage of landscape)
   - Screenshot or sketch the fire vulnerability map

   **Configuration B — With beaver dams:**
   - Place beaver dams and repeat the 3-year drought sequence
   - Record the same measurements
   - Screenshot or sketch the fire vulnerability map

   **Configuration C — Student-designed dam placement:**
   - Students choose their own dam locations to minimize fire risk across the watershed
   - They must justify their placement strategy in writing before running the simulation
   - Record results and compare to Configurations A and B

2. **Data Comparison Table:**

   | Measurement | No Dams | Standard Dams | Custom Dams |
   |-------------|---------|---------------|-------------|
   | High fire risk area (%) | | | |
   | Fire Vulnerability — Point 1 | | | |
   | Fire Vulnerability — Point 2 | | | |
   | Fire Vulnerability — Point 3 | | | |
   | Fire Vulnerability — Point 4 | | | |
   | Fire Vulnerability — Point 5 | | | |

---

### Day 3: Elaborate (continued) and Evaluate

#### Elaborate Continued (15 minutes)

1. **Advanced Variable Exploration (optional, for classes moving quickly):** Students explore one additional variable:
   - **Land Cover Change:** What happens if part of the forested watershed is converted to grassland or bare soil? How does this interact with the beaver dam effect?
   - **Increased Precipitation:** What if a major storm hits after a drought? Do beaver dams help reduce flash flooding?

   Students run one additional simulation and add a row to their comparison table.

2. **Model Limitations Discussion (10 minutes):** Facilitate a whole-class discussion:
   - *"What does our model include that a real watershed has?"* (Terrain, water flow, vegetation, beaver dams, precipitation)
   - *"What does our model leave out?"* (Real soil types and their different absorption rates, underground aquifers, animal behavior, seasonal changes in vegetation, human land use, actual fire behavior)
   - *"Does leaving things out make the model useless?"* (No — models help us understand specific relationships even when they simplify reality. But we need to be honest about what the model can and cannot tell us.)
   - *"How could we make the model better?"* (Add more variables, use real topographic data from a specific watershed, incorporate actual soil data)

#### Evaluate (35-40 minutes)

1. **Evidence-Based Argument — Written Assessment (20 minutes):** Students write an individual response to the following prompt:

   > **Prompt:** A county government is considering whether to reintroduce beavers to a watershed that has experienced increased wildfire risk over the past decade. Using evidence from your simulation data, write a scientific argument that addresses the question: **Should beavers be reintroduced to reduce wildfire risk in this watershed?**
   >
   > Your response must include:
   > - A clear claim (your position)
   > - At least three pieces of evidence from your simulation data (cite specific numbers)
   > - Reasoning that explains how your evidence supports your claim
   > - Acknowledgment of at least one limitation of the model or one factor the county should also consider

2. **Peer Review (10 minutes):** Students exchange papers with a partner and use a simple checklist to verify:
   - [ ] Claim is clearly stated
   - [ ] At least 3 data points are cited
   - [ ] Reasoning connects evidence to claim
   - [ ] At least one limitation or additional factor is mentioned

   Partners write one piece of constructive feedback. Students revise if time permits.

3. **Closing Discussion (5-10 minutes):** Return to the driving question: *"Can beavers make a landscape fireproof?"*
   - Guide students toward a nuanced answer: Beavers cannot make a landscape completely fireproof, but the data shows they significantly reduce fire vulnerability in the areas near their dams by keeping soil and vegetation moist.
   - Connect back to *Hoppers*: The film shows this dramatically, and the real science supports it. This is an example of how a single species — a keystone species — can have cascading effects on an entire landscape.

---

## Computational Modeling Activity — Core Details

### The ModelIt! Watershed Simulation

**What students build and manipulate:**
- A watershed model on a topographic grid with realistic elevation, stream channels, and land cover
- Students place beaver dams and adjust environmental variables to observe system-level changes in water distribution

**Key model variables students control:**
- Beaver dam presence, number, and placement location
- Precipitation type and amount (dry year, average, wet, storm event)
- Season (affects snowmelt, evapotranspiration rates)
- Land cover type (forest, grassland, bare soil — in the Elaborate extension)

**Key model outputs students observe and record:**
- **Hydrograph:** Stream flow rate over time at the watershed outlet (time-series graph)
- **Peak flow rate:** Maximum instantaneous flow during a precipitation event
- **Time to peak:** Duration from precipitation start to peak flow
- **Water retention:** Percentage of total precipitation stored in the watershed (soil, wetlands, ponds)
- **Soil moisture map:** Spatial visualization of water content across the landscape (color-coded heat map)
- **Water table depth:** Groundwater level at designated monitoring points
- **Fire Vulnerability Index:** Calculated from soil moisture and vegetation dryness (used in Day 2-3 drought scenarios)

**Modeling concepts reinforced:**
- Computational models represent complex systems with interacting variables
- Models produce quantitative data that can be used as evidence in scientific arguments
- Changing one variable (adding beaver dams) produces cascading effects across the system
- Models are simplifications — they are powerful tools for understanding, but they have limitations
- Running multiple scenarios and comparing outputs is how scientists use models to investigate questions

---

## Assessment Rubric

| Criteria | Exceeds (4) | Meets (3) | Approaching (2) | Beginning (1) |
|----------|-------------|-----------|-----------------|---------------|
| **Watershed Systems Understanding** | Accurately describes how water moves through a watershed, explains how beaver dams alter flow and storage, and connects these changes to fire resilience with scientific reasoning | Describes water movement in a watershed and explains how beaver dams change water distribution | Can describe some effects of beaver dams on water but understanding of the full watershed system is incomplete | Cannot describe how water moves through a watershed or how beaver dams affect it |
| **Computational Model Use** | Ran all required configurations plus custom investigation, recorded complete and accurate data, and compared results systematically across scenarios | Ran all required configurations and recorded mostly complete data with comparisons | Ran simulations but data recording is incomplete or comparisons between scenarios are missing | Did not complete required simulation runs |
| **Evidence-Based Argument (Written)** | Claim is clear and well-supported with 3+ specific data points, reasoning explicitly connects evidence to claim, and limitations are thoughtfully discussed | Claim is stated with at least 2 data references, reasoning is present, and a limitation is mentioned | Claim is present but evidence is vague or not clearly connected to data; limitation may be missing | No clear claim or no evidence from simulations |
| **Model Evaluation** | Identifies multiple strengths and limitations of the model, suggests specific improvements, and explains why models are useful despite limitations | Identifies at least one strength and one limitation of the model | Can state that models are not perfect but cannot articulate specific limitations | Does not engage with model evaluation |

---

## Extension Activities

1. **Real Data Comparison:** Using publicly available satellite imagery (e.g., Google Earth time-lapse, Sentinel-2 vegetation index data), students compare a real beaver-dammed watershed to an undammed one in the same region. They look for the same patterns their simulation predicted (greener riparian zones, higher vegetation density near dams).

2. **Watershed Field Study:** If there is a stream or creek near the school, students conduct a mini field study: measure stream width, estimate flow speed (using a floating object and a stopwatch), observe riparian vegetation, and note any signs of beaver activity. They compare their real-world observations to the simulation environment.

3. **Data Journalism Project:** Students write a short news article explaining Dr. Emily Fairfax's beaver research for a general audience. The article must include at least one data visualization (graph or map) created from their simulation data.

4. **Policy Brief:** Students write a one-page policy brief for a fictional city council recommending beaver reintroduction as a wildfire and drought resilience strategy. They must include cost-benefit reasoning and address potential concerns (flooding, tree damage).

5. **Cross-Module Connection:** Students who completed Module 1 (Ecosystem Engineers) compare their elementary model to this more complex watershed model. Discussion: *"Both models show beaver dam effects, but what can this model show that the simpler one could not? Why do scientists build models at different levels of complexity?"*

---

## Teacher Notes

- **Prior Knowledge:** Students should have a basic understanding of the water cycle (evaporation, condensation, precipitation, runoff). Familiarity with topographic maps is helpful but not required — the Day 1 orientation covers map reading within the simulation.

- **Differentiation:**
  - *For students needing support:* Provide a completed baseline data set so they can focus on the beaver dam configurations. Use sentence starters for the written argument (e.g., "I claim that beaver dams [should/should not] be used to reduce fire risk because..."). Reduce the number of monitoring points from 5 to 3.
  - *For advanced students:* Have them design a complete watershed management plan that combines beaver dams with other strategies (vegetation planting, controlled burns, water diversion). They can also explore the land cover change variable and write about compound effects.

- **The Written Argument:** The Day 3 written assessment is the most rigorous component. Consider providing a CER (Claim-Evidence-Reasoning) framework graphic organizer for students unfamiliar with scientific argumentation. The peer review step is intentionally brief — its purpose is to give students a chance to catch missing elements before you assess.

- **Common Misconceptions:**
  - Students may think beaver dams prevent all flooding. Clarify that dams reduce *peak* flow and *spread* water over time, but large enough storms will still cause flooding. The simulation shows this if students set precipitation to the highest levels.
  - Students may think "fire-resistant" means "fireproof." The correct framing is that beaver-dammed areas have *reduced* fire vulnerability because of higher soil moisture and greener vegetation, not that they are immune to fire.
  - Students may assume the model output is exactly what would happen in the real world. The model limitations discussion on Day 3 is critical for addressing this.

- **Hoppers Connection:** The satellite image activity on Day 1 directly mirrors visuals from the film. If you have access to promotional images from *Hoppers* showing the contrast between beaver-dammed green areas and surrounding dry/burned land, these make excellent companion visuals. The science is real regardless of the film — Dr. Fairfax's published research is the foundation.

- **About the Science:** Dr. Emily Fairfax's research (published in journals including *Ecological Applications*) demonstrates that beaver-dammed areas remain green during wildfires while surrounding areas burn. Her satellite analysis of multiple fire events across the American West showed that riparian areas with beaver dams maintained significantly higher vegetation greenness (measured by NDVI — Normalized Difference Vegetation Index) compared to undammed streams in the same fire perimeters. This is the real science behind both the film and this lesson. ModelIt! does not claim to replicate her methodology — the simulation is a simplified educational model that demonstrates the same core principles.

- **Assessment Flexibility:** The written argument can be assigned as homework if class time runs short. If you prefer a presentation-based assessment, groups can present their Configuration C (custom dam placement) strategy and results in lieu of the individual written piece.

- **Time Adjustments:** Day 2 is the most content-dense. If periods are under 50 minutes, consider splitting the Explain and Elaborate sections across two days (making this a 4-day module). The drought-fire scenario investigation is the highest-value activity and should not be rushed.

- **Interdisciplinary Connections:** This module connects naturally to social studies (land management policy, human-wildlife conflict), math (data analysis, percentages, graphing), and ELA (argumentative writing, science communication). Coordinate with colleagues if cross-curricular integration is possible.
