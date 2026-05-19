# Integration Test: creative-ideation

## Scenario 1: Single Campaign Routing

**Input**: "Use structural deconstruction to transform this existing battery design"

**Expected behavior**:
1. ENTRY.md routes to structural-deconstruction campaign
2. Campaign loads, presents routing table of 5 strategies
3. Strategy selection based on signal (component-surgery or scamper-transformation)
4. Strategy executes with budget tracking (state ledger)
5. Tactics invoked (component-decomposition, combination-mapping)
6. SOPs dispatched as subagents (surgery-operation, scamper-divergence, etc.)
7. evaluation-filtering tactic produces ranked idea set
8. Context checkpoint saves to context file

**Verification**:
- State ledger printed before each iteration decision
- Budget floor met (±10%)
- All ideas have: description, source method, novelty tier, feasibility signal
- Context file created at `context/creative-ideation-structural-deconstruction-battery.md`

## Scenario 2: Multi-Campaign Orchestration

**Input**: "Generate diverse solutions for reducing energy loss in thermoelectric generators — use multiple creative approaches"

**Expected behavior**:
1. ENTRY.md identifies multi-campaign pattern ("全面发散")
2. Selects 3-4 campaigns based on problem characteristics (e.g., structural-deconstruction + biomimicry + cross-domain-discovery + morphological-exploration)
3. Each campaign executes independently with its own context file
4. Each campaign produces its own ranked idea set
5. Results aggregated at ENTRY level

**Verification**:
- Multiple context files created (one per campaign invoked)
- Each campaign's output independently meets its budget floor
- Final aggregation includes ideas from all invoked campaigns
- No cross-contamination between campaign executions

## Scenario 3: Cross-Domain Discovery with Literature

**Input**: "Find analogies from fluid dynamics that could apply to information routing"

**Expected behavior**:
1. Routes to cross-domain-discovery
2. Selects analogical-transfer or design-by-analogy strategy
3. Import SOPs invoked: paper-overview → paper-search for relevant papers
4. domain-scanning SOP finds candidate source domains (fluid dynamics)
5. analogy-extraction tactic: abstraction → structural-mapping → transfer-validation
6. bridge-validation tactic checks mapping quality
7. Produces structured cross-domain idea report

**Verification**:
- paper-overview called (abstract-level scan)
- paper-search called for promising leads (AI summary level)
- No conclusions drawn from abstracts alone (quality gate respected)
- Analogies rated by depth (surface/structural/systemic)
- Only structural+ analogies pass bridge-validation

## Scenario 4: Lateral Thinking Provocation

**Input**: "Challenge every assumption about how search engines work and generate radical alternatives"

**Expected behavior**:
1. Routes to assumption-destruction (primary) or lateral-thinking
2. assumption-surfacing SOP enumerates search engine assumptions
3. provocation-generation tactic: po-provocation → movement-extraction
4. Produces ideas that violate fundamental assumptions
5. evaluation-filtering produces tiered output

**Verification**:
- Assumptions categorized (physical/temporal/technical/paradigmatic)
- PO provocations generated across all 5 types
- Movement extracted from provocations (not just provocations listed)
- Final ideas have clear mechanisms (not just "what if X didn't exist")
- Novelty tiers assigned: expect ≥1 BREAKTHROUGH or HIGH tier

## Scenario 5: Biomimicry Design Spiral

**Input**: "How do biological systems solve the problem of efficient heat dissipation at small scales?"

**Expected behavior**:
1. Routes to biomimicry campaign
2. Selects biologize-and-discover or functional-analogy strategy
3. problem-biologization SOP restates as biological function need
4. organism-discovery SOP finds relevant organisms
5. biological-strategy-extraction extracts mechanisms
6. abstraction-to-design produces design principles
7. emulation-generation produces technical solutions

**Verification**:
- Problem successfully biologized (functional restatement)
- ≥3 organisms identified with relevant strategies
- Strategies extracted at mechanism level (not just "organism X does Y")
- Design principles are abstract (not organism-specific)
- Technical solutions are concrete and implementable

## Scenario 6: Saturation Detection

**Input**: Run any campaign for 3+ iterations on a narrow problem

**Expected behavior**:
1. After each iteration, saturation-detection SOP is invoked
2. First iterations: CONTINUE verdict (novelty rate > 40%)
3. Later iterations: NEAR-SATURATION or SATURATED
4. Campaign stops when SATURATED (or after NEAR-SATURATION + 1 more iteration)

**Verification**:
- Saturation detection invoked after each iteration
- Novelty rate calculated and reported
- Campaign does not continue indefinitely
- Final output includes saturation evidence
