# Research Figure Prompt System

> A reusable three-part prompting workflow for creating formal,
> publication-quality scientific research figures with AI.

## Repository Title

**Research Figure Prompt System --- Publication-Quality AI Figure
Design**

## GitHub Description

**A reusable prompt system for creating publication-quality research
figures with AI. It guides a three-part workflow: permanent visual
rules, paper-specific scientific content, and refinement for formal,
human-designed, 3D, 4K figures using restrained black, white, red, and
yellow accents!**

------------------------------------------------------------------------

# 1. Purpose of This Repository

This repository contains a **reusable master prompting system for
generating research-paper figures**.

The goal is to make the figure-generation process repeatable across
different research papers, datasets, architectures, methodologies, and
experiments.

Instead of creating a completely new prompt every time, this workflow
separates the process into three parts:

1.  **PART 1 --- Permanent Visual Rules**
2.  **PART 2 --- Research-Specific Scientific Content**
3.  **PART 3 --- Figure Refinement**

The most important principle is:

> **PART 1 controls HOW the figure looks. PART 2 controls WHAT the
> figure shows. PART 3 improves the generated figure without changing
> its scientific meaning.**

The scientific content can change completely from one research paper to
another, while the visual identity remains consistent.

------------------------------------------------------------------------

# 2. Three-Part Workflow

``` text
                 ┌──────────────────────────┐
                 │        PART 1             │
                 │ Permanent Visual Rules    │
                 │                           │
                 │ Formal + Scientific       │
                 │ Black / White / Red /     │
                 │ Yellow + 3D + 4K          │
                 └────────────┬─────────────┘
                              │
                              ▼
                 ┌──────────────────────────┐
                 │        PART 2             │
                 │ Research-Specific        │
                 │ Scientific Content       │
                 │                           │
                 │ Dataset / Method / Model │
                 │ Workflow / Results       │
                 └────────────┬─────────────┘
                              │
                              ▼
                 ┌──────────────────────────┐
                 │   FIRST FIGURE GENERATED │
                 └────────────┬─────────────┘
                              │
                              ▼
                 ┌──────────────────────────┐
                 │        PART 3             │
                 │ Figure Refinement        │
                 │                           │
                 │ Less AI-looking          │
                 │ More formal              │
                 │ Better readability       │
                 │ 3D + 4K                  │
                 └────────────┬─────────────┘
                              │
                              ▼
                 ┌──────────────────────────┐
                 │ FINAL RESEARCH FIGURE    │
                 └──────────────────────────┘
```

------------------------------------------------------------------------

# 3. How to Use This Repository

When creating a new research figure, follow these steps.

### Step 1 --- Start with PART 1

Copy the complete **PART 1 --- Permanent Visual Rules** prompt below and
give it to the image-generation model.

Do not modify the permanent visual rules unless you intentionally want
to change the visual identity of the entire repository.

At the end of Part 1, the model should be instructed to wait for Part 2.

------------------------------------------------------------------------

### Step 2 --- Give PART 2

After Part 1 has been accepted, provide the **research-specific figure
description**.

Part 2 is different for every paper.

For example, Part 2 may describe:

-   Dataset
-   Data preprocessing
-   Feature extraction
-   Model architecture
-   Training
-   Federated learning
-   Compression
-   Pruning
-   Explainable AI
-   SHAP
-   LIME
-   Grad-CAM
-   Experimental pipeline
-   Ablation study
-   Results
-   Deployment
-   Decision process
-   Mathematical equations
-   Tables or metrics

The model should use Part 1 for visual design and Part 2 for scientific
content.

------------------------------------------------------------------------

### Step 3 --- Generate the First Figure

The first generated figure is expected to be a **draft**.

Do not immediately try to solve every visual problem in the first
generation.

The purpose of Part 2 is primarily to establish:

-   Scientific structure
-   Correct components
-   Correct relationships
-   Correct labels
-   Correct workflow
-   Correct hierarchy

------------------------------------------------------------------------

### Step 4 --- Use PART 3

Take the generated figure and provide it to the model again.

Then use the Part 3 refinement prompt.

