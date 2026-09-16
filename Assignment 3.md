# Assignment 3 - Homework & Deliverables

**PROJECT 1 | Team Members:** Avery, Parker, Austin, Derek, Grant

_Repository Link:_ <https://github.com/rudda4-wq/TeamDerick-Project1-CGC>

_Coordinate with your team using your new GitHub repository to complete this document before the next class._

### Grading Rubric (14 Points Total)

**Tech Execution (6 Points):**

- **2 pts:** GitHub Repository successfully created, synced, and used by the team.
- **2 pts:** Whiteboard photo properly embedded using Markdown syntax.
- **2 pts:** Mermaid.js code successfully generated, properly formatted in a code block, and renders a valid flowchart.

**Mind Map & Concepts (8 Points):**

- **4 pts:** Mind Map Breadth (Photo/Code shows robust brainstorming, integrating the blind stimulus with the 25kg challenge, minimum 15+ nodes).
- **4 pts:** Concept Evaluations (Each team member completed their pitch thoroughly, directly addressing how geometry manages the load, and accurately completed the constraint checks).

## Section 1: Tech Setup & AI Digitization (6 Points)

**1a. GitHub Student Pack (Do this immediately)**

- Register for a free [GitHub Student Developer Pack](https://education.github.com/pack). This gives you free access to GitHub Copilot. _(Approval can take time; do this today)._

**1b. Whiteboard Photo**

_(Embed your whiteboard photo here in markdown format: !\[Whiteboard Map\](link-to-image))_

**1c. AI-Generated Mermaid Code**

- **Action:** Open **GitHub Copilot Chat** directly inside VS Code. Click the paperclip icon (or drag-and-drop) to upload the photo of your whiteboard.
- **Prompt:** _"Act as an expert software engineer. Convert this hand-drawn mind map into valid Mermaid.js flowchart code. Use a top-down (TD) orientation. Ensure the concepts marked with stars are noted."_
- **Fallback:** If Copilot struggles to read the handwriting, manually construct your map using the visual editor at [MermaidChart.com](https://mermaidchart.com), then click "View Code" to copy it.
- **Result:** Paste the Mermaid code below and preview it in VSCode using your Markdown/Mermaid extension.

\[Paste your code here\]  
\`\`\`\`mermaid

flowchart TD

DERICK\[Derick\] --> PHONE\[Phone\]

PHONE --> SCREEN\[Screen time\]

PHONE --> GPIO\[GPIO3\]

SCREWS\[Screws\] --> LAPTOP\[Laptop\]

LAPTOP --> PACKAGED\[Packaged in\]

PACKAGED --> CARDBOARD\[Cardboard\]

SCREWS --> METAL\[Metal\]

METAL --> SCREWDRIVER\[Screwdriver\]

SCREWDRIVER --> TOOLS\[Tools\]

TOOLS --> PROBLEMS\[⭐ Solving problems\]

CARDBOARD --> CARRIER\[⭐ Cardboard carrier\]

WOOD\[Wood\] --> CARRIER

RUBBER\[Rubber\] --> CARRIER

LEATHER\[Leather\] --> CARRIER

CARRIER --> CARRIES\[Carries\]

CARRIES --> TRANSPORTATION\[Transportation\]

TRANSPORTATION --> PEOPLE\[People\]

PEOPLE --> CAR\[Car\]

GROCERIES\[Groceries\] --> LIQUIDS\[Liquids\]

LIQUIDS --> RANCH\[Ranch\]

RANCH --> SALAD\[⭐ Salad\]

LETTUCE\[Lettuce\] --> SALAD

SALAD --> PLATE\[Plate\]

SALAD --> CROUTON\[Crouton\]

MOUSE\[Mouse\] --> NEEDS_FOOD\[Needs food\]

MOUSE --> DATA\[Data\]

MOUSE --> FOOD\[Food\]

CAT\[Cat\] --> FOOD

FOOD --> FISH\[Fish\]

FOOD --> WHEAT\[Wheat\]

WHEAT --> BREAD\[Bread\]

FOOD --> SANDWICH\[Sandwich\]

classDef starred fill:#fff3a3,stroke:#b8860b,stroke-width:2px;

class CARRIER,PROBLEMS,SALAD starred;

\`\`\`\`

## Section 2: Rapid Individual Concept Evaluations (8 Points)

_Each team member claims ONE of the starred concepts from the whiteboard to evaluate against the Phase 0/1 constraints. Ensure your pitches explain the mechanics of the geometric joints._

### Concept 1 (Evaluator: \_**\__Parker Nagy_\_**\_**\_**\_**\_**\___\_)

- **Concept Name:** \_**\___Friction fit Dovetail Interlock_\_**\_**\_**\_**\_**\_**\_**\___\__
- **The Pitch (1-2 sentences):** What is it and how does it manage the 25kg shifting load? _(Use Copilot to refine your phrasing)_
  - _Answer: The design uses tapered dovetail joints with a precise friction fit to manage the 25kg shifting load by locking tighter under weight, converting dowward pull into horizontal clamping force across the joint interface_
- **Constraint Checklist:**
  - Cardboard ONLY (no glue/tape/metal)? **\[ Y / N \]**
  - Operable by BOTH 1 AND 2 people? **\[ Y / N \]**
  - What specific fastener-free geometry handles the connection? (e.g., interlocking tabs, friction-fit, precise folds): \_**\_Tapered friction fit dovetails and locking key slots\_\_**\_**\_**\_**\_**\_**\_**_
  - What is the biggest risk for failure during the dynamic carry? (creasing, delamination, joint blowout): \_**\_**\_Delamination or crushing of the dovetail fingers under sudden lateral load shifts_\_**\_**\_**\_**\_**\_**_

### Concept 2 (Evaluator: \_**\__Austin Rudd_\_**\_**\_**\_)

- **Concept Name:** **Interlocking Tab-and-Slot**
- **The Pitch (1-2 sentences):** What is it and how does it manage the 25kg shifting load?
  - _Answer:_ This design uses an interlocking tab-and-slot matrix to manage the 25kg shifting load by converting dynamic downward forces into lateral shear stress across the cardboard panels.
- **Constraint Checklist:**
  - Cardboard ONLY (no glue/tape/metal)? **\[ Y / N \]**
  - Operable by BOTH 1 AND 2 people? **\[ Y / N \]**
  - What specific fastener-free geometry handles the connection?: Tab and slot
  - What is the biggest risk for failure during the dynamic carry?: The slot failing because the carboard is weak

### Concept 3 (Evaluator: Grant Daulton

- **Concept Name:** **Interlocking Cradle**‑**Frame Carrier**
- **The Pitch (1-2 sentences):** What is it and how does it manage the 25kg shifting load?
  - _Answer:_A folded cardboard cradle that locks into a rigid frame using slot‑and‑tab geometry. The cradle suspends the 25 kg shifting load inside a double wall structure, while the frame transfers forces to the carriers' hands without tearing because all load paths run through folded beams rather than single layer panels.
- **Constraint Checklist:**
  - Cardboard ONLY (no glue/tape/metal)? **\[ Y / N \]**
  - Operable by BOTH 1 AND 2 people? **\[ Y / N \]**
  - What specific fastener-free geometry handles the connection?:

doubled‑flange beams — Long edges folded into U‑channels increase stiffness and prevent buckling.

- - What is the biggest risk for failure during the dynamic carry?:

It being too heavy and going out under pressure.

### Concept 4 (Evaluator: \_**\_Avery Theibert\_\_**\_**\_**\_**\_**\___\__)

- **Concept Name:** \_**\__Woven cross-brace sling carrier \_**\_**\_**\_**\_**\_**\_**\_**\_**_
- **The Pitch (1-2 sentences):** What is it and how does it manage the 25kg shifting load?
  - _Answer:_ This design uses long cardboard strips woven into a cross‑brace sling under and around the 25 kg bag, creating a flexible but constrained "basket" that hugs the load. As the bag shifts, the woven pattern redistributes forces across multiple straps, limiting local tearing and keeping the bag centered over uneven terrain.
- **Constraint Checklist:**
  - Cardboard ONLY (no glue/tape/metal)? **\[ Y / N \]**
  - Operable by BOTH 1 AND 2 people? **\[ Y / N \]**
  - What specific fastener-free geometry handles the connection?: \_**\_**\____ Woven cross‑brace straps with folded locking loops at the ends that tuck through slits and hold by friction. \_**\_**\_**\_**\___\__
  - What is the biggest risk for failure during the dynamic carry?: \_**\_**\__Creasing or tearing of a key strap at a high‑bend region, which could cause part of the weave to loosen and reduce load support.\_**\_**\_**\_**\_**\_**_

### Concept 5 (Evaluator: \_**\_**\_Derek Boronski_\_**\_**\___\_) _Only if 5-person team_

- **Concept Name:** \_**\_**\__*folded box frame carrier*\_**\_**\___
- **The Pitch (1-2 sentences):** What is it and how does it manage the 25kg shifting load?
  - _Answer: Uses a rigid folded box‑frame made from layered cardboard panels that lock together using basic tab and fold geometry. The frame surrounds the 25 kg load and keeps it stable by distributing weight through multiple folded beams instead of relying on any single panel._
- **Constraint Checklist:**
  - Cardboard ONLY (no glue/tape/metal)? **\[ Y / N \]**
  - Operable by BOTH 1 AND 2 people? **\[ Y / N \]**
  - What specific fastener-free geometry handles the connection?: simple interlocking tabs and folded beams that slot into corner folds.
  - What is the biggest risk for failure during the dynamic carry?: Corner folds crushing under sudden downward force, which could weaken the frame and reduce stiffness.

_Note: We will use these individual concept evaluations in our upcoming assignment to develop formal design criteria and perform a structured down-selection (using a Morphological Chart or Pugh Matrix). Ensure your GitHub commits are pushed and synced before the next class!_