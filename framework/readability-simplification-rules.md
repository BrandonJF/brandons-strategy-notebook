# Strategic Framework Readability Simplification Rules

## Purpose

Maintain 9th-10th grade reading level in all Strategic Proof Framework documents while preserving logical rigor, evidence standards, and strategic depth.

**Core Principle:** Simplify *language*, not *thinking*.

---

## Target Metrics

- **Flesch-Kincaid Grade Level:** 9-10
- **Average Sentence Length:** 12-20 words
- **Average Paragraph Length:** 3-5 sentences
- **Passive Voice:** <10% of sentences

---

## Rule 1: Sentence Length Control

### Standard
**One idea per sentence. Maximum 25 words per sentence.**

### Detection
- Count commas: If 3+ commas → probably too complex
- Count words: If 35+ words → definitely too long
- Check clauses: If 3+ clauses → break it up

### Fix Pattern
```
BEFORE (98 words):
Given our critical 19-day cash depletion pressure requiring immediate bridge capital, investor requirement for 2-3 repeat customers forcing 3-month validation phase, and razor-thin 3-day operational buffer with baseline $60k bridge, a parallel-track capital strategy of (1) securing additional bridge commitments beyond baseline $60k to extend survival runway, (2) launching immediate angel outreach to build relationships during MVP completion, and (3) executing 3-month paid pilot program to prove repeat customer behavior is the optimal path to secure $500k in VC or angel funding by Q2 2025 while managing existential cash depletion risk.

AFTER (6 sentences, avg 12 words):
We have 19 days of cash left. We need immediate bridge funding to survive. Investors also require proof of 2-3 repeat paying customers, which takes 3 months to demonstrate. Even with our committed $60k bridge, we only have 3 days of buffer.

Our strategy has three parallel tracks:
1. Secure additional bridge funding beyond the $60k baseline to extend our runway
2. Start angel investor conversations now while building the MVP
3. Run a 3-month paid pilot program to prove customers will pay repeatedly

This approach gives us the best chance to raise $500k from VCs or angels by Q2 2025 while avoiding running out of money.
```

### Application
- Break at logical conjunctions (and, but, while, because)
- Pull lists out of sentence prose into bullets
- Separate conditions from consequences into distinct sentences

---

## Rule 2: Vocabulary Simplification

### Standard
**Replace academic/technical vocabulary with plain language equivalents.**

### Common Replacements

| ❌ Complex Term | ✅ Simple Replacement |
|----------------|----------------------|
| Existential | Will kill the company / Critical |
| Optimal | Best |
| Suboptimal | Worse / Not as good |
| Sequential | One at a time |
| Parallel | At the same time / All at once |
| Mitigate | Reduce / Fix / Address / Handle |
| Validated | Confirmed / Proven / Checked |
| Contingent | Depends on |
| Intensification | Increase / Ramp up |
| Forcing function | Pressure / Requirement / Deadline |
| Traction | Proof it's working / Progress |
| Leverage | Use |
| Deploy capital | Spend money / Invest |
| Unit economics | Make money on each customer |
| Materialize | Happen / Show up |
| Viability | Whether it will work |
| Predicated on | Based on / Depends on |
| Articulate | Explain / Say |
| Facilitate | Help / Make easier |
| Demonstrate | Show / Prove |
| Necessitate | Require / Force / Mean we must |
| Constitute | Make up / Are |
| Ascertain | Find out / Determine |
| Initiate | Start / Begin |
| Terminate | End / Stop |
| Utilize | Use |
| Sufficient | Enough |
| Insufficient | Not enough |
| Subsequent | Later / Next / After |
| Prior | Earlier / Before |
| Preliminary | Early / Initial / First |
| Comprehensive | Complete / Full |

### Framework Terms (Keep These)
- ✅ IMMUTABLE / CURRENT / CHOSEN (constraint classifications)
- ✅ GIVEN / THEREFORE / BECAUSE (logical connectors)
- ✅ WE VALIDATE BY (validation statements)
- ✅ Strategic Proof / Strategic Question / Proposition

These are *defined framework vocabulary* and should remain consistent.

### Technical Terms (Explain First Use)
When business/domain jargon is necessary:
```
BEFORE:
For B2B SaaS: $350K-$500K ARR minimum threshold

AFTER:
For our type of business: Need $350K-$500K in yearly recurring revenue (ARR) for VCs to take us seriously
```

Pattern: `plain language (technical abbreviation)` on first use

---

## Rule 3: Active Voice Priority

### Standard
**Subject performs the action. Avoid passive constructions.**

### Detection
- Look for "is/are/was/were" + past participle
- Check if subject receives action vs performs it

### Fix Pattern
```
BEFORE (Passive):
Bridge funding is required to be secured by January 31

AFTER (Active):
We must get bridge funding by January 31
```