Part 3 is specifically designed to correct the common problem where an
otherwise correct figure looks too much like an **AI-generated
infographic**.

The refinement should make it:

-   More formal
-   More academic
-   More restrained
-   Less decorative
-   Less colorful
-   More geometric
-   More readable
-   More suitable for a research paper
-   More professional
-   More human-designed

------------------------------------------------------------------------

# 4. PART 1 --- PERMANENT VISUAL RULES

## COPY THIS ENTIRE SECTION FOR EVERY NEW FIGURE

``` text
===============================================================
PART 1 — PERMANENT VISUAL / DESIGN SPECIFICATION
===============================================================

Create a publication-quality scientific research figure suitable
for a peer-reviewed machine-learning, artificial-intelligence,
computer-science, engineering, or interdisciplinary research paper.

The figure must look professionally designed by a human researcher
or scientific illustrator.

It MUST NOT look like:
- an AI-generated infographic
- a marketing poster
- a business presentation
- a social-media graphic
- a colorful educational cartoon
- a futuristic dashboard
- a decorative illustration
- a game interface
- a stock infographic

The visual language must be:

FORMAL
ACADEMIC
SCIENTIFIC
MINIMAL
PRECISE
STRUCTURED
CLEAN
TECHNICAL
PROFESSIONAL
HIGHLY READABLE
PUBLICATION-READY


===============================================================
1. COLOR SYSTEM — EXTREMELY IMPORTANT
===============================================================

The figure must be predominantly BLACK and WHITE.

Primary visual palette:

- White background
- Black text
- Black or dark-gray outlines
- Dark gray secondary elements
- Light gray supporting elements
- Red as a primary accent
- Yellow as a secondary accent

The default visual feeling must be:

BLACK + WHITE + RED + YELLOW + GRAY

Use color sparingly and intentionally.

RED and YELLOW should identify important scientific elements,
transitions, selected components, highlights, or key outputs.

Do NOT automatically introduce:
- pink
- cyan
- turquoise
- purple
- bright blue
- bright green
- orange
- rainbow colors
- fluorescent colors
- neon colors
- candy colors
- excessive pastel colors

Do not use a rainbow palette.

Do not make every panel a different color.

Do not make the figure look like a colorful AI infographic.

Colors must support scientific communication rather than decoration.

The figure must remain understandable in grayscale.


===============================================================
2. 3D / ISOMETRIC SCIENTIFIC STYLE
===============================================================

The figure MUST have a professional scientific 3D/isometric appearance
where appropriate.

Use:

- subtle isometric geometry
- shallow 3D extrusion
- layered blocks
- stacked slabs
- dimensional scientific modules
- 3D neural-network blocks
- tensor cubes
- stacked data layers
- layered feature representations
- device/platform stacks
- structured architectural blocks

The 3D effect must be subtle, clean, and technical.

Use:
- controlled directional shading
- small soft shadows
- restrained depth
- clean geometric edges

Do NOT use:
- photorealistic rendering
- cinematic lighting
- metallic objects
- glass effects
- chrome
- glossy surfaces
- dramatic reflections
- exaggerated perspective
- floating futuristic objects
- sci-fi interfaces
- game-like 3D
- cartoon-style 3D

The target appearance is:

SCIENTIFIC 3D DIAGRAM

NOT:

CINEMATIC 3D ARTWORK


===============================================================
3. HUMAN-DESIGNED RESEARCH FIGURE RULE
===============================================================

The figure should look like it was carefully constructed by a
researcher using a professional scientific-figure tool.

Prioritize:

LESS DECORATION
MORE SCIENTIFIC STRUCTURE

LESS COLOR
MORE CONTRAST

LESS GLOSS
MORE GEOMETRY

LESS ARTWORK
MORE INFORMATION

LESS AI-STYLE EFFECTS
MORE HUMAN SCIENTIFIC DESIGN


===============================================================
4. BACKGROUND
===============================================================

Use a clean white background.

Do not use:
- photographic backgrounds
- textured backgrounds
- dramatic backgrounds
- dark cinematic backgrounds
- colorful gradients
- decorative patterns

Maintain generous and intentional white space.


===============================================================
5. TYPOGRAPHY
===============================================================

Use clean academic sans-serif typography similar to:

Helvetica
Arial
Inter
or another professional scientific sans-serif font.

Text must be:

- crisp
- dark
- high contrast
- aligned
- consistent
- readable
- professionally sized

Do not use:
- decorative fonts
- futuristic fonts
- handwritten fonts
- cartoon fonts
- distorted typography

Do not allow text to:
- overlap
- become warped
- become illegible
- become cropped
- disappear inside 3D objects

All scientific labels must remain readable.


===============================================================
6. LAYOUT
===============================================================

The layout must be determined by the scientific logic described
in PART 2.

Do NOT force every figure into the same number of panels.

Use the appropriate structure for the scientific problem.

Possible structures include:

- left-to-right pipeline
- top-to-bottom workflow
- parallel branches
- hierarchical architecture
- multi-stage methodology
- encoder-decoder structure
- comparison layout
- input-processing-output pipeline
- training/inference separation
- model architecture
- deployment hierarchy

Every component should have a clear purpose and position.


===============================================================
7. PANELS AND CONTAINERS
===============================================================

Use clean scientific rectangular or gently rounded containers.

Panels should primarily be:

- white
- light gray
- black-outlined

If visual separation is needed, use very restrained red or yellow
accenting.

Avoid large saturated colored backgrounds.

Panel borders must be clean and consistent.

Avoid unnecessary decorative frames.


===============================================================
8. ARROWS AND CONNECTIONS
===============================================================

Arrows must communicate real scientific relationships.

Default arrow color:

BLACK or DARK GRAY

Use RED or YELLOW only when the color has a meaningful purpose.

Arrows must clearly indicate:

- data flow
- processing
- transformation
- dependency
- information transfer
- model flow
- decision flow
- output flow

Avoid:
- excessive curved arrows
- crossing arrows
- decorative arrows
- unexplained arrows
- unnecessarily thick arrows

Connections should be easy to follow.


===============================================================
9. SCIENTIFIC OBJECT REPRESENTATION
===============================================================

Represent scientific concepts using meaningful visual structures.

Examples:

Dataset
→ stacked data slabs / database-like scientific stack

Neural network
→ layered 3D neural-network blocks

Tensor
→ 3D tensor cube

Feature maps
→ stacked matrices or layered feature blocks

Compression
→ reduced or transformed representation blocks

Pruning
→ sparse block with visibly removed regions

Deployment
→ device → edge → cloud structure

Feature importance
→ clean scientific bar chart

Model comparison
→ aligned parallel blocks

Training
→ structured input → model → loss → optimization flow

Use visual representations that match the scientific meaning.

Do not use random decorative icons.


===============================================================
10. ICONS
===============================================================

Icons must be simple, technical, and scientifically meaningful.

Prefer:

- black
- gray
- small red accents
- small yellow accents

Avoid:

- emojis
- cartoon icons
- random stock icons
- colorful decorative icons
- futuristic glowing icons
- unnecessary 3D mascots


===============================================================
11. CHARTS AND DATA VISUALIZATION
===============================================================

Charts must look like scientific charts.

Use:

- black
- gray
- red
- yellow

Use clear axes, labels, legends, and annotations where necessary.

Do not create decorative 3D statistical charts.

Do not add fake values.

Do not invent trends.

Do not imply quantitative differences that are not provided
in PART 2.


===============================================================
12. SCIENTIFIC ACCURACY — ABSOLUTE RULE
===============================================================

Use ONLY the scientific information provided in PART 2.

Do NOT invent:

- datasets
- model names
- numbers
- percentages
- equations
- parameters
- metrics
- results
- conclusions
- relationships
- experiments
- architecture components

Preserve all scientific values exactly as provided.

If a value or scientific relationship is not specified,
do not invent it.

If necessary, use a clean placeholder rather than fabricating
scientific information.


===============================================================
13. READABILITY
===============================================================

Every important component must be understandable immediately.

The viewer should be able to identify:

- input
- preprocessing
- feature/model stages
- data movement
- transformations
- decision points
- outputs
- major contribution

The figure should communicate the research methodology without
requiring excessive explanation.


===============================================================
14. 4K / HIGH-RESOLUTION REQUIREMENT
===============================================================

Generate the figure at 4K-quality or the highest practical
resolution available.

The figure must have:

- sharp edges
- crisp text
- clean geometric shapes
- precise alignment
- consistent line thickness
- high contrast
- clear labels
- professional proportions

Every individual component must remain understandable.

The figure should still look clean and readable when reduced
for inclusion in a research paper.


===============================================================
15. GRAYSCALE COMPATIBILITY
===============================================================

The figure must remain understandable when printed or viewed
in grayscale.

Do not depend only on color.

Use:

- shape
- position
- line style
- borders
- labels
- typography
- spacing

to communicate scientific differences.


===============================================================
16. NO UNNECESSARY DECORATION
===============================================================

Do not add anything simply because it makes the figure look
"cool".

Every visual element must have a scientific or structural purpose.

Avoid:

- decorative circles
- random particles
- glowing effects
- unnecessary gradients
- excessive shadows
- random 3D objects
- ornamental backgrounds
- decorative lines
- unnecessary icons
- visual clutter


===============================================================
17. FINAL VISUAL IDENTITY
===============================================================

The final figure must feel like:

A PROFESSIONAL SCIENTIFIC FIGURE
FOR A HIGH-QUALITY RESEARCH PAPER

The permanent visual identity is:

WHITE BACKGROUND
+
BLACK / DARK GRAY STRUCTURE
+
RED AND YELLOW ACCENTS
+
SUBTLE SCIENTIFIC 3D / ISOMETRIC GEOMETRY
+
4K / HIGH RESOLUTION
+
CRISP TYPOGRAPHY
+
STRONG READABILITY
+
MINIMAL DECORATION
+
HUMAN-DESIGNED ACADEMIC APPEARANCE


===============================================================
18. MOST IMPORTANT FINAL RULE
===============================================================

PART 1 controls ONLY THE VISUAL LANGUAGE.

PART 2 controls THE SCIENTIFIC CONTENT.

Do not let the scientific content change the permanent visual
identity unless explicitly instructed.

Do not replace the formal black/white/red/yellow style with a
generic colorful AI-infographic style.

Keep the final figure:

FORMAL
SIMPLE
SCIENTIFIC
3D
HIGH-RESOLUTION
READABLE
HUMAN-DESIGNED
PUBLICATION-QUALITY


===============================================================
END OF PART 1
===============================================================

STOP HERE.

Do not generate the final figure yet.

Wait for PART 2.

When ready, ask:

"Are you ready for Part 2?"
```

