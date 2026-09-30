# Storytelling with Data: A Data Visualization Guide for Business Professionals — Cole Nussbaumer Knaflic
**Format**: Markdown; title and edition verified in supplied text | **Pages**: 284 PDF pages | **Sections**: 10 | **Depth**: study

## Mental Model (read first)
Explanatory data communication starts with a particular audience and something that audience should understand or do. Choose a display that supports the required comparison, remove irrelevant effort, and direct attention toward the analytical point with labels, hierarchy and sequence. This is the 2015 Storytelling with Data, not Storytelling with You. Focus does not license suppressing opposing evidence, and the book's preference for explanatory communication should not be imposed on open-ended exploration.

## Frameworks & Structure
### 1. The importance of context
Source: chapter 1, pp. 19–33; supplied Markdown lines 505–755.

- **Exploratory versus explanatory analysis**: exploration seeks what is interesting or valid; explanation communicates a selected finding. Do not show every analytical detour to prove effort. Conversely, do not impose a single highlighted story when the audience's task is to discover patterns or compare possible explanations.
- **Who, what, and how**: identify the audience and its relationship with the communicator; identify what it needs to know or do and the delivery mechanism; then determine how the data can support the message. “Everyone interested” is often too broad to guide a design.
- **Audience relationship**: established trust, technical knowledge and decision authority change what must be demonstrated and when. A budget owner needs the requested decision and consequences; an unfamiliar reviewer may first need provenance and methods.
- **Communication mechanism continuum**: a live presenter can explain, pace and respond; a written artifact must carry more of that context itself. Set the density, annotation and narrative layer accordingly.
- **3-minute story**: articulate the essential message without relying on slides. This tests whether the communication has a coherent spine and provides a way to adapt when time is cut. It does not imply that every deck should last three minutes.
- **Big Idea**: adopted explicitly from Duarte: unique point of view, stakes and a complete sentence. Separate the action sought from the evidence available, and qualify the proposition when support is limited.
- **Storyboard**: make a low-cost visual outline before digital production; reorder or discard notes without attachment to polished slides. Where collaboration requires it, use the outline to align expectations early.
- **Opposing data boundary**: the sidebar “Ignore the nonsupporting data?” rejects one-sided evidence selection. Determine the context needed for the audience to assess the claim, including evidence that weakens it.

### 2. Choosing an effective visual
Source: chapter 2, pp. 35–69; especially pp. 39–42, 45–53, 63–65.

| Task | Useful form | Conditions and common failure |
|---|---|---|
| Communicate one or two values | **Simple text** | Keep the baseline, unit and comparison that give the numbers meaning. A single percent change can conceal the original magnitudes. |
| Find exact values or different units | **Table** | Organize rows and columns for lookup; make rules and shading subordinate. Mixed audiences can inspect their own rows. |
| Scan magnitude patterns in a table | **Heatmap** | Use a meaningful ordered scale; retain numbers when precise reading matters. Color is not a precise substitute for position. |
| Examine two quantitative variables | **Scatterplot** | Name units, sample and relevant reference lines; association does not establish causation. |
| Show change over continuous time | **Line graph** | Use a truthful time scale; a decade and a year must not occupy equal distances. Do not connect unrelated categories as a continuous series. |
| Compare change between two states | **Slopegraph** | Keep endpoint labels legible and identify what the two states mean. It does not show the path between them. |
| Compare category magnitudes | **Bar chart** | Use a zero baseline because length carries quantity. Horizontal bars often accommodate long labels better. |
| Show contributions to a whole | **Stacked bars** | Only baseline-aligned segments permit easy precise comparison. Check whether the task concerns totals or individual segments. |
| Explain additions and subtractions to a total | **Waterfall** | Define the starting amount, signed changes and final amount; reconcile the arithmetic. |
| Encode an amount by area | **Area form** | Area, rather than diameter or width alone, must represent magnitude. Prefer more accurate encodings for close comparison. |