```
BEFORE (Passive):
Customer payment willingness will be validated through pilot conversion

AFTER (Active):
We'll validate customer willingness to pay when pilots convert
```

### Exception
Passive is acceptable when:
- Actor is unknown: "Capital was deployed across multiple channels"
- Actor is irrelevant: "The bridge was funded in December"
- Emphasizing the action over actor makes sense

But default to active unless passive has clear advantage.

---

## Rule 4: Concrete Language Over Abstractions

### Standard
**Use specific, tangible verbs and nouns. Avoid abstract noun phrases.**

### Detection
- Look for "-tion" / "-ment" / "-ance" / "-ence" endings (signs of nominalization)
- Check if you're using nouns for actions that could be verbs

### Fix Pattern
```
BEFORE (Abstract):
Investor outreach intensification

AFTER (Concrete):
Start serious investor talks / Ramp up investor conversations
```

```
BEFORE (Abstract):
Payment validation timing integration

AFTER (Concrete):
When we'll check if customers actually pay
```

```
BEFORE (Abstract):
Capital acquisition strategy execution

AFTER (Concrete):
How we'll raise money
```

### Verb > Noun Preference
- "We will execute" → "We will do / run / complete"
- "Requires validation" → "We must test / prove / check"
- "Demonstrates viability" → "Shows it will work / Proves it works"

---

## Rule 5: Parenthetical Extraction

### Standard
**Explanatory content belongs in separate sentences, not parentheses.**

### Detection
- Count parentheses: If 2+ per sentence → extract
- Check length: If parenthetical is 5+ words → extract
- Check nesting: If parentheses inside parentheses → definitely extract

### Fix Pattern
```
BEFORE (Nested):
Angel market timing assumptions: Market research (50% invest at seed/pre-seed) + Josh Powe validation (one angel) suggests MVP-stage engagement possible, but requires 5-10 additional conversations to validate applies to our network

AFTER (Extracted):
Angel investor timing: Research shows 50% of angels invest before companies have revenue. Josh Powe (one angel) says we're ready now. But we need 5-10 more angel conversations to confirm other angels in our network agree.
```