------------------------------------------------------------------------

# 5. PART 2 --- RESEARCH-SPECIFIC CONTENT
#### --> at first the condition 
=== REUSABLE ADD-ON: TOP-VENUE METHOD FIGURE ===

1. BACKBONE IDEA: One thick main flow line enters at the far left and exits at
   the far right through all panels. A mathematical object changes form along it
   ([input] -> [representation] -> [output] -> [score] -> [decision]).

2. EQUATION PILLS: Rounded white pills sit ON the wires, each with a corner tag
   ("Eq. N"). Leave pill interiors EMPTY; I overlay typeset LaTeX afterward.
   Never let the model write math itself.

3. WIRE LANGUAGE (one style per meaning, used consistently):
   thick solid = main flow; medium solid, second color = [method-specific
   operation]; thin solid = [computation/metric]; dashed = reference path and
   ablations; dotted = statistics / confidence / feedback.
   Orthogonal or bezier routing, >= 12 px clearance, junction dots at splits,
   no crossings except deliberate ones.

4. PANELS: N rounded dashed pastel panels, a colored header tag on each top-left
   border ("[X] view"), panel title inside, (a)-(n) labels below.

5. 3D MODULES: Isometric blocks (30 degrees, light from top-left). Block volume
   is proportional to the real quantity it represents (size, width, cost).
   Use visual motifs for operations: sparse empty cells = pruning, stair-step
   lattice = quantization, translucent cells = dropout.