- **Graph axis versus data labels**: use a subdued axis for overall trends; direct values can help exact lookup. Remove redundancy only when it does not remove orientation. Units, percent signs and separators can remain useful even when a title also names the unit.
- **Nonzero baseline boundary**: a line chart can use a nonzero baseline because position, rather than bar length, carries the value. Make the range explicit and avoid exaggerating minor fluctuations. This is not permission to crop a bar axis.
- **Logical category order**: use a natural sequence when it exists; otherwise choose an order that makes the intended comparison easy. Do not reorder time or ordinal levels for visual convenience.
- **Pies and donuts**: the book strongly favors alternatives because angles and areas make close differences hard to judge. A sorted bar chart can clarify ranking, but explicitly preserve the part-to-whole context. The source allows considered use of a pie rather than declaring it intrinsically dishonest.
- **Avoid 3D decoration and misleading perspective**: tilted pies and extruded bars alter apparent magnitude. A real three-dimensional spatial task is a different case from adding depth to a two-dimensional chart.
- **Secondary axes**: two arbitrary scales can manufacture apparent relationships. Prefer aligned panels or another representation whose comparison the audience can interpret without disentangling scales.

### 3. Clutter is your enemy!
Source: chapter 3, pp. 71–95; “Gestalt principles,” “When redundant details shouldn't be considered clutter,” and the six-step decluttering example.

- **Clutter** consists of elements that occupy space without increasing understanding. Distinguish the necessary complexity of the subject from unnecessary effort introduced by the representation. Perceived difficulty can deter engagement, but perceived simplicity is not proof of completeness.
- **Proximity** groups nearby marks; use spacing to guide reading across rows or down columns.
- **Similarity** associates matching colors, shapes or styles. Give the same encoding the same meaning across a display and across slides.
- **Enclosure** marks groups, even with light shading. It can distinguish forecast from actual data without heavy boxes.
- **Closure** allows a chart to remain a recognizable whole after unnecessary borders or background fills are removed.
- **Continuity** helps the eye follow an organized path; alignment and consistent space can reduce the need for explicit rules.
- **Connection** links marks into stronger relations. A connecting line is a semantic assertion, not a neutral decorative stroke.
- **Six-step decluttering example**: remove chart border; remove unnecessary gridlines; remove unnecessary markers; clean up axis labels; label data directly; use consistent color. Apply each step conditionally. Reference lines, observations and boundaries needed for inference should stay.
- **Useful redundancy**: currency symbols, percent signs and number grouping can prevent errors and memory demands. “Already stated in the title” does not by itself make a detail disposable.

### 4. Focus your audience's attention
Source: chapter 4, pp. 97–125; “Preattentive attributes” and “Highlighting one aspect can make other things harder to see.”

- **Preattentive attributes** such as position, length, size and color differences can guide attention before deliberate reading. Use them sparingly; if everything differs, the intended signal disappears.
- **Categorical versus quantitative encoding**: red and blue can distinguish groups but do not naturally specify greater and smaller. Length or position can express magnitude; intensity can imply order but is less precise.
- **Text hierarchy**: bold, size, color and separation can make a main point and supporting explanation visible at different levels. Multiple competing accents destroy that order.
- **Selective emphasis**: de-emphasize contextual series while accenting the one currently discussed. The context should remain inspectable. Weak contrast that makes opposing data effectively invisible is not neutral.
- **Exploration boundary**: highlighting one point can make other patterns harder to see. For an exploratory task, postpone the strong persuasive overlay or provide a neutral view alongside it.
- **Color and accessibility**: use a limited, consistent palette; check how distinctions survive without color and under the actual display conditions. The book is a design guide, not a certificate of compliance with a current accessibility standard.

### 5. Think like a designer
Source: chapter 5, pp. 127–147.

- **Form follows function**: define what the viewer must be able to do before deciding what the chart looks like.
- **Affordances** in this context are visual cues that suggest how to use the display. The three operational lessons are **highlight the important stuff, eliminate distractions, create a clear hierarchy of information**.
- **Highlight only a fraction**: the book cites a roughly 10% highlighting heuristic from another design text. Its purpose is selective emphasis; it is not an empirically universal quota or a reason to hide required information.
- **Accessibility**: choose readable language and typography, explain unfamiliar abbreviations, and reduce avoidable decoding. Do not confuse reducing unnecessary complexity with removing substantive complexity.
- **Aesthetics**: coherent alignment, spacing and restrained color can make the work easier to engage with. Attractive styling cannot repair an unsupported conclusion.
- **Acceptance**: anticipate familiar organizational conventions and explain how a redesign helps the reader. Compare alternatives on the task, not on taste alone.