### Parenthetical Usage Rules
- ✅ Allow: Brief clarifications (1-3 words) like acronym definitions
- ✅ Allow: Simple examples that don't interrupt flow
- ❌ Avoid: Long explanatory clauses (5+ words)
- ❌ Avoid: Critical information (shouldn't be hidden in parentheses)
- ❌ Avoid: Nested parentheticals

---

## Rule 6: Scannable Structure

### Standard
**Use white space, bullets, headers, and formatting to make content scannable.**

### Paragraph Length
- **Maximum:** 5 sentences
- **Ideal:** 3 sentences
- **Very short is fine:** 1-2 sentence paragraphs are acceptable for emphasis

### List Extraction
If sentence contains 3+ items in series:
```
BEFORE (List buried in prose):
The strategy requires MVP completion by November 10, securing bridge funding by January 31, validating customer payment by November 30, and completing pilot phase by February 10.

AFTER (List extracted):
The strategy has four key deadlines:
- MVP completion: November 10
- Customer payment validation: November 30
- Bridge funding secured: January 31
- Pilot phase complete: February 10
```

### Header Clarity
Headers should be explanatory, not cryptic:

```
BEFORE (Academic):
Timeline Mismatch Analysis

AFTER (Clear):
The Timeline Problem: Why We'll Run Out of Cash
```

```
BEFORE (Abstract):
Capital Acquisition Optimization

AFTER (Clear):
How We'll Raise Money
```

Headers should answer: "What will I learn from this section?"

---

## Rule 7: Validation Statement Simplification

### Standard
**"WE VALIDATE BY" statements use checkpoint format, not run-on lists.**

### Detection
- Look for "WE VALIDATE BY" with 3+ validation items in single sentence
- Count parentheticals within validation statement
- Check sentence length (validation statements often 40+ words)

### Fix Pattern
```
BEFORE (49-word run-on):
WE VALIDATE BY tracking weekly bridge pipeline progress ($ committed + strong verbal interest), achieving December 31 checkpoint assessment ($40k+ secured or strong path to $60-80k by Jan 31), and securing full $60-80k bridge commitments with documentation in progress by January 31, 2026 or implementing salary cut fallback.

AFTER (Checkpoint format):
How we'll know if this is working:

- Weekly check: Track how much bridge funding is committed and how many investors are seriously interested
- December 31 check: We should have $40k committed, or a clear path to $60-80k by January 31
- January 31 deadline: Either we have $60-80k in bridge funding with paperwork started, or we cut salaries
```

### Template
```
**How we'll know if this is working:**

- [Timeframe] check: [What we measure] [What success looks like]
- [Timeframe] check: [What we measure] [What success looks like]
- [Timeframe] deadline: [Binary outcome]
```

---

## Rule 8: Annotation Clarity

### Standard
**Annotations explain issues in plain language with specific fixes.**

### Current Annotation Style (Maintain)
Framework annotations already follow good patterns:
- `[LOGICAL GAP: explanation]`
- `[ASSUMPTION: what needs validation]`
- `[CITATION NEEDED: what evidence is missing]`

### Enhancement for Readability
Ensure annotation explanations also follow simplification rules:

```
BEFORE (Complex annotation):
[ASSUMPTION: The extrapolation from Josh Powe's assessment to broader angel network sentiment lacks empirical validation given single data point insufficiency]

AFTER (Simple annotation):
[ASSUMPTION: We're guessing other angels will agree with Josh Powe, but we've only talked to one angel so far]
```

Apply Rules 1-7 to annotation text itself.

---

## Rule 9: Evidence Quality Section Simplification

### Standard
**Evidence classifications explain themselves and use concrete examples.**

### Detection
- Look for: "STRONG evidence," "MEDIUM evidence," "WEAK evidence"
- Check if classification name explains meaning

### Fix Pattern
```
BEFORE (Unclear):
**MEDIUM evidence requiring validation:**

AFTER (Self-explanatory):
**MEDIUM evidence - we think this is true but need to prove it:**
```

```
BEFORE (Dense):
* Angel market timing assumptions: Market research (50% invest at seed/pre-seed) + Josh Powe validation (one angel) suggests MVP-stage engagement possible, but requires 5-10 additional conversations to validate applies to our network

AFTER (Scannable):
* **Angel investor timing:** Research shows 50% of angels invest before companies have revenue. Josh Powe (one angel) says we're ready now. But we need 5-10 more angel conversations to confirm other angels in our network agree.
```

### Template
```
**[CATEGORY] - [what this means in plain language]:**

* **[Topic in bold]:** [What we know]. [What we don't know]. [What we need to find out].
```

---

## Rule 10: Risk Assessment Simplification

### Standard
**Bias/risk names explain themselves. Descriptions use concrete examples.**

### Detection
- Look for academic bias terminology (optimism bias, planning fallacy, sunk cost, etc.)
- Check if risk name requires prior knowledge to understand

### Fix Pattern
```
BEFORE (Academic):
**Optimism bias:** Timeline assumes best-case execution without adequately accounting for typical delays and friction

AFTER (Plain language):
**Being too optimistic:** Our timeline assumes everything goes perfectly (MVP finishes on time, pilots pay us, angels say yes). We're not planning enough for the delays and problems that usually happen.
```

### Common Risk Term Replacements
| ❌ Academic Term | ✅ Plain Language |
|-----------------|-------------------|
| Optimism bias | Being too optimistic |
| Planning fallacy | Underestimating how long things take |
| Sunk cost bias | Sticking with a bad plan too long |
| Confirmation bias | Only looking for evidence we're right |
| Availability bias | Over-focusing on recent/memorable examples |
| Anchoring bias | Getting stuck on first number we heard |

---

## Rule 11: Constraint Compression (Constraint Minimalism)

### Standard
**Constraints should be bare fact statements only. All supporting evidence, calculations, and analysis belong in GIVEN sections.**

### Detection
- Look for constraints with extensive bullet points or sub-explanations
- Check for calculations, percentages, or detailed analysis in constraints
- Count words: If constraint statement >15 words → compress and move detail
- Look for strategic reasoning or implications in constraints

### Fix Pattern
```
BEFORE (Bloated constraint with 4 detailed bullets):
**Team Capacity Limitations:**
* Three-person founding team (CEO, CTO, CPO) limiting parallel execution capacity
* CTO currently working 80-100 hours/week at capacity, cannot sustainably work more
* Team is pre-product preventing immediate customer validation
* CEO time must split between capital acquisition and operations

AFTER (Compressed constraint):
**CURRENT CONSTRAINTS:**
* Limited team capacity (3-person founding team)

THEN IN LOGICAL BODY:
## GIVEN we have limited team capacity

We have only 3 people (CEO, CTO, CPO). CTO is currently working 80-100 hours/week at capacity and cannot sustainably work more without affecting health. CEO time must split between capital acquisition and operations. We're pre-product preventing immediate customer validation.

THEREFORE we choose [strategic decision based on this constraint]
```

### Constraint Minimalism Principle
- **Constraints state WHAT exists** (the limitation itself - brief)
- **GIVEN sections explain WHY it matters** (the supporting evidence and analysis - detailed)
- **GIVEN sections show WHAT we do about it** (the strategic response)
- Maintains clear 1:1 mapping between constraints and logical argument sections

### Application
- Compress all constraints to single-line fact statements
- Move all explanatory detail to corresponding GIVEN section in logical body
- Ensure every significant constraint has a matching GIVEN section
- Use constraints as brief references, GIVEN sections as full explanations

---

## Implementation Checklist

When revising a Strategic Proof document:

### Pass 1: Sentence Structure
- [ ] Identify sentences >25 words → break up
- [ ] Find sentences with 3+ commas → split at logical points
- [ ] Check multi-clause sentences → one idea per sentence
- [ ] Count paragraphs >5 sentences → break at natural divisions

### Pass 2: Vocabulary
- [ ] Replace academic terms with plain language (use table in Rule 2)
- [ ] Convert passive voice to active (check for "is/are/was/were" + past participle)
- [ ] Change abstract nouns to concrete verbs (watch for "-tion" endings)
- [ ] Explain technical terms on first use (plain language + abbreviation)

### Pass 3: Structure
- [ ] Extract buried lists from prose into bullets
- [ ] Pull parenthetical explanations into separate sentences
- [ ] Make headers explanatory, not cryptic
- [ ] Add white space between dense sections
- [ ] Compress bloated constraints to bare fact statements (Rule 11)
- [ ] Move constraint detail to GIVEN sections in logical body (Rule 11)

### Pass 4: Validation & Evidence
- [ ] Convert run-on "WE VALIDATE BY" into checkpoint format
- [ ] Make evidence category names self-explanatory
- [ ] Simplify risk/bias terminology
- [ ] Ensure annotations use plain language

### Pass 5: Quality Check
- [ ] Run Flesch-Kincaid Grade Level check → target 9-10
- [ ] Verify strategic content unchanged
- [ ] Confirm framework structure intact (GIVEN/THEREFORE, constraint categories, etc.)
- [ ] Test with stakeholder: Do they understand it?

---

## What NOT to Change

### Preserve These Elements
- ✅ Framework-specific terminology (IMMUTABLE/CURRENT/CHOSEN, GIVEN/THEREFORE)
- ✅ Logical argument structure and flow
- ✅ Evidence quality standards and citations
- ✅ Validation milestone specificity
- ✅ Constraint classifications
- ✅ Strategic reasoning depth

### Only Change These Elements
- ❌ Sentence complexity → Break up long sentences
- ❌ Academic vocabulary → Use plain language
- ❌ Dense paragraph structure → Add white space and bullets
- ❌ Buried information → Surface with formatting
- ❌ Passive voice → Make active
- ❌ Abstract language → Make concrete

**The rigor stays. The barrier drops.**

---

## Quality Metrics

### Success Criteria
- Flesch-Kincaid Grade Level: 9-10 (not higher, not lower)
- Average sentence length: 12-20 words
- Passive voice: <10% of sentences
- Paragraphs >5 sentences: <5% of paragraphs
- Stakeholder comprehension test: Can read and use without getting overwhelmed

### Failure Signals
- ❌ Grade level >12 → Still too complex
- ❌ Grade level <8 → Oversimplified, might lose precision
- ❌ Strategic depth lost → Went too far with simplification
- ❌ Framework structure broken → Changed wrong elements
- ❌ Stakeholder still overwhelmed → Needs another pass

---

## Examples Reference

See [readability-simplification-examples.md](../examples/readability-simplification-examples.md) for:
- 7 detailed before/after transformations
- Readability testing results (15.2 → 9.1 grade level average)
- Proof that strategic rigor is maintained
- Templates for common patterns

---

## Agent Integration

For the `strategic-framework-maintainer` agent:

### Prompt Enhancement
Add this requirement to agent instructions:
```
READABILITY REQUIREMENT: All Strategic Proof documents must maintain 9th-10th grade reading level (Flesch-Kincaid) while preserving logical rigor and strategic depth. Apply readability simplification rules from framework/readability-simplification-rules.md during all document creation and revision tasks.

After any document changes:
1. Check Flesch-Kincaid Grade Level
2. If >10, apply simplification rules until reaching 9-10 range
3. Verify strategic content unchanged
4. Confirm framework structure intact
```

### Automated Checks
The agent should automatically:
1. Run readability metrics on revised text
2. Flag sentences >25 words for review
3. Identify passive voice for potential conversion
4. Check validation statements for checkpoint format
5. Verify paragraphs don't exceed 5 sentences

---

## Maintenance

This rules document should be updated when:
- New complexity patterns emerge in strategic proofs
- Stakeholder feedback reveals additional comprehension barriers
- Framework terminology evolves requiring new simplification guidance
- Readability testing reveals rules that don't work in practice

**Document owner:** Strategic framework maintainer
**Review frequency:** Quarterly, or after major framework updates
**Last updated:** 2025-10-27