6. KEY-MESSAGE EMPHASIS: One bracket or highlight marks the paper's central
   contrast ("same X, different Y"), visually the most prominent element.

7. REFERENCE VS VARIANT: Dashed reference path runs across the top into the
   comparison panel; ablations drawn as dashed gray ghost blocks.

8. LEGEND STRIP: One sample line per wire type + swatches for reference,
   variant, ablation, equation overlay.

9. HIERARCHY: titles > module labels > wire labels; all text horizontal and
   unclipped; no axis tick numbers.

10. HARD CONSTRAINTS: Use ONLY the numbers and labels I supply. No invented
    results, equations, or modules. Unrenderable label -> gray placeholder bar.

11. NEGATIVE: no photos, humans, robots, glossy renders, neon, stacked shadows,
    spaghetti wires, overlapping labels, watermarks.

12. DELETE-ORDER if cluttered: [list your least important elements here, in the
    order they should be dropped].
    
###-->  === PAPER-SPECIFIC SPEC ===
CANVAS: [aspect ratio, e.g. 16:6]
BACKBONE TOKEN CHAIN: [x -> x' -> ... -> decision]
PANELS: [(a) name | color | tag] ... one line each
MODULES PER PANEL: [3D objects, labels, and exact numbers allowed]
EQUATION PILLS: [Eq. tags and where each sits on a wire]
KEY CONTRAST BRACKET: ["same X, different Y"]
DELETE-ORDER: [first thing to drop, second, third...]

## This section changes for every research paper



After Part 1, provide the scientific description of the figure.

Use this structure as a template:

``` text
===============================================================
PART 2 — DIAGRAM-SPECIFIC RESEARCH CONTENT
===============================================================

IMPORTANT:

EVERYTHING BELOW THIS LINE IS SPECIFIC TO THE CURRENT
RESEARCH PAPER.

KEEP PART 1 UNCHANGED.

Use the permanent visual rules from PART 1.

Use the following scientific information to construct
the figure:

---------------------------------------------------------------
RESEARCH TITLE
---------------------------------------------------------------

[Insert research/project title]

---------------------------------------------------------------
FIGURE PURPOSE
---------------------------------------------------------------

[Explain what the figure must communicate]

---------------------------------------------------------------
INPUT / DATA
---------------------------------------------------------------

[Dataset, input, samples, features, images, signals, etc.]

---------------------------------------------------------------
PREPROCESSING
---------------------------------------------------------------

[Preprocessing steps]

---------------------------------------------------------------
MODEL / METHOD
---------------------------------------------------------------

[Model architecture, algorithm, framework, methodology]

---------------------------------------------------------------
MAIN WORKFLOW
---------------------------------------------------------------

[Describe the complete scientific process]

---------------------------------------------------------------
IMPORTANT COMPONENTS
---------------------------------------------------------------

[List every component that must appear]

---------------------------------------------------------------
EQUATIONS
---------------------------------------------------------------

[Insert equations exactly as required]

---------------------------------------------------------------
RESULTS / METRICS
---------------------------------------------------------------

[Insert only verified results that should appear]

---------------------------------------------------------------
OUTPUT
---------------------------------------------------------------

[Describe the final output]

---------------------------------------------------------------
SPECIAL VISUAL REQUIREMENTS
---------------------------------------------------------------

[Anything scientifically specific about the layout]

---------------------------------------------------------------
SCIENTIFIC RESTRICTIONS
---------------------------------------------------------------

Do not invent any scientific information.

Use only the information provided above.

Preserve all numbers, labels, equations, model names,
metrics, and relationships exactly.

===============================================================
END OF PART 2
===============================================================
```

------------------------------------------------------------------------

# 6. PART 2 --- FINAL GENERATION INSTRUCTION

At the end of the research-specific description, add:

``` text
===============================================================
FINAL GENERATION COMMAND
===============================================================

Follow PART 1 as the permanent visual design specification.

Follow PART 2 as the scientific content specification.

PART 1 tells you:

HOW THE FIGURE MUST LOOK.

PART 2 tells you:

WHAT THE FIGURE MUST SHOW.

Do not remove important scientific information.

Do not invent scientific information.

Do not change scientific values.

Do not replace the formal visual identity with a generic
colorful AI infographic.

Create the complete research figure according to both parts.

Make the scientific workflow immediately understandable.

Use subtle professional 3D/isometric geometry.

Use a predominantly black-and-white visual system with
restrained red and yellow accents.

Use high-resolution / 4K-quality rendering.

Make every important component crisp and readable.

Generate the figure now.
```

------------------------------------------------------------------------

# 7. PART 3 --- FIGURE REFINEMENT PROMPT

## Use this after receiving the first figure

Upload the generated figure and then provide the following prompt:

``` text
===============================================================
PART 3 — FIGURE REFINEMENT / HUMAN-DESIGNED RESEARCH STYLE
===============================================================

Review the attached figure carefully.

The scientific structure and information are already defined.

The main problem is VISUAL STYLE.

The current figure looks too much like it was generated by AI.

Redesign/refine the figure so that it looks like a professionally
constructed scientific figure made for a high-quality research paper.

IMPORTANT:

DO NOT CHANGE THE SCIENTIFIC MEANING.

DO NOT REMOVE IMPORTANT SCIENTIFIC COMPONENTS.

DO NOT INVENT NEW SCIENTIFIC INFORMATION.

DO NOT CHANGE NUMBERS, EQUATIONS, MODEL NAMES, METRICS,
DATASET NAMES, OR SCIENTIFIC RELATIONSHIPS.

Keep the existing scientific workflow and improve the visual design.


===============================================================
COLOR REFINEMENT
===============================================================

Use much simpler and more formal research-paper colors.

The dominant colors must be:

BLACK
WHITE
DARK GRAY
LIGHT GRAY

Use only restrained:

RED
YELLOW

as accent colors.

The figure should feel predominantly black and white.

Do NOT use:

- rainbow colors
- excessive pastel colors
- bright blue
- bright green
- purple
- cyan
- turquoise
- neon colors
- fluorescent colors
- candy colors
- excessive color gradients

Do not make every component colorful.

Color must be used only when it improves scientific communication.


===============================================================
REMOVE THE AI-LOOK
===============================================================

Remove or reduce visual characteristics that make the figure
look AI-generated.

Reduce:

- excessive gradients
- excessive glow
- glossy surfaces
- dramatic lighting
- unnecessary shadows
- decorative 3D effects
- random floating objects
- unnecessary icons
- excessive rounded shapes
- decorative patterns
- visual clutter
- futuristic interface elements
- overly colorful panels
- exaggerated perspective

The figure should look intentionally designed by a human researcher.


===============================================================
3D REQUIREMENT
===============================================================

Keep the figure 3D/isometric where appropriate.

However, the 3D style must be:

- subtle
- scientific
- geometric
- professional
- controlled
- publication-ready

Use:

- shallow extrusion
- layered blocks
- stacked slabs
- clean 3D modules
- subtle directional shading
- small soft shadows

Do NOT make it cinematic or photorealistic.

The goal is:

SCIENTIFIC 3D

NOT:

3D ARTWORK.


===============================================================
4K / HIGH-RESOLUTION REQUIREMENT
===============================================================

Produce the refined figure in 4K-quality or the highest practical
resolution.

Every individual component must be:

- sharp
- crisp
- readable
- properly aligned
- clearly separated

Text must remain readable.

Lines must be clean.

Shapes must have precise edges.

Do not allow:

- blurry text
- distorted labels
- cropped components
- overlapping labels
- unreadable small text


===============================================================
RESEARCH-PAPER APPEARANCE
===============================================================

The final figure should look appropriate for:

- IEEE papers
- ACM papers
- Springer papers
- Elsevier papers
- machine-learning conferences
- AI conferences
- engineering journals
- academic theses

The visual style should communicate:

FORMAL
ACADEMIC
TECHNICAL
SCIENTIFIC
PRECISE
MINIMAL
PROFESSIONAL


===============================================================
VISUAL PRIORITY
===============================================================

Follow this priority order:

1. Scientific correctness
2. Readability
3. Clear workflow
4. Professional structure
5. Black/white contrast
6. Restrained red/yellow accents
7. Subtle 3D depth
8. Visual polish

Never sacrifice scientific readability for decoration.


===============================================================
FINAL DESIGN PRINCIPLE
===============================================================

LESS AI-INFographic
MORE SCIENTIFIC FIGURE

LESS COLOR
MORE CONTRAST

LESS DECORATION
MORE INFORMATION

LESS GLOSS
MORE GEOMETRY

LESS VISUAL NOISE
MORE READABILITY

LESS ARTWORK
MORE RESEARCH

Make the final figure look as though it was carefully designed
by a professional researcher for publication.


===============================================================
FINAL REFINEMENT COMMAND
===============================================================

Refine the attached figure according to all instructions above.

Preserve the scientific content and structure.

Use a formal black-and-white design with restrained red and
yellow accents.

Keep subtle scientific 3D/isometric elements.

Improve alignment, spacing, typography, contrast, hierarchy,
and readability.

Remove the obvious AI-generated visual appearance.

Make the final result publication-quality, human-designed,
scientifically clear, and 4K/high-resolution.

Generate the refined figure.
===============================================================
```

------------------------------------------------------------------------


# 7.5 .Then i can wirte this prompt 

please provide me this in "4k image so that every single can part can be easily understood "



# 8. Quick Version of PART 3

If you are in a hurry, use this shorter version after uploading the
figure:

``` text
The figure looks like it was made using AI.

Please redesign/refine it to look like a professionally
human-designed scientific research figure.

Keep ALL scientific content, numbers, labels, equations,
models, metrics, relationships, and workflow unchanged.

Use a much simpler and more formal color system:

BLACK + WHITE + DARK GRAY
with restrained RED and YELLOW accents.

Do not use rainbow colors, excessive pastel colors, neon colors,
glowing effects, glossy surfaces, or decorative AI-infographic
elements.

Keep it 3D/isometric, but make the 3D style subtle, geometric,
scientific, and professional — not cinematic or photorealistic.

Make it 4K/high-resolution so every single component, label,
arrow, block, and scientific detail is crisp and easy to
understand.

Improve:
- alignment
- spacing
- typography
- contrast
- hierarchy
- readability
- scientific structure

The final result should look like a formal figure prepared for
a high-quality research paper, not an AI-generated infographic.

LESS COLOR.
MORE CONTRAST.
LESS DECORATION.
MORE SCIENTIFIC STRUCTURE.
LESS AI STYLE.
MORE HUMAN RESEARCH DESIGN.
```

------------------------------------------------------------------------

# 9. Recommended File Structure

For long-term use, organize the GitHub repository like this:

``` text
research-figure-prompt-system/
│
├── README.md
│
├── prompts/
│   ├── 01_permanent_visual_rules.md
│   ├── 02_research_specific_prompt.md
│   └── 03_figure_refinement.md
│
├── examples/
│   ├── example_01/
│   │   ├── part2_prompt.md
│   │   ├── initial_figure.png
│   │   └── refined_figure.png
│   │
│   └── example_02/
│       ├── part2_prompt.md
│       ├── initial_figure.png
│       └── refined_figure.png
│
└── generated_figures/
```

------------------------------------------------------------------------

# 10. Prompt File Responsibilities

### `01_permanent_visual_rules.md`

Contains the permanent visual identity.

**Do not change this file for individual research papers.**

It defines:

-   Color
-   Typography
-   3D style
-   Isometric style
-   Layout philosophy
-   Scientific accuracy
-   Readability
-   4K requirement
-   Human-designed appearance
-   Publication quality

------------------------------------------------------------------------

### `02_research_specific_prompt.md`

Contains the content for one specific research figure.

This file changes from project to project.

For a new paper, replace its contents with the new:

-   methodology
-   architecture
-   dataset
-   workflow
-   equations
-   results
-   scientific relationships

------------------------------------------------------------------------

### `03_figure_refinement.md`

Contains the post-generation refinement instructions.

This prompt is used after the first figure has been generated.

Its purpose is to correct:

-   AI-looking visual style
-   excessive colors
-   poor hierarchy
-   excessive decoration
-   weak readability
-   inconsistent geometry
-   excessive 3D effects

------------------------------------------------------------------------

# 11. Important Rules for Future Use

## Rule 1 --- Never mix scientific content into the permanent style unnecessarily

Part 1 should remain reusable.

If a new paper has a completely different methodology, only Part 2
should change.

------------------------------------------------------------------------

## Rule 2 --- Do not let the model invent information

If the research description does not contain a number, metric, equation,
or result, the model must not invent one.

------------------------------------------------------------------------

## Rule 3 --- Scientific correctness comes before visual beauty

A beautiful figure with incorrect scientific information is not useful.

Priority:

``` text
Scientific correctness
        ↓
Readability
        ↓
Workflow clarity
        ↓
Professional layout
        ↓
Visual polish
```

------------------------------------------------------------------------

## Rule 4 --- Avoid excessive color

The permanent visual identity is intentionally restrained.

Default:

``` text
WHITE
BLACK
GRAY
RED
YELLOW
```

Do not allow the figure to automatically become a rainbow infographic.

------------------------------------------------------------------------

## Rule 5 --- Keep 3D controlled

3D is required as a scientific visual language, but it should not become
decorative artwork.

Use geometry and depth to explain scientific structures.

------------------------------------------------------------------------

## Rule 6 --- Part 3 is important

Do not assume the first generated figure is the final figure.

The refinement stage exists because image-generation models frequently
produce figures that are:

-   too colorful
-   too glossy
-   too decorative
-   too futuristic
-   too AI-looking
-   difficult to read

Part 3 is specifically designed to correct these problems.

------------------------------------------------------------------------

# 12. Complete Workflow Checklist

Before starting:

-   [ ] Open `01_permanent_visual_rules.md`
-   [ ] Copy Part 1
-   [ ] Send Part 1 to the model
-   [ ] Wait for confirmation / Part 2 request
-   [ ] Prepare research-specific Part 2
-   [ ] Send Part 2
-   [ ] Generate the first figure
-   [ ] Inspect scientific correctness
-   [ ] Upload the generated figure
-   [ ] Send Part 3
-   [ ] Refine visual style
-   [ ] Check all labels
-   [ ] Check all numbers
-   [ ] Check all equations
-   [ ] Check arrows and relationships
-   [ ] Check readability
-   [ ] Check black/white/red/yellow palette
-   [ ] Check 3D/isometric appearance
-   [ ] Check resolution
-   [ ] Export the final figure

------------------------------------------------------------------------

# 13. Final Master Philosophy

This repository follows one simple principle:

> **The scientific content may change completely, but the visual quality
> standard should remain consistent.**

Every future research figure should aim to be:

**FORMAL**

**SCIENTIFIC**

**HUMAN-DESIGNED**

**MINIMAL**

**READABLE**

**3D / ISOMETRIC**

**BLACK + WHITE DOMINANT**

**RED + YELLOW ACCENTS**

**4K / HIGH-RESOLUTION**

**PUBLICATION-QUALITY**

The goal is not to make the figure look more artistic.

The goal is to make the research easier to understand.

------------------------------------------------------------------------

# 14. One-Line Workflow

``` text
PART 1 → Permanent Visual Rules
        ↓
PART 2 → Research-Specific Scientific Content
        ↓
FIRST FIGURE
        ↓
PART 3 → Human-Designed Scientific Refinement
        ↓
FINAL PUBLICATION-QUALITY FIGURE
```

------------------------------------------------------------------------

## Repository Status

**Purpose:** Reusable research-figure generation system\
**Workflow:** 3-Part Prompting System\
**Visual Identity:** Formal Black / White / Red / Yellow + Scientific
3D\
**Target:** Research Papers, Conferences, Journals, Theses\
**Output Goal:** Clear, accurate, readable, publication-quality
scientific figures