### 6. Dissecting model visuals
Source: chapter 6.

Use exemplary graphics as things to analyze, not compositions to copy. Identify their purpose, chart form, visual order, emphasis, text and context. Ask which design choices let the reader make the intended comparison. Transfer the functional relationship only after checking that the new data and viewing situation share the same requirements.

### 7. Lessons in storytelling
Source: chapter 7, pp. 165–185; particularly “Write the headlines first,” “Narrative flow,” and “The spoken and written narrative.”

- **Beginning, middle and end**: establish the situation and need, develop the evidence, then specify a response. This gives orientation without requiring every report to become a dramatic script.
- **Write the headlines first**: arrange message sentences into a coherent path before finishing charts. The title sequence should tell the argument; the evidence under each title must support it.
- **Chronological order** can help audiences who need to understand the reasoning process or assess credibility. **Lead with the ending** can help a trusted, busy decision maker orient to the request immediately. Choose according to the audience, not a universal consulting template.
- **Spoken versus written narrative**: decide which context the voice supplies and which the artifact must carry. A distributed version needs the missing explanation restored.
- **Horizontal and vertical logic**: check that the sequence of headlines forms a coherent story and that each page's content substantiates its headline. A clear title over unrelated data fails the second test.
- **Repetition and feedback**: revisit the central message at meaningful points and test it with someone who does not already know the story. Repetition should consolidate understanding, not substitute for an argument.

### 8. Pulling it all together
Source: chapter 8, pp. 187–209.

The integrated method is **understand the context; choose an appropriate display; eliminate clutter; draw attention where you want it; think like a designer; tell a story**. These steps are interdependent: discovering that the display does not support the intended claim can send the work back to the context or analysis stage. Visual emphasis is not a one-way march toward a predetermined conclusion.

### 9–10. Case studies; Final thoughts
Source: chapters 9–10.

The cases extend the same method across practical redesign problems, including alternatives to pies and the handling of competing communication constraints. Treat each solution as conditional on its intended comparison. The closing practice discipline is to collect and critique examples, seek feedback, and build repeatable habits. The reference compresses these chapters into transfer rules rather than reproducing their gallery or historical tool instructions.

## Worked Example
Chapter 8 starts with a chart of average retail prices for five products across years. The audience is a VP of Product deciding a launch price. The initial emphasis on prices after Product C's introduction is only one possible reading. Knaflic changes the display to make trends more evident, removes unnecessary visual competition, labels the lines and selectively emphasizes different observations. The same data can reveal post-launch declines or later price convergence. The recommendation must follow the relevant market question, and the narrative guides the reader through the evidence. A defensible new use would also check product comparability, coverage and costs before treating competitor prices as a complete pricing model; the illustrated sequence is not proof that one product caused rivals' price movements.

## Decision Rules & Judgment
- If the audience or action is vague, resolve that before choosing the chart.
- If the task is exact lookup, mixed units or simultaneous comparison, consider a table despite the book's caution about tables during speech.
- If bar length encodes magnitude, retain zero; if a line chart uses a cropped scale, disclose and justify it.
- If a reader needs a numerical qualifier to interpret the claim, it is not clutter.
- If the audience is exploring, do not force a single highlighted interpretation.
- If emphasis obscures opposing evidence, restore an inspectable neutral context.
- If an executive wants the answer first, lead with the recommendation and then substantiate it; if credibility depends on methods, adapt the order.
- If the artifact must travel without its presenter, add the written narrative it needs.

## Key Takeaways
1. Context precedes visualization.
2. Choose the chart for the reader's task.
3. Remove decoding effort while preserving evidence.
4. Emphasis has an opportunity cost: other patterns become harder to see.
5. Titles, charts and narrative must agree about what is established.
